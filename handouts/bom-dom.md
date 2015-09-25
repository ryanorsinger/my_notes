### 23 June 2015

### Lightning review
The BOM is how JS intracts with the web browser.
The `window` object is the global object.
Define a new variable `var newVariable = ", then call it. Now call it with window.
alert, confirm, and prompt are made available through the window object

- `var intervalID = setInterval(someFunction, interval)` runs `someFunction` every `interval` milliseconds.
- `clearInterval(intervalId)`
- `setTimeout()`
- `setTimeout()` accepts two parameters, a function and an interval
- `setTimeout()` works more like an egg timer. It runs once and then it's done.
-  `var timeoutId = setTimeout(somefunction, inverval);`
- `var btnToClick = document.getElementById('btnToClick');`
- `var listItems = document.getElementsByTagName('li');`
- `var evenElements = document.getElementsByClassName('even');`

### Accessing or modifying Element properties

- demo `interval_items.innerText` vs. `interval_items.innerHTML`
- Demo `var username = document.getElementById('username')` then `username.value`
- Demo `username.value = "myUsername"`
- Demo `document.btnToClick.innerText = "Drink me!"`;
- demo `document``document.body.style.backgroundColor = '#0FF';` 

### Adding Event Listeners
- Demo adding a button that changes the background color
- Demo adding a button that increments a click counter
- Demo changing the innerText of the clickCounter button to show current click count
- Demo adding a button and eventlistener + function that changes the background after a delay.

### JS Calculator


BONUS = make a login form with an email address along with a password and password confirmation input. the JS should validate that the email is an email and the password and password confirmation match. they should provide real time output back to the user.