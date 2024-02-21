# Turtle Calc🐢
Финальная задача спринта 2 Яндекс Лицея

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

Запустите базу данных через docker
```sh
docker-compose -f docker-compose.client.yml up
```

### Запуск 🎉
Находясь в папке проекта выполните
```sh
go run cmd/main.go
```
## На локальном хосте по порту ```8000``` [localhost](http://localhost:8000/) будет доступна frontend часть

### Сам сайт можно разбить на три секции слева направо: 
+ Математические примеры, здесь можно написать новый пример и отправить его нажав enter а так же посмотреть статус решения уже других ранее отправленных примеров.
+ Настройка времени выполнения операций, настройка сохраняется как и по enter так и по кнопке submit находящейся ниже.
+ Сервера, список серверов и того какую операцию они сейчас выполняют.

### Схема работы
![diagram](./diagram.png)

## Оссобености

> в файле .env можно настроить количество серверов

> выражение разделяется на группы которые считаются на разных серверах (горутинах)

> простой, минималистичный интерфейс

> информация о примерах и серверах постоянно динамически обновляется

### если возникнут вопросы или проблемы с установкой/ настройкой проекта пишите в тг @somuthink
