---
-_-
---
[MM](https://MahadevMata)

9-8-2021 10:08 AM Svn mass

```
React
16-8-2021
CDN using get
```

```html
<!-- Note: when deploying, replace "development.js" with "production.min.js". -->
<script src="https://unpkg.com/react@17/umd/react.development.js" crossorigin></script>
<script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js" crossorigin></script>

<!-- Load Babel v6 -->
<!--    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>-->
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>

<body>

<script type="text/babel">
    class App extends React.Component {
        render() {
            return (
                    // jsx (javascript xml)
                    <div className="app-content">
                        <h1>Hi Vish</h1>
                    </div>
                    // limitation
                    // 1. one root element in write all html (jsx)
                    // 2. class in javascript is reserved keyword use className
            )
        }
    }

    ReactDOM.render(<App/>, document.getElementById('app'));
</script>

</body>
```
