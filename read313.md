Read: Class 13
----------------------------------------------------------------------------
## CRUD

![CRUD](https://www.dorusomcutean.com/wp-content/uploads/2020/03/crud.jpg)

### In your own words, describe what each group of status code represents:
100’s = informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
200’s =These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request
300’s =These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore
400’s =the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication
500’s =the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

### What is a status code 202?

The HyperText Transfer Protocol (HTTP) 202 Accepted response status code indicates that the request has been accepted for processing, but the processing has not been completed; in fact, processing may not have started yet

### What is a status code 308?

The HyperText Transfer Protocol (HTTP) 308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers. ... Note: Some Web applications may use the 308 Permanent Redirect in a non-standard way and for other purposes

### What code would you use if an update didn’t return data to a client?

The answer, therefore, to your question is use 404 in your case. 204 is a specialized reponse code that you shouldn't often return to a browser in response to a GET

### What code would you use if a resource used to exist but no longer does?

PUT /objects/{id} HTTP/1.1

### What is the ‘Forbidden’ status code?


The HTTP 403 Forbidden client error status response code indicates that the server understood the request but refuses to authorize it. This status is similar to 401 , but in this case, re-authenticating will make no difference.

--------------------------------------------------------------------------------

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

To become dynamic and change when you upload it online

### What is middleware?

A middleware is basically a function that will the receive the Request and Response objects, just like your route Handlers do. As a third argument you have another function which you should call once your middleware code completed

### What does app.use(express.json()) do?

express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app

### What does the /:id mean in a route?

And the root that the router will return to if pressed

### What is the difference beween PUT and PATCH?

The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

### How do you make a defalut value in a schema?

Defaults. Each SchemaType that you define (you can read more about them in the model definition chapter ) can have a default value. Default values

### What does a 500 error status code mean?

The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. This error response is a generic "catch-all" response

### What is the difference between a status 200 and a status 201?

The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page)

![CRUD](https://codeteddycom.files.wordpress.com/2017/06/statuscode.png)
