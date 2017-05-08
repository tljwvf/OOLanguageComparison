# Properties
## Swift
In swift getters and setters apply to computed properties. This means that the propeties do no have backing variables.

    var x:Int

    var xTimesTwo:Int {
        set {
           x = newValue / 2
        }
        get {
            return x * 2
        }
    }
