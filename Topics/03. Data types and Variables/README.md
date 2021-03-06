<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Data Types and Variables
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic00.png" style="top:46%; left:50%; width:44.96%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic01.png" style="top:0%; left:86.00%; width:17.49%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic02.png" style="top:0%; left:55.42%; width:21.16%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic03.png" style="top:0%; left:26.14%; width:19.30%; z-index:-1" /> -->
<div class="signature">
	<p class="signature-course"></p>
	<p class="signature-initiative"></p>
	<a href="https://telerikacademy.com/" class="signature-link"></a>
</div>

<!-- section start -->
<!-- attr: { hasScriptWrapper:true } -->
# Table of Contents
- Data Types
  - Integer
  - Floating-Point
  - Boolean
  - String
- Declaring and Using Variables
  - Identifiers
  - Declaring Variables and Assigning Values
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic04.png" style="top:18.51%; left:69.08%; width:32.91%; z-index:-1" /> -->

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Data Types in JavaScript
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic05.png" style="top:45%; left:65%; width:35.41%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic06.png" style="top:45%; left:5%; width:52.01%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# How Computing Works?
- Computers are machines that process data
  - Data is stored in the computer memory in **variables**
  - Variables have **name**, **data type** and **value**
- _Example_ of variable definition and assignment in JavaScript:

```js
var count = 5;
```

<div class="fragment balloon" style="top:63%; left:12%">Variable name</div>
<div class="fragment balloon" style="top:57%; left:30%">Variable value</div>

<!-- attr: { hasScriptWrapper:true } -->
# What Is a Data Type?
- A **data type**:
  - Is a domain of values of similar characteristics
  - Defines the type of information stored in the computer memory (in a variable)
- _Examples_:
  - Positive integers: `1`, `2`, `3`, `…`
  - Alphabetical characters: `a`, `b`, `c`, `…`
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic07.png" style="top:48.55%; left:86.08%; width:18.51%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# JavaScript Data Types
- JavaScript is actually **typeless** language
  - i.e. the type of a variable can be changed
  - All variables are declared with the keyword `var`

```js
var count = 5; // variable holds an integer value
count = 'hello'; // the same variable now holds a string
var name = 'Teleirk Academy'; // variable holds a string
var mark = 5.25 // mark holds a floating-point number
```

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Introducing Variables
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic08.png" style="top:43.20%; left:37.43%; width:38.79%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic09.png" style="top:7.05%; left:81.40%; width:22.43%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# What Is a Variable?
- A **variable** is a:
  - Placeholder of information that can usually be changed at run-time
  - A piece of computer memoryholding some value
- Variables allow you to:
  - Store information
  - Retrieve the stored information
  - Manipulate the stored information
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic10.png" style="top:45%; left:71.17%; width:32.52%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Variable Characteristics
- A variable has:
  - Name
  - Type (of stored data)
  - Value
- _Example_:
  - Name: `counter`
  - Type: `integer`
  - Value: `5`

```js
var counter = 5;
```

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic11.png" style="top:14.10%; left:67.37%; width:35.37%; z-index:-1" /> -->

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Integer Types
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic12.png" style="top:42%; left:24%; width:54.38%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# What are Integer Types?
- Integer types:
  - Represent whole numbers
  - Have range of values, depending on the size of memory used
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic13.png" style="top:55.24%; left:75.94%; width:28.21%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Integer Types – _Example_
- **Integer** type can hold numbers from `-9007199254740992` to `9007199254740992`
  - The underlying type behind is a floating-point number (**IEEE-754**)

```js
var studentsCount = 5;
var maxInteger = 9007199254740992;
var minInteger = -9007199254740992;
var a = 5, b = 3;
var sum = a + b; // 8
var div = a / 0; // Infinity
```

<!-- attr: { hasScriptWrapper:true, class:'slide-section demo' } -->
# Integer Types
## [Demo]()
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic14.png" style="top:40%; left:65.70%; width:33%; z-index:-1" /> -->

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Floating-Point Numbers
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic15.png" style="top:45%; left:28%; width:44%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# What are Floating-Point Types?
- Floating-point types:
  - Represent real numbers
  - Have range of values and precision
  - Can behave abnormally in the calculations
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic16.png" style="top:50%; left:40%; width:42%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Floating-Point Types
- Floating-point size depend on the platform
  - The browser and the OS
