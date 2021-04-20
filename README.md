# usage
include crack.js to your page, or paste all of code to console and call generateLicense function

call function generateLicense with your need license params

## params
- [first arg] - license owner name (string)
- [second arg] - license expire years (integer)
- [third ard] - json encoded array of license domains (string)

## example of generate license 
```php
generateLicense('alexandr.hackimov', 10, '["yourdomain.com","yourseconddomain.com","anotherdomain.com","localhost"]');
```
