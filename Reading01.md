## Component-Based Architecture

1. What is a “component”?
A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface. A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionality
veiws of a component
    object-oriented view
    conventional view
    process-related

2. What are the characteristics of a component?
Reusability- components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task
Replacement- components may be freely substituted with other similar components
Not Context Specific- components are designed to operate in different environments and context
Extensible- a component can be extended from existing components to provide new behavior
Encapsulated- a component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state
Independent- components are designed to have minimal dependencies on other components  

3. What are the advantages of using component-based architecture?
ease of deployment
reduced cost
ease of development
reusable
modification of technical complexity
reliability
system maintenance and evolution
independent

## What is Props and How to Use it in React

1. What is “props” short for?
Components need to communicate (send data to each other) and the way to pass data between components is by using props
"props" is a special keyword in React, which stands for properties and is being used for passing data from one component to another
But the most important part here is that data with props are being passed in a uni-direction flow

2. How are props used in React?
Firstly, define an attribute and its value (data)
Then, pass it to child component(s) by using props
Finally, render the props

3. What is the flow of props?
One way from parent to chiild
