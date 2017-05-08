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
