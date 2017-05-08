# Null/Nil References
## Swift

Swift uses the keyword Nil. On top of this Swift also uses Optionals. Optionals are created to handle the abscence of value.
This tells the user whether a variable has a value or does not have a value. They were created to prevent dereferencing Nil values.

They are created using the ? operator and are used as follows:

    var myString:String? = nil

    if myString != nil {
       println(myString)
    }else {
       println("myString has nil value")
    }


## C#

C# uses null keyword. Null simply translates to a null reference or a refecent to no objects. This is the default value for reference variables/objects. 

    string s = null
    
C# has a very nice way of determining if an object has a null value by the .IsNullOrEmpty() method objects have.

    public static String Test(s) {
        if (String.IsNullOrEmpty(s))
            return "is null or empty";
        else
            return String.Format("(\"{0}\") is not null or empty", s);


[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
