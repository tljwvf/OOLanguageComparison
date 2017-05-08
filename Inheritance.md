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



## C#

C# uses inheritance and extensions to improve the functionality of a class/interface. C# doesn't support multiple inheritance. 

    //Base class or Parent class.  
    class Shape  
    {  
        public double Width;  
        public double Height;  
        public void ShowDim()  
        {  
            Console.WriteLine("Width and height are " +  
            Width + " and " + Height);  
        }  
    }  
    // Triangle is derived from Shape.  
    //Drived class or Child class.  
    class Triangle : Shape  
    {  
        public string Style; // style of triangle  
        // Return area of triangle.  
        public double Area()  
        {  
            return Width * Height / 2;  
        }  
        // Display a triangle's style.  
        public void ShowStyle()  
        {  
            Console.WriteLine("Triangle is " + Style);  
        }  
    }  
    
  [Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)  
    
