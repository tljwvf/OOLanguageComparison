# Memory Management
## Swift
For the most part, Swift handles allocating and deallocating memory on a user's behalf throughout the program. Swift is able to do this thanks to a technlogy known
as Automatic Reference Counting. This is an automatic system that is able to predictably and efficiently use resources within an environment. 
This means that the user does not have to explicity state the resources that need to be used, but the user does still need to monitor relationships between objects to avoid memory leaks. Automatic Reference Counting also handles garbage collection so the user does not have to handle it.


## C#

C# has automatic memory management. When an object is created/defined it has a destructor method, these methods cannot be called but instead when the object is no longer able to be used it terminates itself via a destructor invoke. After the object is destructed garbage collection takes over and frees memory associated with the object. 




[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
