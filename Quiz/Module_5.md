# Module 5
## Android App Components - Intents Activities and Broadcast Receivers

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
