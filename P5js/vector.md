## Vector in p5 is undefined

```javascript
p5.Vector; //undefined
```

Sketch of p5-react-wrapper and p5 from function Sketch has the same p5 instance => conflict.

-> Use `p5.constructor.Vector` instead
