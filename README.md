# MERN Stack Interview
video link - https://www.youtube.com/watch?v=j6jWMxlquEI

## React JS

1. What is JSX?
* A syntax extension to JavaScript.
* Using JSX, you can write HTML structures in the same file containing JavaScript code.

2. What is Virtual Dom?
* React keeps a lightweight representation of the Real DOM in the memory, and that is known as the Virtual DOM.
* Maintaining Real DOM is much slower than manipulating Virtual DOM.
* When the state of an object changes, Virtual DOM changes only that object in the real DOM instead of updating all the objects.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/2134f7a5-4aab-41b3-a6c1-359cf0fdd840)

3. What are React Extensions? Name a Few.
* Flux - the application architecture that Facebook uses for building web applications.
* React Native - React Native lets you build mobile apps using only JavaScript.

4. What is an Event in React? How do you create one?
* An event is an action that can be triggered by a User or any System event like pressing a key, a mouse click, etc.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/24b56edf-c7ce-4fb9-b691-bd17e77932d1)

5. What are the Components in React JS?
* Components are the building blocks of any React application, and a single app usually consists of multiple components.
* It splits the User Interface into independent, reusable pieces that can be processed separately.

6. What is a State in React? How do you implement it?
* A state is an object that stores the values of properties belonging to a component that could change over a period of time.
* A state can be modified based on the user action or network changes.
* Every time the state of an object changes, React re-renders the component to the browser.
* The state object is initialized in the constructor.
* The state object can store multiple properties.
* this.setState() is used to change the value of the state object.
* A state holds the data that a component renders on the webpage.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/51827060-b2e7-4bf8-b7f7-0ca872091ee9)

7. What is a Higher Order and Pure Components in React?
* A higher-order component is a function that takes a component and returns a new component. It facilitates the reusing of component logic.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/26e338d8-2eb8-4cbf-9df7-e058678dc35b)

* A React component is considered pure if it renders the same output for the same state and props.

8. How do you implement React Routing?
* We can implement using react-router-dom.

## Node JS

### Beginner Node JS Questions

1. What is Node JS?
* Node JS is an open-source, cross-platform JavaScript runtime environment and library for running web applications outside the client's browser.
* It is used for creating server-side web applications.

2. How Node JS works?
* Node JS itself builds on the V8 engine. V8 JavaScript engine is the same engine that runs JavaScript in your web browser.

3. Where can we use Node JS?
* Web Applications
* Distributed Systems
* Network Applications

4. What do you understand by the term I/O?
* Operation or device that transfers data.

5. Explain the difference between frontend and backend development.

Frontend:
 * Frontend refers to the client side of an application.
 * Users can see and interact with.
 * FE Development - HTML/CSS/JS, Angular, React

Backend: 
  * Backend refers to the server side of an application.
  * everything that happens behind the scenes.
  * Communicates with a database to server requests.
  * BE Development - Java, PHP, Python, Node JS

6. What is NPM?
* NPM stands for Node Package Manager.
* Responsible for managing all the packages and modules for Node JS. 

7. What are modules in Node JS?
* Modules are like JavaScript libraries that can be used in a Node JS application to include a set of functions.
* To include a module in a Node Js application, use the require() function with the parenthesis containing the name of the module.

8. Why is Node JS being preferred over other backend technologies like Java and PHP?
* Node Js is really fast.
* NPM facilitates to installation of additional packages.
* Better synchronization of code between server and client due to the same code base.
* Easy for web developers to start using Node Js in their projects as it is a JavaScript library.

9. Which database is more popularly used with Node Js?
* MongoDB
  - NoSQL
  - cross-platform
  - document-oriented
  - high performance
  - high availability
  - easy scalability

10. Mention a couple of popular libraries used in Node JS.
* Express JS - allowed to build APIs more quickly.
* Mongoose - makes connecting an application to  the database a much simpler task.


11. What are the pros and cons of Node JS?
* Pross
  - Fast processing and an event-based model.
  - Uses JavaScript which is known by many developers.
  - There are so many packages.

* Cons
  - Not suitable for heavy computational tasks.
  - Using callback is complex since you end up with many nested callbacks.
  - Dealing with relational databases is not a good option for Node Js.

12. What is the command used to import external libraries?

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/43ae7184-ad7f-4761-82ee-a8712fca209d)

### Intermediate Node JS Questions



 
