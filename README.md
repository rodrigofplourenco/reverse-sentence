# reverse-sentence
Reverses the words of a sentence.

## Install
```sh
npm install @rodrigofplourenco/reverse-sentence
```

## API
```js
require("reverse-sentence") => Function
reverse(sentence) => String
```

## Example
```js
const reverseSentence = require("reverse-sentence");
const sentence = "Hello Rodrigo Lourenço!"; 
const reversed = reverseSentence(sentence); 
console.log(reversed) // Lourenço! Rodrigo Hello
```

## License
ISC