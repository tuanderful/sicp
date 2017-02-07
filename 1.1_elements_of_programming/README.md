# Elements of Programming

Mechanisms for combining simple ideas to form more complex ideas:
* primitive expressions
* means of combination
* means of abstraction

## Expressions
__Compound expression__ expressions representing values, be combined with expressions representing a primitive procedure
__Combinations__ list of expressions within parens
```(<operator> <operands>)```

__REPL__ read-evaluate-print loop

## Naming and the Environment
Use `define` to name things, to identify a variable whose value is a computational object.
```(define <name> <value>)```
_define is a __special form__, an exception to the general evaluation rule_

__environment__ memory that keeps track of name-object pairs

## Evaluating Combinations
1. Evaluate the subexpressions
2. Apply the procedure that is the value of the operator, to the operands.

__tree accumulation__ process for evaluating treelike objects (includes "percolating vaues upward")

## Compound Procedures
__procedure definition__ an abstraction technique, to give compound operations a name

```scheme
(define (square x) (* x x))```

