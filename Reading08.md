# API Design Best Practices

1. What does REST stand for?
Representational State Transfer

2. REST APIs are designed around a ____.
resources

3. What is an identifier of a resource? Give an example.
which is a URI that uniquely identifies that resource
example: https://adventure-works.com/orders/1

4. What are the most common HTTP verbs?
GET, POST, PUT, PATCH, and DELETE

5. What should the URIs be based on?
reference collections

6. Give an example of a good URI.
For example, /customers is the path to the customers collection

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
 The more requests, the bigger the load. It is a bad thing and should be avoid "chatty" web APIs that expose a large number of small resources. 

8. What status code does a successful GET request return?
A successful GET method typically returns HTTP status code 200 (OK)

9. What status code does an unsuccessful GET request return?
If the resource cannot be found, the method should return 404 (Not Found).

10. What status code does a successful POST request return?
It returns HTTP status code 201 (Created)

11. What status code does a successful DELETE request return?
If it is successful, the web server should respond with HTTP status code 204 (No Content)