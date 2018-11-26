---
title: "HttpClient Data Type"
ms.author: solsen
ms.custom: na
ms.date: 10/17/2018
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
author: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# HttpClient Data Type
Provides a data type for sending HTTP requests and receiving HTTP responses from a resource identified by a URI.


The following methods are available on instances of the HttpClient data type.

|Method name|Description|
|-----------|-----------|
|[Clear()](httpclient-clear-method.md)|Sets the HttpClient variable to the default value.|
|[GetBaseAddress()](httpclient-getbaseaddress-method.md)|Gets the base address of Uniform Resource Identifier (URI) of the Internet resource used when sending requests.|
|[SetBaseAddress(String)](httpclient-setbaseaddress-method.md)|Sets the base address of Uniform Resource Identifier (URI) of the Internet resource used when sending requests.|
|[DefaultRequestHeaders()](httpclient-defaultrequestheaders-method.md)|Gets the default request headers which should be sent with each request.|
|[Timeout([Duration])](httpclient-timeout-method.md)|Gets or sets the duration in seconds to wait before the request times out.|
|[Get(String, var HttpResponseMessage)](httpclient-get-method.md)|Sends a GET request to get the resource identified by the request URL.|
|[Delete(String, var HttpResponseMessage)](httpclient-delete-method.md)|Sends a DELETE request to delete the resource identified by the request URL.|
|[Post(String, HttpContent, var HttpResponseMessage)](httpclient-post-method.md)|Sends a POST request to the specified URI as an asynchronous operation.|
|[Put(String, HttpContent, var HttpResponseMessage)](httpclient-put-method.md)|Sends a PUT request to the specified URI as an asynchronous operation.|
|[Send(HttpRequestMessage, var HttpResponseMessage)](httpclient-send-method.md)|Sends an HTTP request as an asynchronous operation.|
|[AddCertificate(String, [String])](httpclient-addcertificate-method.md)|Adds a certificate to the HttpClient class.|

[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)  