# Inheritance
## Swift
Inheritance in swift is when a class inherits functionality from a class. In this example realTesting extends Test and is able to utilize all of its functionality.

   class Test {
        func go() {
            print("Go!")
        }
    }

    class RealTesting: Test {
    }

    let goVar = RealTesting()
    goVar.go() // prints "Go!"
