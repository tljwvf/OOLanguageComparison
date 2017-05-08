# Comparisons
## Swift

In Swift, comparisons are handled by value and not by reference. For example, the following code would work perfect in Swift but not Java which compares by reference.

    let x = "hello"
    let y = "hello"
    let isEqual = (x == y)
