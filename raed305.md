### Read: Class 05
-----------------------------------------------------------------------------------------------
#### Putting it all together

![Image of Yaktocat](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSe49Ll7nrzm_vbBhvpoxdW7JYB0Kut0d9ww9bCMI4eKYn_kJx9c5TqttyuRbs6jrwpsSk&usqp=CAU)

----------------------------------------------------------------------------------------------------

###### How would you break a mock into a component heirarchy?

1- **Break The UI Into A Component Hierarchy**
2- **Build A Static Version in React**
3- **Identify The Minimal (but complete) Representation Of UI State**
4- **Identify Where Your State Should Live**
5- **Add Inverse Data Flow**

###### What is the single responsibility principle and how does it apply to components?

![Image of Yaktocat](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210505204130/How-To-Use-Single-Responsibility-Principle-in-ReactJS.png)

> In React, the Single Responsibility Principle means that a component is required to have only one reason to change. In short, the Single Responsibility Principle means that code with the same functionality should not exist in multiple places


###### What does it mean to build a ‘static’ version of your application?

> tatic applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies


###### Once you have a static application, what do you need to add?

 Babel and webpack, When you're ready to deploy to production, running npm run
 
 
###### What are the three questions you can ask to determine if something is state?


- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.


###### How can you identify where state needs to live?

- Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).

-Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
Let’s run through this strategy for our application:

![Image of Yaktocat](https://www.erasmuslifebudapest.com/wp-content/uploads/2018/11/reactjs-thumb.jpg)














