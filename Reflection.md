# Reflection
## Swift
Reflection in Swift allows a user to inspect names and types of properties in a structure or class. This can be accomplished using a Mirror Struct.

    let bookMirror = Mirror(reflecting: book)
    
Once a user creates a variable and utilizes Mirror telling it which class or structure to reflect, they can then iterate through the properties of that object. In this case, they could iterate through book analyzing each property
