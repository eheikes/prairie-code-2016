# Translation Pitfalls

[@austhomp](https://twitter.com/austhomp) / [github.com/austhomp](https://github.com/austhomp)

## Culture Differences

* numbers: [http://www.statisticalconsultants.co.nz/blog/how-the-world-separates-its-digits.html](http://www.statisticalconsultants.co.nz/blog/how-the-world-separates-its-digits.html)
* [https://blog.codinghorror.com/whats-wrong-with-turkey/](https://blog.codinghorror.com/whats-wrong-with-turkey/)
* time zones
* addresses
* phone numbers
* personal names: [https://www.w3.org/International/questions/qa-personal-names](https://www.w3.org/International/questions/qa-personal-names)
* language

## Top 3 things

1. Avoid cut-off text. Translated text can be much longer.
2. Concatenate strings at your peril: grammar/word order, gender
3. Use libs for i18n / g11n

## More on translation

* Have someone who kinda knows the language to skim the translations.
* Idioms, memes, partial phrases are tricky

## Locales

* Start with simple phrasing for your basic language (e.g. "en")
* Provide translations with informal/fun phrasing for specific locales (en-GB, en-US)
* Text in images -- SVG is good, otherwise need multiple versions of images
* Some significant differences in language between locales

## Cultural connotations / differences

* color
* icons (e.g. checkmark can mean no/wrong)
* flags for choosing language/locale
* gestures

## Plurals

* English: singular, other
* French: <2, other
* Chinese, Japanese: other
* Irish: don't ask
* Russian: get out yer calculator

## Context Clues

* homonyms are hard
* context splits (e.g. German has light blue and dark blue)
* naming nuances (e.g. Fook Yue)

## Translation Errors

* Machine translation is getting better, but not perfect
* Have someone who kinda knows the language to skim the translations.

## Takeaways

* 80/20 rule

## Misc

* Check the language HTTP header, but still offer a locale/language dropdown to choose
