# Android_Miscellaneous_ANE
==================================================

ANE collection of various Android native function :

-----------------

-Get the device ID
```
var id:String = AndroidMiscellaneous.getInstance().getDeviceId();
```

- Get the time in miliseconds since the last boot
```
-var time:Number = AndroidMiscellaneous.getInstance().getElapsedTimeSinceBoot();
```

- Enter Immersive fullscreen mode / param : Boolean isSticky
```
AndroidMiscellaneous.getInstance().activateImmersiveMode(true);
```
- Get the device ID
```
var id:String = AndroidMiscellaneous.getInstance().getDeviceId();
```

- Get the the screen Height when immersive mode
```
var screenHeight:int=AndroidMiscellaneous.getInstance().getImmersiveScreenHeight();
```

- Get the the screen Width when immersive mode
```
var screenWidth:int=AndroidMiscellaneous.getInstance().getImmersiveScreenWidth();
```

- Show Message using android native toast / param : msg:String,duration:int
```
AndroidMiscellaneous.getInstance().showToast("Hello Toast",AndroidMiscellaneous.TOAST_LENGTH_LONG);
```
- Show Local Notification using android native notification /  param: title:String,msg:String,notificationID:int,isSoundOn:Boolean
```
AndroidMiscellaneous.getInstance().showLocalNotification("My title", "Hello world", 1234, true);
```
(app icon is used and notification opens your app when clicked on)
In order to use showLocalNotification function you need to add  [Android_Support_v4_Lib_ANE](https://github.com/GrumpyCarrot/Android_Support_v4_Lib_ANE)


- Shows the native android Share via dialog / params : subjectText:String,mainText:String
```
AndroidMiscellaneous.getInstance().shareIt("My subject","My main text");
```

-----------------

This ANE was created with  -swf-version=30 / AIR 19.

```
<extensionID>com.grumpycarrot.ane.androidmiscellaneous</extensionID>
```

------------------------------------------------
 [GrumpyCarrot](http://www.grumpycarrot.com)