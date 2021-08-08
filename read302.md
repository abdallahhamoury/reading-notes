### Read: Class 02

## React
### Component Lifecycle Events

![React](https://miro.medium.com/max/2000/0*pqn5ljaOw4kWrUdF)


> What are component lifecycle events

React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

##### Mounting means

###### `putting elements into the DOM.`

----------------------------------------------------------------------------------------------------------------------------------------------------



React has four built-in methods that gets called, in this order, when mounting a component:

- constructor()
- getDerivedStateFromProps()
- render()
- componentDidMount()


The `render()` method is required and will always be called, the others are optional and will be called if you define them.


#### constructor
The `constructor()` method is called before anything else, when the component is initiated, and it is the natural place to set up the initial state and other initial values.

### getDerivedStateFromProps

![React](https://i.stack.imgur.com/Tl3gq.png)

The getDerivedStateFromProps() method is called right before rendering the element(s) in the DOM.

It takes state as an argument, and returns an object with changes to the state.

### render


The `render()` method is required, and is the method that actually outputs the HTML to the DOM

### componentDidMount
The componentDidMount() method is called after the component is rendered.
![React](https://miro.medium.com/max/1400/1*O7h3a4pKrgvnsxJm6BKHfA.png)
> This is where you run statements that requires that the component is already placed in the DOM.

### Updating

> The next phase in the lifecycle is when a component is updated.

###### A component is updated whenever there is a change in the component's state or props.

React has five built-in methods that gets called, in this order, when a component is updated:

- getDerivedStateFromProps()
- shouldComponentUpdate()
- render()
- getSnapshotBeforeUpdate()
- componentDidUpdate()


> The `render()` method is required and will always be called, the others are optional and will be called if you define them.

