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



## C#

C# supports the use of Interfaces which mimic the java interfaces. They share the same funcitonality and restrictions.

    interface ISampleInterface
    {
        void SampleMethod();
    }

    class ImplementationClass : ISampleInterface
    {
        // Explicit interface member implementation: 
        void ISampleInterface.SampleMethod()
        {
            // Method implementation.
        }

        static void Main()
        {
            // Declare an interface instance.
            ISampleInterface obj = new ImplementationClass();

            // Call the member.
            obj.SampleMethod();
        }
    }
    
Interfaces are used to describe functionality of certain classes. They serve mostly as a template since the class that inherits from the interface must define the interfaces methods.




[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
