---
-_-
---
[MM](https://MahadevMata)

16-8-2021 Lesson 5 State

```text
jsx comment error

babel comments code

// <!-- <button onClick={}>Submit</button> -->
// babel.min.js:1 Uncaught SyntaxError: /Inline Babel script: Unexpected token (28:25)
```

### React Form Input Bindings

```js

handleChange = (e) => {
    this.setState({
        name: e.target.value
    })
}


<form action="" onSubmit={this.handleSubmit}>
    <input type="text" onChange={this.handleChange}/>
    <button>Submit</button>
    {/* // <!-- <button onClick={}>Submit</button> -->*/}
</form>

```

### vue js framework

    very easy Form Input Bindings
    no addition method write - sort code

```text
data(){
    return{
     form: {
            name: ''
       } 
    }
}

v-model using direct 

<input v-model="form.name" placeholder="edit me">
<p>Message is: {{ message }}</p>
```