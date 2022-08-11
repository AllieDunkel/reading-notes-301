### Reading: Functional Programming Concepts

1. What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

2. What is a pure function and how do we know if something is a pure function?
It returns the same result if given the same arguments and it does not cause any observable side effects.

3. What are the benefits of a pure function?
easier to test
do not need to mock anything

4. What is immutability?
unchanged over time or unable to be changed. If you need to change something you create a new object with the new value. 

5. What is Referential transparency?
Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
An example:
pure functions + immutable data = referential transparency

### Videos: Node JS Tutorial for Beginners #6 - Modules and require()

1. What is a module?
it is a file containing code

2. What does the word ‘require’ do?
reads a JavaScript file, executes the file, and then proceeds to return the exports object

3. How do we bring another module into the file the we are working in?
you have to require it

4. What do we have to do to make a module available?
export it
For example:
module.export = counter 
