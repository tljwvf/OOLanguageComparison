# Multithreading
## Swift

To accomplish mutlithreading in Swift, the user must use the object oriented class Grand Central Dispatch. For example:

    DispatchQueue.global(qos: .userInitiated).async {  
        // Download file or perform expensive task

        DispatchQueue.main.async {  
            // Update the UI  
        }
    }
    
This code would create an asynchronous task that would first download then update the UI. Grand Central Dispatch has multiple options for concurrent execution
such as async() and after() to delay a task.



## C#

C# threading abilties are similar to java's. When a thread is created one could request information from it, request it to die, put it to sleep, and get state.

Multitasking is different from the standard threading. In C# multitasking is achieved through the task class. Tasks use threads but schedule them in a much more efficient manor. Also threads can only be used once when using standard threading, but with tasks it can reuse threads and eliminate unnecessary waste.


[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
