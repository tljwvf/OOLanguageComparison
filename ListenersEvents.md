# Listeners and Event Handlers
## Swift

Swift uses the NSNotificationCenter class to implement the Observer pattern in which a listener waits for a broadcaster to send a message. This
class allows the user to add an observer, notify the observer, and remove the observer. 

This class allows the user to add an observer.
    
    NSNotificationCenter.defaultCenter().addObserver(self, selector: "actOnButton1:", name: Constants.BUTTON_1_CLICK_NOTIFY, object: nil)
    
Then the user can use to class to send notifications to observer.

    func postNotificationName(notificationName: String, object notificationSender: AnyObject?)


## C#

C# uses a delegate object as the EventHandler thanks to the .NET Framework guidelines. 

    public delegate void ChangedEventHandler(object sender, EventArgs 

C# uses event object as the Listener 
   
     public event ChangedEventHandler Changed;


[Back to Home](https://github.com/tljwvf/OOLanguageComparison/blob/master/README.md)
