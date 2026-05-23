# PracticeQuetion-in-javascript

## 1. Can we connect JavaScript Directly with Actual Database. can you give reason of it ?

```javascript
a) Yes;
b) No;
c) Sometime;
d) Some Database
```

<details>
<summary>View Answer</summary>

Answer: b) No

Reason: Frontend JavaScript should not directly connect with database because it exposes credentials and creates security risks.

</details>

---

## 2. Which of the following is NOT a JavaScript data type?

```javascript
a) String
b) Boolean
c) Float
d) Undefined
```

<details>
<summary>View Answer</summary>

### Answer:
c) Float

### Reason:
JavaScript does not have a separate Float datatype.  
All decimal numbers are stored as `Number`.

### My Comment:
Many beginners think Float is a separate datatype like C/C++, but in JavaScript both integer and decimal values come under the `Number` type.

</details>

---

## 3. Which symbol is used for single-line comments in JavaScript?

```javascript
a) //
b) /*
c) #
d) <!--
```

<details>
<summary>View Answer</summary>

### Answer:
a) //

### Reason:
`//` is used for single-line comments in JavaScript.

Example:

```javascript
// This is a comment
console.log("Hello");
```

### My Comment:
Comments improve code readability and help developers understand the code easily.

</details>

---

## 4. What will typeof null return?

```javascript
a) "null"
b) "object"
c) "undefined"
d) "string"
```

<details>
<summary>View Answer</summary>

### Answer:
b) "object"

### Reason:
This is a historical bug in JavaScript.

```javascript
typeof null
```

returns:

```javascript
"object"
```

even though `null` is not actually an object.

### My Comment:
This is one of the most famous JavaScript interview questions.

</details>
