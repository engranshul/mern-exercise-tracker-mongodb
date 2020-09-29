## My learnings from this project

* in this project i have learnt how to intergrate react bootstrap frontend
  with backend..both frontend and backend have been created as a part of 
  one project
* creating navbar with the help of react and bootstrap and in each navbar
  this is a form that makes request to a particular backend api upon 
  submission
* concept that data that is accessed together should be stored together
* mongo db atlas : cloud mongo database
* in mongo atlas we can see and update our collections 
* in mongo db atlas there are bunch of cloud providers : aws,azure etc
* diff ways to connect with mongo db : connect with mongo shell,connect
  your application,connect with mongo db compass
* mongo db object id has unix timestamp + random value + count.  
* mongo db object id is guaranteed to be unique across mongo collection
* two ways to check if mongoose is connected to mongo db 
  a) in callback check for error..
     looks like "err" in function (err) {} has a special   meaning
  b) listen for an event like connected or error
* concept of creating an router and exporting it from that file
* in models we define schema 
* casting in node js example
  Number(req.body.duration);
  Date.parse(req.body.date);
* in jsx we use className instead of class
* bootstrap npm package : npm i bootstrap
* npm i react-router-dom : helps to map urls path to specific components
* u can print this to see what it is referring to..In class based components
  some method binding is required in constructor so that this doesnt refer to
  undefined
* arrays map method usage
* react date picker to show date picker on browser
* axios.post returns a promise
* on form submission we can call an api
* concept of handling what we show when the user first lands on a component..
  componentDidMount is used of this case in class based components..

### additional details    
* Video Tutorial: https://www.youtube.com/watch?v=7CqJlxBYj-M
* Article Tutorial:
  https://medium.com/@beaucarnes/learn-the-mern-stack-by-building-an-exercise-tracker-mern-tutorial-59c13c1237a1
* This project was bootstrapped with 
  [Create React App](https://github.com/facebook/create-react-app).




  