# Passing Functions as Props

## List & keys :

### What does .map() return?

- it returns a new array with the same length of the original one.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

- using curly braces {}

### Each list item needs a unique **key**.

### What is the purpose of a key?

- Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity

---

## spread operator

### What is the spread operator?

- it is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

### List 4 things that the spread operator can do.

- adding items to arrays
- combining arrays
- combining objects
- spreading an array out into a function’s arguments.

### Give an example of using the spread operator to combine two arrays.

let arr1 = [1,2,3];
<br>
let arr2 = [4,5,6];

let spArr = [...arr1,...arr2];

console.log (...combineArr) // output : [1,2,3,4,5,6]

### Give an example of using the spread operator to add a new item to an array.

let arr1 = [1,2,3]

let spArr = [...arr1,...4]

console.log(spArr); // output : [1,2,3,4]

### Give an example of using the spread operator to combine two objects into one.

let obj1 = { name : 'sara' };
let obj2 = { age : 20 };

let spObj = {...obj1, ...obj2};

console.log(spObj); // output : [ name : 'ahmad' age : 20]

## pass functions between components

### In the video, what is the first step that the developer does to pass functions between components?

- create function in the parent then pass it to the children

### In your own words, what does the increment function do?

- increade count by one.

### How can you pass a method from a parent component into a child component?

- by using props.

### How does the child component invoke a method that was passed to it from a parent component?

- (this.props.method)
