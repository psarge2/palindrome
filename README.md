# Phrase object (with palindrome detector)

This is a sample NPM module created as a more elaborate form of an exercise from [*Learn Enough JavaScript to Be Dangerous*](https://www.learnenough.com/javascript-tutorial).

The module can be used as follows:

```
$ npm install --global psarge-palindrome
$ vim test.js
let Phrase = require("psarge-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```
