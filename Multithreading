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

    namespace MultithreadingApplication
    {
       class ThreadCreationProgram
       {
          public static void CallToChildThread()
          {
             Console.WriteLine("Child thread starts");
          }

          static void Main(string[] args)
          {
             ThreadStart childref = new ThreadStart(CallToChildThread);
             Console.WriteLine("In Main: Creating the Child thread");
             Thread childThread = new Thread(childref);
             childThread.Start();
             Console.ReadKey();
          }
       }
    }
