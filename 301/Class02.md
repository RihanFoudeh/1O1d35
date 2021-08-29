# React lifecycle & State and Props

## What are component lifecycle events?

Each component in React has a lifecycle which you can monitor and manipulate during its three main phases.

The three phases are: **Mounting, Updating, and Unmounting.**

### 1- Mounting

Mounting means putting elements into the DOM.

**React has four built-in methods that gets called, in this order, when mounting a component:**

- constructor()
- getDerivedStateFromProps()
- render()
- componentDidMount()

The render() method is required and will always be called, the others are optional and will be called if you define them.

### 2- Updating

A component is updated whenever there is a change in the component's state or props.

**React has five built-in methods that gets called, in this order, when a component is updated:|**

- getDerivedStateFromProps()
  shouldComponentUpdate()
- render()
- getSnapshotBeforeUpdate()
- componentDidUpdate()

### 3- Unmounting

**React has only one built-in method that gets called when a component is unmounted:**

- componentWillUnmount().

---

## React-Bootstrap :

React-Bootstrap replaces the Bootstrap JavaScript. Each component has been built from scratch as a true React component, without unneeded dependencies like jQuery.

---

### State :

- The state object is where you store property values that belongs to the component.

- When the state object changes, the component re-renders.

- Refer to the state object anywhere in the component by using the this.state.propertyname syntax:

- To change a value in the state object, use the this.setState() method. When a value in the state object changes, the component will re-render, meaning that the output will change according to the new value(s).

- it is only handle what inside the components.

---

### Props

- it stand for properties.
- transfer data between components.
- it is only handle what outside the components.
- it use the same syntax as HTML attributes.
- The component receives the argument as a props object.
- If your component has a constructor function, the props should always be passed to the constructor and also to the React.Component via the super() method.

---

#### Resources :

<br>
(React Life Cycle)[https://www.w3schools.com/react/react_lifecycle.asp]
<br>
(State))[https://www.w3schools.com/react/react_state.asp]
<br>
(Props)[https://www.youtube.com/watch?v=IYvD9oBCuJI]
