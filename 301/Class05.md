# Putting it all together

## How would you break a mock into a component heirarchy?

- draw boxes around every component and give them all names.

## What is the single responsibility principle and how does it apply to components?

- a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

## What does it mean to build a ‘static’ version of your application?

- to build a version that takes your data model and renders the UI but has no interactivity.

## Once you have a static application, what do you need to add?

- add State to make the UI interactive

## What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.

Does it remain unchanged over time? If so, it probably isn’t state.

## How can you identify where state needs to live?

- Identify every component that render something.
