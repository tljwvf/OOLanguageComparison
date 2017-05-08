# Classes

## Swift
A class in swift is defined using the keyword class and is placed within a pair of braces.

    class SomeClass {
    // class definition goes here
    }

Creating a new instance is accomplished by calling the constructor.

    let hd = Resolution(width: 1920, height: 1080)
    
The object is constructed using Init().

    class MarksStruct {
       var mark: Int
       init(mark: Int) {
          self.mark = mark
       }
    }
    
Deinitialization is accomplished using the key word Deinit.

    deinit {
    // perform the deinitialization
    }


## C#

Classes are defined using the class keyword 

    public class Customer
    {
        //code goes here
    }

The creation of an object is by the keyword new, which follows java’s design.

    Customer object1 = new Customer();

Constructors are used to initialized the object

    public class Person
    {
        // Field
        public string name;

        // Constructor that takes no arguments.
        public Person()
        {
            name = "unknown";
        }
    }

Destructors are used to destroy an instance of a class/classes, these cannot be called and due to this they happen automatically.
       
       class Car
        {
            ~Car()  // destructor
            {
                // cleanup statements...
            }
        }


[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
