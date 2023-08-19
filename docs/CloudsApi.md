# swagger_client.CloudsApi

All URIs are relative to *http://localhost:8080/api/v1/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cancel_cloud_by_id**](CloudsApi.md#cancel_cloud_by_id) | **DELETE** /clouds/{cloud_id} | method of deleting order in the cloud
[**create_cloud**](CloudsApi.md#create_cloud) | **POST** /clouds | method of creating order in the cloud
[**get_all_clouds**](CloudsApi.md#get_all_clouds) | **GET** /clouds | method of getting cloud resource
[**get_order_by_id**](CloudsApi.md#get_order_by_id) | **GET** /clouds/{cloud_id} | method of getting order

# **cancel_cloud_by_id**
> Cloud cancel_cloud_by_id(cloud_id)

method of deleting order in the cloud

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.CloudsApi()
cloud_id = 'cloud_id_example' # str | order identification in cloud

try:
    # method of deleting order in the cloud
    api_response = api_instance.cancel_cloud_by_id(cloud_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling CloudsApi->cancel_cloud_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cloud_id** | **str**| order identification in cloud | 

### Return type

[**Cloud**](Cloud.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_cloud**
> Cloud create_cloud()

method of creating order in the cloud

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.CloudsApi()

try:
    # method of creating order in the cloud
    api_response = api_instance.create_cloud()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling CloudsApi->create_cloud: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Cloud**](Cloud.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_all_clouds**
> Cloud get_all_clouds()

method of getting cloud resource

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.CloudsApi()

try:
    # method of getting cloud resource
    api_response = api_instance.get_all_clouds()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling CloudsApi->get_all_clouds: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Cloud**](Cloud.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_order_by_id**
> Cloud get_order_by_id(cloud_id)

method of getting order

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.CloudsApi()
cloud_id = 'cloud_id_example' # str | order identification in cloud

try:
    # method of getting order
    api_response = api_instance.get_order_by_id(cloud_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling CloudsApi->get_order_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cloud_id** | **str**| order identification in cloud | 

### Return type

[**Cloud**](Cloud.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

