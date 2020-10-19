# Granatum API

## Токен
Для авторизации необходимо послать токен в заголовке Authorization
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

## Получить список всех курсов

### Return type
```http request
POST api.granatum.solutions
Authorization: {token}
Content-Type: application/json


```
### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


# **coursesIdProgressGet**
> List coursesIdProgressGet(id)

Прогресс пользователей курса

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id курса | [default to null]

### Return type

[**List**](../\Models/Progress.md)



### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


# **coursesIdSessionsGet**
> List coursesIdSessionsGet(id)

Получить список сессий курса

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id курса | [default to null]

### Return type

[**List**](../\Models/Session.md)



### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


# **coursesIdUsersGet**
> List coursesIdUsersGet(id)

Получить список пользователей курса

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id курса | [default to null]

### Return type

[**List**](../\Models/User.md)



### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


# **registerPost**
> CreateUserResponse registerPost(createUserRequest)

Создать новый аккаунт

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUserRequest** | [**CreateUserRequest**](../\Models/CreateUserRequest.md)|  |

### Return type

[**CreateUserResponse**](../\Models/CreateUserResponse.md)



### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


# **sessionsIdResultsGet**
> List sessionsIdResultsGet(id)

Результаты прохождения тестов в сессии

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id сессии | [default to null]

### Return type

[**List**](../\Models/TestResult.md)



### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


# **sessionsIdUsersGet**
> List sessionsIdUsersGet(id)

Получить список пользователей сессии

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id сессии | [default to null]

### Return type

[**List**](../\Models/User.md)



### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


# **usersGet**
> List usersGet()

Получить список всех пользователей

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../\Models/User.md)



### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

