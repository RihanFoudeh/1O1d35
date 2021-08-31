# React and Forms :

## What is a ‘Controlled Component’?

- it is one that takes its current value through props and notifies changes through callbacks like onChange.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- we should do update the state as soon as the user enter the data or change it becaues the setState function is async function.

## How do we target what the user is entering if we have an event handler on an input field?

- handleChange(event) { this.setState({value: event.target.value}); }

---

## Why would we use a ternary operator?

- beacuse it’s shortened way of writing an if-else statement, by writing one line of code with three arguments, the condition, the result upon the true comparison, and the result upon the false comparison.

## Rewrite the following statement using a ternary statement.

if(x===y){
console.log(true);
}else{
console.log(false);
}

let result = ((x===y)? ‘true’: ‘false’);
