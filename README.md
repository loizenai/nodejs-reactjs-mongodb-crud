# Reactjs Nodejs MongoDB CRUD Example – MERN Stack Application

Tutorial at: [Reactjs Nodejs MongoDB CRUD Example](https://loizenai.com/reactjs-nodejs-mongodb-crud/)

In the tutorial, I introduce how to build an “React.js Nodejs CRUD MongoDB Example” project with the help of Ajax to POST/GET/PUT/DELETE requests with step by step coding examples:

– Nodejs project produces CRUD RestAPIs with MongoDB database using the supporting of Mongoose ODM.
– React.js project will consume the Nodejs CRUD RestAPIs by Ajax then show up on Reactjs component’s views.

## List to do:

– I draw a fullstack overview Diagram Architecture from React.js Frontend to MongoDB database through Nodejs RestAPI backend.
– Develop Nodejs CRUD RestAPIs with the supporting of Mongoose ODM.
– Implement Reactjs CRUD application with Ajax fetching APIs to do CRUD request (Post/Get/Put/Delete) to Nodejs Backend APIs.
– I create a testsuite with a number of integrative testcases with CRUD RestAPI requests from Reactjs to do CRUD requests to Nodejs RestAPIs Server and save/retrieve data to MongoDB database.

## Overall Architecture System: Reactjs + Nodejs + MongoDB

![Reactjs + Nodejs + MongoDB system](https://loizenai.com/wp-content/uploads/2020/11/React.js-Nodejs-MongoDB-Diagram-Architecture.png)

- We build a backend: Nodejs CRUD Application with MongoDB that provides RestAPIs for POST/GET/PUT/DELETE data entities and store them in MongoDB database.
- We implement React.js CRUD Application that use Ajax to interact (call/receive requests) with Nodejs CRUD application and display corresponding data in Reactjs Component.

## Nodejs MongoDB CRUD Design Application

![Nodejs MongoDB CRUD Design Application](https://loizenai.com/wp-content/uploads/2020/11/Nodejs-MongoDB-CRUD-Example.png)

We have 4 main blocks for the application:

- For building RestAPIs in Nodejs application, we use Express framework.
- For interacting with database MongoDB, we use Mongoose ODM.
- We define APIs URL in router.js file
- We implement how to process each API URL in controller.js file
- We use Bootstrap and JQuery Ajax to implement frontend client.

## Reactjs CRUD Application Design

![Reactjs CRUD Application design](https://loizenai.com/wp-content/uploads/2020/11/Reactjs-CRUD-RestAPI-Application-Frontend-Architecture-Diagram-4.png)

- React.js components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
- Ajax is used by Reactjs component to fetch (post/put/get/delete) data from remote restapi by http request

Reactjs CRUD Application defines 5 components:

- Home.js is used serve as the landing page for your app.
- AppNavbar.js is used to establish a common UI feature between components.
- CustomerList.js is used to show all customers in the web-page
- CustomerEdit.js is used to modify the existed customer
- App.js uses React Router to navigate between components.

## Integrative Project Goal

![Integrative Project Goal](https://loizenai.com/wp-content/uploads/2020/11/Project-Goal-Customer-List-3.png)

Tutorial: [Reactjs Nodejs MongoDB CRUD Example](https://loizenai.com/reactjs-nodejs-mongodb-crud/)


Related posts:
- [How to Integrate Reactjs with Nodejs Tutorial](https://loizenai.com/integrate-reactjs-nodejs-tutorial/)
- [Reactjs Node.js MySQL CRUD Example](https://loizenai.com/reactjs-nodejs-crud-mysql/)
- [Reactjs Nodejs PostgreSQL Example](https://loizenai.com/reactjs-nodejs-postgresql-example/)
- [Reactjs Nodejs MongoDB CRUD Example – MERN Stack Application](https://loizenai.com/reactjs-nodejs-mongodb-crud/)
