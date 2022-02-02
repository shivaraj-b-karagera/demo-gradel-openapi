# TopicControllerApi

All URIs are relative to *http://localhost:8086*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addTopic1**](TopicControllerApi.md#addTopic1) | **POST** /demo/topics | 
[**getAllTopics1**](TopicControllerApi.md#getAllTopics1) | **PUT** /demo/topics | 
[**getAllTopics2**](TopicControllerApi.md#getAllTopics2) | **DELETE** /demo/topics | 
[**getAllTopics3**](TopicControllerApi.md#getAllTopics3) | **GET** /demo/topics | 


<a name="addTopic1"></a>
# **addTopic1**
> addTopic1(topic)



### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.TopicControllerApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost:8086");

    TopicControllerApi apiInstance = new TopicControllerApi(defaultClient);
    Topic topic = new Topic(); // Topic | 
    try {
      apiInstance.addTopic1(topic);
    } catch (ApiException e) {
      System.err.println("Exception when calling TopicControllerApi#addTopic1");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **topic** | [**Topic**](Topic.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json, */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Success |  -  |
**400** | Invalid id supplied |  -  |
**404** | not found |  -  |

<a name="getAllTopics1"></a>
# **getAllTopics1**
> getAllTopics1()



### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.TopicControllerApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost:8086");

    TopicControllerApi apiInstance = new TopicControllerApi(defaultClient);
    try {
      apiInstance.getAllTopics1();
    } catch (ApiException e) {
      System.err.println("Exception when calling TopicControllerApi#getAllTopics1");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Success |  -  |
**400** | Invalid id supplied |  -  |
**404** | not found |  -  |

<a name="getAllTopics2"></a>
# **getAllTopics2**
> getAllTopics2()



### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.TopicControllerApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost:8086");

    TopicControllerApi apiInstance = new TopicControllerApi(defaultClient);
    try {
      apiInstance.getAllTopics2();
    } catch (ApiException e) {
      System.err.println("Exception when calling TopicControllerApi#getAllTopics2");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Success |  -  |
**400** | Invalid id supplied |  -  |
**404** | not found |  -  |

<a name="getAllTopics3"></a>
# **getAllTopics3**
> getAllTopics3()



### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.TopicControllerApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost:8086");

    TopicControllerApi apiInstance = new TopicControllerApi(defaultClient);
    try {
      apiInstance.getAllTopics3();
    } catch (ApiException e) {
      System.err.println("Exception when calling TopicControllerApi#getAllTopics3");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Success |  -  |
**400** | Invalid id supplied |  -  |
**404** | not found |  -  |

