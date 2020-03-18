# Android-App-Screen-On

The application was created with the goal of bypassing the phone screen timeout function. I wanted an app that can allow me to play music on Youtube while i'm cooking without the need of tapping my phone every few minutes. There were some app with this feature in Play Store like Stay Alive! but requires premium version.

The easiest way to bypass screen timeout would be to use "FLAG_KEEP_SCREEN_ON" but this only works if you let the app run indefinitely. If I switch to Youtube, the flag will automatically be removed and the screen will shut down. After spending some time on Stack Overflow, there was a response that seems to have answered my question.

"Add android:keepScreenOn="true" to some widget in your layout XML resource for this activity. So long as that widget is visible on the screen, the screen will not turn off automatically."

Following the developer's advice, I moved on to creating a floating widget app with the help of a tutorial. There were few errors but were ultimately solved using the links below. Lastly, i added "android:keepScreenOn="true" to the widget.xml and the app was a success at the end. 

---

Google Developer documentation:

https://developer.android.com/training/scheduling/wakelock#screen

Android keep screen on tutorial:

https://www.android-examples.com/prevent-android-app-activity-screen-from-sleeping-programmatically/

Keep screen on while browsing answer: 

https://stackoverflow.com/questions/9335908/how-to-prevent-the-screen-of-an-android-device-to-turn-off-during-the-execution/9336008

Android floating widget tutorial:

https://www.spaceotechnologies.com/android-floating-widget-tutorial/

AppCompatActivity error fix:

https://stackoverflow.com/questions/23330816/error-package-android-support-v7-app-does-not-exist

How to add icon.png to Android Studio:

https://stackoverflow.com/questions/29047902/how-to-add-an-image-to-the-drawable-folder-in-android-studio

Window type 2002 error fix:

https://stackoverflow.com/questions/52059033/permission-denied-for-window-type-2002-in-android-studio

How to change app title on Android Studio:

https://www.youtube.com/watch?v=mKmHvU7cz_w


