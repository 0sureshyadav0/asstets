**JavaScript Course**

**Introduction to JavaScript**
JavaScript is a versatile programming language used for web development, backend development, and more. It is primarily used to create interactive and dynamic web applications.

### **Module 1: JavaScript Basics**
1. **Introduction to JavaScript**
   - What is JavaScript?
     - JavaScript is a high-level, interpreted programming language primarily used to enhance web pages by making them interactive.
   - History and Evolution
     - Initially created by Netscape in 1995 as "LiveScript," it was later renamed JavaScript.
   - Setting up a development environment
     - Install Node.js and use a browser's developer console.

2. **Variables and Data Types**
   - **var, let, and const**
     ```js
     var x = 10;
     let y = 20;
     const z = 30;
     ```
   - **Primitive Data Types**
     ```js
     let name = "John"; // String
     let age = 25; // Number
     let isStudent = true; // Boolean
     let value = null; // Null
     let value2; // Undefined
     ```
   - **Type Conversion and Type Coercion**
     ```js
     let num = "5";
     let convertedNum = Number(num); // Explicit conversion
     let result = num + 10; // Implicit coercion ("510")
     ```

3. **Operators and Expressions**
   - **Arithmetic Operators**
     ```js
     let sum = 5 + 3; // Addition
     let diff = 10 - 2; // Subtraction
     ```
   - **Comparison Operators**
     ```js
     console.log(10 == "10"); // true (loose comparison)
     console.log(10 === "10"); // false (strict comparison)
     ```

4. **Control Flow**
   - **Conditional Statements**
     ```js
     let age = 18;
     if (age >= 18) {
       console.log("Adult");
     } else {
       console.log("Minor");
     }
     ```
   - **Looping**
     ```js
     for (let i = 0; i < 5; i++) {
       console.log(i);
     }
     ```

### **Module 2: Functions and Objects**
1. **Functions in JavaScript**
   - **Function Declaration**
     ```js
     function greet(name) {
       return "Hello, " + name;
     }
     ```
   - **Arrow Functions**
     ```js
     const greet = (name) => `Hello, ${name}`;
     ```

2. **Objects and Arrays**
   - **Creating Objects**
     ```js
     let person = {
       name: "John",
       age: 30,
       greet: function () {
         return "Hello!";
       }
     };
     ```
   - **Array Methods**
     ```js
     let numbers = [1, 2, 3, 4];
     let squared = numbers.map(num => num * num);
     console.log(squared); // [1, 4, 9, 16]
     ```

### **Module 3: DOM Manipulation and Events**
1. **Document Object Model (DOM)**
   ```js
   document.getElementById("demo").innerHTML = "Hello, World!";
   ```

2. **Event Handling**
   ```js
   document.getElementById("btn").addEventListener("click", function() {
     alert("Button Clicked!");
   });
   ```

### **Module 4: Asynchronous JavaScript**
1. **Promises**
   ```js
   let promise = new Promise((resolve, reject) => {
     setTimeout(() => resolve("Success!"), 2000);
   });
   ```

2. **Async/Await**
   ```js
   async function fetchData() {
     let response = await fetch("https://jsonplaceholder.typicode.com/todos/1");
     let data = await response.json();
     console.log(data);
   }
   ```

### **Module 5: JavaScript in Web Development**
1. **Fetch API**
   ```js
   fetch("https://jsonplaceholder.typicode.com/todos/1")
     .then(response => response.json())
     .then(data => console.log(data));
   ```

### **Module 6: Advanced JavaScript Concepts**
1. **Closures**
   ```js
   function outer() {
     let count = 0;
     return function inner() {
       count++;
       return count;
     };
   }
   let counter = outer();
   console.log(counter()); // 1
   ```

2. **Event Loop**
   ```js
   console.log("Start");
   setTimeout(() => console.log("Timeout"), 0);
   console.log("End");
   ```

### **Module 7: JavaScript Frameworks and Libraries**
1. **React.js Example**
   ```js
   function App() {
     return <h1>Hello, React!</h1>;
   }
   ```

2. **Node.js Example**
   ```js
   const http = require("http");
   http.createServer((req, res) => {
     res.write("Hello World");
     res.end();
   }).listen(3000);
   ```

### **Final Project**
- Build a JavaScript-based real-world application using all learned concepts.

This course provides detailed explanations along with code examples. Let me know if you need further details!

