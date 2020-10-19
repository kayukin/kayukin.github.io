# Documentation for Granatum API

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *https://api.granatum.solutions/integration*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**coursesGet**](Apis/DefaultApi.md#coursesget) | **GET** /courses | Получить список всех курсов
*DefaultApi* | [**coursesIdProgressGet**](Apis/DefaultApi.md#coursesidprogressget) | **GET** /courses/{id}/progress | Прогресс пользователей курса
*DefaultApi* | [**coursesIdSessionsGet**](Apis/DefaultApi.md#coursesidsessionsget) | **GET** /courses/{id}/sessions | Получить список сессий курса
*DefaultApi* | [**coursesIdUsersGet**](Apis/DefaultApi.md#coursesidusersget) | **GET** /courses/{id}/users | Получить список пользователей курса
*DefaultApi* | [**registerPost**](Apis/DefaultApi.md#registerpost) | **POST** /register | Создать новый аккаунт
*DefaultApi* | [**sessionsIdResultsGet**](Apis/DefaultApi.md#sessionsidresultsget) | **GET** /sessions/{id}/results | Результаты прохождения тестов в сессии
*DefaultApi* | [**sessionsIdUsersGet**](Apis/DefaultApi.md#sessionsidusersget) | **GET** /sessions/{id}/users | Получить список пользователей сессии
*DefaultApi* | [**usersGet**](Apis/DefaultApi.md#usersget) | **GET** /users | Получить список всех пользователей


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Course](./\Models/Course.md)
 - [CreateUserRequest](./\Models/CreateUserRequest.md)
 - [CreateUserResponse](./\Models/CreateUserResponse.md)
 - [Role](./\Models/Role.md)
 - [Session](./\Models/Session.md)
 - [User](./\Models/User.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="ApiKeyAuth"></a>
### ApiKeyAuth

- **Type**: API key
- **API key parameter name**: token
- **Location**: HTTP header

