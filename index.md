# Granatum API

## Токен
Для авторизации необходимо послать токен в заголовке Authorization
```
Authorization: {token}
```

## OpenAPI спецификация
[Swagger-UI](/swagger)  
[openapi.yaml](/todo)

# Авторизация

## Создать новый аккаунт

#### Ответ
```json
{
  "email": "string",
  "password": "string"
}
```

# Статистика

## Получить список всех курсов

#### Ответ
```json
[
  {
    "email": "string",
    "externalId": "string",
    "active": true,
    "role": "USER"
  }
]
```
## Прогресс пользователей курса

#### Ответ
```json
[
  {
    "email": "string",
    "sessions": [
      {
        "id": "string",
        "name": "string",
        "averageScore": 0
      }
    ]
  }
]
```
## Получить список сессий курса

#### Ответ
```json
[
  {
    "id": "string",
    "name": "string",
    "description": "string",
    "courseId": "string",
    "startDate": "2020-10-19T17:49:45.632Z"
  }
]
```
## Получить список пользователей курса

#### Ответ
```json
[
  {
    "email": "string",
    "externalId": "string",
    "active": true,
    "role": "USER"
  }
]
```
## Результаты прохождения тестов в сессии

#### Ответ
```json
[
  {
    "email": "string",
    "attempts": 0,
    "score": 0
  }
]
```
## Получить список пользователей сессии

#### Ответ
```json
[
  {
    "email": "string",
    "externalId": "string",
    "active": true,
    "role": "USER"
  }
]
```
## Получить список всех пользователей

#### Ответ
```json
[
  {
    "email": "string",
    "externalId": "string",
    "active": true,
    "role": "USER"
  }
]
```