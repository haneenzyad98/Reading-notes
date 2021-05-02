# Express


- What’s the difference between PUT and PATCH ?

 PUT : update 

 PUT is most-often utilized for update capabilities, PUT-ing to a known resource URI with the request body containing the newly-updated representation of the original resource.


 PATCH:

Patch request says that we would only send the data that we need to modify without modifying or effecting other parts of the data. Ex: if we need to update only the first name, we pass only the first name.


 Provide links to 3 services or tools that allow you to “mock” an API for development like json-server?

 1 – Nock

 2 – MockServer

 3 – Beeceptor

 ### Compare and contrast Swagger and APIDoc.js 
1 Which HTTP status codes should be sent with each type of (un)successful API call?

 The documentation tells developers and other API consumers how to use the API. After all, how can your API be successful if developers don’t know how to use it?

An API specification provides a broad understanding of the functionality of the API and the expected results. The specification is largely about the design of the API or your design philosophy. API design and functionality are key factors when choosing to integrate an API with an application.

[I am reading from this page](https://swagger.io/resources/articles/difference-between-api-documentation-specification/)


Compare and contrast SOAP and ReST?

SOAP and REST both allow you to create your own API

REST was created to address the problems of SOAP.


- SOAP (Simple Object Access Protocol) is a standards-based web services access protocol that has been around for a long time. Originally developed by Microsoft, SOAP isn’t as simple as the acronym would suggest.

- REST (Representational State Transfer) is another standard, made in response to SOAP’s shortcomings. It seeks to fix the problems with SOAP and provide a simpler method of accessing web services. 