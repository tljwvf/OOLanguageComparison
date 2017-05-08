# Singleton
## Swift

A Singleton is an object which is instantiated exactly one time. Only one copy of the object exits, but its state is reachable by other objects. The easiest
way to accomplish this in Swift is to create a class with a static variable that is set to a manager.

    class SomeManager {
        static let sharedInstance = SomeManager()
    }

Then you simply have to instantiated the class and access the sharedInstance.


## C#

C# can have thread safe, not thread safe, and Lazy singletons.

1. not thread safe
        
       public sealed class Singleton
        {
            static Singleton instance=null;

            Singleton()
            {
            }

            public static Singleton Instance
            {
                get
                {
                    if (instance==null)
                    {
                        instance = new Singleton();
                    }
                    return instance;
                }
            }
        }
        
 2. Thread Safe
 
        public sealed class Singleton
        {
            static Singleton instance=null;
            static readonly object padlock = new object();

            Singleton()
            {
            }

            public static Singleton Instance
            {
                get
                {
                    lock (padlock)
                    {
                        if (instance==null)
                        {
                            instance = new Singleton();
                        }
                        return instance;
                    }
                }
            }
        }
        
3. Lazy 

        public sealed class Singleton
        {
            Singleton()
            {
            }

            public static Singleton Instance
            {
                get
                {
                    return Nested.instance;
                }
            }

            class Nested
            {
                // Explicit static constructor to tell C# compiler
                // not to mark type as beforefieldinit
                static Nested()
                {
                }

                internal static readonly Singleton instance = new Singleton();
            }
        }
        
        
        
 [Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
