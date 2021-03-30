#### Javascript Manipulation Of The Dom Document Object Model Course by Laurence Svekis
built in functions and property explained
```js
console.dir() // display the property of the spesified javascript object
console.dir(window) // display the window object property
console.dir(document) // display the document object property
```

#### Get element property by id
```js
var myOutput = document.getElementById("btn1"); // get element by id
console.dir(myOutput); // display element property
```

#### Get element property by class
```js
var myButtons = document.getElementsByClassName("btn); // get element by class name
console.dir(myButtons[1]);
```

#### Get element property by tag name
```js
var myTags = document.getElementsByTagName("div"); // get element by tag name
console.dir(myTags); // display myTags property
```