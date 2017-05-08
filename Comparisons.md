# Comparisons
## Swift

In Swift, comparisons are handled by value and not by reference. For example, the following code would work perfect in Swift but not Java which compares by reference.

    let x = "hello"
    let y = "hello"
    let isEqual = (x == y)


## C#

In C# you can use either == or .Equals however if you use == they must both be of type string otherwise it could fail. The safer option is .Equals

    string a = new string(new char[] {'h', 'e', 'l', 'l', 'o'});
    string b = new string(new char[] {'h', 'e', 'l', 'l', 'o'});
    
    Console.WriteLine (a.Equals(b));
    
    
    
[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
