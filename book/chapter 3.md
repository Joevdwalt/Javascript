# JavaScript syntax basics
A program does has multiple lines. Each line ends in a semi-colon or ;. 

Example: 

``` javascript
console.log('hello');
```

is a typical line in javascript. A javascript program consists of many lines. Each command will be on its own line and will execute sequencially. 

Example:

``` javascript
console.log('hello');
console.log(1+2);
```

## Variables
A variable can be though of a place to store a value in memory temporarily. Most programs will have multiple different variables that change as the program runs.
In order to use a you must first declare it. A variable is declare by using the "var" keyword.

Example:

```
var price;
```

In the example I have declared a variable called price. After I have declared the variable, I can assign a value to it. 

Example:

``` javascript
var price;
price = 20;
```

Using the console I can print the value of price

``` javascript
var price;
price = 20;
console.log(price); 
```

Running the example: 
1. create a new file called chapter_3.js
2. copy the following into the file 

``` javascript
var price;
price = 20;
console.log(price); 
```

3. run the command node ./chapter_3.js

``` bashshell
$ node ./chapter_3.js
```

## Functions and parameters 
When building programs, we don't want all our code in one place. We try to apply the concept of not repeating ourselfs (dry - don't repeat yourself). The reason for this are plentiful and is outside the scope of this book. 

A way to logically group functionality is to write the code in a function. In simple term a function is a set of programming instructions the you can invoke at different places in your program code. 

The syntax for a javascript function as follows. 

``` javascript
    function HelloWorld(){
        console.log('hello world');
    }
```

To invoke a function you can "call"




