# simple-password-generator
A simple JavaScript password generator that does what you need it to.

## Usage
```js
const generate = require("@bytedefined/simple-password-generator");

// First generation type
const password = generate();
console.log(password); // => "gllusviuarzrdopp" //string

// Second generation type
const password = generate({
    length: 20,
    numbers: true,
    uppercase: true,
});
console.log(password); // => "ZpfgmfLdw1RQ3wYgGFro" //string
```
