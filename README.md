# JSEpisodeTwo-Demo

[Slides]()

---

### Code Blocks (Arrays)

BLOCK 01 (DEFINING ARRAY)

```javascript
let words = ["stuff", "another", "laugh", "live", "love", "like", "long"];
```

BLOCK 02 (ACCESSING ARRAY VALUES)

```javascript
let words = ["stuff", "another", "laugh", "live", "love", "like", "long"];
console.log(words[4]);
console.log(words[5]);
```

BLOCK 03 (MODIFYING ARRAY VALUES)

```javascript
let words = ["stuff", "another", "laugh", "live", "love", "like", "long"];
words[1] = "miss";
```

---

### Code Blocks (Loops)

BLOCK 01 (CONSOLE LOG ARRAY)

```javascript
let primes = [1, 3, 5, 7, 11, 13, 17, 23];
console.log(primes); // output looks bad
```

BLOCK 02 (CONSOLE LOG ARRAY ELEMENTS)

```javascript
let primes = [1, 3, 5, 7, 11, 13, 17, 23];
console.log(primes[0]); // output looks better, but repeated code is bad.
console.log(primes[1]);
console.log(primes[2]);
console.log(primes[3]);
console.log(primes[4]);
console.log(primes[5]);
console.log(primes[6]);
console.log(primes[7]);
```

BLOCK 02 (WHILE LOOP)

```javascript
let index = 0;
let primes = [1, 3, 5, 7, 11, 13, 17, 23];
while (index < primes.length) {
  // there we go!
  console.log(primes[index]);
  index++;
}
```

BLOCK 03 (FOR LOOP EQUIVALENT)

```javascript
let primes = [1, 3, 5, 7, 11, 13, 17, 23];
for (let index = 0; index < primes.length; index++) {
  console.log(primes[index]);
}
```
