# JS Introduction Worksheet

The purpose of this document is to help you note important concepts in the introductory JS material.  It is suggested to read/watch the material and answer the questions as you encounter the answers.

## Variables

1.  Explain what the following keywords do and how they differ:

`let` -

`var` -

`const` -


2.  Explain the difference between backticks ( \` ) and strings enclosed with double quotes ( " ) and single quotes ( ' ).




3.  Explain how falsy values in JavaScript differ from those in Ruby?






4.  Create an Array of 3 strings which are pet names.




5.  Take the string above and add, "Scar" to the list.




6.  Replace that element with "Simba".





7.  In Ruby what do JavaScript Objects most resemble?




8.  Write code to give `Dylan` a new cat.


```JavaScript
let example1 = {
    firstName: 'Dylan',
    lastName: 'Israel',
    address: {
        city: 'Austin',
        state: 'Texas'
    },
    age: 30,
    cats: ['Milo', 'Tito', 'Achieles']
};

// Your code goes here




```



9.  Finish the code below to print out:  "You may drive", if age is greater than or equal to 16, and isLicensed is true.  If age is greater than or equal to 16, but isLicensed is false print out "You need a license".  Otherwise print out "You'll need to beg a ride."


```JavaScript
let age = // some number from the keyboard
let isLicensed = // true or false from the keyboard












```


10.  What do switch statements most resemble in Ruby?



11.  Explain what the 3 parts of the `for` loop do.

```JavaScript

for(let i = 0 /*part 1*/; i < 10 /*part 2*/; i++ /*part 3*/) {

  console.log(`i = ${i}`);
}
```



12.  Convert this ruby method into a JavaScript function.


```ruby
def calculateSalesTax(subtotal)
  TAX_RATE = 0.08;
  return subtotal * TAX_RATE;
end 
```
