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

In this case GermanShephard uses the Barker protocol meaning it must provide an implementation for bark(). Classes can also adopt multiple protocols in order to utilize more functionality.
