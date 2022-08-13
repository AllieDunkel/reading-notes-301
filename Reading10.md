### Reading: Understanding the JavaScript Call Stack

1. What is a ‘call’?
A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

2. How many ‘calls’ can happen at once?
one

3. What does LIFO mean?
Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
function firstFunction(){
  throw new Error('Stack Trace Error');
}
function secondFunction(){
  firstFunction();
}
function thirdFunction(){
  secondFunction();
}
thirdFunction();

5. What causes a Stack Overflow?
A stack overflow occurs when a function that calls itself without an exit point. The hosting environment has a maximum stack call that it can accommodate before throwing a stack error.

### JavaScript error messages

1. What is a ‘reference error’?
you try to use a variable that is not yet declared you get this type os errors.

2. What is a ‘syntax error’?
you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. What is a ‘range error’?
you try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

4. What is a ‘type error’?
show up when the types  you are trying to use or access are incompatible, 

5. What is a breakpoint?
If the line you selected was run you will be able to see what has happened before that point and you can try and evaluate the next lines to check if everything is outputting what you are expecting.

6. What does the word ‘debugger’ do in your code?
creates a breakpoint 