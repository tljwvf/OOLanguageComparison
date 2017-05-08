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
