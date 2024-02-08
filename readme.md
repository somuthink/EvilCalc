# Turtle Calc🐢
Финальная задача спритна 2 Яндекс Лицея

## Технологии
- HTMX
- Go
- MySQL
- Docker

## Использование
 Установите [docker desktop](https://www.docker.com/products/docker-desktop/) если у вас его еще нету

Установите все зависимости 
```sh
go mod download
```

Утсановите и запустите локальную базу данных через docker
```sh
docker-compose -f docker-compose.client.yml up
```

### Запуск 🎉
Находясь в папке проекта выполните
```sh
go run cmd/main.go
```
## На локальном хосте по порту ```8000``` [localhost](http://localhost:8000/)http://localhost:8000/  будет доступна frontend часть

# Проект делался два поздних вечера поэтому дизайн и функционал такие простые и скромные😢🥹

