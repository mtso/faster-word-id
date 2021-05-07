# faster-word-id

Faster, simpler generator of random ID strings composed of words (than `word-id`).
The default word list guarantees word segment lengths between 4 and 7.

## Usage

```js
const generateWordId = require('faster-word-id')

const wordId = generateWordId({
  wordCount: 2, // default 2
  join: '-', // default '-'
  // wordList: [...], default dictionary contains 1525 words of length 4-7.
})

console.log(wordId) // e.g. 'choose-smile'
```
