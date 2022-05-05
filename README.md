# Random element selector

`random-element-selector` returns one randomly chosen element from the passed-in array.

## Setup

Install the package:

```
npm install random-element-selector
```

## Usage

```js
import randomElement from 'random-element-selector';

const myArray = [3, 'cat', 'didgeridoo', { hello: 'World' }, 999];
console.log(randomElement(myArray)); // 'didgeridoo'
console.log(randomElement(myArray)); // 999
console.log(randomElement(myArray)); // { hello: 'World' }
console.log(randomElement(myArray)); // 999
console.log(randomElement(myArray)); // 3
console.log(randomElement(myArray)); // 3
console.log(randomElement(myArray)); // 'cat'
```
