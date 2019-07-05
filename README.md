# JavaScript sessions
1. Variables - numbers and strings (objects)
1. functions
1. What is document?
1. how to create elements?
1. how to set attributes?
1. flow controls (if and else)
1. loops using for
1. `use strict` mode
```javascript
(function(){
    'use strict';
})()

someVar = 10;
```
1. closures - private variables and accessing it
```javascript
function Employee(name) {
    var _firstName = name;

    this.getFirstName() {
        return _firstName;
    }
}

var emp1 = new Employee('Agilesh');
emp1.getFirstName();
```