- 32-bit OS and browser have 32 bits for number, while 64-bit have 64 bits
  - It is good idea to use up to 32-bit numbers
    - Will always work on all platforms

<!-- attr: { hasScriptWrapper:true } -->
# Floating-Point Types – _Example_
- The **floating-point** type can hold numbers from `5e-324` to `1.79e+308`

```js
var PI = Math.PI; // 3.141592653589793
var minValue = Number.MIN_VALUE; // 5e-324
var maxValue = Number.MAX_VALUE; // 1.79e+308
var div0 = PI / 0; // Infinity
var divMinus0 = -PI / 0; // -Infinity
var unknown = div0 / divMinus0; // NaN
```

<!-- attr: { hasScriptWrapper:true, style:'font-size:0.9em' } -->
# Abnormalities in the Floating-Point Calculations
- Sometimes abnormalities can be observed when using floating-point numbers
  - Comparing floating-point numbers can not be performed directly with the **equals** operators (`==` and `===`)
- _Example_:

```js
var a = 0.1;
var b = 0.2;
var sum = 0.3;
var equal = (a+b == sum); // false!!!
console.log('a+b = '+ (a+b) + ', sum = ' +
  sum + ', sum == a+b? is ' + equal);
```

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic17.png" style="top:50%; left:80%; width:22.04%; z-index:1" /> -->

<!-- attr: { hasScriptWrapper:true, class:'slide-section demo' } -->
# Floating-Point Types
## [Demo]()
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic18.png" style="top:45%; left:60%; width:40%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Numbers in JavaScript
- All numbers in JavaScript are stored internally as double-precision floating-point numbers
- According to the **IEEE-754** standard
  - Can be wrapped as objects of type `Number`
- _Example_:

```js
var value = 5;
value = 3.14159;
value = new Number(100); // Number { 100 }
value = value + 1; // 101
var biggestNum = Number.MAX_VALUE;
```

<!-- attr: { hasScriptWrapper:true, style:'font-size:0.95em' } -->
# Numbers Conversion
- Convert `floating-point` to `integer` number

```js
var valueDouble = 8.75;
var valueInt = valueDouble | 0; // 8
```
- Convert to `integer` number with rounding

```js
var valueDouble = 8.75;
var roundedInt = (valueDouble + 0.5) | 0; // 9
```
- Convert `string` to `integer`

```js
var str = '1234';
var i = str | 0 + 1; // 1235
```

<!-- attr: { hasScriptWrapper:true, class:'slide-section demo' } -->
# Number Conversion
## [Demo]()
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic19.png" style="top:55%; left:36%; width:28%; z-index:-1" /> -->

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Boolean Type
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic20.png" style="top:42.31%; left:53.33%; width:46.72%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic21.png" style="top:42.31%; left:14.03%; width:24.68%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# The Boolean Data Type
- The **Boolean** **data type**:
  - Has two possible values:
    - `true` and `false`
  - Is useful in logical expressions
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic22.png" style="top:15.51%; left:69.40%; width:31.38%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Boolean Values – _Example_
- _Example_ of boolean variables taking values of `true` or `false`:

```js
var a = 1;
var b = 2;
var greaterAB = (a > b);
console.log(greaterAB);  // false
var equalA1 = (a == 1);
console.log(equalA1);    // true
```

<!-- attr: { hasScriptWrapper:true, class:'slide-section demo' } -->
# Boolean Type
## [Demo]()
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic23.png" style="top:0%; left:65%; width:38%; z-index:-1" /> -->

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# String Type
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic24.png" style="top:45%; left:0%; width:35%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic25.png" style="top:45%; left:60%; width:35%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# The String Data Type
- The **string data type**:
  - Represents a sequence of characters
- Strings are enclosed in quotes:
  - Both `'` and `"` work correctly
    - Best practices suggest using single quotes
- Strings can be concatenated
  - Using the `+` operator

```js
var s = 'Welcome to JavaScript';
```

```js
var name = 'Ivaylo' + ' ' + 'Kenov';
```

<!-- attr: { hasScriptWrapper:true } -->
# Saying Hello – _Example_
- Concatenating the two names of a person to obtain his full name:
  - _Note_: a space is missing between the two names! We have to add it manually

