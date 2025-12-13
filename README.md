# sql_replica1

    Запуконтейнеры:

docker-compose up -d

    Проверьте статус контейнеров:

docker-compose ps

Master сервер:

    Хост: localhost
    Порт: 5432
    Пользователь: postgres
    Пароль: postgres

psql -h localhost -p 5432 -U postgres -d postgres

Slave сервер:

    Хост: localhost
    Порт: 5433
    Пользователь: postgres
    Пароль: postgres

psql -h localhost -p 5433 -U postgres -d postgres

Тестирование репликации

Проверка статуса репликации
