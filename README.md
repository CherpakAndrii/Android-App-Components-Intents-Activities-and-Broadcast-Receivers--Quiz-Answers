# Android-App-Components--Intents-Activities-and-Broadcast-Receivers
## Coursera quiz answers - 100%

* [Module 1 (100%)](https://github.com/CherpakAndrii/Android-App-Components--Intents-Activities-and-Broadcast-Receivers#module-1)
* [Module 2 (100%)](https://github.com/CherpakAndrii/Android-App-Components--Intents-Activities-and-Broadcast-Receivers#module-2)
* [Module 3 (100%)](https://github.com/CherpakAndrii/Android-App-Components--Intents-Activities-and-Broadcast-Receivers#module-3)
* [Module 4 (not ready)](./README.md#module-4)
* [Module 5 (100%)](https://github.com/CherpakAndrii/Android-App-Components--Intents-Activities-and-Broadcast-Receivers#module-5)

# Module 1
### Question 1: Which of the following are examples of hardware elements commonly found in Android devices (choose all that apply):

* Intent
* ***Wifi***
* ***Random access memory***
* Activity
* ***Central processing unit***
* Broadcast Receiver
* ***Accelerometer***
* ***Graphics processing unit***

### Question 2: Which of the following describe the purposes of the Android Linux kernel (choose all that apply):
* ***Optimizes GNU Linux to meet the needs of mobile devices and apps***
* A set of Java-based services that form the environment in which Android apps run and are managed
* Provides reusable capabilities that extend hardware-centric OS kernel and protocol mechanisms
* ***Shields higher layers of Android from hardware diversity***
* ***Mediates access to--and sharing of--hardware resources***
* Shields OEMs from GNU Public License "virality"

### Question 3: Which of the following are examples of layers and/or elements found in Android's middleware infrastructure (choose all that apply):
* Power Management
* Activity Manager Service
* Binder (IPC) Driver
* ***Native C/C++ libraries***
* ***Hardware abstraction layer***
* ***Android Run-Time (ART)***

### Question 4: Which of the following are examples of Android app components (choose all that apply):
* ***Broadcast Receivers***
* Package Manager
* ***Activities***
* Dalvik Virtual Machine
* ***Content Providers***
* ***Services***

### Question 5: Which of the following are true statements about Java threads (choose all that apply)
* Starting a thread takes a trivial amount of time and system resources
* ***Every thread contains a call stack to keep track of method state***
* ***Each process can have multiple threads***
* ***A thread is the smallest unit of execution for sequences of programmed instructions***
* ***A Java thread must be given code to run when it is started***
* Starting a Java thread is the only way to write a concurrent Android app

### Question 6: Which of the following are true statements about application frameworks in the context of Android (choose all that apply):
* ***Android frameworks provide an integrated set of components that provide a reusable architecture for a family of related mobile apps***
* ***Android frameworks enhance systematic reuse by providing canonical structure and functionality to mobile apps***
* ***Android frameworks use an event-driven programming model to plug app code into them***
* Android frameworks enable app component to dictate the flow of control in a program, rather than the frameworks themselves

### Question 7: Which of the following are true statements about the Android Application Framework layer (choose all that apply):
* It shields OEMs from GNU Public License "virality"
* ***It contains system services that provide apps with the capabilities and info they need to do their work***
* ***Its system services run continuously during system operation***
* It optimizes GNU Linux to meet the needs of mobile devices and apps

### Question 8: Which of the following are true statements about the Android apps (choose all that apply):
* The bulk of these apps are written in C/C++
* These apps cannot be written in C/C++
* ***The bulk of these apps are written in Java***
* ***It's possible to write portions of the apps in C/C++***

# Module 2

### Question 1: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you want to start a local git repository. What command allows you to start that repository?
* git begin
* git start
* none of the above
* ***git init***
* git commit

### Question 2: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you have previously started a git repository. What command allows you to track new files or changes to existing files?
* ***git add***
* git include
* git also
* git git
* none of the above

### Question 3: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you have included a new file to be tracked to your current index. What command allows you to create a new snapshot of the progress you have made?
* git status
* git add
* git remove
* none of the above
* ***git commit***

### Question 4: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you have an existing repository. What command allows you to check the current status of the repository?
* git remove
* git add
* ***git status***
* git clean
* none of the above

### Question 5: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you have an existing repository. What command allows you to create new branches or see information on existing branches?
* git look
* git add
* git read
* ***git branch***
* git init
* none of the above

### Question 6: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you have an existing repository. What command allows you to send your changes to a remote repository?
* ***git push***
* git upload
* git send
* git download
* none of the above

### Question 7: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you have an existing repository. What command allows you to download changes from a remote repository?
* git acquire
* none of the above
* git push
* ***git pull***
* git download

### Question 8: Assuming you are using the git command line terminal: The terminal's current location is in a folder where you have an existing repository. What command allows you to combine two branches into one branch?
* git combine
* ***git merge***
* git add
* git status
* none of the above

# Module 3

### Question 1: Which of the following correctly describe what an intent is in Android (choose all that apply):
* A message that provides a screen within which users can interact in order to do something
* An event handler that responds to system-side broadcast announcements
* A component that runs in the background to perform long-running operations or access remote resources
* ***A message that describes an action to perform or an event that has occurred***

### Question 2: Which of the following correctly describe benefits that an intent provides to apps in Android (choose all that apply):
* An intent manages secure access to structured data
* ***An intent simplifies app development since existing components can be reused as "black-boxes"***
* An intent defines the smallest unit of execution for sequences of programmed instructions
* ***An intent is the "glue" that helps integrate Android apps***

### Question 3: Which of the following correctly describe what is meant by an intent being a "passive" data structure (choose all that apply):
* An intent cannot be used in a concurrent program
* An intent only contains public fields
* An intent only contains static getter/setter methods
* ***An intent just consists of fields and field access/mutator methods***

### Question 4: Which of the following correctly describe what is meant by an intent enabling "late runtime binding" of apps to components (choose all that apply):
* App components started by intents must run in separate processes
* ***App components can be discovered and used at runtime vs compile-time***
* App components started by intents are slow to launch
* App components can be discovered and used at compile-time vs. runtime

### Question 5: Which of the following correctly describe the benefits of runtime discovery of app component (choose all that apply):
* It ensures that developers know at compile-time which component implementations their app will use
* It enhances the security and robustness of apps by disallowing trojan horses
* ***It enables systematic reuse that creates apps from predefined software components***
* ***It enables apps with loosely-coupled components that can be extended and integrated dynamically***

### Question 6: Which of the following are elements in an Android intent (choose all that apply):
* ***Extras***
* Stack
* ***Name***
* URL
* ***Action***
* Service
* ***Data***
* ***Flags***

### Question 7: Which of the following statements are true for an "implicit" intent (choose all that apply):
* The action must not be specified
* ***The name must not be specified***
* The data must not be specified
* The category must not be specified

### Question 8: Which of the following are true statements about implicit and explicit intent (choose all that apply):
* ***Android delivers an explicit intent to a target component without consulting filters in the AndroidManifest.xml file***
* ***Implicit intents are typically used to interact with components residing in other apps***
* ***Explicit intents are particularly important when starting or binding to services***
* Implicit intents are used to "tightly couple" activity and broadcast receiver components
* Explicit intents are typically used to interact with components residing in other apps
* ***Android delivers an implicit intent to a target component only if it matches one of its intent filters in the AndroidManifest.xml file***

### Question 9: Which of the following elements must match during implicit intent filtering for an intent to be delivered to a target component (choose all that apply):
* Extras
* Flags
* Name
* ***Action***
* ***Category***
* ***Data***

### Question 10: Which of the following correctly describe what Android's IntentService does (choose all that apply):
* It is an event handler that responds to system-side broadcast announcement
* ***It expresses requests as intents & passes them between threads and/or processes***
* It is a component that provides a screen within which users can interact in order to do something
* ***It's a framework that handles asynchronous requests on demand***

# Module 4

### Question 1: Which of the following correctly describe what an activity is in Android (choose all that apply): 
* An event handler that responds to system-side broadcast announcements
* ***A component that defines a user-facing operation that's displayed on a device screen***
* A component that runs in the background to perform long-running operations or access remote resources
* A message that describes an action to perform or an event that has occurred

### Question 2: Which of the following correctly define what a hook method is (choose all that apply):
* It is an unnamed block of code that can be passed around and executed later
* ***It is used to customize reusable framework classes to run app-specific logic***
* It is the smallest unit of execution for sequences of programmed instructions
* It is an event handler that responds to broadcast announcements

### Question 3: Which of the following are lifecycle hook methods provided by Android's activity framework (choose all that apply):
* ***onPause()***
* ***onStop()***
* ***onStart()***
* ***onDestroy()***
* onBind()
* ***onCreate()***
* onReceive()
* ***onResume()***

### Question 4: Which of the following statements about the startActivityForResult() method are true (choose all that apply):
* This method is asynchronous and one-way
* ***This method is asynchronous and two-way***
* This method is synchronous and one-way
* This method is synchronous and two-way

### Question 5: Which of the following lifecycle hook methods may not be called in low memory situations (choose all that apply):
* ***onDestroy()***
* ***onStop()***
* onPause()
* onResume()

### Question 6: Which of the following Android system services call lifecycle hook methods on activities, services, and broadcast receivers (choose all that apply):
* ***Activity Manager Service***
* Location Manager Service
* Notification Manager Service
* Window Manager Service

### Question 7: Which of the following statements accurately reflect what happens when a user enters text via the Android virtual keyboard (choose all that apply):
* The onResume() hook method is called back to return UI focus for this screen
* ***The UI focus is unchanged and no lifecycle hook methods are called***
* A new activity is started and its onCreate() hook method is called
* The onStart() hook method is called back and the activity becomes visible

### Question 8: Which of the following correctly define what a "task" is in the contact of Android activities (choose all that apply):
* It is an unnamed block of code that can be passed around and executed later
* It is a unit of execution for sequences of programmed instructions
* It is a component that runs in the background performing long-running operations or accessing remote resources
* ***It is a group of activities a user interacts with when performing a certain job***

### Question 9: Which of the following correctly describe how activities can be used in concurrent apps (choose all that apply):
* ***Any long-duration operations must run in background threads via concurrency frameworks***
* ***UI toolkit components should only be accessed by the UI thread***
* ***All methods called in the UI thread must be short-duration and non-blocking***
* An activity cannot be used in a concurrent app

### Question 10: Which of the following correctly describes the capabilities of the Android HaMeR framework (choose all that apply):
* It handles asynchronous requests on demand and expresses these requests as intents that are passed between threads and/or processes
* It enables operations to run in one or more background threads and publish results to the UI thread without directly using threads, handlers, messages, and/or runnables
* It is a component that runs in the background to perform long-running operations or access remote resources
* ***It enables operations to run in one or more background threads and publish results to the UI thread***

# Module 5

### Question 1: Which of the following correctly describe what a broadcast receiver is in Android (choose all that apply):
* ***An event handler that responds to broadcast announcements***
* A message that describes an action to perform or an event that has occurred
* A component that runs in the background to perform long-running operations or access remote resources
* A component that defines a user-facing operation that's displayed on a device screen

### Question 2: Which of the following Android system services are involved in routing intents to broadcast receivers (choose all that apply):
* Telephony Manager Service
* ***Activity Manager Service***
* Window Manager Service
* Download Manager Service

### Question 3: Which of the following things can be done in receiver's onReceive() hook method (choose all that apply):
* ***Start other Android components***
* ***Pop up toast messages***
* Show a dialog
* ***Create status bar notifications***
* Register other receivers
* Bind to a service

### Question 4: Which of the following are types of Android intent broadcast mechanisms (choose all that apply):
* Async
* Static
* ***Sticky***
* Dynamic
* ***Ordered***
* ***Normal***

### Question 5: Which of the following are reasons why broadcasting intents raises security issues (choose all that apply):
* ***sendBroadcast() allows any other app to receive broadcast intents***
* ***An app can send an intent to any receiver registered via registerReceiver or the AndroidManifest.xml file***
* ***The intent namespace is global***
* The onReceive() hook method in a receiver is called back in the UI thread

### Question 6: Which of the following are key differences between the PingPongReceivers and PingPongReceiversEx apps (choose all that apply):
* ***The PingPongReceivers app displays "ping" and "pong" strings via toasts instead of via the notification status bar area.***
* The PongReceiver in PingPongReceivers runs in a different process as the MainActivity, whereas the PongReceiver in PingPongReceiversEx runs in the same process as MainActivity.
* The PingPongReceivers app uses setPackage() to limit receivers to its components only, whereas the PingPongReceiversEx app does not.
* The PingPongReceiversEx app displays "ping" and "pong" strings via toasts instead of via the notification status bar area.

### Question 7: Which of the following statements are correct with respect to the capabilities provided by Android's LocalBroadcastManager (choose all that apply):
* It uses the Activity Manager Service to efficiently route intents to zero or more components
* It allows broadcast receivers to run in the background performing long-running operations and/or accessing remote resources
* ***It performs optimizations for intra-app communication by ensuring intents don't cross process boundaries***
* ***It enhances app security by ensuring intents can't be sent or received by components in other apps***

### Question 8: Which of the following are key differences between the ImageDownloaderBRD and ImageDownloaderBRS apps (choose all that apply):
* ***ImageDownloaderBRS uses SharedPreferences to communicate between  the DownloadReceiver and the MainActivity, whereas ImageDownloaderBRD uses a boolean to communicate between the DownloadReceiver and the MainActivity.***
* ImageDownloaderBRS uses the LocalBroadcastManager to route intents, whereas ImageDownloaderBRD uses the Activity Manager Service
* The DownloadReceiver in ImageDownloaderBRS runs in a different process as the MainActivity, whereas the DownloadReceiver in ImageDownloaderBRD runs in the same process as MainActivity.
* ***ImageDownloaderBRS uses the Activity Manager Service to route intents, whereas ImageDownloaderBRD uses the LocalBroadcastManager***
