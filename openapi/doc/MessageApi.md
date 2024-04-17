# openapi.api.MessageApi

## Load the API package
```dart
import 'package:openapi/api.dart';
```

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**updatePet**](MessageApi.md#updatepet) | **POST** /chat | Update an existing Message


# **updatePet**
> Message updatePet(message)

Update an existing Message

Update an existing pet by Id

### Example
```dart
import 'package:openapi/api.dart';

final api_instance = MessageApi();
final message = Message(); // Message | Update an existent pet in the store

try {
    final result = api_instance.updatePet(message);
    print(result);
} catch (e) {
    print('Exception when calling MessageApi->updatePet: $e\n');
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **message** | [**Message**](Message.md)| Update an existent pet in the store | 

### Return type

[**Message**](Message.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

