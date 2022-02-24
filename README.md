# AppiumExamples

To Start Automation with Appium, we have to follow some certian steps.
First we have to make our system ready and then we can start our journey with appium.

1. Download & Install JDK - 
https://www.oracle.com/java/technologies/downloads/#jdk17-windows
2. Download & Install or Download & Unzip Eclipse
https://www.eclipse.org/downloads/
3. Download & Install android studion - Android SDK thourgh Android Studio
https://developer.android.com/studio
4. Set environment variable(path)
5. Set JAVA_HOME & ANDRIOD_HOME
6. Plugin Device (turn on developer mode & USB debugging)
    Find build number under settings and tap 7 times on build number.
    Enter your pattern, PIN or password to enable the Developer options menu.
    The "Developer options" menu will now appear in your Settings menu.
    Turn On the "USB Debugging" option from "Developer Options"
7. Indentify appPackage & appActivityName
    Open the app in your device : and use the command - adb shell "dumpsys activity activities | grep mResumedActivity"
8. Create Java(Maven) Project in Eclipse
9. Add Dependencies
https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java
https://mvnrepository.com/artifact/io.appium/java-client
10. Identify Elements
11. Start Writing Automtion Code

Desired Capabilities :
https://appium.io/docs/en/writing-running-appium/caps/

