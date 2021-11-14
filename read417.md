# Read: 17 - Spring Authorization
------------------------------------------------------------------------
Individual registration can be done by credibility from GitHub or Google
And they are all supported by OAuth 2.0

There are several models based on each other such as:
- simple
- click
- logout
- two-providers:
- custom-error
> That is, it adds the link and the user has to click on it and log out. The logout link for authenticated users can also be added, and the registration provider adds a second login for the user to choose on the home page


### It is a simple way to protect data and interact with it, and it is an open source standard and is encoded with a unique code on the Internet


Add a Home Page
You can add it to your project and it will work on coding and be effective

### Securing the app with GitHub and Spring Security
To make your application secure you must include Security OAuth 2.0 Client starter

### Boot Up the Application

You can run the application and visit the home page, you must be redirected to log in

# Spring Authorization
To render content on the condition that the user is authenticated, you have the option of either server-side or client-side rendering.
To get started with the dynamic content:
```java
<div class="container unauthenticated">
    With GitHub: <a href="/oauth2/authorization/github">click here</a>
</div>
<div class="container authenticated" style="display:none">
    Logged in as: <span id="user"></span>
</div>
```
By default, the first `<div>` will show, and the second one won’t. Note also the empty `<span>` with an id attribute.
then add the script :
```js
<script type="text/javascript">
    $.get("/user", function(data) {
        $("#user").html(data.name);
        $(".unauthenticated").hide()
        $(".authenticated").show()
    });
</script>
```
add the server-side endpoint just mentioned. It will send back the currently logged-in user:
```java
    @GetMapping("/user")
    public Map<String, Object> user(@AuthenticationPrincipal OAuth2User principal) {
        return Collections.singletonMap("name", principal.getAttribute("name"));}
```
- **Making the Home Page Public**: becouse the app work fine and authenticate, but it’s still going to redirect before showing the page. you need to make the link visible.
- **Add a Logout Button**: adding a button that allows the user to log out of the app.
- **Adding a Logout Endpoint**: The /logout endpoint requires us to POST to it, and to protect the user from Cross Site Request Forgery (CSRF, pronounced "sea surf"), it requires a token to be included in the request. The value of the token is linked to the current session.
- **Login with GitHub**:
  - Initial setup.
  - Setting the redirect URI.
  - Adding the Client Registration.
  - Adding the Login Link.
- **Adding an Error Page for Unauthenticated Users**: to give some feedback to users that cannot authenticate. And extends the authentication logic to include a rule that only allows users if they belong.
<hr>
<br>
**Sources**
- Spring Boot and OAuth2 / spring.
