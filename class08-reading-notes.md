# API-Design-Best-Practices

What does REST stand for? REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

REST APIs are designed around a resources, which are any kind of object, data, or service that can be accessed by the client.

What is an identifier of a resource? Give an example. A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

HTTP

Copy https://adventure-works.com/orders/1

What are the most common HTTP verbs? The most common operations are GET, POST, PUT, PATCH, and DELETE.

What should the URIs be based on? URIs should be based on 4 levels Level 0: Define one URI, and all operations are POST requests to this URI. Level 1: Create separate URIs for individual resources. Level 2: Use HTTP methods to define operations on resources. Level 3: Use hypermedia (HATEOAS).

Give an example of a good URI. A Good URIs are: Globally unique: One URI should never refer to two different concepts at the same time, even ones that may seem equivalent. Persistent: A URI should continue to resolve for the forseeable future. ... Stable: A URI should never be re-used for different things between data releases, even if the original is deleted.

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. It is good to have a chatty API because it enable clients to get multi needed information all at once.

What status code does a successful GET request return? The 200 OK status code means that the request was successful, but the meaning of success depends on the request method used: GET: The requested resource has been fetched and transmitted to the message body. HEAD: The header fields from the requested resource are sent in without the message body.

What status code does an unsuccessful GET request return? If not valid, 400 Bad Request is returned.

What status code does a successful POST request return? If a PUT method creates a new resource, it returns HTTP status code 201 (Created), as with a POST method.

What status code does a successful DELETE request return? If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), indicating that the process has been successfully handled, but that the response body contains no further information. If the resource doesn't exist, the web server can return HTTP 404 (Not Found).