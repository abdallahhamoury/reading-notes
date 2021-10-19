Read 09 - WRRC and Java
-----------------------------------------------------------------------------------------------------

### The HTTP Request Lifecycle
![http](https://miro.medium.com/max/689/1*4SEvcz6KvyaqOqBpJABTBg.png)

- A lot can happen during this step depending on the applicant who made the request. I will continue to understand that this request is being made by a browser, rather than a cURL, an API client like Postman, or some other application.
- Resolving the IP address from DNS Server 2 is a many-step sequence, involving failovers if the first request fails to return the address. If the cache lookup fails we'll assume it happened, your browser will stop the DNS request using UDP3. The DNS request contains the host whose IP address you are trying to resolve is contained in the Request's section. UDP
- The only mandatory field in an HTTP request is HOST, which contains the domain and port the request is being sent to (domain.com:8080), although in some cases the port can be omitted. Outside of the host field, common standard HTTP header fields include Origin
But it often contains something like form data or JSON

![http](https://cdn.journaldev.com/wp-content/uploads/2015/03/java-HttpURLConnection.png)

HTTP requests are messages sent by a client or user to initiate an action on the server. The first line of the message includes the request message from the client to the server,

the server; Then the server returns a response to the client. The response contains status information about the request and may also contain the requested content.
