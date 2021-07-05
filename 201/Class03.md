# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow


# HTML :

### HTML provides three types of lists : Ordered lists <ol> list is numbered, Unordered lists <ul> list is not numbered, Definition lists <dl> terms that we want to put explain ,In addition, we can include a list within a list.
```HTML
<ul>
  <li> .... </li>
  <li> 
    <ol>
      <li> .... </li>
      <li> .... </li>
    </ol>
  </li>
  <li> .... </li>
</ul>

<dl>
  <dt> terms want to explain </dt>
  <dd> explanation </dd>
  <dt> terms want to explain </dt>
  <dd> explanation </dd>
</dl>
```
# css : 
### We use Height and Width to reset the size of any box inside the html.
### We can determine the minimum width, length, highest width and length by:min-width, max-width, min-height, max-height.
### overflow : use it if the content contained within a box is larger  than the box itself.By using it, we can hidden the excess content or scroll so that we can read the entire content.
### any box in the html has three properties border, margin, padding ,It can be modified like the color of spaces or even the pattern of punctuation.
### Text can be aligned and centered for example through : text-align.
### We can present properties in several forms, three examples of them:inline ,block ,inline-block-none ,none .
### We can hide or show the element by , visibility: hidden /visible.
### We can place a shadow behind any box by : box-shadow.
### We can define edges for any box by : border-radius.


## Some examples :
```CSS
height: Size in px or percentage;
width: Size in px or percentage;
min-width: Size in px or percentage;
max-width: Size in px or percentage;
min-height: Size in px or percentage;
max-height: Size in px or percentage;
overflow: hidden;
overflow: scroll;
text-align: center;
```

# javascript :
### An array is a special variable, which can hold more than one value at a time, An array can hold many values under a single name, and you can access the values by referring to an index number ,The count inside array starts at index 0.
#### Ex :
```JAVASCRIPT
var array_name = [item1, item2, ...]; 
```
### if statement to specify a block of JavaScript code to be executed if a condition is true.

#### Ex :
```JAVASCRIPT
if (condition1) {
  //  block of code to be executed if condition1 is true
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true
} else {
  //  block of code to be executed if all condition1 is false
}
```
### switch statement is used to perform different actions based on different conditions.

#### Ex :
```JAVASCRIPT
switch(Value) {
  case x:
    // code block
    break; // To finish code block
  case y:
    // code block
    break; // To finish code block
  default: // If all conditions do not match
    // code block
}
```

### Type coercion : JavaScript understands the type of input variables on their own, but in some other programming languages the type of input must be specified.

### There is two types of values truthy and falsy

### Loops can execute a block of code a number of times, and there are 3 main types, which are: for, while, do while. And there is one difference between them is that do while you execute the first time before checking the condition.

#### Ex :
```JAVASCRIPT
for ( sets a variable ; condition ; increases ) {
  // code block to be executed
}

while (condition) {
  // code block to be executed
}

do {
  code block to be executed
}
while (condition);
```


[ Back To README !]( https://yousefabujalboush.github.io/reading-notes/ )