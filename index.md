#### Copy by value and reference

1. Go through the code and answer

```js
let x = 10;
let y = 'Hello';
let a = x;
let b = y;
```
Answer the following after looking at above code along with the reason:

- Value of x // 10
- Value of y // "Hello"
- Value of a // 10 
- Value of b // "Hellp"

2. Go through the code and answer

```js
var x = 10;
var y = 'Hello';
var a = x;
var b = y;
a = 5;
b = 'test';
```
Answer the following after looking at above code along with the reason:

- Value of x // 10
- Value of y // "Hello"
- Value of a // 5
- Value of b // "test"

3. Go through the code and answer

```js
var users = ['sam', 'aman'];
var usersCopy = users;
users.push('nathan');
```
Answer the following after looking at above code along with the reason:

- Value of users //  ['sam', 'aman','nathan']
- Value of usersCopy //  ['sam', 'aman','nathan']
- Length of the users variable // 3
- Length of the usersCopy variable // 3

4. Go through the code and answer

```js
let a = { language: 'Javascript' };
let b = a;

console.log(a); // 1
console.log(b); // 2

a.language = 'Python';

console.log(a); // 3
console.log(b); // 4
```
Answer the following after looking at above code along with the reason:

- Output of 1 // { language: 'Javascript' }
- Output of 2 // { language: 'Javascript' } 
- Output of 3 // { language:  'Python' }
- Output of 4 // { language:  'Python' }

5. Go through the code and answer

```js
let username = 'Arya';
let usernameCopy = username;
let userInfo = {
  name: 'John',
};
let userCopy = userInfo;
```
Answer the following after looking at above code along with the reason:

- username == usernameCopy; // true
- username === usernameCopy; // true
- userInfo === userCopy; // true
- userInfo == userCopy; // true
- userInfo.name == userCopy.name; // true
- userInfo.name === userCopy.name; // true
- username == userInfo.name; // false

6. What does the following code print to the console?

```js
var game = { game: 'Vollyball' };
console.log(game === game);
```

// Output - true


7. What does the following code print to the console and Why?

```js
var game = { title: 'Vollyball' };
var sameGame = { title: 'Vollyball' };
console.log(game === sameGame);
```
// Output - false