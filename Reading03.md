### React Docs - lists and keys

1. What does .map() return?
it returns a new array and elements of arrays are result of callback function

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
use map()

3. Each list item needs a unique ____.
key

4. What is the purpose of a key?
help react identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity

### The Spread Operator

1. What is the spread operator? 
a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functions aruguments 

2. List 4 things that the spread operator can do.
copying an array
using math functions
using an array as arguments 
adding to state in react

3. Give an example of using the spread operator to combine two arrays.
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

4. Give an example of using the spread operator to add a new item to an array.
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

5. Give an example of using the spread operator to combine two objects into one.
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