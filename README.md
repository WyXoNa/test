# Simple Usage :

```javascript
const wyxo = require('wyxo')
const app = wyxo()

app.get('/', (req, res) => {
    res.send('Hello World')
})

app.listen(3000)
```

# Installation

```
$ npm install wyxo
```

