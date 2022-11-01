# CRUD

## Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:

100’s = This is to let the user knows that the header part of their request has be received in which the server will comply with the transmission demand of the client.

200’s = These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

400’s = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.

What is a status code 202? Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.

What is a status code 308? This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

What code would you use if an update didn’t return data to a client? 204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.

What code would you use if a resource used to exist but no longer does? It's used when the server knows that the requested URI used to refer to a resource, but no longer does. The server doesn't know any new URI for the resource; if it did, it would send a 301 (“Permanent Redirect”).

What is the ‘Forbidden’ status code? The HTTP 403 Forbidden response status code indicates that the server understands the request but refuses to authorize it. This status is similar to 401 but for the 403 Forbidden status code, re-authenticating makes no difference.

Why do we need to pull our MongoDB database string out of our server and put it into our .env? MongoDB connection string is defined as connection format to join the MongoDB database server, we have using username, hostname, password, and port parameter to connect the database server. Without a connection string, we cannot connect to the database server, we need a connection string to connect the database server.

What is middleware? Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system. Data management, application services, messaging, authentication, and API management are all commonly handled by middleware.

What does app.use(express.json()) do? json() is a built-in middleware function in Express. This method is used to parse the incoming requests with JSON payloads and is based upon the bodyparser. This method returns the middleware that only parses JSON and only looks at the requests where the content-type header matches the type option.

What does the /:id mean in a route? The Route Order ID is a unique identifier assigned to every order that is protected by Route Package Protection. This number allows us to view all the important information to report an order issue.

What is the difference between PUT and PATCH? PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

How do you make a default value in a schema? You can specify a default value for an item using the default keyword.

What does a 500 error status code mean? The HTTP status code 500 is a generic error response. It means that the server encountered an unexpected condition that prevented it from fulfilling the request. This error is usually returned by the server when no other error code is suitable.

What is the difference between a status 200 and a status 201? “Everything is OK.” This is the code that is delivered when a web page or resource acts exactly the way it's expected to. 201: “Created.” The server has fulfilled the browser's request, and as a result, has created a new resource.