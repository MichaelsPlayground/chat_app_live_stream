# chat_app_live_stream

```plaintext
dependencies:
firebase_core: ^1.6.0
firebase_auth: ^3.1.0
cloud_firestore: ^2.5.1
```

```plaintext
based upon:
https://github.com/tensor-programming/chat_app_live_stream
Originalprojekt nicht null safety
changed to null safety and running 

todo: if not registered user logs in there is an exception in concole
but no feedback to user to register instead
```

Setup:
```plaintext
Firebase console: https://console.firebase.google.com/
Name: ChatAppLiveStream

IOS:
in Podfile:
platform :ios, '10.0'

AppleBundleIdentifier: de.fluttercrypto1.chatAppLiveStream
Authentication with Email + Passwort activated

Android:

Open up android/build.gradle and add this under dependencies:
classpath 'com.google.gms:google-services:4.3.10'

Then open up android/app/build.gradle and add this:
apply plugin: 'com.google.gms.google-services'

PackageName: de.fluttercrypto1.chat_app_live_stream

in build.gradle (app):
defaultConfig {
applicationId "de.fluttercrypto1.simple_flutter_chat_app"
minSdkVersion 21
```

```plaintext

```

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
