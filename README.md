1️ What is the difference between var, let, and const?
var:
var is used to declare a variable. It can be changed and also redeclared. It is mainly function scoped which means it works inside a function.
let:
let is used to declare a variable that can be changed later, but it cannot be redeclared in the same scope. It is block scoped, which means it only works inside { }.
const:
const is used for variables that should not change. Once a value is assigned, it cannot be changed or redeclared. It is also block scoped.
 
2️ What is the spread operator (...)?
The spread operator (...) is used to copy or combine arrays and objects easily without changing the original data.In simple terms, it spreads the values out.
exp:
const numbers = [1,2,3]
const newNumbers = [...numbers, 4, 5]
console.log(newNumbers)
output:[1,2,3,4,5]

3️ What is the difference between map(), filter(), and forEach()?
map:
map() is used to create a new array by changing each element of the original array.
filter:
filter() is used to create a new array with elements that match a condition.
forEach()
forEach() is used to loop through an array, but it does not return a new array.It is mainly used when we just want to run some code for each item.

4️ What is an arrow function?
An arrow function is a shorter way to write functions in JavaScript using =>, which helps make the code simpler and easier to read.

5️ What are template literals?
Template literals are strings written with backticks (` `) that allow us to easily include variables and expressions inside a string using ${}. They make the code cleaner and easier to read.
