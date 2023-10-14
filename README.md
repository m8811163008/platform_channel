# batterylevel

Flutter uses a flexible system that allows you to call platform-specific APIs in a language that works directly with those APIs:

* Kotlin on Android
* Swift  on iOS

On the client side, MethodChannel enables sending messages that correspond to method calls. On the platform side, MethodChannel on Android (MethodChannelAndroid) and FlutterMethodChannel on iOS (MethodChanneliOS) enable receiving method calls and sending back a result.

Check here for Swift code: https://github.com/m8811163008/platform_channel/blob/main/ios/Runner/AppDelegate.swift

Check here for Kotlin code: https://github.com/m8811163008/platform_channel/blob/main/android/app/src/main/kotlin/com/example/batterylevel/MainActivity.kt
