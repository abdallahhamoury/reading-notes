Read: Class 01

# Class



### The primary objective of component-based architecture is to ensure component reusability. A component encapsulates functionality and behaviors of a software element into a reusable and self-deployable binary unit. 

## What is a Component?
>A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.
>A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.
>A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.


#### Characteristics of Components

- **Reusability:** Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
- **Replaceable:** Components may be freely substituted with other similar components.
- **Not context specific:** Components are designed to operate in different environments and contexts.
- **Extensible:** component can be extended from existing components to provide new behavior.
- **Encapsulated:** component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
- **Independent:** Components are designed to have minimal dependencies on other components.

![Component](https://www.tutorialspoint.com/software_architecture_design/images/principles_of_component_based_design.jpg)
--------------------------------------------------------------------------------------------------------------------------------
## Props
`React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.`

**Props** s a special keyword in React, which stands for properties and is being used for passing data from one component to another.
## HOW Using Props in React
- define an attribute and its value(data)
- pass it to child component(s) by using Props
- render the Props Data

### EX:
class ParentComponent extends Component {  
  render() {
    return (
      <h1>
        I'm the parent component.
        <ChildComponent />
      </h1>
    );
  }
}
----------------------------------------------------------------------------------------------------------------------------------
### WHAT ARE PROPS IN REACT?
Normally you start out with React's JSX syntax for rendering something to the browser when learning about React. Basically JSX mixes HTML with JavaScript to get the best of both worlds.
![react](https://cdn-media-1.freecodecamp.org/images/1*Rzaf_TyulUee7xEdDs3bRw.png)


#### Introducing JSX

It is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.

> JSX produces React “elements”. We will explore rendering them to the DOM in the next section. Below, you can find the basics of JSX necessary to get you started.

##### Why JSX?
**React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.**

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

### Rendering Elements

The ReactDOM.render() function takes two arguments, HTML code and an HTML element.

The purpose of the function is to display the specified HTML code inside the specified HTML element.

**Example**
Display a paragraph inside the "root" element:

ReactDOM.render(<p>Hello</p>, document.getElementById('root'));
The result is displayed in the <div id="root"> element:

<body>

  <div id="root"></div>

</body>
  
---------------------------------------------------------------------------------------------------------------------------------
### Function and Class Components

  
 ![Components](https://www.cloudsavvyit.com/p/uploads/2021/01/24b43beb.jpg) 
  
A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element.
