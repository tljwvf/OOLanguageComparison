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
