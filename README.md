# Array-Constructor

The “Array Constructor” refers to a method of creating arrays by invoking the Array constructor function. This approach allows for dynamic initialization and can be used to create arrays with a specified length or elements.

**Syntax:**
let arrayName = new Array();

// Declaration of an empty array 
// using Array constructor 
let names = new Array(); 
console.log(names); 

// Creating and Initializing an array with values 
let courses = new Array("HTML", "CSS", "Javascript", "React"); 
console.log(courses); 

// Initializing Array while declaring 
let arr = new Array(3); 
arr[0] = 10; 
arr[1] = 20; 
arr[2] = 30; 
console.log(arr);

**Output**

[]
[ 'HTML', 'CSS', 'Javascript', 'React' ]
[ 10, 20, 30 ]
