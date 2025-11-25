# flow.DefaultApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**status**](DefaultApi.md#status) | **GET** /status | Get API status


# **status**
> Status200Response status()

Get API status

### Example


```python
import flow
from flow.models.status200_response import Status200Response
from flow.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = flow.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
with flow.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = flow.DefaultApi(api_client)

    try:
        # Get API status
        api_response = api_instance.status()
        print("The response of DefaultApi->status:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->status: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**Status200Response**](Status200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | OK - The API is running and returns the current version. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

