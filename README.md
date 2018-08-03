# JAVASCRIPT
### Useful Links
### Data types 
[What is immutable in JS ?](https://stackoverflow.com/questions/3200211/what-does-immutable-mean) <br>
Objects are copied by reference in JS. <br>
```javascript
// The primitive data type String is stored as a value
var person = "Kobe";  
var anotherPerson = person; // anotherPerson = the value of person
person = "Bryant"; // value of person changed

console.log(anotherPerson); // Kobe
console.log(person); // Bryant
``` 
<br>

```javascript
var person = {name: "Kobe"};
var anotherPerson = person;
person.name = "Bryant";

console.log(anotherPerson.name); // Bryant
console.log(person.name); // Bryant
```

[Everything about JS object](http://javascriptissexy.com/javascript-objects-in-detail/) <br>




[When is JavaScript synchronous?](https://stackoverflow.com/questions/2035645/when-is-javascript-synchronous) <br>
[Static typed vs Dynamic typed languages](https://stackoverflow.com/questions/1517582/what-is-the-difference-between-statically-typed-and-dynamically-typed-languages)(See the answer by Akavall) <br>
[JavaScript primitive datatyped](https://www.w3schools.com/js/js_datatypes.asp) <br>
[Undefined VS NULL in JavaScript](https://stackoverflow.com/questions/5076944/what-is-the-difference-between-null-and-undefined-in-javascript) <br>
[Operator Precedence and Associativity in JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence) <br>
[Coercion in JS](https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript) <br>
[Comparison Operators in JS (Coercion)](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237496?start=0) <br>
[Equality vs Strict Equality in js](https://stackoverflow.com/questions/359494/which-equals-operator-vs-should-be-used-in-javascript-comparisons?noredirect=1&lq=1) <br>
[Equality table, comparison bw Equality, Strict Equality and Object.is](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness) <br>
[When to use Coercion](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237498?start=0) <br>
[Coercion, another use case](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237500?start=0) <br>
[How frameworks use default values](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237502?start=0) <br>

### Objects and Functions in JavaScript
[Whole chapter on functions and objects](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237510?start=0) <br>
[Why use object literal in JS](https://stackoverflow.com/questions/1600130/javascript-advantages-of-object-literal) <br>

JSON is inspired by JavaScript Object Literal. <br>
[JSON vs XML](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237518?start=0) <br>
[JSON vs XML (StackOverflow)](https://stackoverflow.com/questions/4862310/json-and-xml-comparison) <br>
[First class functions](https://stackoverflow.com/questions/705173/what-is-meant-by-first-class-object) <br>
[Functions are Objects in JS](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237520?start=0) <br>
[Function statements and expressions](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237524?start=0) <br>
[Javascript Pass by value and Pass by Reference](https://stackoverflow.com/questions/7744611/pass-variables-by-reference-in-javascript)
[Pass objects by values? (SO)](https://stackoverflow.com/questions/7574054/javascript-how-to-pass-object-by-value) <br>

### `this` keyword 
[this keyword and self (Udemy)](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237526?start=0) <br>
[this keyword (SO)](https://stackoverflow.com/questions/3127429/how-does-the-this-keyword-work) <br>

### Arguments 
[Arguments and hoisting(Udemy)](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237528?start=0) <br>

### Automatic Semicolon Insertion
[Dangers of not using your own semicolon and relying on syntax parsers](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237538?start=0)

### Whitespaces
[whitespaces](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237604?start=0)

### IIFE
[IIFE ](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237540?start=0)
[Why use IIFE](https://stackoverflow.com/questions/37021349/benefit-of-immediately-invoked-function-expression-iife-over-a-normal-function)

### Closure
[Closue (SO)](https://stackoverflow.com/questions/111102/how-do-javascript-closures-work) <br>
`setTimeout  asynchronous in that it breaks the synchronous flow, but it's not actually going to execute concurrently/on a separate thread.` <br>
[setTimeout using closures](https://stackoverflow.com/questions/19626680/is-settimeout-a-good-solution-to-do-async-functions-with-javascript)

### Object Oriented JS
[Classical VS Prototypal Inheritance](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237552?start=0) <br>
[Function Constructors](https://www.udemy.com/understand-javascript/learn/v4/t/lecture/2237568?start=0)

