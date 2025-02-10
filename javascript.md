# What is JavaScript?
JS is a programming language. We use it to give instructions to the computer.

Input (code)-----> computer--->  output


## Setting up VS Code </>

It is a free & popular code editor by Microsoft



Our 1st JS Code

Console.log is used to log (print) a message to the console

console.log("Hello word");

Variables in JS

Variables are containers for data

### Variable Rules
Variable names are case sensitive; "a" & "A" is different.

Only letters, digits, underscore() and $ is allowed, (not even space)

Only a letter, underscore() or S should be 1st character.

Reserved words cannot be variable names.

### let, const & var

var: Variable can be re-declared & updated. A global scope variable.

e let: Variable cannot be re-declared but variable. can be updated. A block

const: Variable cannot be re-and or updated. A block scope variable.

### Data Types in JS

Primitive Types: Number, String, Boolean, Undefined, Null, Bigint, Symbol



### Comments in JS

Part of Code which is not executed

//This is a single line comment

/*This is a multi-line. comment.*/

### Operators in JS

Used to perform some operation on data

#### Arithmetic Operators

+, -,* *,1

• Modulus

• Exponentiation

• Increment

.Decrement



#### Assignment Operators


== *=%=

**=



#### Comparison Operators

Equal to ==

Not equal to !=

Equal to & type ===

Not equal to & type !==

>, >=, <, <=



#### Logical Operators

Logical AND &&

Logical OR ||

Logical NOT !



## Conditional Statements
To implement some condition in the code

If Statement

let color: 
if(mode== "dark-mode"){
color= "black";
}
Conditional Statements

if-eise Statement

let color; If (mode "dark-mode") ( color "black";

} else {

color "white":



Conditional Statements

else-if Statement

Lflage 18) (

console.log("Junior");

console.log("senior");

else if (age 60) ( } else {

console.log("middle

Mona

Operators in JS

Ternary Operators

condition ? true output: false output

age > 18? "adult": "not adult";



Loops are used to execute a piece of code again & again

for Loop

for



console.log apna college");

:

Loops in JS

Infinite Loop: A Loop that never ends.


Loops in JS

while Loop

while (condition) (

// do some wank

College

Loops in JS

do-while Loop

do [

// do some work

} while (condition);


Loops in JS

for-of Loop

for (let val of strVar) {

do some wo

na colle

}

Loops in JS

for-in Loop

for (let key in objvar) {

}

//do some work



Strings in JS

String is a sequence of characters used to

Create String

let str "Apna Colle

Apnaresent

text de

String Length

str.length

String inves

str[0], str[1]. str[2]

Template Literals in JS

A way to have embedded expressions in strings

this is a template literal

String Interpstation

To create strings by doing substitution of planet

string text Sexpression) string text

String Methods in JS

These are built-in functions to manipulate a string

str.toUpperCase()

str.toLowerCase()

str.trim()/ removes whitesp

"Apna College

String Methods in JS

str.slice(start, end?) Il returns part of string

str1.concat( str2) // joins str2 with str1

str.replace( searchvalnem

str.charAt(idx)


Arrays in JS

Collections of items

Create Array

let heroes =["ironman", "hulk", " thor", "batman"

let marks [96, 75, 48,

83.667 na College

let info ["rahul", 86, "Delhi" ];

Arrays in JS

Array Indices

arr[0], arr[1], arr[2]

0

Ona

2

3 4

College

Looping over an Array

Print all elements of an array






**Arrays in JS

Array Met

Push(): add to end

Pop(): delete from end & return

Apna College

toString(): converts array to string

Arrays in JS

Array Mothe

Concat(): joins multiple arrays & returns result

Unshift(): add to start



shift(): delete from start & return.

Arrays in JS

Array Methods

Slice(): returns a piece of the array

slice startida, endidx)

College

Splice(): change original array (add, remove, replace) Anna

splice( startidx, delCount, newEll..)

Let's Practice

Qs. Create an array to store companies-> "Bloomberg", "Microsoft", "Uber", "Google", "IBM", "Netflix"

a. Remove the first company from the array

b. Remove Uber & Add Olai


c. Add Amazon at the end
**


Arrays in JS

Array Met

Push(): add to end

Pop(): delete from end & return

Apna College

toString(): converts array to string

Arrays in JS

Array Mothe

Concat(): joins multiple arrays & returns result

Unshift(): add to start

Apna College

shift(): delete from start & return.

Arrays in JS

Array Methods

Slice(): returns a piece of the array

slice startida, endidx)

College

Splice(): change original array (add, remove, replace) Anna

splice( startidx, delCount, newEll..)

Let's Practice

Qs. Create an array to store companies-> "Bloomberg", "Microsoft", "Uber", "Google", "IBM", "Netflix"

a. Remove the first company from the array

b. Remove Uber & Add Olai


c. Add Amazon at the end


Functions in JS

Block of code that performs a specific task, can be invoked whenever needed


Functions in JS

Function Definition

Function Call

function functionName() (

//do some work

functionName();

}

function functionName(param1, param2....) ( Anna

College

//do some work

}

Arrow Functions

Compact way of writing a function

const functionName= (param1, param2.

//do some work

}

const sum = (a, b) [

return a + b;



forEach Loop in Arrays

arr.forEach(callBackFunction)

CallbackFunction: Here, it is a function to execute for each element in the array

A callhack is a function passed as an argument to another function

arr.forEach((val)

console.log(val);



Let's Practice

Qs. For a given array of numbers, print the square of each value using the forEach loop.



Some More Array Methods

Map

Creates a new array with the results of some operation. The value its callback returns are used to form new array

arr.map(callbackFnx(value, index, array))

let newArr arr.map((val

return val2.

Some More Array Methods

Filter

Creates a new array of elements that give true for a condition/filter.

Eg: all even elements

let newArr arr.filter(((val)(

retum val% 2 0.


Some More Array Methods

Map

Creates a new array with the results of some operation. The value its callback returns are used to form new array

arr.map( callbackFnx(value, index, array))


let newArr = arr.map((val){

return val *2;
})

Some More Array Methods

Filter

Creates a new array of elements that give true for a condition/filter. Eg: all even elements

let newArr = arr.filter(((val) => {

return val %2 === 0;
})


Some More Array Methods

Reduce

Performs some operations & reduces the array to a single value. It returne that single value.

JavaScript Demo: Array.reduce()

1 const array1 [1, 2, 3, 4];

//0+1+2+3+4

const initialValue = 0;

 const sumwithInitial =array1.reduce(

(accumulator, currentValue) accumulator currentValue,
 initialValue,

 console.log(sumwithInitial);

// Expected output: 10
