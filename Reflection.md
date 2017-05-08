# Reflection
## Swift
Reflection in Swift allows a user to inspect names and types of properties in a structure or class. This can be accomplished using a Mirror Struct.

    let bookMirror = Mirror(reflecting: book)
    
Once a user creates a variable and utilizes Mirror telling it which class or structure to reflect, they can then iterate through the properties of that object. In this case, they could iterate through book analyzing each property


## C# 

Refection objects in C# are used to retrieve data from the running program. 

    System.Reflection.MemberInfo info = typeof(MyClass);
    
A couple advantages to Reflection objects is that 
1. Attributes/metadata can be viewed at runtime
2. It also allows the creation of new types durring the runtime


[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
