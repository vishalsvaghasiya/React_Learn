---
-_-
---
[MM](https://MahadevMata)

16-8-2021 Lesson 5 State

state using dynamic dom in change

```js
state = {
    name: 'vish',
    age: 24
}

handleClick = (e) => {
    //this.state.name = 'isha';
    this.setState({
        name: 'isha',
        age: 26
    });
    console.log(this.state);
}
```

Notes:

```txt
https://www.w3schools.com/js/js_arrow_function.asp
Arrow functions were introduced in ES6.
Arrow functions allow us to write shorter function syntax:
function 6 in not direct work state
----------------------------------------------
js = () => { }
value of state using * this * keyword function inside direct use value?
=> arrow function use
function 7 in not direct work state
console.log(e.target);
Uncaught TypeError: Cannot read property 'state' of undefined
```
