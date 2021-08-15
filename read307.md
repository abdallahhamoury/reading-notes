### Read: Class 07
--------------------------------------------------------------------------------------------------------
#### Who is Roy Fielding?

![Image of Yaktocat](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Roy_Fielding.jpg/675px-Roy_Fielding.jpg)
He helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.

#### Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

Well, there's this concept that people are calling “Web Services” or "APIs". It means a lot of different things to a lot of different people but the basic concept is that machines could use the web just like people do.

#### What is the HTTP protocol that Fielding and his friends created?

The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypermedia information systems.

![Image of Yaktocat](https://www.universityofcalifornia.edu/sites/default/files/domain_http.jpg)


#### What does a GET do?

> GET is used to request data from a specified resource.

> GET is one of the most common HTTP methods.

#### What does a POST do?

POST is used to send data to a server to create/update a resource. POST is one of the most common HTTP methods. Some other notes on POST requests: POST requests are never cached.

#### What does PUT do?

PUT method is used to update resource available on the server. Typically, it replaces whatever exists at the target URL with something else. You can use it to make a new resource or overwrite an existing one.


#### What does PATCH do?
 used to make changes to part of the resource at a location. That is, it PATCHES the resource — changing its properties. It is used to make minor updates to resources and it's not required to be idempotent
 
 
 ![Image of Yaktocat](https://www.devopsschool.com/blog/wp-content/uploads/2018/09/http-method-put-post.jpg)
