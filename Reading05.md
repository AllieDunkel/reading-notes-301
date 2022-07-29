### React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
the single responsibility principle is like deciding if you soulf create a new function or object, in other words, a component should only do one thing

2. What does it mean to build a ‘static’ version of your application?
It implements your app but has no interactivity. Static requires alot of typing and no thinking 

3. Once you have a static application, what do you need to add?
a library of reverable components that render your model

4. What are the three questions you can ask to determine if something is state?
Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?
Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

### Higher-Order Functions

1. What is a “higher-order function”?
Functions that operate on other functions, either by taking them as arguments or by returning them

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

3. Explain how either map or reduce operates, with regards to higher-order functions.
The map method transforms an array by applying a function to all of its elements and building a new array from the returned values
another thing to do with arrays is to compute a single value from them and you can do that with reduce
