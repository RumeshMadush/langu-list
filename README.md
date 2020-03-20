# langu-list
Map Stores ISO ISO 3166 language codes to language names and vice versa.




# example 

``` js
var languages = require('langu-list')();

console.log(languages.getLanguageName('sk_SK')); // Sinhala
console.log(languages.getLanguageCode('Sinhala')); // sk_SK
```

# methods

Usage:

```
var languages = require('language-list')();
```
All input is case-insensitive.

## getLanguageName(languageCode)

Expects the language code.
Returns the language name for that language code.
If not found, it returns `undefined`.

## getLanguageCode(languageName)

Expects the language name.
Returns the language code for that language.
If not found, it returns `undefined`.

## getLanguageNames()

Returns an array of all language names.

## getLanguageCodes()

Returns an array of all language codes.

## getData()

Returns an array of all language information, in the same format as it gets imported.

# install

``` cli
npm i langu-list
```

# license

BSD
