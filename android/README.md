# Android

## Android core

* **Android application components** <br />
&nbsp; Activities <br />
&nbsp; Services <br />
&nbsp; Broadcast receivers <br />
&nbsp; Content providers
* **What is `Context`? How is it used?** <br />
* **Life cycle of Android activity** <br />
    * onCreate()
    * onStart()
    * onResume()
    * onPause()
    * onStop()
    * onDestroy()
* **Intent and it's types**
    Intent is used to send action to another component of application, other application or system component. <br/>
    Intent can be:
  * Implicit - used to call system for some action, system asks user what app to use for this action, or using default application
  * Explicit - used to invoke certain component of your app or another app thai supports it (activity should have intent filter set in manifest).
* **When only onDestroy is called for an activity without onPause() and onStop()?** <br/>
    If finish() is called or activity initialization occurred inside onCreate().


