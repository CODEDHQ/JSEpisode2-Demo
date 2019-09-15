# JSEpisodeTwo-Demo

[Slides](https://docs.google.com/presentation/d/1dkovfExxp06AMyyvZ2Vr5i4H6CuDikzGNVZrzUMsOwk/)

---

All demos should be done in `script.js` file of an [`HTML` repl](https://repl.it/languages/html)

### Code Blocks (Arrays)

BLOCK 01 (DEFINING ARRAY)

```javascript
const instructors = ["Asis", "Hamsa", "Fawas", "Huss", "Lailz", "Mshary"];
```

(explain the real meaning of `const`)

BLOCK 02 (ACCESSING ARRAY VALUES)

```javascript
console.log(instructors[0]);
console.log(instructors[2]);
console.log(instructors[6]);
```

BLOCK 03 (MODIFYING ARRAY VALUES)

```javascript
instrutors[5] = "Mishmish";
```

---

### Code Blocks (Array Properties)

BLOCK 01 (ARRAY LENGTH)

```javascript
console.log(instructors.length);
```

BLOCK 02 (PUSH)

```javascript
instructors.push("Laila B");
```

BLOCK 03 (POP)

```javascript
const lastInstructor = instructors.pop();
console.log(lastInstructor);
```

---

### Code Blocks (Loops)

BLOCK 01 (WHILE LOOP - NO ARRAY)

```javascript
let userInput = "";
while (userInput !== "supersecretpassword") {
  userInput = prompt("What's the password?");
}
```

BLOCK 02 (SAY HELLO)

```javascript
console.log(`Hello, I'm ${instructors[0]}`);
console.log(`Hello, I'm ${instructors[1]}`);
console.log(`Hello, I'm ${instructors[2]}`);
console.log(`Hello, I'm ${instructors[3]}`);
console.log(`Hello, I'm ${instructors[4]}`);
console.log(`Hello, I'm ${instructors[5]}`);
```

BLOCK 03 (WHILE LOOP - WITH ARRAY)

```javascript
let i = 0;
while (i < instructors.length) {
  console.log(`Hello, I'm ${instructors[i]}`);
  i++;
}
```

BLOCK 04 (FOR LOOP EQUIVALENT)

```javascript
for (let i = 0; i < instructors.length; i++) {
  console.log(`Hello, I'm ${instructors[i]}`);
}
```
