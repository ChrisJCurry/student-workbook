# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
  let, var, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
  a block of code designed to perform a particular task
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
  S - Single responsibility principle
  O - Open-Closed principle
  L - Liskov substitution principle
  I - Interface segregation principle
  D - Dependency inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
  2. Arrays start at 0, and it's in the 3rd position.
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
  let testVar = (biggerNum > smallerNum) ? "is bigger"(true) : "is smaller" (false)
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
  incrementor, i++.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
  Document Object Model. index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
  1. undefined
  2. boolean
  3. number
  4. string
  5. bigint
  6. symbol
  7. object
  8. function
  9. null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
  parameters are at the declaration of the function. They store a copy of the data passed through them.
  arguments are passed at the call of the function. They pass their data through the parameters
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
  primitives store the actual values, whereas references store a copy of the value.
```