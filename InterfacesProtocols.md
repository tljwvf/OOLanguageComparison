# Interfaces and Protocols
## Swift
A protocol in Swift defines methods or properties that can be adopted and utilized by a class.

    protocol Barker {
        func bark()
    }

    class GermanShephard: Barker {
       func bark() {
        print("Bark")
       }
    }
