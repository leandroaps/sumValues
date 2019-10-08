# sumValues
This snippet can be used to find the sum of two or more numbers or arrays.

```
const sum = (...arr) => [...arr].reduce((acc, val) => acc + val, 0);
```

**Usage:**
```
sum(1, 2, 3, 4); // 10
sum(...[1, 2, 3, 4]); // 10
```
