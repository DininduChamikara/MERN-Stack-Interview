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

1. What does event-driven programming mean?
* If something happens, something else happens as a response. An event can be anything, such as the pressing of a key or clicking a mouse button.

2. What is an Event Loop in Node JS?
* An event loop is an endless loop, which waits for tasks, executes them and then sleeps until it receives more tasks.

3. What is an Event Emitter in Node JS?
* EventEmiter is a class that holds all the objects that can emit events.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/45206060-90ca-4c78-8693-8acc03c8eec6)

4. What are the two types of API functions in Node JS?
* Asynchronous, non-blocking functions
* Synchronous, blocking functions.

5. What is a package.json file?
* Holds the metadata about a particular project.
* package.json is present in the root directory of any Node application or module.

6. How would you use a URL module in Node JS?
* It is a built-in module that helps in splitting up the web address into a readable format.

7. What is the Express JS package?
* Express is a flexible Node JS web application framework that provides a wide set of features to develop both web and mobile applications.

8. What are the Streams in Node JS?
* Streams are objects that let you read data or write data continuously.
* There are 4 types of streams:
  - Readable
  - Writable
  - Duplex: both readable and writable
  - Transform: Streams that can manipulate the data while it is being read or written.

9. How to create a simple server in Node JS that returns Hello World?

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/a810aed7-39d7-413f-a434-c85ad0f38c9d)

10. Explain asynchronous and non-blocking API in Node JS.
* All the APIs of the Node JS library are asynchronous which means non-blocking.
* Node.js based server never waits for an API to return data, instead it moves to the next API after calling it, and a notification mechanism of events of Node.js responds to the server for the previous API call.

11. How do we implement async in Node.js?

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/52888297-4cb5-4603-be91-4d40b4897005)

12. What is the purpose of module.exports?
* A module in Node JS is used to encapsulate all the related codes into a single unit fo code which can be interpreted by shifting all related functions into a single file.
* You can export a module using module.exports so that it can be imported in another file using require keyword.

13. What is a callback function in Node JS?
* A callback is a function called at the completion of a given task and this prevents any blocking, and allows other code to be run in the meantime.


## MongoDB

1. Explain what is MongoDB and its features?
* MongoDB is a NoSQL database that stores large volumes of data in the form of documents.
* NoSQL can be faster than SQL since the SQL basically follows the normalized structure and so, when quiering sometimes need to connect more tables in SQL.

2. What are some alternative NoSQL databases to MongoDB?
* Cassandra - scalability and high availability
* Amazon DynamoDB
* redis

3. What type of NoSQL database is MongoDB?

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/eb6864d3-288e-469a-b61c-a0b8e280cf18)

4. How does MongoDB store data?
* MongoDB stores data records as documents (specifically BSON documents) which are gathered together in a collection.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/bc4999af-6cf7-4ba9-8f86-0e2feee02daf)

5. MongoDB is a Schema-less database. If yes, how do you create Schema in MongoDB?
* The schema of a database describes the structure of the data to be stored.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/04b49f80-b0b3-4bc9-9c15-59c626b4935a)

6. How is MongoDB different from SQL and better than MySQL?
* MongoDB is a document-oriented NoSQL database used for high-volume data storage.
* SQL is a programming language used to communicate with and manipulate relational database like MySQL.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/3a533c8a-cb70-42e0-a794-7f3d504e5ea2)

* MongoDB is better at handling unstructured data.
  
7. How does indexing work in MongoDB?
* Indexes provide users with an efficient way of querying data.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/7978675a-396c-405f-bdd2-afbb7cfe63d1)

8. What is MongoDB replication and Sharding?
* Replication means duplicating the same data across multiple MongoDB servers.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/c485c1a0-bd52-41ca-8f02-c57f9c8740f0)

* Sharding is a method of distributing data across multiple Databases MongoDB supports developments with large data sets and high throughput operations via Sharding.

10. Explain Horizontal and Vertical scaling.
* Vertical scaling refers to adding more resources to your server (database or application server remains one) as on demand.
* Horizontal Scaling involves adding more processing units or physical machines to your server or database.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/d9f3dcdb-380d-462b-b15a-5f975c0d6805)

11. What are Replica Sets? Explain primary and secondary replica sets.

![image](https://github.com/DininduChamikara/MERN-Stack-Interview/assets/73112985/ea7397a1-53d4-4111-bcfe-ff93b057e157)

12. What is meant by _id field in MongoDB?
* _id is the field that uniquely identifies a document in the MongoDB collection. If you insert a document that does not contain the _id field, then MongoDB automatically generates the unique id.



 
