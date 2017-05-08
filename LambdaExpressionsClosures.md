# Lambda expressions/Closures
## Swift 

Swift uses Closures which are similar to Lambda Expressions in C#. Closures are capable of copying and storing references to any constant
and variables within the context of where they are defined. Swift handles the memory management backend of this capability. 

Closures have three forms:

1. Global functions are closures that have a name and do not capture any values.
2. Nested functions are closures that have a name and can capture values from their enclosing function.
3. Closure expressions are unnamed closures written in a lightweight syntax that can capture values from their surrounding context.

The following example shows a function being passed to another function, telling it which function to use to sort data. This is a simple example of a closure in Swift.

    func backward(_ s1: String, _ s2: String) -> Bool {
        return s1 > s2
    }
    var reversedNames = names.sorted(by: backward)


## C#

C# uses Lambda expressions which are denoted by the lambda operator => 

    (x, y) => x == y
 
 There are multiple forms of lambdas in C#
 1. Expression Lambdas = they have an expression on the right
 
         (input-parameters) => expression
 2. Statement Lambdas = they have a statement on the right enclosed with brackets
 
        (input-parameters) => { statement; }
        
 3. Async Lambdas = These are either Expression Lambdas or Statement Lambdas but also use keywords such as async and await
 4. Lambdas that use Standard Query operators
 
 
 
 [Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
