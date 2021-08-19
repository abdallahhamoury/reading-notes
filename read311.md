### Read: Class 11
----------------------------------------------------------------------------------------
## Authentication
![Authentication](https://www.loginradius.com/blog/start-with-identity/static/c49123200495a3bc193612dc9923645d/a3513/Authentication-vs.-Authorization.png)

### 1-What is OAuth?

OAuth is an open standard for access delegation, commonly used as a way for Internet users to grant websites or applications access to their information on other websites but without giving them the passwords

### 2-Give an example of what using OAuth would look like?

one website saying “HEllo, do you want to log into our website with other website's login?
![Authentication](https://d33wubrfki0l68.cloudfront.net/ecfd750086b8ac97fe5aaa08fdde917732b13225/f58f5/assets-jekyll/blog/oauth/biketoworkday-fb-login-f00e39aabbf3e44bc3570333643cbf5d966fc27367dbffd2623ff4a3694831c3.png)

### 3-How does OAuth work? What are the steps that it takes to authenticate the user?

- The User Shows Intent.
- The Consumer Gets Permission.
- The User Is Redirected to the Service Provider.
- Bitly directs Joe to Twitter for authorization
- The User Gives Permission.
- The Consumer Obtains an Access Token.

### 4-What is OpenID?

OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords

----------------------------------------------------------------------------------------------------------------------------------

### 1-What is the difference between authorization and authentication?

Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.

### 2-What is Authorization Code Flow?

Authorization code flow is used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token. A refresh token is valid indefinitely and provides ability for your application to schedule tasks on behalf of a user without their interaction

### 3-What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.

### 4-What is Implicit Flow with Form Post?

mplicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

### 5-What is Client Credentials Flow?
The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present. It can be nightly operations, or other that involve contacting OAuth protected APIs.

### 6-What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text

### 7-What is Resource Owner Password Flow?
The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. The primary difference is that the user's password is accessible to the application.

![Authentication](https://docs.wso2.com/download/attachments/60493894/OAuth%20grant%20types%20-%20password.png?version=1&modificationDate=1510604129000&api=v2)
