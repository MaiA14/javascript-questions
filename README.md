# js-ques

1) **What is var let and Const in Javascript?**\
   All of those are diffrenet ways to define variables while var is in global scope, let and const are in block scope. const is useable when you are not willing to change your
   variable in comparison to let.
2) **What is hoisting?**\
  Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution. Inevitably, this means that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local.
3) **What are the advantages of typescript? give examples to features in ts.**
   - Code scalability with “Interface oriented development”
   - TypeScript helps you dealing with growing teams.
   - Types have a proven ability to enhance code quality and understandability.\
   features: interefaces.
4) **What is the difference between switchmap and mergemap?**\
  switchMap cancels previous HTTP requests that are still in progress, while mergeMap lets all of them finish. 
5) **What are the differences between css variables and scss variables?**\
   SASS variables are replaced with their values as the preprocessor produces its CSS output long before the browser interprets the code, while CSS custom properties are  
   evaluated by the browser at runtime.
   Custom properties (sometimes referred to as CSS variables or cascading variables) are entities defined by CSS authors that contain specific values to be reused throughout a 
   document. They are set using custom property notation (e.g., --main-color: black;) and are accessed using the var() function (e.g., color: var(--main-color);).
6) **What is async pipe?**\
   The async pipe subscribes to an Observable or Promise and returns the latest value it has emitted. When a new value is emitted, the async pipe marks the component to be 
   checked for changes. When the component gets destroyed, the async pipe unsubscribes automatically to avoid potential memory leaks.
7) **What is critical rendering?**\
   The Critical Rendering Path is the sequence of steps the browser goes through to convert the HTML, CSS, and JavaScript into pixels on the screen. Optimizing the critical 
   render path improves render performance.The critical rendering path includes the Document Object Model (DOM), CSS Object Model (CSSOM), render tree and layout.
8) **What is the difference between promise and observable?**\
   a Promise is always asynchronous, while an Observable can be either synchronous or asynchronous, a Promise can provide a single value, whereas an Observable is a stream of 
   values (from 0 to multiple values), you can apply RxJS operators to an Observable to get a new tailored stream.
9) **What is DOM tree JavaScript?**\
   According to the Document Object Model (DOM), every HTML tag is an object. ... Nested tags are “children” of the enclosing one. The text inside a tag is an object as well. 
   All these objects are accessible using JavaScript, and we can use them to modify the page.
10) **Is JavaScript multithreaded?**\
    JavaScript is single threaded and only one line of code can be executed at any given time. 
11) **Let's say you have complex calculation where will you calculate it?**\
    Web Workers makes it possible to run a script operation in a background thread separate from the main execution thread of a web application.
12) **What is debounce function?**\
    The debounce() function forces a function to wait a certain amount of time before running again. The function is built to limit the number of times a function is called.
    A quick example:  you have a resize listener on the window which does some element dimension calculations and (possibly)  repositions a few elements.  That isn't a heavy 
    task in itself but being repeatedly fired after numerous resizes will really slow your site down.  
13) **What is the difference between classical inheritance and prototypal inheritance?**\
    - Class Inheritance: instances inherit from classes (like a blueprint — a description of the class), and create sub-class relationships: hierarchical class taxonomies.
      Instances are typically instantiated via constructor functions with the `new` keyword. Class inheritance may or may not use the `class` keyword from ES6.
    - Prototypal Inheritance: instances inherit directly from other objects. Instances are typically instantiated via factory functions or `Object.create()`. 
      Instances may be   composed from many different objects, allowing for easy selective inheritance.
14) **Angular vs React**\
     React seems simpler at first sight, and it takes less time to start working on a React project. However, that simplicity as the main advantage of React is neutralized 
     because you have to learn to work with additional JavaScript frameworks and tools. Angular itself is more complex and takes quite some time to master.
15) **Suppose the server sends a ping every so often. How will the client communicate with him?**\
    setTimeout, Promises, async await.
16) **What is the difference between Subject and BehaviorSubject?\**
    A BehaviorSubject holds one value. When it is subscribed it emits the value immediately. A Subject doesn't hold a value.
17) **What is change detection?\**
    Angular includes a mechanism that detects change detection loops. In development mode, the framework runs change detection twice to check if the value has changed since 
    the first run. In production mode change detection is only run once to have a better performance.
