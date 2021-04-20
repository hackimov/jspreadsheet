https://jspreadsheet.com/ License generator

# Usage
1. Include jspreadsheetCrack.js to your page, or paste all of code to dev tools console.
2. Call function generate license with your need license params.

## Params
- [first argument] - license owner name (string)
- [second argument] - license expire years (integer)
- [third argument] - json encoded array of license domains (string)

## Example of generate license 
```php
generateLicense('alexandr.hackimov', 10, '["yourdomain.com","anotherdomain.com","localhost"]');
```
