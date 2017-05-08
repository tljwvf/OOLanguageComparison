# Classes

## Swift
### Definition
A class in swift is defined using the keyword class and is placed within a pair of braces.

    class SomeClass {
    // class definition goes here
    }

Creating a new instance is accomplished by calling the constructor.

    let hd = Resolution(width: 1920, height: 1080)
    
The object is constructed using Init()

    class MarksStruct {
       var mark: Int
       init(mark: Int) {
          self.mark = mark
       }
    }
    
Deinitialization is accomplished using the key word Deinit

    deinit {
    // perform the deinitialization
    }
