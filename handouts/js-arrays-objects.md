# Agenda

- Function review
- Scope review
- Best practices for managing scope
- Introduce Arrays
- Intro to Objects
- Reading and working with JSON

## Working with arrays

- How to define arrays, assign values, and determine stuff about arrays and elements
- How to iterate across arrays 
    - for loop with `for(var i=0; i < array.length; i++>)`
    - forEach loops with `forEach(function (element, index, array) `
- Manipulating arrays
    - Adding elements with `.push(itemToAddToEnd)` and `.unshift(itemToAddToBeginning)`
    - Remove elements `.pop()` and `.shift()`
    - Reverse array order with `.reverse()`
    - Sort array elements with `.sort()`
- Using `.splice()` to remove, add, and replace elements in an array
- Converting arrays to strings and strings to arrays
    - Split a string into an array with `.split(',')`
    - Join array elements into a string with `.join(',')`

## Introducing objects

- Intro to objects
    - Objects group data and functionality
    - Data items in an object are its properties
    - Functions on an object are called methods
- Creating our own objects with object literal notation
- Setting and accessing properties on objects with dot notation
- Think about some things which may feel like objects already...
    - When we do ``"a string".length`, length accesses a property.
    - And `"some string".toUpperCase()`, toUpperCase() is a method.
    - Think about the CSS you've written. Look at Bootstrap CSS. It looks like an object literal!
    - Imagine using CSS selectors like variables that point to specific **objects** on your page.
- Defining functions on objects (methods)

## JSON - JavaScript Object Notation

- Demo the GitHub api in the browser.
    - Start at https://api.github.com/orgs/twbs/repos/
        - Find the url for the api for the basic Bootstrap repository and go there.
        - Scan the JSON, how many open issues do you see? How many subscribers? 
    - Go to https://api.github.com/users/your-username/repos and check it out!