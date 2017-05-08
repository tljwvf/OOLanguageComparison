# Singleton
## Swift

A Singleton is an object which is instantiated exactly one time. Only one copy of the object exits, but its state is reachable by other objects. The easiest
way to accomplish this in Swift is to create a class with a static variable that is set to a manager.

    class SomeManager {
        static let sharedInstance = SomeManager()
    }

Then you simply have to instantiated the class and access the sharedInstance.
