# Module 3
## Android App Components - Intents Activities and Broadcast Receivers

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

