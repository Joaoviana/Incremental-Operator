## Incremental-Operators


### Index
* [Learning Objective](#learning-objective)
* [Study Snippet](#study-snippet)
* [Helpful Links](#helpful-links)

___

## Learning Objective

Studying the precedence of the incremental operator in an expression and what effects it does have being before or after the operand. 

Concepts:
 * Operator precedence - Determines the way in which operators are parsed with respect to each other
 * Pre vs Pro Increment Operator

[TOP](#index)

___
 
## Study Snippet

```js
let input = 0;
(String(++input) + String(input++)) + Number(String(input++) + String(++input))
```

 Both versions of operators will increment a value (in this case, 'input'), but the key difference is at what point that increment applied and assigned in memory. And, of course, what is returned to the primitive type 'String()'.
 
 * Python Tutorial 
 
 [Left-Hand-Side](https://goo.gl/qH2MsR)
 [Right-Hand-Side](https://goo.gl/Puq2gN)
 
[TOP](#index)

___

## Helpful Links

[CodeBurst.io](https://codeburst.io/javascript-increment-and-decrement-8c223858d5ed)

[JSForAllOf.us](http://jsforallof.us/2014/07/10/pre-increment-vs-post-increment/)

[TOP](#index)

