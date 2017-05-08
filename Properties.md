# Properties
## Swift
In swift getters and setters apply to computed properties. This means that the properties do not have backing variables.

    var x:Int

    var xTimesTwo:Int {
        set {
           x = newValue / 2
        }
        get {
            return x * 2
        }
    }

## C#

Setters and getters in C# are defined by their corresponding keyword get, set. C# does use backing variables but it is unnecessary to write them since it handles them for you. C# does use computer properties.

     private string _something;
     public string Something
     {
        get { return _something; }
        set { _something = value; }
     }
     
     
     
[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
