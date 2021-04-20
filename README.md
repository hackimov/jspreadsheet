# Usage
1. include jspreadsheetCrack.js to your page, or paste all of code to dev tools console and call generateLicense function
2. call function generate license with your need license params

## Params
- [first arg] - license owner name (string)
- [second arg] - license expire years (integer)
- [third ard] - json encoded array of license domains (string)

## Example of generate license 
```php
generateLicense('alexandr.hackimov', 10, '["yourdomain.com","anotherdomain.com","localhost"]');
```
