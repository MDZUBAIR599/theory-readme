What is the difference between props and state in React.JS?

In React, the developers build basic components and then use those basic components to build larger components, leading to a complete web page. While building these components,
two important data manipulation methods are the state and props.



state
The state is a set of variables that determine the current condition of the component. The state of a component is internal, i.e., defined inside the component and changeable only within the component. Any change in state renders the component again.


props=

Props is short for properties. It is the set of attributes that are passed from a parent component to a child component. These can be data variables or function


What is useState Api used for?
The React useState Hook allows us to track state in a function component.
in use state there is initialdat, currentdata, updatatingdata

const=[acurrentdata,updatedata]=useState(initialdata)



Explain the how map, filter, reduce ?

Map, reduce, and filter are all array methods in JavaScript. Each one will iterate over an array and perform a transformation or computation. Each will return a new array based on the result of the function

=> The map() method is used for creating a new array from an existing one, applying a function to each one of the elements of the first array.

Syntax
var new_array = arr.map(function callback(element, index, array) {
    // Return value for new_array
}[, thisArg])
---------------------------------------
own map;

const numbers = [1, 2, 3, 4];
const doubled = numbers.map(item => item * 2);
console.log(doubled); // [2, 4, 6, 8]


-----------------------------------
FILTER:

The filter() method takes each element in an array and it applies a conditional statement against it. If this conditional returns true, the element gets pushed to the output array. If the condition returns false, the element does not get pushed to the output array.

const numbers = [1, 2, 3, 4];
const evens = numbers.filter(item => item % 2 === 0);
console.log(evens); // [2, 4]
-------------------------------------------------------------

Reduce
The reduce() method reduces an array of values down to just one value. To get the output value, it runs a reducer function on each element of the array.



const numbers = [1, 2, 3, 4];
const sum = numbers.reduce(function (result, item) {
  return result + item;
}, 0);
console.log(sum); // 10
