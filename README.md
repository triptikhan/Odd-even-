# JavaScript Even and Odd Numbers

## Code
```javascript
const evens = [];
const odds = [];

for (let i = 1; i <= 30; i++) {
  if (i % 2 === 0) {
    evens.push(i);
  } else {
    odds.push(i);
  }
}

console.log('Even numbers:', evens);
console.log('Odd numbers:', odds);
```

## Output
```text
Even numbers: [ 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30 ]
Odd numbers: [ 1, 3, 5, 7, 9, 11, 13, 15, 17, 19, 21, 23, 25, 27, 29 ]
```
