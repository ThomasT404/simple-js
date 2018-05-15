# Simple-JS
Simple js is made for simplify your javascript code without use jquery

# Functions s.

### Post and Get request

```javascript
s.get('data.html', 'search=example', function(html){
    //Callback function
})

s.get('data.html', function(html){
    //Callback function
})

s.get('data.html', s.jsontourl([{ name: 'simple', value: 'js'}]), function(html){
    //Callback function
})

s.post('data.html', s.jsontourl([{ name: 'simple', value: 'js'}]), function(html){
    //Callback function
})

s.post('data.html', 'search=example', function(html){
    //Callback function
})
```

### DOM manipulation

```javascript
s.select('#container').toggleClass('superclass')
```