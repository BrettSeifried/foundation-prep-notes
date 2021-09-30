# Day 3 Notes

* Single Quotes for Javascript

[Template for Alchemy](https://github.com/alchemycodelab/alchemy-bootstrap-template)

* .eslintrc is a template to help out ESlint

* Interger = whole. floating = decimal
* decimals are bad for computers, careful with currency and rounding issues

* ` creates a portal to use JS exprssion within the string.
* can only use the ${} with a backtick

* log, 2nd option, enter. create console log

``` // logs first in string
let colors = ['red', 'white', 'blue'];
console.log(colors[0]);

// logs Blue
const theColorBlue = colors[2];
console.log(theColorBlue);

// changes blue to purple
colors[2] = 'purple';
console.log(colors);

// add to end
colors.push('orange');
console.log(colors);

//Remove last
colors.pop();
console.log(colors);

// removes first element
colors.shift();
console.log(colors);
```

* highlight tab right, shift+tab left

*button#idname = 
    ```
   <button id="name"></button>
    ```