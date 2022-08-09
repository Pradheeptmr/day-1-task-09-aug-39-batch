# day-1-task-09-aug-39-batch
Task documents 
1.Difference between HTTP1.1 and HTTP 2.0
HTTP 2 is much faster and more reliable than the HTTP 1.1.
HTTP1 loads the a single request for every Tcp connection.
While HTTP 2 avoids network delay sensitive protocol in the sense of if less network delay it loads faster.
To speed up web browser proformance both HTTP1.1 and HTTP 2.0 compress message to make them smaller.
HTTP2 uses more advance compress method called HPACK that eliminates redundant information in HTTP headers packers.
HTTP is based on clients and server model that two methods
Client( Receiver of service) and server (provider of service)
HTTP 2 allows multiple requests for data in parallel over in single TCP connection.
HTTP 2 reduces Round trip time.
Example HTTP 1.1 number of request 102
Load time:12.97s
HTTP 2 number request 102 Load time        11.19s.


2.Write a blog about objects and its internal      representation in Javascript

Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).
Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:

Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:
