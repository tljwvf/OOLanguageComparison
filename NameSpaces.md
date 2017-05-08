 # Name Spaces
## Swift

The most common way to create a name space in Swift is to use structures. These can then be used as a universally easy to understand constant that can store important information within the structure.

    struct API {

    static let BaseURL = "https://example.com/v1/"
    static let Token = "sdfiug8186qf68qsdf18389qsh4niuy1"
    
    }


## C#

Namespaces are used to control/restrict the scope of the class and method names. Along with assisting in organization.

    namespace SampleNamespace
    {
    class SampleClass
    {
        public void SampleMethod()
        {
            System.Console.WriteLine(
              "SampleMethod inside SampleNamespace");
        }
    }
    }
