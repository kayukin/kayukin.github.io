# Granatum API

## Создание нового пользователя
```json
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