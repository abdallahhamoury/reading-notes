Read: 16 - Spring Authentication
---------------------------------------------------------------------------------------
# Spring Authentication
Application security mainly consists of two parts: authentication (who are you?) and authorization (what are you allowed to do?).
Spring Security is a powerful and highly customizable authentication and access control framework. It is the de facto standard for securing spring based applications.

After the authentication is successful, we proceed to authorization, the main interface of which is AccessDecisionManager.
Spring Security is based on Servlet filters. There are multiple layers of filters that each play a special role, despite being shown by their own container as a single filter.

Spring Security Architecture && Spring Auth Cheat Sheet

## Two problems of app security: authentication and authorization

> Authentication The Authentication Manager is the main strategic interface for authentication in the authentication functionality. The AuthenticationManager can accomplish one of three things: If it can verify that the input is a valid base Film Throwing an authenticity exception is a runtime exception that is generally handled in a generic way by an application Spring Security is the AuthenticationManagerBuilder

> Authorization or Access Control

> AccessDecisionManager is the primary method for licensing. The framework provides three applications, each of which delegates a series of AccessDecisionVoter objects. And be ready to work

## Web Security
Servlet filters are used in the Web layer of Spring Security. A client sends a single HTTP request to the application, and the container defines which filters and servlets it applies to based on the request's URI path. The filters create a string and it can also change the request or response used by the final filters and servlets. FilterChainProxy is a concrete type of Spring Security which are all unknown to the container and are maintained by Spring Security at the same top level of FilterChainProx

## Method Security
In addition to support for securing web applications, Spring Security provides support for applying access rules to Java method implementations. For Spring Security, this is just a different kind of "protected resource". For users, this means that the access rules are declared using the same format as ConfigAttribute strings

#### Spring Auth Cheat Sheet       [Source](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)
Step 1: set up a user model and repo

Step 2: create a controller for that model

Step 3: UserDetailsServiceImpl implements UserDetailsService

Step 4: ApplicationUser implements UserDetails

Step 5: WebSecurityConfig extends WebSecurityConfigurerAdapter

- has a UserDetailsService
- passwordEncoder bean
- configure AuthManagerBuilder
- configure HttpSecurity
Step 6: registration page

- create it w/ form
- ensure it posts to a route your controller is ready for
- check it's saving in the DB
 Step 7: login page
- create it w/ form
- ensure it posts to the route you specified in web config
try it out!
- add to a template w/ things about the Principal ==> [Source](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)
