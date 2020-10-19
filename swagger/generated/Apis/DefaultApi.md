# DefaultApi

All URIs are relative to *https://api.granatum.solutions/integration*

Method | HTTP request | Description
------------- | ------------- | -------------
[**coursesGet**](DefaultApi.md#coursesGet) | **GET** /courses | Получить список всех курсов
[**coursesIdProgressGet**](DefaultApi.md#coursesIdProgressGet) | **GET** /courses/{id}/progress | Прогресс пользователей курса
[**coursesIdSessionsGet**](DefaultApi.md#coursesIdSessionsGet) | **GET** /courses/{id}/sessions | Получить список сессий курса
[**coursesIdUsersGet**](DefaultApi.md#coursesIdUsersGet) | **GET** /courses/{id}/users | Получить список пользователей курса
[**registerPost**](DefaultApi.md#registerPost) | **POST** /register | Создать новый аккаунт
[**sessionsIdResultsGet**](DefaultApi.md#sessionsIdResultsGet) | **GET** /sessions/{id}/results | Результаты прохождения тестов в сессии
[**sessionsIdUsersGet**](DefaultApi.md#sessionsIdUsersGet) | **GET** /sessions/{id}/users | Получить список пользователей сессии
[**usersGet**](DefaultApi.md#usersGet) | **GET** /users | Получить список всех пользователей


<a name="coursesGet"></a>
# **coursesGet**
> List coursesGet()

Получить список всех курсов

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../\Models/Course.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="coursesIdProgressGet"></a>
# **coursesIdProgressGet**
> List coursesIdProgressGet(id)

Прогресс пользователей курса

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id курса | [default to null]

### Return type

[**List**](../\Models/Progress.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="coursesIdSessionsGet"></a>
# **coursesIdSessionsGet**
> List coursesIdSessionsGet(id)

Получить список сессий курса

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id курса | [default to null]

### Return type

[**List**](../\Models/Session.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="coursesIdUsersGet"></a>
# **coursesIdUsersGet**
> List coursesIdUsersGet(id)

Получить список пользователей курса

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id курса | [default to null]

### Return type

[**List**](../\Models/User.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="registerPost"></a>
# **registerPost**
> CreateUserResponse registerPost(createUserRequest)

Создать новый аккаунт

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUserRequest** | [**CreateUserRequest**](../\Models/CreateUserRequest.md)|  |

### Return type

[**CreateUserResponse**](../\Models/CreateUserResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="sessionsIdResultsGet"></a>
# **sessionsIdResultsGet**
> List sessionsIdResultsGet(id)

Результаты прохождения тестов в сессии

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id сессии | [default to null]

### Return type

[**List**](../\Models/TestResult.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="sessionsIdUsersGet"></a>
# **sessionsIdUsersGet**
> List sessionsIdUsersGet(id)

Получить список пользователей сессии

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Id сессии | [default to null]

### Return type

[**List**](../\Models/User.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="usersGet"></a>
# **usersGet**
> List usersGet()

Получить список всех пользователей

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../\Models/User.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

