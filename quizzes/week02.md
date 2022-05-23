# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Var, let, and const are the 3 ways to declare a variable.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
The definition of a function is a subprogram for a specific task
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The SOLID acronym starts for:
  S- single responsibility principle
  O- open closed principle
  L- liskov substitution principle
  I- interface segregation principle 
  D- dependency inversion principle
      big thanks to c#corner.com for actually having the acronym and definition right at the beginning of their article.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
pineapple's current position is at fruit[2]. I know this because it is the third string in the array and arrays start counting the first item at 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
The  if Conditional in JavaScript is the if statement along with the else and else if statements.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
I++ or I+=1
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for document object model and the first file accessed to render it is the html file.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
The 9 ECMAScript types defined by MDN are Data properties, accessor properties, boolean, null, undefined, number, bigint, string, and symbol
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are the names of the things being passed to the function and arguments are the values nested inside of the parameters.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive data type in JavaScript are single pieces of data while reference value are objects that can store many different types of data.
```