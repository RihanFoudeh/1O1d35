# Forms
form :  different elements that allow you to collect information from visitors to 
your site.

# type of form <br>

### 1- adding text

example : text input, password.

### 2- making choices

example : radio button, checkbox.

### 3- submit

example : submit button, file upload.

#### cheat sheet:

\<form action ="" methode""> 

\<input type="text" >

\<input type="password">

\<textarea cols= "20" rows ="4">

\<input type="radio" value="rock">

\<input type="checkbox" value="Itunes">

\<select> => drop down list

\<option> => provide the option to the list

\< input type="file">

\<input type=" submit">

\<input type=" image" src="">

\<lable> =>  e purpose of each one in text.

\<fieldset> => group related form together.

\<legend> caption which helps identify the purpose .

requaired => we use it to tell the user he must fill this.




# List Table Form

#### cheat list:

list-style-type => change the bullet point in the list

example

ol {

list-style-type: lower-roman;

}

list-style-image => change the bullet to image

example

ul {

list-style-image: url("images/star.png");

}

list-style-position => y indicates whether the marker should appear on the inside or the outside.

example

ul.illuminations {

list-style-position: outside;

}
ul.season {

list-style-position: inside;

}


#### cheat table:

width => width of the tabale.

padding => space btween border of each cell.

text-transform => change to upper case.

border top , border bottom => set border above and below the table.

background-color => put color to the background table.

:hover => highlight a table row.

empty-cells => show or hide the empty cells.

border-spacing, border-collapse.


#### cheat form :

font-size => set the size when the user input text.

color => text color.

background-color => color for the input background.

border => add borderof input text.

border-radius => create rounded corners.

: focus => change the background color we it beaing used.

background-image =>add image to the box.

cursor => control type of mouse.



# Event
#### type of event

### 1-Ui Events

example:load, unload,error, scroll.

### 2-Keyboared Event

example:Keydown, Keyup, Ketpress.

### 3-Mouse Events

example

Click, mousedown, mousemove.

4- Form Event

example

input, Change, Submit.

How event tigger javascript code?

there is steps:

1- select the element node.

2- Choose which event you want.

3- put the code you wnat to run.

Three way to bind an event to an element:

1- HTML event handlers.

2-DOM event handlers.

3- DOM level 2 event listeners.

1-HTML event handlers.
this considered bad practice

example

\<input type "text" id ="userName" onblur="checkUsername()" />

function checkUsername(){ => this function will work when the user fill the input text.
//code
} 


2- DOM event handlers.

Syntax to bind an event.

element.onevent= functionName;

example

function checkName(){
//code
}  

let el=  document.getElementByld('username') ; 
el.onblur= checkName;

3- event listeners:

Syntax to bind an event

element.addEventListeners('event', function [,boolean]);

example

function checkName(){
//code
}  

let el=  document.getElementByld('username') ;

el. addEventlistener('blur', checkUsername, false) ;
