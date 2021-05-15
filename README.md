# reactapp
## for learn about to you how to import and export file in reactjs
### index.js
```javascript
import React from 'react';
import ReactDOM from 'react-dom';
import {add,sub,mul,div} from './App';

ReactDOM.render(<><h1>keshav agarwal</h1>
<ol>
  <li> this two number sum is {add(10,3)}</li>
  <li> this two number subtraction is{sub(10,3)}</li>
  <li> this two number multipuly is{mul(10,3)}</li>
  <li> this {div(10,3)}</li>
</ol>
</>,
  document.getElementById("root")
  )
  ```
#### App.jsx
```javascript
function add(a,b){
    return a+b;
}
function sub(a,b){
    return a-b;
}
function mul(a,b){
    return a*b;
}
function div(a,b){
    return a/b;
}
export {add,sub,mul,div}
```
