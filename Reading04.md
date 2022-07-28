### React Docs - Forms

1. What is a ‘Controlled Component’?
controlled compoents are those in which form data is handled by the component's state
is one that takes a vaule through props and notifies changes through callbacks like onChange 
    //controlled 
      <input type= "text" value= {value} onChange= {handleChange}/>

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
After they submit the form

3. How do we target what the user is entering if we have an event handler on an input field?


### The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
condition ? value if true
          : value if false

Its a way to shorten it

2. Rewrite the following statement using a ternary statement:
if(x===y){
  console.log(true);
} else {
  console.log(false);
} 

if(x===y){
  console.log(?);
  else {
    console.log(:)
  }
}