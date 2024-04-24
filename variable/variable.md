# Variable in Java Script


Variables are Containers for Storing Data

> JavaScript Variables can be declared in 4 ways:

+ Automatically
+ Using var
+ Using let
+ Using const

## 1. create variable - Automatically 
In this first example, x, y, and z are undeclared variables.
### Example -1 
They are automatically declared when first used:

```js
x = 5;
y = 6;
z = x + y;

```

> [!NOTE]
> It is considered good programming practice to always declare variables before use.


## 2. Create variable - Using var 

> [!IMPORTANT]
> + The var keyword was used in all JavaScript code from 1995 to 2015.
> + The let and const keywords were added to JavaScript in 2015.
> + The var keyword should only be used in code written for older browsers.
### Example -2 
```js
var x = 5;
var y = 6;
var z = x + y;
```

## 2. Create variable - Using let 


### Example -3 
```js
let x = 5;
let y = 6;
let z = x + y;
```


## 4. Create variable - Using const 

### Example -4
```js
const x = 5;
const y = 6;
const z = x + y;
```

## Create mix variable 

### Example -5
```js
const price1 = 5;
const price2 = 6;
let total = price1 + price2;
```



+ The two variables price1 and price2 are declared with the const keyword.

+ These are constant values and cannot be changed.

+ The variable total is declared with the let keyword.

+ The value total can be changed.

### When to Use var, let, or const?
 >[!TIP]
> 1. Always declare variables
> 2. Always use const if the value should not be changed
> 3. Always use const if the type should not be changed (Arrays and Objects)
> 4. Only use let if you can't use const
> 5. Only use var if you MUST support old browsers.



## Rule for Creating Variable. 
+ All JavaScript variables must be identified with unique names.
+ These unique names are called identifiers.
+ Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).
+ The general rules for constructing names for variables (unique identifiers) are:
+ Names can contain letters, digits, underscores, and dollar signs.
+ Names must begin with a letter.
+ Names can also begin with $ and _ (but we will not use it in this tutorial).
+ Names are case sensitive (y and Y are different variables).
+ Reserved words (like JavaScript keywords) cannot be used as names.












