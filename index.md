# Granatum API

## Создание нового пользователя
```http
> POST https://api.granatum.solutions/integration/register  
Authorization: token {TOKEN}

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