Reading for class 2

## React lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
render happens first

2. What is the very first thing to happen in the lifecycle of React?
mounting- constructor 

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
constructor
render
componentDidMount
react updates
componentWillUnmount

4. What does componentDidMount do?
If you need to load anything using a network request or initalize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don't forget to unsubscribe in componentWillUnmount()


## Videos: React State Vs Props

1. What types of things can you pass in the props?
As you have seen, props enable you to pass values from one component to another component down the component tree. In the previous example, it was only a string variable. But props can be any JavaScript data type from integers over objects to arrays

2. What is the big difference between props and state?
props you pass in a component and state is handled inside of that component and propsare handled on the component 

4. When do we re-render our application?
React components automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the User Interface (UI) elements to be re-rendered automatically.

5. What are some examples of things that we could store in state?
In React , whenever we are working with any data, we always use state for storing that data which may be a string , number or any complex object.



