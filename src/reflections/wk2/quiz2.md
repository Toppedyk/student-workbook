# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, & const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a subprogram designed to perform a particular task.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S: Single Responsibility Principle, a function or class should only have one purpose each.

O: Open/Closed Principle, software entities classes, modules, functions should be open for extension, but closed for modification

L: Liskov Substitution Principle, objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program

I: Interface Segregation Principle, many client-specific interfaces are better than one general-purpose interface

D: Dependency Inversion Principle, depend upon abstractions, not concretions
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
index 2, in a zero based index the first element is index 0. 
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them.name)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if, for, while
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
incrementer ,i++
```

```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, the html file renders the dom and we use JS to manipulate it. 
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined 
Boolean 
Number 
String 
BigInt 
Symbol 
Object
Function 
Null

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
a parameter is what is used when the function is defined and the argument is what is passed in when the function is invoked
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
The basic difference is that primitive variables store the actual values, whereas reference variables store the addresses of the objects they refer to
```