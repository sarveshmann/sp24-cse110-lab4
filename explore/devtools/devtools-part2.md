#### 1. The bug is that when we call the function `calculateSum` on line 7 in `explore.js`, we pass in `num1` and `num2` as type `String`.

#### 2. To fix the problem, convert `num1` and `num2` to type `Number` using Type conversion:

```
document.getElementById("sum").innerHTML = "Sum: " + calculateSum(Number(num1), Number(num2));
```