```js
var firstName = 'Ivan';
var lastName = 'Ivanov';
console.log('Hello, ' + firstName + '!');

var fullName = firstName + ' ' + lastName;
console.log('Your full name is ' + fullName);
```

<!-- attr: { hasScriptWrapper:true } -->
# Strings are Unicode
- Strings are stored as Unicode
  - Unicode supports all commonly used alphabets in the world
    - E.g. Cyrillic, Chinese, Arabic, Greek, etc. scripts

```js
var asSalamuAlaykum = 'السلام عليكم';
alert(asSalamuAlaykum);
var кирилица = 'Това е на кирилица!';
alert(кирилица);
var leafJapanese = '葉';
alert(leafJapanese);
```

<!-- attr: { hasScriptWrapper:true, class:'slide-section demo' } -->
# String Data Type
## [Demo]()
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic26.png" style="top:55%; left:50%; width:40%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic27.png" style="top:10%; left:15%; width:70%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true, style:'font-size:0.8em' } -->
# Parsing String to Numbers
- Strings can be parsed to numbers
  - Floating-point and rounded (integer)
- The trivial way to parse string to a number is using the functions `parseInt()` and `parseFloat()`:

```js
var numberString = '123'
console.log(parseInt(numberString); //prints 123
var floatString = '12.3';
console.log(parseFloat(floatString); //prints 12.3
```

- Yet a strange behavior is supported:
  - If a non-number string starts with a number, only the number is extracted:

```js
var str = '123Hello';
console.log(parseInt(str)); //prints 123
```

<!-- attr: { hasScriptWrapper:true, style:'font-size:0.9em' } -->
# Better String to Number Parsing
- `parseInt()` and `parseFloat()` are great, but slow
  - Better ways to parse string to numbers are as follows:
    - With rounding:
```js
'123.3' | 0 -> returns 123
```
    - As is:
```js
Number('123.3') -> returns 123.3
'123.3' * 1 -> returns 123.3
+'123.3' -> returns 123.3
```

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Undefined and Null Values
## Understanding '`undefined`' in JavaScript
<!-- <img class="slide-image" showInPresentation="false" src="imgs/pic28.png" style="top:11.78%; left:26.90%; width:55.10%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic29.png" style="top:0%; left:76.05%; width:20%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Undefined and Null Values
- In JS there is a special value `undefined`
  - It means the variable has not been defined (no such variable in the current context)
- `undefined` is different than `null`
  - `null` means that an object exists and is empty

```js
var x = 5;
x = undefined;
alert(x); // undefined
x = null;
alert(x); // null
```

<!-- attr: { hasScriptWrapper:true } -->
# Checking a Variable Type
- The variable type can be checked at runtime:

```js
var x = 5;
console.log(typeof(x)); // number
console.log(x); // 5
x = new Number(5);
console.log(typeof(x)); // object
console.log(x); // Number {}
x = null;
console.log(typeof(x)); // object
x = undefined;
console.log(typeof(x)); // undefined
```

<!-- attr: { hasScriptWrapper:true, class:'slide-section demo' } -->
# Undefined / Null / Typeof
## [Demo]()
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic30.png" style="top:55%; left:60%; width:35%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic31.png" style="top:0%; left:76.05%; width:20%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic32.png" style="top:45%; left:9.28%; width:22.49%; z-index:-1" /> -->

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Declaring and Using Variables
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic33.png" style="top:55%; left:55%; width:40%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Declaring Variables
- When declaring a variable we:
  - Specify its **name** (called identifier)
  - May give it an **initial value**
  - The **type** is identified by the value
- The syntax is the following:
- _Example_:

```js
var <identifier> [= <initialization>];
```

```js
var height = 200;
```

<!-- attr: { hasScriptWrapper:true } -->
# Identifiers
- Identifiers may consist of:
  - Letters (Unicode)
  - Digits [`0`-`9`]
  - Underscore '`_`'
  - Dollar '`$`'
- Identifiers
  - Can begin only with a letter, `$`, or an underscore
  - Cannot be a JavaScript keyword
