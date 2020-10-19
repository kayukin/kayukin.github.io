# Granatum API

## Токен
Для авторизации необходимо послать токен в заголовлке Authorization
```
Authorization: {token}
```

## Swagger-UI
[Swagger-UI](/swagger)

## Создание нового пользователя

> POST https://api.granatum.solutions/integration/register  
```json
{
	"email": ""
}
```
< 201
```json
{
	"email": "",
	"password": ""
}
```