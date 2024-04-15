0x11. ES6 data manipulation
Description :bulb
some key ES6 features related to data manipulation:

Array Destructuring: ES6 allows you to extract values from arrays and assign them to variables in a concise and readable way. This can simplify code when working with arrays by eliminating the need for manual indexing. For example:
const [first, second, third] = [1, 2, 3];
console.log(first); // Output: 1
console.log(second); // Output: 2
console.log(third); // Output: 3

Spread Operator: The spread operator (...) allows you to expand an iterable, such as an array or string, into individual elements. It is commonly used for array manipulation, function arguments, and object manipulation. For example:
const arr1 = [1, 2, 3];
const arr2 = [...arr1, 4, 5, 6];
console.log(arr2); // Output: [1, 2, 3, 4, 5, 6]

Array Methods: ES6 introduced several new array methods that make data manipulation more efficient and readable. Some notable methods include map(), filter(), reduce(), and find(). These methods allow you to transform, filter, aggregate, or find elements within an array without needing explicit loops.

Object Enhancements: ES6 brought enhancements to object manipulation, including shorthand property syntax, computed property names, and object destructuring. These features make it easier to create and manipulate objects. For example:
const name = "John";
const age = 30;

const person = { name, age }; // Shorthand property syntax
console.log(person); // Output: { name: 'John', age: 30 }

Template Literals Template literals allow you to create dynamic strings using backticks (`) instead of single or double quotes. They support variable interpolation and multiline strings, making string manipulation more flexible and readable. For example:
const name = "John";
const greeting = `Hello, ${name}!`;
console.log(greeting); // Output: Hello, John!

ES6 provides many more enhancements, including arrow functions, classes, modules, and promises, which collectively improve code readability, modularity, and maintainability.

Resources :books
Read or watch:

Array
Typed Array
Set Data Structure
Map Data Structure
WeakMap
Requirements :hammer
Ubuntu 18.04 LTS using NodeJS 12.22.x
Jest Testing Framework
ESLint
Task Files :card_file_box
0. Basic list of objects
1. More mapping
2. Filter
3. Reduce
4. Combine
5. Typed Arrays
6. Set data structure
7. More set data structure
8. Clean set
9. Map data structure
10. More map data structure
11. Weak link data structure
