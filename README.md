Welcome to the TypeScript Learning Journey! This README provides an overview of the topics covered in each class.

📚 **Note:** This README is a work in progress. As more classes are covered, I will continue updating the file with detailed summaries, topics, and assignments. Stay tuned for comprehensive insights into TypeScript and web development concepts!


# Class 1: Introduction to TypeScript and Web Concepts

- **`TypeScript Introduction:`** [TypeScript](https://www.typescriptlang.org/) is a programming language that builds upon JavaScript by adding static type-checking and other features. It enhances code quality and helps catch errors early in development.
- **`Web Concepts:`** Understand the evolution from Web 1.0 to Web 2.0 to Web 3.0: These terms refer to different stages in the evolution of the World Wide Web. Web 1.0 was the static web of early days, Web 2.0 brought interactive and social elements, and Web 3.0 aims to create a more intelligent, decentralized web.
- **`Introduction to Next.js:`**  Next.js is a popular React framework for building web applications. It enhances React with features like server-side rendering and routing.
- **`Serverless Technology:`** [Serverless computing](https://www.cloudflare.com/learning/serverless/what-is-serverless/) allows developers to focus on writing code without managing server infrastructure. It automatically scales based on demand.
- ## Assignments:
  - Install development tools and console log "Hello, World!" using TypeScript.
- ### [Class 1 Code](https://github.com/usmanashrf/typescript-batch48/tree/main/Morning-section/class-1)

# Class 2: TypeScript Fundamentals

- **`Programming Environment Setup:`** Configure [`Node.js`](https://nodejs.org/en), [`Visual Studio Code`](https://code.visualstudio.com/), and [`TypeScript`](https://www.typescriptlang.org/download) to create a development environment.
- **`Variables In Typescript:`**  A Variable is a named container or storage location that holds a value. It's used to store and manage data that a program needs to work with. In TypeScript variables are used to store different types of values, such as numbers, strings, objects, arrays, and more To use them, declare with `let`, `const`, or `var`, assign values, and manipulate as needed
- **`Primitive Data Types:`** Explore string, number, boolean, undefined, Symbol, BigInt, and null types.
- **`Template Literals:`**  Creating strings with embedded expressions for easier concatenation and formatting.
- **`Operators In Typescript:`** Using arithmetic, assignment, comparison, and logical operators to manipulate values.
- ### Online Recorded Sessions & videos:
  - [Operators](https://www.youtube.com/watch?v=wxS7j9q0nyc)
  - [Template Literals](https://www.youtube.com/watch?v=PFzeMUojeQY&t=80s&pp=ygUadGVtcGxhdGUgbGl0ZXJhbHMgaW4gaGluZGk%3D)
  - [Primitive Data Types](https://youtu.be/qpU3WIqRz9I?list=PLu0W_9lII9ahR1blWXxgSlL4y9iQBnLpR)
  - [Variables (let, var & const)](https://www.youtube.com/watch?v=Icev9Oxf0WA&list=PLu0W_9lII9ahR1blWXxgSlL4y9iQBnLpR&index=3&pp=iAQB)
- ## Assignments:
  - Complete assignments related to variables, types, and operators.
- ### [Class 2 Code](https://github.com/usmanashrf/typescript-batch48/tree/main/Morning-section/class-2)

# Class 3: Functions, Arrays, and User Input

- **`Prompt Library:`** Learn how to take user input using the [Prompt library](https://www.npmjs.com/package/prompt).
- **`Functions in TypeScript:`** Functions in TypeScript are named code blocks used to encapsulate and reuse sets of instructions, enhancing code organization and maintainability.
- **`Array in TypeScript:`** Arrays in TypeScript are data structures that allow you to store collections of values of the same or different types. They are a fundamental part of programming and are used to manage lists of items efficiently. 
- ### Online Recorded Sessions & videos:
  - Functions: [Part 1](https://www.youtube.com/watch?v=8yc2Yd8kJ_E) & [Part 2](https://www.youtube.com/watch?v=iRan4VCOy0A)
  - Array & Array Methods: [Part 1](https://www.youtube.com/watch?v=S7FfBHs-_BU), [Part 2](https://www.youtube.com/watch?v=ScuESgM3KWE) & [Part3](https://www.youtube.com/watch?v=dCMt2lr5Hrs)
- ## Assignments:
  - **Building a grading system:** Assigned students to build a grading system using user input and conditional statements.
  - **User input handling with Prompt:** Practically implemented user input capture using Prompt.
- ### [Class 3 Code](https://github.com/usmanashrf/typescript-batch48/tree/main/Morning-section/class-3)

# Class 4: Conditional Statements and Loops

- **`Return Type Annotations:`** A return [type annotation](https://www.tektutorialshub.com/typescript/type-annotation-in-typescript/) in TypeScript specifies the type of value that a function will provide as its output. It helps clarify what the function returns and catches type-related errors.
- **`Arrow Function:`** An arrow function is a more concise way to define functions in JavaScript and TypeScript. It provides a shorter syntax compared to traditional function expressions. Arrow functions were introduced in ECMAScript 6 (ES6) and have become a popular choice for writing functions in modern JavaScript and TypeScript code.
- **`Conditional Statements:`** Conditional statements are programming constructs that allow you to make decisions in your code based on certain conditions. They control the flow of your program by executing different blocks of code depending on whether a specified condition is true or false.
- **`Nested Statements:`** Nested statements are programming constructs where one or more statements are placed within another statement's block of code. We use nested statements to build more complex logic and implement decision-making processes that involve multiple levels of conditions.
- **`For Loops:`** A "for loop" is a programming construct that allows you to repetitively execute a block of code for a predetermined number of iterations. It consists of three main components: initialization, a condition, and an iteration statement.
- ### Online Recorded Sessions & videos:
  - [Arrow Function](https://www.youtube.com/watch?v=44aVMRtxKyc)
  - Conditional Statements: [Part 1](https://www.youtube.com/watch?v=MrRJqVtxETs) & [Part 2](https://www.youtube.com/watch?v=bGjWAbMfkNE)
  - [Loops](https://www.youtube.com/watch?v=QsaHgcjPqH8)
- ## Assignments:
  - Solve assignments related to implementing conditional statements and loops. ([Example](https://github.com/usmanashrf/typescript-batch48/blob/main/Morning-section/class-4/index.ts))
- ### [Class 4 Code](https://github.com/usmanashrf/typescript-batch48/tree/main/Morning-section/class-4)

# Class 5: Modules and Asynchronous Operations

- **`CommonJS Modules vs. ECMA Modules:`** Difference between CommonJS and ECMAScript modules lies in their syntax, loading mechanisms, and compatibility with different environments. While CommonJS is commonly used in Node.js and follows a synchronous approach, ECMAScript modules are used both in browsers and Node.js, and they use asynchronous loading with a more structured syntax.
- **`Asynchronous vs. Synchronous Operations:`**
  - **Synchronous Operations:** Blocking, sequential execution, and tasks are completed in a specific order. Execution follows a single-threaded approach.
  - **Asynchronous Operations:** Non-blocking, tasks can be executed in parallel or concurrently, and execution is often associated with callbacks, promises, or async/await mechanisms.
- **`Aync Await Syntax:`** async and await are features in JavaScript that make it easier to work with asynchronous code. An async function returns a promise and can use the await keyword to pause execution until an asynchronous task is done, making code look more like traditional synchronous code.
- **`Inquirer Librarie:`** Inquirer is a powerful Node.js library that simplifies the process of creating interactive command-line interfaces (CLIs). It provides a collection of prompts and utilities for easily gathering user input and building user-friendly command-line applications.
- **`Chalk Librarie:`** Chalk is a Node.js library for styling text in the terminal. It allows you to apply colors and formatting to the output text in your command-line applications, making them more visually appealing and easier to read.
- **`Further Learning:`** For more information, you can explore the [Inquirer documentation](https://www.npmjs.com/package/inquirer) and [Chalk documentation](https://www.npmjs.com/package/chalk).
- ### Online Recorded Sessions & videos:
  - Cjs & ES Modules: [Part 1](https://www.youtube.com/watch?v=RNkAHEyRk8A&t=154s) & [Part 2](https://www.youtube.com/watch?v=QqLO8wqlMf0)
  - [Asynchronous & Synchronous](https://www.youtube.com/watch?v=i7Ws2AkZDKg)
  - [Aync Await Syntax](https://youtu.be/bLre6Uf4Op0?list=PLu0W_9lII9ahR1blWXxgSlL4y9iQBnLpR)
- ### Assignments:
  - **modular calculator:** Create a modular calculator program using TypeScript. The program should take user input through the Inquirer library and implement various arithmetic operations  (addition, subtraction, multiplication, division) as separate ES modules.
    - [Video Tutorial](https://www.youtube.com/watch?v=ifGvJlg4L0I)
    - [Solved Assignment](https://github.com/a-rehman-ujjan/PIAIC-Projects/tree/main/calculator)
  - **Quiz application:** Create a quiz application using TypeScript and the Inquirer library. The program should take user input through Inquirer, implement a quiz with a variable number of questions, calculate the quiz score in a separate ES module, and display the final result along with correct and incorrect user-given answers.
    - [Video Tutorial](https://www.youtube.com/watch?v=uPFKtQ8kIQk&t=776s)
- ## [Class 5 Code](https://github.com/usmanashrf/typescript-batch48/tree/main/Morning-section/class-5)

# Class 6: Advanced TypeScript Concepts and Package Management

- **`TypeScript Unions:`** TypeScript unions allow you to define a variable or parameter that can hold values of multiple specified types. Unions are used to create more flexible and versatile data types, accommodating different data variations. A value assigned to a union type can be of any of the specified types.
- **`Type Literals:`** Type literals allow you to define exact values that a variable can hold. This is useful when you want to restrict a variable to only accept specific values.
- **`Type Aliases:`** Type aliases allow you to create custom names for types. This is helpful for making your code more readable and for simplifying complex type definitions, especially when unions are involved.
- **`TypeScript Objects:`** In TypeScript, an object is a data structure that holds key-value pairs. Keys are strings, and values can be of any type. Objects help organize related data, and you can access values using keys.
- **`NPM and Package Management:`** NPM (Node Package Manager) is a tool for managing and sharing JavaScript code. It helps you add, update, and remove packages (libraries) in your projects, making it easier to build and collaborate on software.
- ### Online Recorded Sessions & videos:
  - [npm and Node.js Packages](https://youtu.be/nSFe1-kpfbQ?list=PLu0W_9lII9ahR1blWXxgSlL4y9iQBnLpR)
  - [Typescript Unions and Literals](https://www.youtube.com/watch?v=oZata4VXyRw)
  - [Type Aliases and Typescript Objects](https://www.youtube.com/watch?v=mCatIHCmems)
- ## Assignments:
  - Publish your finished assignments from the previous class (Calculator & Quiz App) on [npmjs](https://www.npmjs.com/).
    - [How to Publish NPM Package?](https://www.youtube.com/watch?v=C56TrsGNgOk)
  - Verify the functionality of your package by installing it. Ensure that it runs properly in the command-line interface (CMD) without automatically opening the code file.
- ### [Class 6 Code](https://github.com/usmanashrf/typescript-batch48/tree/main/Morning-section/class-6)

Remember, each class builds on the previous ones, deepening your understanding of TypeScript and web development concepts. For detailed information about each topic, refer to the provided [class slides](https://docs.google.com/presentation/d/1-7Kb3laJjJ68mOTF9v0fHImk5vTol0CeE43Sg8hoUXQ/mobilepresent#slide=id.gcb9a0b074_1_0).

Feel free to explore the topics further through online resources, video tutorials, and hands-on practice. Happy learning!


