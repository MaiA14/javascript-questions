# js-ques

1) **What is var let and Const in Javascript?**\
   All of those are diffrenet ways to define variables while var is in global scope, let and const are in block scope. const is useable when you are not willing to change your
   variable in comparison to let.
2) **What is hoisting?**\
  Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution. Inevitably, this means that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local.
3) **What are the advantages of typescript? give examples to features in ts.**\
   - Code scalability with “Interface oriented development”
   - TypeScript helps you dealing with growing teams.
   - Types have a proven ability to enhance code quality and understandability.
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
    
