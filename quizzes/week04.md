# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Asynchronous code is code that does not necessarily run in order. Some requests for data that go outside the code can be instructed to wait and then run code based on if what data was returned. While waiting for that data, the rest of the code is still being ran.

Synchronous code means that the code has to run in the exact order that it was written and called in. If there is a request for outside data and there is a time delay to receive a response, the code will effectively stop running until some sort of response is received.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a method that is linked to some sort of action in the code. Like data changing and triggering a ProxyState.on or maybe a click or hover event being attached to an HTML element.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The O in SOLID stands for the open-closed principle, which states that objects should be open for extension but closed from modification.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a function that is stored while the program continues to run. When the data the callback is set to wait for is received, then the callback could be ran if its conditions are met. Because callback are placed inside other functions that specify when/if something should be ran, they are functions that take imput from another function, they are considered higher order functions.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is a sort of value given to data that hasn't been received from an async code, and 'promises' that a value will be given to it in the future. Errors from promises are captured with catch methods and specify what actions the code will take if the criteria for received data is not met.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Get, Post/put, and delete. There are some others but they seem like delineations of some of the 3 already listed
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API stands for Application Program Interface.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The Service is responsible for making calls to the APIs.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
The purpose of encapsulation is to separate out code into different files that can only interact with each other through specifically designated ways. It is meant to be a constraint on what can be sent in and how those inputs are given to a encapsulated program, than a security feature of code. Although it does make files harder to mess with, its main purpose it to filter what is being sent in so that the inputs work with the code inside.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
A successful request response code will come in the form of some sort of 200s ok response.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A 500 error is a internal server response error telling you it does not know how to handle the situation you sent to it.
```