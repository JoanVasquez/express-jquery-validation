# This is a simple Node Js project with Express Validation and JQuery Validation

In this code I will show you how to implement **validation in Client and Server** side using **express-validator** and **JQuery Validation**. It is an small project that demonstrate the validation on a form. If this code helped you to solve your problem, please help with a coffee. Thanks.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AFSV8TQBVW6LC)

## Instruction
Remember to make **npm i or npm install** in the root of the app to install the **modules**.

## Structure
* index.js -> Our app server.
* public -> Static files (CSS, JS, IMGS).
    * js
        * validation.js -> Our script to validate with **JQUERY VALIDATION**
* app -> routes and views
    * routes
        * home.js
    * views
        * home.html

### Dependencies of this project
```JSON
"dependencies": {
    "body-parser": "^1.18.3",
    "express": "^4.16.3",
    "express-session": "^1.15.6",
    "express-validator": "^5.2.0",
    "hbs": "^4.0.1"
  }
```

### Validations resources
[Express Validator!](https://github.com/chriso/validator.js#validators)

[JQuery Validation!](https://github.com/jquery-validation/jquery-validation)

### Demonstrations

![Form](https://raw.githubusercontent.com/JoanVasquez/express-jquery-validation/master/form.PNG)

![Validation](https://raw.githubusercontent.com/JoanVasquez/express-jquery-validation/master/jqueryvalidation.PNG)
![Validation](https://raw.githubusercontent.com/JoanVasquez/express-jquery-validation/master/expressvalidation.PNG)