Read: 16 - Spring Authentication
---------------------------------------------------------------------------------------
# Spring Authentication

### The implementation is implemented to control access and each request passes to the resource is protected by its methods and each request can ignore what is passed to the next method

### The security context object contains information about the authenticated user and can be accessed by Java programming that treats the request as a local object.

### The login processing filter is responsible for processing login requests. This form is usually run on the URL form. If the request URL matches one of the filter's configured patterns, it will attempt an authentication based on the information in the request.

### The Filter Security Interceptor is the last line of defense in the filter security chain. It is responsible for making sure that no unauthenticated request reaches the protected resource. If this filter determines that a request for a protected resource is not authenticated

> Spring Security is the leading choice for securing Spring applications. It offers a large number of alternatives that apply to different styles and structures.

### You have to implement security in layers for your system, and for each layer, different practices should be used. Spring Security is an application level security related project.

### Safety is one of the most important things in projects. At the beginning of the project, you should think about the safety mechanism in order for the site to be protected and integrated

### The Open Web Application Security Project (OWASP) is an excellent place to start and always come back to it when it comes to vulnerabilities and security concerns. And it should be reviewed periodically

### In some cases, simple gaps can cause big problems, especially in safety because it is one of the most important points that must be focused on in order to give the site reliability.


FOR MORE INFORMATION Spring Auth Cheat Sheet Steps [link](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)
