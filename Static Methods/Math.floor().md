**The Math.floor() static method always rounds down and returns the largest integer less than or equal to a given number.**

``` javascript
console.log(Math.floor(5.95));
// Expected output: 5
```

**Description**

Because floor() is a static method of Math, you always use it as Math.floor(), rather than as a method of a Math object you created (Math is not a constructor).

``` javascript 

Math.floor(-Infinity); // -Infinity
Math.floor(-45.95); // -46
Math.floor(-45.05); // -46
Math.floor(-0); // -0
Math.floor(0); // 0
Math.floor(4); // 4
Math.floor(45.05); // 45
Math.floor(45.95); // 45
Math.floor(Infinity); // Infinity
```