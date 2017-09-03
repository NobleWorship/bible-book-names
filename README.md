# bible-book-names
Bible books names in various languages in JSON format


## Usage:
```
var bookName=  require('bible-book-names');

// index is the number(n'th) of the book in the order of the bible.

var anyBook= bookName['en'][index];  // for english
//or
var anyBook= bookName['fr'][index]; //for french
```
You can also iterate through it
```
bookName['en'].forEach(function(book) {
    console.log(book);
}, this);

```

## Contribute ?

You can add more translations to contribute :)

Thank you in advance!