- Variables / functions names: use **camelCase**
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic34.png" style="top:21.54%; left:64.10%; width:36.14%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true, showInPresentation:true } -->
<!-- # Identifiers -->
- Identifiers
  - Should have a descriptive name
  - It is recommended to use only Latin letters
  - Should be neither too long nor too short
- Names in JavaScript are **case-sensitive**
  - Small letters are considered different than the capital letters

<!-- attr: { hasScriptWrapper:true } -->
# Identifiers – _Examples_
- _Examples_ of correct identifiers:
- _Examples_ of incorrect identifiers:

```js
var new;	// new is a keyword
var 2Pac;	// Cannot begin with a digit
```

```js
var New = 2; // Here N is capital
var _2Pac; // This identifier begins with _
var поздрав = 'Hello'; // Unicode symbols used
// The following is more appropriate:
var greeting = 'Hello';
var n = 100; // Undescriptive
var numberOfClients = 100; // Descriptive
// Overdescriptive identifier:
var numberOfPrivateClientOfTheFirm = 100;
```

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, class:'slide-section' } -->
# Assigning Values To Variables
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic35.png" style="top:53%; left:30%; width:40%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic36.png" style="top:-0.14%; left:79.76%; width:15.89%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Assigning Values
- Assigning values to variables
  - Is achieved by the `=` operator
- The `=` operator has
  - Variable identifier on the left
  - Value on the right
    - Can be of any value type
  - Could be used in a cascade calling, where assigning is done from right to left
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic37.png" style="top:15.51%; left:78.60%; width:23.32%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Assigning Values – _Examples_
- Assigning values example:

```js
var firstValue = 5;
var secondValue;
var thirdValue;

// Using an already declared variable:
secondValue = firstValue;

// The following cascade calling assigns
// 3 to firstValue and then firstValue
// to thirdValue, so both variables have
// the value 3 as a result:

thirdValue = firstValue = 3; // Avoid this!
```

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic38.png" style="top:18.91%; left:84.21%; width:18.95%; z-index:1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Initializing Variables
- Initializing
  - Is assigning of initial value
  - Must be done before the variable is used!
- Several ways of initializing:
  - By using a literal expression
  - By referring to an already initialized variable
- Uninitialized variables are undefined
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic39.png" style="top:12.69%; left:94.16%; width:9.34%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Initialization – _Examples_
- _Example_ of some initializations:

```js
// This is how we use a literal expression:
var heightInMeters = 1.74;

// Here we use an already initialized variable:
var greeting = 'Hello World!';
var message = greeting;
```

<!-- attr: { hasScriptWrapper:true, class:'slide-section demo' } -->
# Assigning and Initializing Variables
## [Demo]()
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic40.png" style="top:44%; left:5%; width:25.65%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic41.png" style="top:44%; left:75%; width:23.80%; z-index:-1" /> -->

<!-- attr: { hasScriptWrapper:true } -->
# Local and Global Variables
- Local variables
  - Declared with the keyword `var`
- Global variables
  - Declared **without** the keyword `var`
  - Bad practices – never do this!

```js
var a = 5; // a is local in the current scope
a = 'alabala'; // the same a is referenced here
```

```js
a = undefined;
a = 5; // the same as window.a = 5;
```

<!-- section start -->
<!-- attr: { hasScriptWrapper:true, showInPresentation:true, class:'slide-section' } -->
<!-- # Data Types and Variables
## Questions -->

<!-- attr: { hasScriptWrapper:true } -->
# Free Trainings @ Telerik Academy
- "Web Design with HTML 5, CSS 3 and JavaScript" course @ Telerik Academy
    - [html5course.telerik.com](http://html5course.telerik.com)
  - Telerik Software Academy
    - [academy.telerik.com](http://academy.telerik.com)
  - Telerik Academy @ Facebook
    - [facebook.com/TelerikAcademy](https://facebook.com/TelerikAcademy)
  - Telerik Software Academy Forums
    - [forums.academy.telerik.com](https://telerikacademy.com/Forum/Home)

<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic42.png" style="top:58.18%; left:90.52%; width:16.97%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic43.png" style="top:38.35%; left:68.14%; width:36.30%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic44.png" style="top:52.92%; left:75.91%; width:10.85%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="imgs/pic45.png" style="top:20.88%; left:91.56%; width:14.23%; z-index:-1" /> -->
