>[!SUMMARY]- Table of Contents

>- [[Java_Script#Java_Script (Part-1)|Java_Script (Part-1)]]
>    - [[Java_Script#Variables|Variables]]
>    - [[Java_Script#Data Types|Data Types]]
>        - [[Java_Script#Numbers in JS|Numbers in JS]]
>    - [[Java_Script#Operations in JS|Operations in JS]]
>    - [[Java_Script#NaN in JS|NaN in JS]]
>    - [[Java_Script#Operator Precedence|Operator Precedence]]
>    - [[Java_Script#let, const & var keywords|let, const & var keywords]]
>        - [[Java_Script#Const Keyword:|Const Keyword:]]
>        - [[Java_Script#Var Keyword|Var Keyword]]
>    - [[Java_Script#Practice Qs:|Practice Qs:]]
>    - [[Java_Script#Assignment Operators|Assignment Operators]]
>    - [[Java_Script#Unary Operators|Unary Operators]]
>    - [[Java_Script#Practice Qs:|Practice Qs:]]
>    - [[Java_Script#Identifier Rules|Identifier Rules]]
>        - [[Java_Script#CamelCase|CamelCase]]
>    - [[Java_Script#Boolean in JS|Boolean in JS]]
>    - [[Java_Script#TypeScript|TypeScript]]
>        - [[Java_Script#What is TypeScript?|What is TypeScript?]]
>    - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#Strings in JS|Strings in JS]]
>    - [[Java_Script#String Indices|String Indices]]
>        - [[Java_Script#Concatenation|Concatenation]]
>    - [[Java_Script#null & undefined in JS|null & undefined in JS]]
>    - [[Java_Script#Practice Qs:|Practice Qs:]]
>- [[Java_Script#JavaScript (Part 2)|JavaScript (Part 2)]]
>    - [[Java_Script#Console.log()|Console.log()]]
>    - [[Java_Script#Linking JS File|Linking JS File]]
>    - [[Java_Script#Template Literals|Template Literals]]
>    - [[Java_Script#Operators in JS|Operators in JS]]
>    - [[Java_Script#Comparison Operators|Comparison Operators]]
>    - [[Java_Script#Comparison for Non-numbers|Comparison for Non-numbers]]
>    - [[Java_Script#Conditional Statements|Conditional Statements]]
>    - [[Java_Script#If statement|If statement]]
>    - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#Else if Statement|Else if Statement]]
>    - [[Java_Script#Else Statement|Else Statement]]
>    - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#Nested If-else |Nested If-else ]]
>    - [[Java_Script#Logical Operator|Logical Operator]]
>        - [[Java_Script#Logical AND|Logical AND]]
>        - [[Java_Script#Logical OR|Logical OR]]
>        - [[Java_Script#Logical NOT !|Logical NOT !]]
>        - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#truthy & falsy|truthy & falsy]]
>    - [[Java_Script#Switch Statement|Switch Statement]]
>    - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#Alerts & Prompts|Alerts & Prompts]]
>- [[Java_Script#JavaScript (part 3)|JavaScript (part 3)]]
>    - [[Java_Script#String Methods|String Methods]]
>    - [[Java_Script#Trim methods|Trim methods]]
>    - [[Java_Script#String are immutable in JS|String are immutable in JS]]
>    - [[Java_Script#ToUpperCase and ToLowerCase|ToUpperCase and ToLowerCase]]
>    - [[Java_Script#String Methods with Arguments-indexof|String Methods with Arguments-indexof]]
>        - [[Java_Script# IndexOf| IndexOf]]
>    - [[Java_Script#Method Chaining|Method Chaining]]
>    - [[Java_Script#Slice Method|Slice Method]]
>    - [[Java_Script#Replace & repeat Methods|Replace & repeat Methods]]
>        - [[Java_Script#Repeat Method|Repeat Method]]
>    - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#Array (Data Structure)|Array (Data Structure)]]
>    - [[Java_Script#Visualizing Array|Visualizing Array]]
>    - [[Java_Script#Creating Arrays|Creating Arrays]]
>    - [[Java_Script#Arrays are Mutable|Arrays are Mutable]]
>    - [[Java_Script#Arrays Methods|Arrays Methods]]
>    - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#Indexof & includes Method|Indexof & includes Method]]
>    - [[Java_Script#Concatenation & reverse|Concatenation & reverse]]
>    - [[Java_Script#Slice in Array|Slice in Array]]
>    - [[Java_Script#Splice in Array|Splice in Array]]
>    - [[Java_Script#Sort in Array|Sort in Array]]
>    - [[Java_Script#Practice Qs|Practice Qs]]
>    - [[Java_Script#Array reference|Array reference]]
>    - [[Java_Script#Constant Array|Constant Array]]
>    - [[Java_Script#Nested Arrays|Nested Arrays]]
>    - [[Java_Script#practices Qs|practices Qs]]
>- [[Java_Script#JavaScript (Part4)|JavaScript (Part4)]]
>    - [[Java_Script#Loops|Loops]]
>        - [[Java_Script#FOR Loop|FOR Loop]]
>            - [[Java_Script#DryRun:|DryRun:]]
>            - [[Java_Script#Print all ODD numbers (1 to 15)|Print all ODD numbers (1 to 15)]]
>            - [[Java_Script#Print Even numbers (2 to 10)|Print Even numbers (2 to 10)]]
>            - [[Java_Script#Infinite Loops|Infinite Loops]]
>            - [[Java_Script#Print Multiplication Tables for 5|Print Multiplication Tables for 5]]
>            - [[Java_Script#Nested For Loops|Nested For Loops]]
>    - [[Java_Script#While Loop|While Loop]]
>    - [[Java_Script#Favorite Movie|Favorite Movie]]
>    - [[Java_Script#Break Keyword|Break Keyword]]
>    - [[Java_Script#Loops with Array|Loops with Array]]
>    - [[Java_Script#Nested loops with nested Arrays|Nested loops with nested Arrays]]
>    - [[Java_Script#for of loop|for of loop]]
>    - [[Java_Script#Nested for of loop|Nested for of loop]]
>    - [[Java_Script#TODO APP|TODO APP]]
# Java_Script (Part-1)
## Variables
 **What is a Variable?**
**A variable is simple the name of a storage locator**
![alt](./Assets/Pasted%20image%2020240122234041.png)

**Whenever if we want to store any data or information we will be using Variables.
From the above image assume that you have 2 data's 23 & Tony Stark. Now to store these data we will be using variables which are age & name.**

```JS
age = 23;
name = "Tony Stark";
name = 'Tony Stark';
```

**Here for storing a numbers we can directly use the numbers but if you are storing a string we need to use double-quote("") or single-quotes('').**

**To run the above code in console follow below:**
Right click on webpage 
Go to inspect
![alt](./Assets/Pasted%20image%2020240122235254.png)
![alt](./Assets/Pasted%20image%2020240122235404.png)

## Data Types
**Primitive Types**
- Numbers
- Boolean
- String
- Undefined
- Null
- Bigint (Not used much)
- Symbol (Not used much)

**Lets start with basic example lets take a = 25; and now you need to find which type of DataType. So you can easily use (typeof a). we will be seeing a output as number.**

**Here Type-of is a operator which will tell you what type of datatype is storing inside a variable.** 

```JS
a = 25;
typeof a;

b ='Tony stark'
typeof b;

c = true;
typeof d;
```

### Numbers in JS
- Positive(14) & Negative(-4)
- Integers (45, -50)
- Floating numbers - with decimals (4.6, -8.9)

JavaScript will detects automatically what is the type of variables. No need to giving int a =25; like java and other programming languages.

In JavaScript al positive and negatives & float will comes under one datatype which is "number". 

> **When we are storing data in a variable we will be having one particular limit.**

```JS
a = 0.99999999;
we can store the data upto certain limit.below if i increase the limit of 9's then it will round of and give me 1.
a =0.99999999999999999999999;
```

![[Pasted image 20240123231725.png]]

## Operations in JS

```JS
a = 20;
b = 10;

//addition
sum = a + b;
//Subtraction
diff = a - b;
//multiplication
prod = a * b;
//division
div = a / b;
//modulo
rem = a % b;
```

- Modulo (remainder operator)
      12 % 5 = 2
![alt](./Assets/Pasted%20image%2020240123232321.png)
- Exponentiation (power operator)
       2 ** 3 = 8

## NaN in JS
**The NaN global property is a value representing ==Not-A-Number.==**
- 0 / 0
- NaN - 1
- NaN * 1
- NaN + NaN
So in my console if i type 0 / 0 then i will be getting an output is NaN. which means Not-A-Number but if i see type of NaN it will show number. It is a number which is not valid.

![alt](./Assets/Pasted%20image%2020240123233025.png)
```JS
0 / 0;
NaN + 1;
NaN - 1;
NaN * 1;
NaN / 1;
NaN % 1;
NaN ** 1;
NaN + NaN;
```

## Operator Precedence

**This is the general Order of solving an expression.**
- ()
- **
-  ( * ) ,  / , %  ==Note: in obsidian *  is bold so used ()==
- +, -
If you got an big expression to calculate example: 5 + 4 * 16 / 2 + 3 +5.

**In Math's, we will be following a set of rules to calculate a big expression. Which is BODMAS.**
> BO = brackets
> D = Division
> M = Multiplication
> A = addition
> S = subtraction

**So in the same way we will be using some rule in JavaScript. The first precedence is goes to () >> ** >> * , /, % >> +,- .**

Example: (5+2) / 7 + 1 * 2

Here as per the rules we need to first calculate the brackets value which is (5+2)= 7  |  (7) / 7 +1 * 2

Now  Second precedence is power( ** )  but in our example we are not using power so we will be skipping it.  (7) / 7 +1 * 2

Coming to 3rd precedence all 3 are given same equal precedence so we will going left to right in the expression.
 (7) / 7 +1 * 2
 -------------->
 1 + 2 
now we will be performing 4th precedence which is addition 1 + 2 = 3

![alt](./Assets/Pasted%20image%2020240123235258.png)

```JS
(2 + 1) * 3;
3 / 1 + 2 ** 2
4 + 1 * 6 / 2

try by yourself and write it in console to get the answers
```

## let, const & var keywords

**Syntax of declaring variables**
```JS
let age = 23;
age = age + 1;

let cgpa;
cgpa = 8.9;

let num1 = 1;
let num2 = 2;
let sum = num1 + num2;
```

**Till now to declaring a variables we are using like a = 5; but this is not good method. Whenever you are declaring variable for the first time we need to use let a = 5; and after we can use a = a+1 but when we are using for first time we need to use let keyword.**

**Example: square**

![alt](./Assets/Pasted%20image%2020240124225503.png)

```JS
let side =4;
area = side * side; (or) side ** 2;
console.log(area);
```

### Const Keyword:
**Values of constants can't be changed with re-assignment & they can't be re-declared.**

```JS
const year = 2025;
year = 2026; \\ Error
year = year + 1 ; \\Error

const pi = 3.14;
const g = 9.8;
```

![alt](./Assets/Pasted%20image%2020240124230053.png)

**From the above image i have took const newNum =5; now if i want to reassign the value from 5 to 10 that is not possible once we declared the value in const keyword we can't do any changes.**

**Example: finding Area**

![alt](./Assets/Pasted%20image%2020240124230348.png)
### Var Keyword
> Old syntax of writing variables

```JS
var age = 23;
var cgpa = 8.9;

var num1 = 1;
var num2 = 2;
var sum = num1 + num2;
```

## Practice Qs:
![alt](./Assets/Pasted%20image%2020240124230754.png)

## Assignment Operators

```JS
age = age + 1;
age += 1; \\ short form

age = age - 1;
age -= 1; \\ short form

age = age * 1;
age *= 1; \\ short form

age = age / 2;
age /= 2; \\ short form

age = age % 9;
age %= 9; \\ short form
```

**Till now we have saw = operator like let a = 5; let b =10; we have few more assignment operators are given above.**

## Unary Operators

```JS
age = age + 1;
age +=1;
age++; \\increment

age = age - 1;
age -= 1;
age --; \\Decrement
```

**Till now we have learnt about binary operators which means 2. it will run on 2 operands like (a+b, a-b, a /b...etc)**

**In JavaScript we can work on single operands also which is 1 means it is a Unary operator.**

**Lets take one example let me use a year and every year i need to update it.**
```JS
year = 2000;
year += 1; \\2001
year += 1; \\ 2002
year += 1; \\ 2003
year += 1; \\ 2004
year += 1; \\ 2005
```

from above i need to perform same take in order to make it  even more short we will be using year++;.
```JS
year = 2000;
year++; \\2001 
year++; \\2002
year++; \\2003
year++; \\2004
year++; \\2005
```

**We can declare the increment in 2 ways . suppose i am taking a variable. 1 way is i can user a++; 2nd way is ++a; (a-- --a).**
- ++a (pre-increment)
- a++ (post- increment)
- --a (pre-increment)
- a-- (post- increment)

==**Pre-increment ( change, then use)**==
```JS
let age = 10;      \\ here age =10 but we used pre-inc so it                          will become 11 so age = 11
let newAge = ++age; \\ newAge = 11
```
![alt](./Assets/Pasted%20image%2020240124233841.png)
==**Post-increment (use, then change)**==

```JS
let age = 10;      \\ here age = 10 but we used post-inc so it will be same 10 here
let newAge = age++; \\ here in newAge it will change to 10 and after now age value will be changing to 11
```
![alt](./Assets/Pasted%20image%2020240124233911.png)

![[Pasted image 20240124234027.png]]

## Practice Qs:

**What is the value of each variable in each line of code?**
```JS
let num = 5;  \\ 5
	let newNum = num++; \\ 5
newNum = ++num; 
when this step is running the current value of num is 6 due to we used num++ after running that step the actual value of num will be changed so it will become 6. when 3rd statment is running it will change the value to 7 in num and then adds in newNum
```
![alt](./Assets/Pasted%20image%2020240124234909.png)
## Identifier Rules

**All JavaScript variables must be identified with UNIQUE NAMES(identifiers).**

- Names can contain letters, digits, underscores, and dollar signs.(NO SPACE).
- Names must begin with a letter.
- Names can also begin with $ and __ .
- Names are case sensitive (y and Y are different variables).
- Reserved words(like JavaScript keywords) CANNOT be used as names.

![alt](./Assets/Pasted%20image%2020240124235428.png)
### CamelCase
**Ways of writing identifiers**

- camelCase (JS naming conversion)  ||  eg: fullName
- snake_case  || eg: full_name
- PascalCase  || eg: FullName

## Boolean in JS

**Boolean represents a truth value -> true or false/ yes or no**
```JS
let age = 23;
let isAdult = true;

let age = 13;
let isAdult = false;
```


![alt](./Assets/Pasted%20image%2020240125000202.png)
```JS
isAdult = True; \\ we will get error we need to use small t
isAdult = 'True'; \\ will not show error but it will become                          string but not boolean you cna check by                         using
typeof isAdult
'string'
```

**In JavaScript we have one special thing. for any one particular variable type we can change the Type. example i used let a =5; now typeof a is 'number' but if we want to change the type we can do it like a = true; now typeof  a is 'Boolean' .**

**This is not allowed in another programming languages like java c++**

![alt](./Assets/Pasted%20image%2020240125001007.png)

## TypeScript

### What is TypeScript?

**Static Typed, where JS is dynamic typed**
**Designed by Microsoft**

**From the above example we can to know that we can change the type of a variable so we will be calling JS as dynamic typed. **

**Whereas TypeScript is a static Typed we can't change the typeof variable.**
```TS
a = 5;
a = true; \\ we will be getting Error because TypeScript is static
```

```JS
a = 5;
a = true; \\ Here we will not be getting an error because we                 are using JS. JS is dynamic typed
```

## Practice Qs
**Find the errors in the following code?**
```JS
let 1age = 5;
let 2age = 10;

let marks = 75;
let isPass = True;

let isPass = 'true';
```

## Strings in JS

**String are text or sequence of characters**

```JS
let name = "Tony Stark";
let role = 'ironman';
let char = 'a';
let num = '23';
let empty = "";

let sentence = "this is a 'apple'"  \\fine
let sentence = 'this is a "apple"'   \\fine
let sentence = 'this is a 'apple''    \\Error
let sentence = "this is a "apple""    \\Error

Note: we will be using for single charcter ('') if it is a sentence then we will be using ("").
```

## String Indices

let name = "TONY STARK";
![alt](./Assets/Pasted%20image%2020240125002925.png)

name[0] -> 'T'
name[1] -> 'O' .....

**When we are giving any string it will be given a index value like from the above figure. Indexing means position**

```JS
let name = "TONY STARK";
```

**Internally in JS those strings will be given a position. for the first character it will be 0 and continues..... space is also getting an index.**

**This indexing starts from ZERO , so we will be calling it as 0 based indexing.**

**We can also access individual character of a string like below**
```JS
let name = "TONY STARK";
name[0]; \\ will be getting 'T'
name[1];  \\ will be getting 'O'
name[10000];  \\ we will be getting undefined
```

**We can also printout the variable length**
```JS
let name = "TONY STARK"; \\Total we have 9 index staring from 0.
when we are using length it will start from 1 so we will be getting 10.

number.length; #Here length is a property means a special value.

typeof name.length;  \\type wil be number

"Chiranjeevi".length;; \\ this will also show length of string
"Chiranjeevi"[6];
"Chiranjeevi"[0];
```

```JS
let name = "TONY STARK";
name[name.length]; \\ undefined because it is checking for 10th index which is not present we have upto 9th index.

to see 9th index we can use

name[name.length - 1]; \\Showing K
name[name.length - 2]; \\Showing R
name[name.length - 3]; \\Showing A
name[name.length - 4]; \\Showing T
```

### Concatenation
**Adding strings together**

"tony" + "" + "stark" = "tony stark";
"tony" + 1 = "tony1";
![alt](./Assets/Pasted%20image%2020240125004927.png)
## null & undefined in JS
**undefined**
**A Variable that has not been assigned a value is of type undefined**
```JS
let a;
a;

let name;
name;  \\ undefined
typeof name; \\undefined
```

**Null**
**The null value represents the ==intentional== absence of any object value.**
**To be explicitly assigned.**
```JS
let a = null;
a; \\ will get null but not undefine

let year = null;  \\ we dont know year at this point but for later use we will giving null
year = 2000;
year;

let null =4; \\ Error
```

## Practice Qs:
- **Declare your name as a string and print its length in JS.**
- **Declare your first name as a string and print its first character.**
- **Declare your first name  as a string and print its last character.**
- **What is the output of the following code:**
```JS
"apnacollege" + 123;
```
- **What are lengths of an empty string & a string with a single space?**


# JavaScript (Part 2)

## Console.log()
**To write (log) a message on the console**
**If i want to print anything on console we will be using console.log()**
```JS
console.log("Apna College");
console.log(1234);
console.log(2+2);
console.log("apna","college",123);
```

```JS
let num = 123;
console.log("num");  \\ this will print num becuase we used ""

console.log(num);  \\ to get output of a variable use without ""

console.log(1+2);  \\ will be getting 3

console.log("Hello", "world", num, (1+5));
```

**Till now we have used JS in web console from now on we will be using in JS in JS file.**

## Linking JS File

```HTML
<script src="app.js"></script>
```

- Create a html file 
- Create a app.js file
- Now link app.js to html

```JS
console.log("hello world!");

//this is the comment in JS
```

```HTML
<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>test</title>

  <link rel="stylesheet" href="style.css"

</head>

<body>
...........................................
;;;;;;;;;;;;;;;;;;;;;;;;data;;;;;;;;;;;;;;;
<script src="app.js"></script>
</body>

</html>
```

**Script should be coming by the end of </body> tag because firstly it should load all html CSS.**

## Template Literals

**They are used to add embedded expressions in a script**
```JS
let a =5;
let b =10;

console.log(`your pay ${a + b} rupees`); 
\\ here it is not a single quote it is a backtick used it will be present in below of ~ in key word

\\console.log ("Price is", a+b, "rupees.");
```

```JS
let pencil = 10;
let eraser = 5;

let output = "This totla price is :" + (pencil + eraser) + "Rupees.";
console.log(output);

\\ If we ar writing as above code this will work but everytime i need to add + ""(). this will be more content instead of using the above we can use tempalte literals

let pencil = 10;
let eraser = 5;
let output = (`This total price is : ${pencil + eraser} Rupees`);
console.log(output);

\\ or we can directly using in console.log instead of taking output variable

console.log(`This total price is : ${pencil + eraser} Rupees`);
```

**Here system will calculate the value inside ${ a + b} and then it will embed into the string.**

## Operators in JS

- Arithmetic (+, -, * , /, %, ** )
- Unary (++, --)
- Assignment (=, +=, -=, * =, /=, %= etc)
- Comparison
- Logical

**Main use of operators is to do perform the operations. like a+b**
**Here a, b is a operand  & + is a operator.**
```JS
\\Arithmetic

let a = 10;
let b = 5;

console.log(a + b);
console.log(a - b);
console.log(a * b);
console.log(a / b);
console.log(a ** b);
console.log(a % b);

\\Unary
console.log(a++); //10
console.log(++a); //12
```

## Comparison Operators
**Comparison Operator to compare 2 values**
- >    Greater than   
- >=   Greater than or equal to
- <   lesser than
- <= lesser than or equal to
- ==   equal to 
- !=   not equal to
```JS
let age = 18;
console.log(age > 18); //false
console.log(age >= 18);  //True
console.log(age < 18); //false
console.log(age <= 18); //True
console.log(age == 18); //True
console.log(age != 19); //True
3 >5 ;
5 >6;
5<6;
5 >= 6;
0> 5;
0 < -2;
0 > -99;
5 == 5;
5 != 4;
5 == '5' //check this i will be getting true

let n = 5;
let str = '5';

typeof n;
typeof str;
n == str;
```

**Comparison operator will not compare the typeof to make it strict we will be using another operator which is "triple equal to operator" This will compare the value + type also. **

![alt](./Assets/Pasted%20image%2020240125224123.png)

## Comparison for Non-numbers

![alt](./Assets/Pasted%20image%2020240125224425.png)

**From the above example we have compared a with A and we got true how ?**
**Automatically JS will have a predefined values like for a value is 61 and A value is 41 ... using this it will compare the2 operands and shows the results. that number 41 or 61 is called as Uni-code.**

## Conditional Statements
- if-else
- nested if-else
- switch

## If statement
```JS
// SOMED CODE BEFORE IF

if(some condition){
//Do SOMETHING
}

// some code after if 
```

```js
console.log("Before my if statment");
let age = 23;
if(age >= 18) {
	console.log("You can vote");
	console.log("You can drive");
}
console.log("After my if statment");

\\ check the output we can see all statments but what if i change the age to 14?

console.log("Before my if statment");
let age = 14;
if(age >= 18) {
	console.log("You can vote");
	console.log("You can drive");
}
console.log("After my if statment");

\\ Check the output
```

```JS
console.log("Before my if statment");
let age = 23;
if(age >= 18) {
	console.log("You can vote");
	console.log("You can drive");
}
if(age <18) {
	console.log("You can not vote");
	console.log("You can not drive");
}
console.log("After my if statment");

```

```JS
let firstName = "Chiranjeevi";
if(firstName == "Chiranjeevi") {
	console.log(`Welcome ${firstName}`);
}
```

## Practice Qs

**Create a traffic light system that shows what to do based on color.**

```JS
let tlight = "red";
if (tlight === "green"){
	console.log("Vechicals can move now");
}
if (tlight === "orange"){
	console.log("make your vehicals started");
}
if (tlight === "red"){
	console.log("Vechicals mush stop");
}
```

## Else if Statement
```JS
if (condition1){
	 //DO SOMETHING
}
else if (condition2){
	// DO SOEMTHING ELSE
}

else if (condition3){
	//DO SOMETHING ELSE
}
```

**Here  if the 1st condition becomes false then only it will go to second condition if second condition is also false then it will go to 3rd condition. if the 1st condition is true then it will show the content inside that condition and stops there it will not check for else if.**

```JS
let age = 40;
if(age >= 18) {
	console.log("you can vote");
} else if(age < 18) {
	console.log("you can not vote");
}
```

**Note: we can't directly write else if statement to write a else if firstly we need to declare IF statement**

```JS
let marks = 31;

if (marks >= 80) {
	console.log("hey Congrates, you got A+");
} else if (marks >= 60) {
	console.log("hey Congrates, you got A");
} else if (marks >=33) {
	console.log("hey Congrates, you got B");
} else if (marks < 33) {
	console.log("I am sorry, you have failed");
}
```

```JS
let month = "april";

if (month === "january") {
	console.log("Winter is here");
} else if (month === "april") {
	console.log("Summer is here");
}
```

``` JS
let tlight = "red";
if (tlight === "green"){
	console.log("Vechicals can move now");
} else if (tlight === "orange"){
	console.log("make your vehicals started");
} else if (tlight === "red"){
	console.log("Vechicals mush stop");
}
```

## Else Statement

```JS
if(condition1) {
	//DO SOMETHING
}

else {
	//DO SOMETHING 
}
```

**This is helpful when the top conditions all becomes false then else statement comes into picture. here if my if condition becomes false then else condition will run.**

```JS
let age = 18;
if (age >=18) {
	console.log(" you can vote");
	
} else {
	console.log(" you can't vote");
	
}
```

```JS
let color = "e";

if (color === "red") {
	console.log(" stop");
	
} else if (color === "yellow") {
	console.log(" get ready");
	
} else if  (color === "green"){
	console.log(" get ready");
	
} else {
	console.log(" Traffic light is under maintance");
	
}
```

## Practice Qs
**Create a system to calculate popcorn price based on the size customer asked for:

- if size is 'XL', price is Rs. 250
- if size is 'L', price is Rs. 200
- if size is 'M', price is Rs. 100
- if size is 'S', price is Rs. 50

```JS
let size = "XL";

if(size === "XL") {
	console.log("Price is 250 Rs");
	
} else if (size === "L"){
	console.log("Price is 200 Rs");
	
} else if (size === "M"){
	console.log("Price is 100 Rs");
	
} else if (size === "S"){
	console.log("Price is 50 Rs");
} else {
	console.log("out of stoke");
}
```

## Nested If-else 
**Nesting is writing if-else inside if-else statements. it can have many levels.**

```JS
if marks >= 33
	if marks >= 80
		print "0"
	else
		print "A"
else
	print "better luck next time!"
```

```JS
let marks = 45;

if(marks >= 33){
	console.log("pass");
	if(marks >= 80){
		console.log("Grade: O");
	} else{
		console.log("Grade: A");
	}
}else{
	console.log("failed")
}
```

## Logical Operator

**Logical Operators to *combine expressions***
 **&& Logical AND        (exp1)&&(exp2)
 
![alt](./Assets/Pasted%20image%2020240126012131.png)

- Logical AND   &&
- Logical OR       ||
- Logical NOT     !

### Logical AND
| answer | value 1 | value 2 |
| ---- | ---- | ---- |
| T | T | T |
| F | T | F |
| F | F | T |
| F | F | F |
```JS
(5 > 3) && (3 > 1); \\ both are true so true is my output

(5 > 3)  && (1 > 3);  \\ i will be getting false
```

```JS
let marks = 90;

if (marks >=90 && marks >=80) {
	console.log("pass");
	console.log("A+);
} 
```

### Logical OR
| answer | value 1 | value 2 |
| ---- | ---- | ---- |
| T | T | T |
| T | T | F |
| T | F | T |
| F | F | F |

### Logical NOT !
**! Logical Not  !(exp)

| Answer | value |
| ---- | ---- |
| false | !true |
| true | !false |
```JS
let marks = 75;

if (!(marks < 33)) {
	console.log("pass");
	console.log("A+");
}
```

**Whenever we are adding multiple logical operators it will execute from left to right.**
```JS
let marks = 75;

if ((marks > 33 && marks <=80) || !false) {
console.log("pass");
}
```

### Practice Qs

**A "good string"  is a string that starts with letter 'a' & has a length >3.Write a program to find if a string is good or not.
```JS
let string = "abc";

if((string[0] === "a") && (string.length > 3)){
	   console.log("Good string");
} else {
	console.log("Bad string");
}

```

**2. Predict the output of the following code:**

```JS
let num = 12;

if((num%3 === 0) && (num+1 ==15) || (num-1 ==11)) {
	console.log("safe");
} else {
	console.log("Unsafe");
}
```

## truthy & falsy
**Everything in JS is true or false (in Boolean context).**

```JS
if (true) {
	console.log("it has true value");
}  else{
	console.log("it has false value");
}

\\ here we directly used true in condition so it will be given true statment and it will ever run the false statment

\\example:2
if (0) {
	console.log("it has true value");
}  else{
	console.log("it has false value");
}

\\ Here 0 will be getting it has false value menas there is some value inside 0 so we are seeing that its a false and given the flase statment which is:"it has false value".

here we are not comapring 0 with another value but 0 has some inner value that is equal to false
what if i use 1

if (1) {
	console.log("it has true value");
}  else{
	console.log("it has false value");
}

\\ I will be getting true statment.

here we are not comapring 1 with another value but 1 has some inner value rthat is equal to true 

if ("") {
	console.log("it has true value");
}  else{
	console.log("it has false value");  //false
}

if (" ") {
	console.log("it has true value");  //true
}  else{
	console.log("it has false value");
}

\\ from above 2 code i have taken one empty string and one spaced string. empty string will give me false value everytime but where as if i give space it will become true try it

if ("chiru") {
	console.log("it has true value");
}  else{
	console.log("it has false value");
}
```

**This doesn't means their value itself is false or true, but they are treated as false or true if taken in Boolean context.**

**<span style="color:#ffc000">Falsy Values:</span>**
**false, 0, -0, 0n(Biglnt value), ""(empty string), null, undefined, NaN**

**<span style="color:#ffc000">Truthy Values:</span>**
**Everything else**
```JS
let num = -10;

if (num){
	console.log("num is not equal to zero");
} else {
	console.log("num is equal to zero");
}
```

## Switch Statement

**Used when we have some fixed values that we need to compare to**

```JS
let color = "red";

switch(color) {
	case "red" :
		console.log("stop");
		break;
	case "yellow" :
		console.log("get ready");
		break;
	case "green" :
		console.log("you can go now");
		break;
	default :
		console.log("Broken Light");
}
```

## Practice Qs
**Use switch statement to print the day of the week using a number variable 'day' with values 1 to 7.

**1 = Monday, 2=Tuesday & so on**

```JS
let day = 7;

switch(day) {
	case 1 :
		console.log("Monday");
		break;
	case 2 :
		console.log("Tuesday");
		break;
	case 3 :
		console.log("wedsday");
		break;
	case 4 :
		console.log("Thusday");
		break;
	case 5 :
		console.log("friday");
		break;
	case 6 :
		console.log("Sat");
		break;
	case 7 :
		console.log("Sunday");
		break;
	default :
		console.log("Week has only 7 days");
	
}
```

## Alerts & Prompts

**<span style="color:#ffc000">Alert</span> displays an alert message on the page.**
```JS
alert("Something is wrong!");
```

```JS
we have another type of console too which is error. it is same a log. see below snip for reference

console.log("This is a simple log");
console.error("This is a error msg");
console.warn("This is a war msg");
```
![alt](./Assets/Pasted%20image%2020240126110414.png)
**<span style="color:#ffc000">Prompt </span>display a dialog box that asks user for some inputs.**
```JS
prompt("enter your name");
```

![alt](./Assets/Pasted%20image%2020240126110632.png)

```JS
let firstname = prompt("enter your name");
console.log(firstname);
```

![alt](./Assets/Pasted%20image%2020240126110848.png)
![alt](./Assets/Pasted%20image%2020240126110917.png)

```JS
let firstname = prompt("enter your firstname");
let lastname = prompt("enter your lastname");

let msg = (`welcome ${firstname + lastname}!`);
alert(msg)
```

# JavaScript (part 3)
## String Methods
<span style="color:#ffc000">Methods</span> - actions that can performed on objects.
```JS
stringName.method()
```

**Till now we have used one method in our examples which is console.log. Here .log is a method which helps us to print on screen.**

**When we are using () then we can say it is a method like example alert() error() these are all methods. methods which are basically used to perform some actions**
## Trim methods
```JS
let msg = " hello ";
```

 **str.<span style="color:#ffc000">trim()</span>**
**Trims whitespaces from both ends of the string & returns a new one.**
```JS
let msg = "  Hello ";
msg.trim();
msg
output: 'hello'
\\ trim will only remove the spaces from both ends but not in middle of the string suppos like below 

let msg = "Hello   World";
msg.trim();
msg
output: 'Hello   World'
```
**<span style="color:#ffc000">output: "Hello"</span>, but value of msg remains same.**
![alt](./Assets/Pasted%20image%2020240126160801.png)
```JS
let password = promt("set your passowrd");
console.log(password.trim());
```

**Now we will create one variable str and assign a value using spaces. now we need to trim the str variable so i will use str.trim() now all extra spaces has been removed.**

**Now again type str it will shows value with spaces why? because trim method will not change the actual vale of variable but it will creates its own value by removing the spaces. o understand this see the below example

```JS
let str = "  hello  ";
let greet = str.trim();
console.log(greet);   //trim will create a new string will no                           change the actuall str value.
console.log(str) // this will remains same
```

## String are immutable in JS

**<span style="color:#00b050"><b>immutable = will not change.</b></span>**
**No changes can be made to strings**
**Whenever we do try to make changes, a new string is created and old one remains same.**
```JS
let str = "  hello  ";
let greet = str.trim();
console.log(greet);   //trim will create a new string will no                           change the actuall str value.
console.log(str) // this will remains same
```

## ToUpperCase and ToLowerCase

```JS
let str ="Random string";

str.toUpperCase()  "RANDOM STRING"
str.toLowerCase()  "random string"
```

```JS
let name = "Chiranjeevi";
let capname = name.toUpperCase();
let smallname = name.toLowerCase();

console.log(capname);
console.log(smallname);
```

## String Methods with Arguments-indexof

**Argument is a some value that we pass to the method**

```JS
stringName.method(agr);
stringName.method(agr1, agr2);
```

###  IndexOf
**Returns the first index of occurrence of some value in string. Or gives -1 if not found.**
```JS
let str = "ILoveCoding";

str.indexOf("love");   //1
str.indexOf("J");    //-1 (not found)
str.indexOf("o");    //  2 (only 1 index)

I L o v e C o d i n g
0 1 2 3 4 5 6 7 8 9 10

when i am searching for love it will chekc for L and L is in 1st index so it will showcase 1.

when i am searching for o it will check for o and o is present in 2nd & 6 index. here indexof will take only o apperas at the firsttime alone so it will take 2nd index
```

## Method Chaining

**Using one method after another. Order of execution will be left to right**
```JS
let str = "  Chiranjeevi ";
str.toUpperCase().trim();
```

```JS
let msg = "   Hello   ";
let newMsg = msg.trim();
console.log(newMsg);

newMsg = msg.toUpperCase();
console.log(newMsg);


Here we havr trimed the msg and the we have conbverted to uppercase using 2 methods. we can also do like above or we can do it as below which is simple this is called "Method chaining"
it will go from left to right.

let msg = "   Hello   ";
let newMsg = msg.trim().toUpperCase();
console.log(newMsg);

here it will go as left to right means firstly we have used trim method and then Uppcase method so firstly it will do trim and then it will do uppercase.
```

## Slice Method
**Return a part of the Original string as a new string.**

```JS
let str = "ILoveCoding";

str.slice (Start, end);
str.slice(5);                //"Coding"
str.slice(1, 4);             //"love"
str.slice(-num);   = str.slice(length-num) //given negative number
```

**Assume now i want love to print lets check the index of love**
```JS
let str = "ILoveCoding";
I L o v e C o d i n g
0 1 2 3 4 5 6 7 8 9 10

if i want to get only love we will using slice(start, end)

Love chekc what is the start index here for L is 1 and end is 4 and we need to add +1 which is 5 

here ending index will not include it will be (1-4)
we can also write str.slice(start) in this case ending will be str.length means from the start to ending of the str.
```

```JS
let msg = "Chiranjeevi_Dronamraju";

i need only chira now.

C H I R A N J E E V I  _  D  R  O  N  A  M  R  A  J  U
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21
console.log(msg.slice(0, 5)); //A is 4 and we need to +1=5
//JS will not include 5 so 5-1=4

same way i wan only dronamraju

console.log(msg.slice(12)); //D index is 12 and msg.length

//We have not more special thing in slice is -num
str.slice(-num);   = str.slice(length-num)

let msg = "Chiranjeevi_Dronamraju";
console.log(msg.slice(-2)); 
//total length of msg is 21. now we have given -2 so it will do 21 -2 = 19 so i will be getting JU as my output 
console.log(msg.slice(-10));

// string si 21 and i have given 21-10 = 11 so i will be getting D  R  O  N  A  M  R  A  J  U
```

## Replace & repeat Methods
**Searches a value in the string & returns a new string with the value replaced.**

**Note: this will also change only first occurrence like only first 0 will replaced in Love but not coding o  **
```JS
let str = "IIloveCoding";

str.replace("love", "do"); //IdoCoding
str.replace("O", "X"); //IIxveCoding
```

```JS
let name = "Chioanjeevi"

let final = name.replace("o","r" );

console.log(final);

let name = "ChioanjeeviDoh"
let final = name.replace("o","r" ).replace("o","r" ).replace("o","r" );
console.log(final);
//ChiranjeeviDrh
```

### Repeat Method

**Returns a string with the number of copies of a string**
```JS
let str = "Mango";
str.repeat(3); //"MangoMangoMango"

let name = "Chiranjeevi";
name.repeat(5);  //"ChiranjeeviChiranjeeviChiranjeeviChiranjeeviChiranjeevi"
```

## Practice Qs
**1.For the Given String:**
```JS
let msg = "help";
//Trim it & convert it to uppercase
```
**2. For the string -> let name = "Chiranjeevidronamraju", predict the output for the following:**
```JS
name.slice(4,9);
name.indexOf("na");
name.repalce("Apna", "Our")
```
**3. Separate the "college" part in above string & replace 'I' with 't' in it

## Array (Data Structure)

**Linear collection of things**

![alt](./Assets/Pasted%20image%2020240126191008.png)

**Lets assume that we need to store 3 student names till now what we can do is we will create a variable and we will storing it**
```JS
let student 1 = "chiranjeevi";
let student 2 = "John Cena";
let student 3 = "nani";

what if we have 100 student's there will be a lot of variables that we will be coding to avoid this proble, we got Arrays
```

**To create an Array follow below:**
```JS
let Students = ["chiranjeevi", "Johncena", "nani"];
console.log(Students);
```

## Visualizing Array

| <span style="color:#ffc000">**   </span><span style="color:#ffc000">2</span>** | <span style="color:#ffc000">4</span> | <span style="color:#ffc000"> 6</span> | **<span style="color:#ffc000"><span style="color:#ffc000">8</span></span>** | <span style="color:#00b050">value</span> |
| ---- | ---- | ---- | ---- | ---- |
| 0 | 1 | 2 | 3 | <span style="color:#00b050">Index</span> |
```JS
let nums = [2, 4, 6, 8];
console.log(nums);

//We can also access indivual vlaue in array using []
nums[0]; // 2
nums[1]; // 4
nums[2]; // 6
nums[3]; // 8
nums[4]; // undefined
nums.length // 4
typeof nums // object
//Array are object type what is object? we will be learning later
```

## Creating Arrays
**Different ways of creating Array**
```JS
let marks = [99, 10, 53, 80, 70];
let names = ["admin", "bob", "chiru"];
let info = ["nani", 25, 6.1]; //mixed array

//empty arry

let newArr = [];
newArr.length  //0

we can also create a array with using variables like below
[].length;
[1, 2, 3, 4].length;

let info = ["nani", 25, 6.1];
info[0];
//Now we now what i will be getting 0 index of info which is nani but what if i give like below?

info[0] [0];  // this will given 0th index of 0th character value which is 'n'
info[0] [1]; //a
info[0] [2]; //n

//we can also find length of value inside the array using below
info [0].length; //4
```

## Arrays are Mutable

**Values inside of an Arrays can be changed**
```JS
let fruits = ["Mango","Apple","litchi"];
fruits[0] = "Banana";
console.log(fruits);
//outpu: ["Banana","Apple","litchi"];
```

```JS
\\ lets try with str str is immutable but array is mutable

let name = "chiru";
name[0] = "A";
console.log(name); \\ i will be getting chiru only because string are immutable
```

```JS
we can also story our value in any index like below example
let fruits = ["Mango","Apple","litchi"];
fruits[10] = "Banana";
console.log(fruits);
```
![alt](./Assets/Pasted%20image%2020240127004756.png)

## Arrays Methods

<span style="color:#ffc000">Push:</span> Add to end                                     <span style="color:#ffc000">Unshift:</span> add to start

<span style="color:#ffc000">Pop:</span> delete from end & returns it            <span style="color:#ffc000">Shift:</span> delete from start &                                                                                      return it

```JS
#push_method
let cars = ["Aadi", "bmw", "maruthi", "xuv"];

\\Now i need to add another brand toyota to add it we will be using push

cars.push("Toyota");
console.log(cars);
//output:(5) ['Aadi', 'bmw', 'maruthi', 'xuv', 'Toyota']
```

```JS
#POP
let cars = ["Aadi", "bmw", "maruthi", "xuv"];
cars.pop(); // 'xuv'
//It will remove last index value and shows the output
console.log(cars);

//output: (3) ['Aadi', 'bmw', 'maruthi']
```

```JS
#UNSHIFT
let cars = ["Aadi", "bmw", "maruthi", "xuv"];
cars.unshift("rx100");
//unshift help you add your value at the start of the error
console.log(cars);
//output: (5) ['rx100', 'Aadi', 'bmw', 'maruthi', 'xuv']
```

```JS
#shift
let cars = ["Aadi", "bmw", "maruthi", "xuv"];
cars.shift();
//This will remove first value of index in array
console.log(cars);
//output:(3) ['bmw', 'maruthi', 'xuv']
```

## Practice Qs
**For the given start state of an array , change it to final form using methods.**
```JS
start:['january', 'july', 'march', 'august']
final:['july', 'june', 'march', 'august']
```

```JS
let months = ['january', 'july', 'march', 'august'];
months[0] = 'July';
months[1] = 'june';

console.log(months);

#another method
let months = ['january', 'july', 'march', 'august'];
months.shift();
months.shift();

months.unshift(june);
months.unshift(july);

console.log(months);
```
## Indexof & includes Method

<span style="color:#ffc000">indexOf:</span> return index of something

```JS
let primary = ["red", "yellow", "blue"];
                 0       1        2

primary.indexOf("yellow");  //1
primary.indexOf("green");   // -1
primary.indexOf("Yellow");  // -1 because here we have Y
```

<span style="color:#ffc000">includes</span>: search for a value
```JS
let primary = ["red", "yellow", "blue"];

primary.includes("red"); //true
primary.includes("green");  //false
```

## Concatenation & reverse
**<span style="color:#ffc000">concat:</span> merge 2 arrays**
```JS
let primary = ["red", "yellow", "blue"];
let secondary = ["orange", "green", "purple"];

let allcolors = primary.concat(secondary);

console.log(allcolors);
//output:(6) ['red', 'yellow', 'blue', 'orange', 'green', 'purple']

if you see the ouput we got primary arry data first and then we got secondary. if we want make secondary data first then use like below

let allcolors = secondary.concat(primary);

//output: ['orange', 'green', 'purple', 'blue', 'yellow', 'red']
```

**<span style="color:#ffc000">reverse: </span>reverse an array**
```JS
let primary = ["red", "yellow", "blue"];
primary.reverse();

//output:(3) ['blue', 'yellow', 'red']
```

## Slice in Array

<span style="color:#ffc000">**slice: </span>copies a portion of an array**
slice (start, end)

```JS
let colors = ["red", "yellow", "blue", "orange", "pink",  "white"];

colors.slice();
//(6) ['red', 'yellow', 'blue', 'orange', 'pink', 'white']
colors.slice(2);
// (4) ['blue', 'orange', 'pink', 'white']
colors.slice(2, 3);
//['blue']
colors.slice(-2);
//(2) ['pink', 'white']

```

## Splice in Array

**<span style="color:#ffc000">splice:</span> remove / replace / add elements in place**
**splice(start, deleteCount,item0...itemN)**

**<span style="font-style:italic; font-style:italic; color:#ffc000">Note:</span> Slice will not change the array it will copies a portion of an array where as Splice it will do changes in original array**
```JS
let colors = ["red", "yellow", "blue", "orange", "pink",  "white"];

colors.splice(4);
//(2) ['pink', 'white']

colors
//(4) ['red', 'yellow', 'blue', 'orange']

colors.splice(0, 1);
//['red']

colors
//['yellow', 'blue', 'orange']

colors.splice(0,1, "black", "grey");
//['yellow']

colors
//(4) ['black', 'grey', 'blue', 'orange']
```

```JS
let cars = ["Aadi", "bmw", "maruthi", "xuv"];
              0       1       2         3
cars.splice(3); // it will remove xuv and show the removed value

cars.splice(0,1); // telling start from 0th index and remove item so oth index is Aadi so it will remove aadi and shows aadi has removed

car.push("rx200");
car.push ("rx100");
cars;
(5) ['Aadi', 'bmw', 'maruthi', 'rx200', 'rx100'];

cars.splice(0,2); //teling start from 0th index and remove 2 items. in our case AADI and bmw will be removed and shows aadi bmw has removed.
cars
(3) ['maruthi', 'rx200', 'rx100']


cars.splice(0, 0 , "Aadi", "bmw");

//telling start from 0 and removing item is 0 so it will not remove any item from array + on the 0th index add Aaddi & bmw and maruthi will be automatically pushed to last.
 (5) ['Aadi', 'bmw', 'maruthi', 'rx200', 'rx100']

```

```JS
let cars = ["toyota", "xuv", "maruti", "bmw", "ferrari"];

//Now i need to add new item b/w toyota & xuv?

cars.splice(1,0, "rx100");

cars
(6) ['toyota', 'rx100', 'xuv', 'maruti', 'bmw', 'ferrari']

//Now i need to replace rx100 with mercedes

cars.splice(1,1, "mercedes");
(6) ['toyota', 'mercedes', 'xuv', 'maruti', 'bmw', 'ferrari']
```
## Sort in Array

**<span style="color:#ffc000">sort:</span> sorts an array  means  assigning to descending order and vice-versa**
```JS
let cars = ["toyota", "xuv", "maruti", "bmw", "ferrari"];

cars.sort();
(5) ['bmw', 'ferrari', 'maruti', 'toyota', 'xuv']


//example2:

let chars = ['x', 'a', 'd', 'f', 'k']; 
chars.sort();
(5) ['a', 'd', 'f', 'k', 'x']


//sort will not work correctly with numbers
let numbers= [25, 1, 30, 60, 20, 10, 100, 70];
numbers.sort();
(8) [1, 10, 100, 20, 25, 30, 60, 70]
```

==**What will happens when we use sort method. Internally  values in array will converts into string and then it will start sorting.**==

**from above example numbers which are 1 ,10.... those will convert into string values based on that values it will sort the array**

**Sort also will do changes on original array itself**

```JS 
let numbers= [25, 1, 30, 60, 20, 10, 100, 70];
let sortting = numbers.sort();

numbers
(8) [1, 10, 100, 20, 25, 30, 60, 70]
```
## Practice Qs

**1. For the given start state of an array, change it to final form using splice**
```JS
start: ['january', 'july', 'march', 'august']
final: ['july', 'june', 'march', 'august']
```

**2.Return the index of the "JavaScript" from the given array, if it was reversed**
```Js
['c', 'c++', 'html', 'javascript', 'python', 'java', 'c#', 'sql']
```

## Array reference

```JS
[1] === [1]
false
[1]  == [1]
false
```

reference in memory. if i take a string "name" == "name" i will be getting true. if i give === ,  "name" === "name" now also i will be getting true because type of both are strings.

same as above if i compare any array [1] === [1]  i will be getting false. JS is telling both arrays are not equal what if i use == .  [1] == [1] here also i will be getting false. what if i use empty array [] == [] or [] === []
here also i will be getting false. JS is telling both are not same.

Why this is happening it is due to Array reference

whenever we create an array for that particular array in memory it will create a reference variable  and for my array exact location will be different.

Assume let i create a variable let num = [1, 2, 3]. here num is my reference variable and values can be stored anywhere in memory.
only reference variable knows what is the oth indexes of that array.

==Here reference variable will not store the values it will stores address==
![alt](./Assets/Pasted%20image%2020240127164154.png)

```JS
let arr = ['a', 'b'];

let arrCopy = arr;

arrCopy

arrCopy.push('C');

arr

arr == arrCopy;
```
![alt](./Assets/Pasted%20image%2020240127164523.png)
## Constant Array
```JS
const arr = [1,2,3];

//As of our knowledge when we are using const arr means it will not change but this is not the case with array. Now let us add 4 in const array.

arr.push(4);

arr
arr.pop();

arr

even if it is a constant array we can perform some changes, but thing that we can't perform is

1. we can't make the constant array as new array like below

const arr = [1,2,3];
arr = [1,2,3]; // this will give an error

let cars = ["toyota", "xuv", "maruti", "bmw", "ferrari"];
arr = cars; //this is also not possibel
```

## Nested Arrays
**Array of arrays  we can called it as multi-dimension array**

```JS
let num = [ [2,3], [2,4], [4,8] ];

num
1. (3) [Array(2), Array(2), Array(2)]

1. 0: (2) [2, 3]
2. 1: (2) [2, 4]
3. 2: (2) [4, 8]
4. length: 3
5. [[Prototype]]: Array(0)

num.length;
num[0];

num[0] [0];
```

![alt](./Assets/Pasted%20image%2020240127170146.png)

## practices Qs

**Create a nested array to show the following tic-tac-toe game state**

```JS
let tic= [ ['X',' ', 'O'],
		   [' ', 'X', 'O'],
		   ['O', ' ', 'X']];
tic

1. (3) [Array(3), Array(3), Array(3)]

1. 0: (3) ['X', ' ', 'O']
2. 1: (3) [' ', 'X', 'O']
3. 2: (3) ['O', ' ', 'X']
4. length: 3
5. [[Prototype]]: Array(0)

//we can use null also 
let tic= [ ['X','null', 'O'],
		   ['null', 'X', 'O'],
		   ['O', 'null', 'X']];
tic
// if i want 0 in in first line then we can do change like below

tic[0][1] = 'O'
1. (3) [Array(3), Array(3), Array(3)]

1. 0: (3) ['X', 'O', 'O']
2. 1: (3) [' ', 'X', 'O']
3. 2: (3) ['O', ' ', 'X']
4. length: 3
5. [[Prototype]]: Array(0)
```

# JavaScript (Part4)

## Loops

**If i want to print 1 to 10 we can do it like below**
```JS
console.log("1");
console.log("2");
console.log("3");
console.log("4");
console.log("5");
console.log("6");
console.log("7");
console.log("8");
console.log("9");
console.log("10");
```

**what if i want to print 100 number or 10,000 number? if i want to repeat the same process we will be using loops**

### FOR Loop

```JS
for(initialisation; condition; updation) {
	//DO something
}

for (let i =1; i <= 5; i++) {
	console.log(i);
}
```

#### DryRun:

**Lets Dry run the below code**

```JS
for (let i =1; i <= 5; i++) {
	console.log(i);
}
```

**firstly i have take one variable let i = 1 and then it will check the condition i <= 5 which is 1 <= 5 which is true. If it is true then it will execute the statement inside for loop which is console.log(i); = 1. after  that it will do update which is i ++ means 2**

- step-1 : let i = 1;
- Step-2: check the condition;
- Step-3: print the statements inside of for loop
- Step-4: updating

| Output | i values |
| ---- | ---- |
| 1 | i = 1; true; i++ |
| 2 | i=2; 2<=5(true); i++ |
| 3 | i=3; 3<=5(true); i++ |
| 4 | i=4; 4<=5(true); i++ |
| 5 | i=5; 5<=5(true); i++ |
|  | i=6; 6<=5(false); exit form the loop |

**We can also run in backwards**
```JS
for (let i=5; i>=1; i--) {
	console.log(i);
}

for (let i=5; i>=1; i-3) {
	console.log(i);
}

```

#### Print all ODD numbers (1 to 15)
Numbers that are not come in 2 tables those are all odd number like 1,3,5,7,11,13,15.

```JS
for (let i=1; i<=15; i=i+2) {
	console.log(i);
}

for (let i=20; i>=1; i=i-2) {
	console.log(i);
}
```

#### Print Even numbers (2 to 10)

```JS
for(let i =2; i<=10; i=i+2) {
console.log(i);
}
```

#### Infinite Loops
```JS
for (let i=1; i>=0; i++){

}

for (let i=1; i<=5; i--) {

}

for(let i=1; ; i++) {

}
```

#### Print Multiplication Tables for 5

```JS
for(let i =5; i<=50; i= i + 5){
	console.log(i);
}
```

```Js
let n = promt("Write a number");
n = parseInt(n);  //make str to int
for (let i=n; i<n*10; i=i+n){
	console.log(i);
}
```

#### Nested For Loops
```JS
for (let i=1; i<=3; i++) {
	console.log(`outer loop ${i}`);
	for(let j=1; j<=3; j++){
		console.log(i);
	}
}
```

## While Loop

```JS
while(condition) {
	//DO SOMETHING
}
```

```JS
let i =1;

while(i<=5) {
	console.log(i);
	i++;
}
```
**Print 0 to 20 numbers using while loop**

```JS
let i = 0;
while (i <=20) {
	console.log(i);
	i++;
}
```

**Even Numbers**
```JS
let i = 0;
while (i <=20) {
	console.log(i);
	i = i + 2;
}
```

**ODD Numbers**
```JS
let i = 1;
while (i <=20) {
	console.log(i);
	i = i + 2;
}
```

## Favorite Movie
```JS
const favMovie = "Avengers";
let guess = promt("Guess my fav movie");

while ((guess !=favMovie) && (guess != "quite")) {
	guess = promt("wrong guess try again");
	
}

if(guess == favMovie) {
	console.log("Congrats!!");
} else {
	console.log("quite from the game");
}
```

## Break Keyword
```JS
ket i=1;
while(i<=5) {
	if(i == 3) {
		break;
	}
	console.log(i);
	i++;
}
console.log("we used break at 3");
```

```JS

const favMovie = "Avengers";
let guess = promt("Guess my fav movie");

while (guess !=favMovie) {
	if(guess == "quit") {
		console.log("you quit");
		break;
	}
	guess = promt("wrong guess try again");
	
}

if(guess == favMovie) {
	console.log("Congrats!!");
} else {
	console.log("quite from the game");
}
```

## Loops with Array

```JS
let fruits = ["mango", "apple", "banana", "litchi", "orange"];

for(let i=0; i<fruits.length; i++) {
	console.log(i, fruits[i]);
}

// if i want to print only odd numbers in array
let fruits = ["mango", "apple", "banana", "litchi", "orange"];

for(let i=1; i<fruits.length; i=i+2) {
	console.log(i, fruits[i]);
}

//reverse
let fruits = ["mango", "apple", "banana", "litchi", "orange"];

for(let i =fruites.length-1; i>=0; i-- ) {
	console.log(i, fruits[i]);
}
```

## Nested loops with nested Arrays
```JS
let heroes = [["ironman","spiderman","thor"], ["superman","wonder woman","flash"]];

for(let i=0; i<heroes.length; i++) {
	console.log(`List #${i}`);
	for(let j=0; j<heroes[i].length; j++) {
		console.log(heroes[i] [j]);
	}
}
```

## for of loop

```JS
for (element of collection) {
	//Do something
}
```

```JS
let fruits = ["mango", "apple", "banana", "orange"];

for (fruit of fruits) {
	console.log(fruit);
}

for (char of "chiranjeevi") {
	console.log(char);
}
```

## Nested for of loop

```JS
let heroes = [["ironman","spiderman","thor"], ["superman","wonder woman","flash"]];

for(list of heroes) {
	for(hero of list) {
		console.log(hero);
	}
}

let heroes = [["ironman","spiderman","thor"], ["superman","wonder woman","flash"]];

for(list of heroes) {
	for(hero of list) {
		for (hero of list) {
			console.log(hero);
		}
	}
}
```

## TODO APP

- List - to show all todos
- add - to add a todo
- delete - to delete a task
- quit - to exit the todo

```html
<body>
	<h1>To do App</h1>
	<h3>Enter "list" to show all tasks </h3>
	<h3>Enter "add" to add a tasks </h3>
	<h3>Enter "delete" to remove a tasks </h3>
	<h3>Enter "quite" to quit todo</h3>
	<script src="app.js"></script>
<body>
```

```JS
let todo = [];

let req = prompt("please enter your request")

while(true) {
	if(req === "quit") {
		console.log("quitting app");
		break;
	}

	if (req == "list") {
		console.log("----------------");
		for(let i =1; i<todo.length; i++) {
			console.log(i, todo[i]);
		}
		console.log("----------------");
	} else if(req == "add"){
		let task = prompt("please enter the task you want to add");
		todo.push(task);
		console.log("task added");
	} else if ( req == "delete") {
		let idx = prompt("Please enter the task index");
		todo.splice(idx, 1);
		console.log("Tak deleted")
	} else {
		console.log("Wrong request");
	}
	 req = prompt("please enter your another request")
}
```