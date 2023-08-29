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

# Class 7: TypeScript Interfaces and Type Compatibility

In 7th class, we explored TypeScript interfaces, delving into the concepts of structural and nominal typing. We highlighted the distinctions between these approaches and their impact on type comparisons.

We then delved into the realm of "fresh" and "stale" objects in TypeScript.

- **`Interfaces in TypeScript:`** [Interfaces](https://www.typescriptlang.org/docs/handbook/interfaces.html) allows you to define the structure of objects, specifying what properties and methods an object of a particular type should have. They serve as a contract that enforces a consistent shape for objects that adhere to that interface, preventing errors if required properties or methods are missing. Interfaces encourage reusable code and allow extension, letting you inherit properties and methods from other interfaces for creating new ones.
- **`Type Compatibility:`** [Type compatibility](https://learntypescript.dev/04/l9-type-compatibility) in TypeScript refers to how the type system determines whether one type can be assigned to another without causing type errors. It involves checking the structure and properties of the types involved to ensure they match appropriately. TypeScript's type compatibility rules allow for more flexible code while maintaining type safety.

TypeScript utilizes structural typing to determine type compatibility. When two types possess compatible structures, they're deemed compatible, regardless of separate definitions or distinct names. For object assignments, if the target type contains all properties of the source type and potentially more, the assignment is permitted. Surplus properties in the source type aren't problematic, as long as the required ones match.

In function types, parameter compatibility is examined. If a function anticipates certain parameter types, a compatible function with identical parameter structures can be assigned, even with different parameter names. Types featuring optional properties or rest elements can coexist with types possessing equivalent properties, even if not explicitly labeled as optional or part of the rest. TypeScript frequently broadens literal types to their corresponding primitive types, influencing type compatibility.
- **`Structural Typing:`**  [Structural typing](https://www.typescriptlang.org/play#example/structural-typing) is based on the structure or shape of types. Two types are considered compatible if their structures match, even if they were defined independently, regardless of their names or where they were defined. Type names are not significant; only the structure matters.
- **`Nominal Typing:`** [Nominal typing](https://www.typescriptlang.org/play#example/nominal-typing) relies on the explicit names of types. Two types with the same structure but different names are not considered compatible, Even if two types have the same structure, they are not compatible if their names differ.

In many languages, including TypeScript, structural typing is the default approach. TypeScript uses structural typing to compare types and determine compatibility. This approach promotes code reusability and flexibility, as types that share the same structure are considered compatible, regardless of their names. However, there are scenarios where nominal typing might be preferred, especially when strong type separation is needed to prevent accidental type compatibility.

Understand the concept of "fresh" and "stale" objects in TypeScript, exploring how the language handles object immutability and mutability.

- **`Fresh & Stale Objects:`** To determine whether an object is fresh or stale, we examine its composition. If the object contains explicit key-value pairs defined directly on its right side, it is considered fresh. On the other hand, if the object references a previously defined object by its name, rather than having its own key-value pairs, it is deemed stale.
In TypeScript, a fresh object is one that is initialized with new key-value pairs on its right side, while a stale object is characterized by the act of assigning an object's name to another object, bypassing the use of distinct key-value pairs.
- **`Assigning Objects to Different Interfaces:`** To practically apply our knowledge, we created two interfaces: "Motorbike" and "Car". "Motorbike" had properties like model, mileage, and speed, while "Car" had properties "model" and "mileage". We then instantiated two objects, "BMW" using the "Car" interface and "H2R" using the "Motorbike" interface, Interestingly, attempting to assign "H2R" to "BMW" didn't raise errors. However, attempting the opposite – "BMW" to "H2R" – did trigger an error. This highlighted the concept of type compatibility. check Code of the class for example.
- ### [Class 7 Code](https://github.com/usmanashrf/typescript-batch48/tree/main/Morning-section/class-7)
- ### Online Recorded Sessions & videos:
  - Adding Soon
- ## Assignments:
  - `Modeling Online Store Entities` You're building a TypeScript application for an online store. Define the following types and interfaces:
    - Define an interface Product with properties like id, name, price, and category.
    - Create a type Cart that represents an array of Product objects.
    - Define an interface Customer with properties like id, name, and email.
    - Create a type Order that represents an object containing a Customer and a Cart.
    - Implement a function that calculates the total price of products in the cart.

  - `Building a Blog System` Imagine you're developing a TypeScript application for a blogging platform. Create the following types and interfaces:
    - Define an interface Author with properties like id, name, and bio.
    - Create a type Comment that represents an object with author (of type Author), content, and timestamp.
    - Define an interface Post with properties like id, title, content, author (of type Author), and an array of Comments.
    - Implement a function that sorts posts based on their number of comments.

  - `Social Media Platform` Develop a TypeScript application for a social media platform. Define the following types and interfaces:
    - Define an interface Profile with properties like id, username, bio, and an array of Posts.
    - Create a type Like that represents an object with user (of type User) and timestamp.
    - Define an interface Comment with properties like id, user (of type User), content, and timestamp.
    - Implement a function that finds the most liked post and the user who posted it




Remember, each class builds on the previous ones, deepening your understanding of TypeScript and web development concepts. For detailed information about each topic, refer to the provided [class slides](https://docs.google.com/presentation/d/1-7Kb3laJjJ68mOTF9v0fHImk5vTol0CeE43Sg8hoUXQ/mobilepresent#slide=id.gcb9a0b074_1_0).

Feel free to explore the topics further through online resources, video tutorials, and hands-on practice. Happy learning!


