# _Pig Latin Translator_

#### By _**Christopher Neal & Christy Welch**_

#### _A simple application that allows users to convert text to **tHiS stYLe wRItiNg**_

## Technologies Used

* _HTML_
* _CSS_
* _Bootstrap_
* _Javascript_
* _jQuery_

## Description

_This project was created for Epicodus bootcamp to show proficiency in arrays and looping._
_This program converts inputted text into pig latin following the language requirements. The program also preserves the punctuation and capitalization of the original text._

## Setup/Installation Requirements

* _Clone the [repository](https://github.com/ChristopherMNeal/pig-latin) from GitHub or download and open the Zip on your machine._
* _Open index.html in your preferred browser_

## Known Bugs

* _None at this time_

## Future Updates

* _Refactor to use RegEx_

## License

_[MIT](https://opensource.org/licenses/MIT)_

Copyright (c) _2021_ _Christopher Neal & Christy Welch_

## Support and Contact Details
* _christopher.m.neal@gmail.com_

Describe: pigLatinTranslator()

Test: "It returns a single word string that beings with a vowel with "-way" appended."
Code: pigLatinTranslator("ate");
Expected Output: "ate-way"

Test: "It returns a single word string following previous Pig Latin rules regardless of capitalization."
Code: pigLatinTranslator("AtE")
Expected Output: "AtE-way"

Test: "It returns a word with the consonant(s) at the end plus -ay from a single word beginning with consonant(s)."
Code: pigLatinTranslator("cat")
Expected Output: "at-cay"

Test: "It returns a word with the consonants including 'qu' at the end plus -ay from a single word beginning with consonants including 'qu.'"
Code: pigLatinTranslator ("squeal")
Expected Output: "eal-squay"

Test: "It returns an empty string if there is no input."
Code: pigLatinTranslator("")
Expected Output: ""

Test: "It will keep word-initial puctuation intact."
Code: pigLatinTranslator("¿creates")
Expected Output: "¿eates-cray"

Test: "It will keep word-final punctuation intact."
code: pigLatinTranslator("creates?")
Expected Output: "eates-cray?"

Test: "It will keep multiple instances of punctuation intact."
Code: pigLatinTranslator("creates...")
Expected Output: "eates-cray..."


Describe: paragraphTranslator()

Test: "It returns a string of words all following previous Pig Latin rules."
Code: pigLatinTranslator("Cats squeal")
Expected Output: "at-cays eal-squay"
