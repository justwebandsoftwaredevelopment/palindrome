# Phrase Object (With Palindrome Detector)

This is a sample NPM module created in [*Frontmatters*](https://www.frontmatters.com/javascript-tutorial) by St. Asuzu Alfred P. M..

The module can be used as follows:

```
$ npm install --global alfred-palindrome
$ vim test.js
let Phrase = require("alfred-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```
