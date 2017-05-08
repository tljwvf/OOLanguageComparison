# Errors and Exceptions
## Swift

Errors in Swift are represented by values of types that canform to Swifts Error protocol. Swift enumurations allow the user to model a group of error conditions.

    enum VendingMachineError: Error {
        case invalidSelection
        case insufficientFunds(coinsNeeded: Int)
        case outOfStock
    }
    
Users can use do-catch blocks to handle multiple exceptions.

    do {
        try expression
        statements
    } catch pattern 1 {
        statements
    } catch pattern 2 where condition {
        statements
    }


## C#

C# handles exceptions similar to java. They can be done via throw or a try catch.

    static double SafeDivision(double x, double y) {
        if (y == 0)
            throw new System.DivideByZeroException();
        return x / y;
    }
    
    try {
        code...
    } 
    catch (DivideByZeroException e) {
        code...
    }
    catch (Exception e) {
        code..
    }
    
    
    
