# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
  C stands for create, R for read, U for update, and D for delete.
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
  The Create crud action corresponds to Post http request. The reading action represents the Get request. Update with Put, and delete is pretty self explanitory with its corresponding http request also being delete. 
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
  ORM stand for Object Relational Mapper. The ORM we use when communicating with MongoDB is Mongoose.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
  Post and Put both include a body. 
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
  The first blank is a syncronous coding model, and the second is a asyncronous coding model.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
  import mongoose from "mongoose"
  let Schema = mongoose.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
  Middleware is a almost plug in to the running software that adds some sort of functionality that is not included in the original software. 
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
  For the life of me I cannot remember the names, find them on google or anything.
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
get/?tag=winter
```