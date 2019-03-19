<!-- badges -->
<div align="center">

<!-- title -->

# Awesome Firebase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- subtitle -->

The most **up to date** list of [Firebase][firebase] docs, talks, tools, examples &amp; articles the internet has to offer.

<!-- image -->

<a href="https://firebase.google.com/docs/" target="_blank" rel="noopener noreferrer">
  <img src="images/firebase-services.gif" />
</a>

<!-- other language links -->
<p align="right">
    <!-- <sup><a href="README_ES.md">es</a></sup>
    <sup><a href="README_ID.md">id</a></sup>
    <sup><a href="README_JA.md">ja</a></sup>
    <sup><a href="README_KO.md">ko</a></sup>
    <sup><a href="README_PT.md">pt</a></sup>
    <sup><a href="README_ZH.md">zh</a></sup> -->
</p>

[Firebase][firebase] is an app dev platform built on the [Google Cloud Platform][gcp-products] providing services and cross-platform SDKs!

</div>

<!-- toc -->

## Contents

- [Featured (new releases)](#featured-new-releases)
- [Official Firebase Docs & Quickstarts](#official-firebase-docs--quickstarts)
- [Web](#web)
- [Mobile](#mobile)
- [Server-side (Cloud Functions, BigQuery etc)](#server-side-cloud-functions-bigquery-etc)
- [CLI & Editor](#cli--editor)
- [Other](#other)
- [Follow](#follow)

<p>
  <b>Legend</b>:
    <em>
    📝 blog posts
    · 💡 examples
    · 📖 docs
    · 🔌 libraries
    · 🔧 tools
    · 📹 talks/video
    </em>
</p>

<!-- START content -->

## Featured (new releases)

- 📖 [Hosting Version History][new-1] - Automatic deletion of older versions of your site deployments.
- 🔌 [Integrify][new-2] - Enforce referential and data integrity in Firestore using pre-canned Cloud Functions triggers.
- 🔧 [Firepit][new-3] - Firepit is a standalone, portable version of the Firebase CLI which has no depedencies (including Node.js).
- 🔧 [VSCode Firebase Explorer][new-4] - Explore and manage your Firebase projects.
- 🔌 [React Firebase Hooks][new-5] - React Hooks for Firebase services.

## Official Firebase Docs & Quickstarts

- 📖 [Firebase Documentation][docs-1] - Official Firebase Documentation.
- 💡 [Firebase Quickstarts][docs-2] - Official Firebase Quickstarts.

## Web

- 🔌 [Firebase UI][web-1] - FirebaseUI is an open-source JavaScript library for Web that provides simple, customizable UI bindings on top of Firebase SDKs to eliminate boilerplate code and promote best practices.
- 🔌 [Firebase UI for React][web-2] - React Wrapper for firebaseUI Web.
- 🔌 [GeoFire for JavaScript][web-3] - Realtime location queries with Firebase.
- 💡 [FirePad][web-4] - Collaborative Text Editor Powered by Firebase.
- 🔌 [Ember Fire][web-5] - Official Ember data adapter for Firebase.
- 🔌 [Firebase Dart][web-6] - Dart wrapper for Firebase.
- 🔌 [PolymerFire][web-7] - Polymer Web Components for Firebase.
- 🔌 [VueFire][web-8] - Firebase bindings for Vue.js.
- 🔌 [Angular Fire 2][web-9] - Official library for Firebase and Angular.
- 🔌 [Re-base][web-10] - Relay inspired library for building React.js + Firebase applications.
- 🔌 [React Redux Firebase][web-11] - Redux bindings for Firebase. Includes Higher Order Component for use with React.
- 🔌 [GatsbyJS Firebase Data Source][web-12] - Query your Firebase data right into your statically generated pages with Gatsby.
- 🔌 [Apollo Link Firebase][web-13] - Provides a local GraphQL interface to RealtimeDB. DB syncs locally to device, Apollo Link provides querying into the local DB.
- 🔌 [BuckleScript Bindings for Firebase][web-14] - BuckleScript bindings for Firebase for use in ReasonML projects.
- 💡 [Angular Firebase PWA][web-15] - Is an Angular PWA powered by Firebase. It can serve as a foundation to learn this stack and roll out more complex features.
- 🔌 [FireSQL][web-16] - Query Firestore using SQL syntax. Issues the minimum amount of queries necessary in order to get the data that you request.

## Mobile

- 📖 [Firebase Flutter Documentation][mobile-1] - Official Firebase Flutter Setup.
- 🔌 [NativeScript plugin Firebase][mobile-2] - NativeScript plugin for Firebase.
- 🔌 [FlutterFire][mobile-3] - Use Firebase services in your cross-platform [Flutter][mobile-3-flutter] application.
- 🔌 [React Native Firebase][mobile-4] - Well-tested feature rich modular Firebase implementation for React Native. Supports both iOS & Android platforms.
- 🔌 [React Native Firebase Cloud Messaging][mobile-5] -
  React Native module for Firebase Cloud Messaging and local notification.
- 💡 [Expo Native Firebase][mobile-6] - Native Firebase Expo App (iOS, Android) Demo for Firestore, Notifications, Analytics, Storage, Messaging, Database.
- 💡 [Flutter Calendar App][mobile-7] -
  New Flutter application implementing a simple mobile calendar app for storing basic events into Firebase cloud database.

### Android

- 🔌 [GeoFire for Java][android-1] - Realtime location queries with Firebase.
- 🔌 [Firebase UI][android-2] - Optimized UI components for Firebase.
- 🔌 [FireXtensions][android-3] - Unofficial Kotlin Extensions for the Firebase Android SDK.

### iOS

- 🔌 [GeoFire for Objective-C][ios-1] - Realtime location queries with Firebase.
- 🔌 [Firebase UI][ios-2] - iOS UI bindings for Firebase.
- 💡 [MLKit - ARCore][ios-3] - Example detecting objects and tags them with 3D labels in Augmented Reality. Uses Firebase ML Kit, ARCore and Firebase RTDB.
- 💡 [MLKit - ARKit][ios-4] - Example detecting objects using Firebase ML Kit and tags them with 3D labels in Augmented Reality.

## Server-side (Cloud Functions, BigQuery etc)

- 📖 [Firebase Admin Documentation][server-1] - Official Firebase Admin SDK Server Setup.
- 💡 [Functions Samples][server-2] - Collection of sample apps showcasing popular use cases using Cloud Functions for Firebase.
- 💡 [Express Server on Cloud Functions][server-3] - Host an Express server on Cloud Functions.
- 📝 [GraphQL Server on Cloud Functions][server-4] - Host an Express server with GraphQL middleware on Cloud Functions.
- 💡 [Compiled Code with Cloud Functions][server-5] - Compile your Flow, TypeScript or ReasonML to the correct Node runtime using Babel, TypeScript Compiler or ParcelJS.
- 📝 [BigQuery & Google Analytics][server-6] - How Do I Create a Closed Funnel in Google Analytics for Firebase Using BigQuery.
- 📹 [Official Cloud Function #Firecasts][server-7] - YouTube video series about understanding how Cloud Functions work.

## CLI & Editor

- 🔧 [Firebase Tools][cli-editor-1] - The Firebase Command Line Tools.
- 🔧 [Firebase CI][cli-editor-2] - Simplified Firebase interaction for continuous integration.
- 🔧 [VSFire][cli-editor-3] - VSCode extension for syntax highlighting & code completions with Firestore security rules & indexes.
- 🔧 [Firebase Firestore Snippets][cli-editor-4] - Contains the snippet for both firebase and firestore in VS Code editor.
- 🔧 [Fuego][cli-editor-5] - Firestore client CLI supporting document add/update/query with filtering and pagination.
- 🔧 [Firestore Rules Generator][cli-editor-6] - Official (but experimental) Firebase Rules Generator for Cloud Firestore based on Google's Protocol Buffer format.

## Other

- 🔌 [FireDrill][other-1] - Find, Edit, Add, Remove, Import, Export, and Report on your Firebase data.
- 💡 [Unity Solutions][other-2] - Use Firebase tools to incorporate common features into your games.
- 🔌 [Firebase AIR Native Extension][other-3] - Firebase ANE collection give you access to the Google Firebase project in your AdobeAir projects supported on both Android and iOS with 100% identical ActionScript API.
- 🔌 [QtFirebase][other-4] - An effort to bring Google's Firebase C++ API to Qt + QML.
- 📝 [StackBlitz to Firebase Hosting Deployments][other-5] - StackBlitz (online code editor) to Firebase Hosting static deployments.
- 🔧 [Flamelink][other-6] - CMS for Firebase. Supports Firestore, RealtimeDatabase & Storage.
- 🔧 [Canner CMS][other-7] - CMS for developers supporting data sources such as Firebase/Firestore, GraphQL and Restful APIs.
- 📹 [Firebase Summit 2018][other-8] - All Firebase Summit 2018 talks.
- 📹 [Firebase @ Google Cloud Next '18][other-9] - All Firebase talks @ Google Cloud Next 2018.
- 📹 [Firebase @ Google IO '18][other-10] - All Firebase talks @ Google IO 2018.
- 📹 [#AskFirebase YouTube Playlist][other-11] - Official #AskFirebase playlist on YouTube.

<!-- END content -->

## Follow

### Official

📹 [Firebase YouTube][official-1] 📝 [Firebase Blog][official-2] 🐦 [@firebase][official-3] 🐦 [@bestoffirebase][official-4]

### Community

📹 [Fireship - AngularFirebase][community-1]

Who else should we be following!?

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors][contributors]!

## License

[CC0 License][license]

<!-- Links -->

[firebase]: https://firebase.google.com
[gcp-products]: https://cloud.google.com/products

<!-- Contents -->
<!-- Featured (new releases) -->

[new-1]: https://firebase.google.com/docs/hosting/deploying#set_limit_for_retained_versions
[new-2]: https://github.com/anishkny/integrify
[new-3]: https://github.com/abehaskins/firepit
[new-4]: https://github.com/jsayol/vscode-firebase-explorer
[new-5]: https://github.com/CSFrequency/react-firebase-hooks

<!-- Official Firebase Docs & Quickstarts -->

[docs-1]: https://firebase.google.com/docs
[docs-2]: https://github.com/firebase?utf8=%E2%9C%93&q=quickstart&type=&language=

<!-- Web -->

[web-1]: https://github.com/firebase/firebaseui-web
[web-2]: https://github.com/firebase/firebaseui-web-react
[web-3]: https://github.com/firebase/geofire-js
[web-4]: https://github.com/FirebaseExtended/firepad
[web-5]: https://github.com/firebase/emberFire
[web-6]: https://github.com/FirebaseExtended/firebase-dart
[web-7]: https://github.com/FirebaseExtended/polymerfire
[web-8]: https://github.com/vuejs/vuefire
[web-9]: https://github.com/angular/angularfire2
[web-10]: https://github.com/tylermcginnis/re-base
[web-11]: https://github.com/prescottprue/react-redux-firebase
[web-12]: https://www.gatsbyjs.org/packages/gatsby-source-firebase/#gatsby-firebase-source
[web-13]: https://github.com/Canner/apollo-link-firebase
[web-14]: https://github.com/avohq/bs-firebase
[web-15]: https://github.com/codediodeio/angular-firestarter
[web-16]: https://github.com/jsayol/FireSQL

<!-- Mobile -->

[mobile-1]: https://firebase.google.com/docs/flutter/setup
[mobile-2]: https://github.com/EddyVerbruggen/nativescript-plugin-firebase
[mobile-3]: https://github.com/flutter/plugins/blob/master/FlutterFire.md
[mobile-3-flutter]: https://flutter.io/
[mobile-4]: https://github.com/invertase/react-native-firebase
[mobile-5]: https://github.com/evollu/react-native-fcm
[mobile-6]: https://github.com/EvanBacon/expo-native-firebase
[mobile-7]: https://github.com/mattgraham1/FlutterCalendar
[android-1]: https://github.com/firebase/geofire-java
[android-2]: https://github.com/firebase/firebaseui-android
[android-3]: https://github.com/rosariopfernandes/firextensions
[ios-1]: https://github.com/firebase/geofire-objc
[ios-2]: https://github.com/firebase/firebaseui-ios
[ios-3]: https://github.com/FirebaseExtended/MLKit-ARCore
[ios-4]: https://github.com/FirebaseExtended/MLKit-ARKit

<!-- Server-side (Cloud Functions, BigQuery etc) -->

[server-1]: https://firebase.google.com/docs/admin/setup
[server-2]: https://github.com/firebase/functions-samples
[server-3]: https://github.com/jthegedus/firebase-gcp-examples/tree/master/fb-functions-express
[server-4]: https://codeburst.io/graphql-server-on-cloud-functions-for-firebase-ae97441399c0
[server-5]: https://github.com/jthegedus/firebase-gcp-examples/tree/master/fb-functions-compiled_code
[server-6]: https://medium.com/firebase-developers/how-do-i-create-a-closed-funnel-in-google-analytics-for-firebase-using-bigquery-6eb2645917e1
[server-7]: https://www.youtube.com/watch?v=2mjfI0FYP7Y&list=PLl-K7zZEsYLm9A9rcHb1IkyQUu6QwbjdM

<!-- CLI & Editor -->

[cli-editor-1]: https://github.com/firebase/firebase-tools
[cli-editor-2]: https://github.com/prescottprue/firebase-ci
[cli-editor-3]: https://github.com/toba/vsfire
[cli-editor-4]: https://github.com/peterhdd/firebase-firestore-snippets
[cli-editor-5]: https://github.com/sgarciac/fuego
[cli-editor-6]: https://github.com/FirebaseExtended/protobuf-rules-gen

<!-- Other -->

[other-1]: https://github.com/scottlepp/fire-drill
[other-2]: https://github.com/FirebaseExtended/unity-solutions
[other-3]: https://github.com/myflashlab/Firebase-ANE
[other-4]: https://github.com/Larpon/QtFirebase
[other-5]: https://medium.com/@ericsimons/announcing-split-second-static-deploys-for-firebase-7440d8e84879
[other-6]: https://flamelink.io/
[other-7]: https://github.com/Canner/canner
[other-8]: https://www.youtube.com/watch?v=lN0VXVXsj9k&list=PLl-K7zZEsYLnqdlmz7iFe9Lb6cRU3Nv4R
[other-9]: https://www.youtube.com/watch?v=OPj26MY16F8&list=PLl-K7zZEsYLmYx3MkJRIUPH_JVFHLTlwL
[other-10]: https://www.youtube.com/watch?v=e-8fiv-vteQ&list=PLl-K7zZEsYLn1omgx_VUhCDFsQMA7PRDd
[other-11]: https://www.youtube.com/watch?v=TSzhzR4wzSE&list=PLl-K7zZEsYLkkCFs6T9mlqG8v6NCs38pA

<!-- Follow -->

[official-1]: https://www.youtube.com/user/Firebase
[official-2]: https://firebase.googleblog.com/
[official-3]: https://twitter.com/firebase
[official-4]: https://twitter.com/bestoffirebase
[community-1]: https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA

<!-- Contributors -->

[contributors]: https://github.com/jthegedus/awesome-firebase/graphs/contributors

<!-- License -->

[license]: https://github.com/jthegedus/awesome-firebase/blob/master/LICENSE
