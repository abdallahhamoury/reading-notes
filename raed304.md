#### Read: Class 04
------------------------------------------------------------------------------------------------------------------------------

## Forms

#### Controlled Components

###### What is a ‘Controlled Component’?

A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state.

In a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state
  
![Image of Yaktocat](https://i.ytimg.com/vi/7FQS6_fOgR8/maxresdefault.jpg)


###### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

Almost every application needs to accept user input at some point, and this is usually achieved with the venerable HTML form and its collection of input controls.


###### How do we target what the user is entering if we have an event handler on an input field?

This will be done with event handlers like the ones we used previously in the course. Essentially, we're going to write a bunch of event handlers that just call  setState .


---------------------------------------------------------------------------------------------------------------------------

###### Why would we use a ternary operator?


The ternary operator in the react js works in the same way how it works in the Javascript. With the help of the ternary operator, we can display the contents on the basis of one condition where everything depends on the condition true and false we can put the contents on the conditional basis.

Ex :
 `if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }`
