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

<!-- translations -->

Translations: [🇬🇧 en](README.md) · [🇷🇺 ru](README_RU.md) <!-- · [🇪🇸 es](README_ES.md) · [🇮🇩 id](README_ID.md) · [🇯🇵 ja](README_JA.md) · [🇰🇷 ko](README_KO.md) · [🇵🇹 pt](README_PT.md) · [🇨🇳 zh](README_ZH.md) -->

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

**Legend**: 📝 blog posts · 💡 examples · 📖 docs · 🔌 libraries · 🔧 tools · 📹 talks/video

<!-- START content -->

## Featured (new releases)

- 🔧 [Fireward][fireward] - Easy to use language for Firestore rules, similar to Firebase Bolt.
- 📝 [Scheduled (Cron) Cloud Functions for Firebase][cron-cloud-functions] - Firebase-native Cron triggers for Firebase Cloud Functions.
- 🔌 [Integrify][integrify] - Enforce referential and data integrity in Firestore using pre-canned Cloud Functions triggers.
- 🔧 [VSCode Firebase Explorer][vscode-firebase-explorer] - Explore and manage your Firebase projects.
- 🔌 [React Firebase Hooks][react-firebase-hooks] - React Hooks for Firebase services.

## Official Firebase Docs & Quickstarts

- 📖 [Firebase Documentation][fb-docs] - Official Firebase Documentation.
- 💡 [Firebase Quickstarts][fb-quickstarts] - Official Firebase Quickstarts.
- 💡 [Google Codelabs | Firebase][google-codelabs] - Google Developers Codelabs provide a guided, tutorial, hands-on coding experience.

## Web

- 🔌 [Firebase UI][firebase-ui] - FirebaseUI is an open-source JavaScript library for Web that provides simple, customizable UI bindings on top of Firebase SDKs to eliminate boilerplate code and promote best practices.
- 🔌 [Firebase UI for React][fb-ui-react] - React Wrapper for firebaseUI Web.
- 🔌 [GeoFire for JavaScript][geofire] - Realtime location queries with Firebase.
- 💡 [FirePad][firepad] - Collaborative Text Editor Powered by Firebase.
- 🔌 [Ember Fire][ember-fire] - Official Ember data adapter for Firebase.
- 🔌 [Firebase Dart][fb-dart] - Dart wrapper for Firebase.
- 🔌 [PolymerFire][polymer-fire] - Polymer Web Components for Firebase.
- 🔌 [VueFire][vue-fire] - Firebase bindings for Vue.js.
- 🔌 [Angular Fire 2][ng-fire] - Official library for Firebase and Angular.
- 🔌 [Re-base][rebase] - Relay inspired library for building React.js + Firebase applications.
- 🔌 [React Redux Firebase][react-redux-fb] - Redux bindings for Firebase. Includes Higher Order Component for use with React.
- 🔌 [GatsbyJS Firebase Data Source][gatsby-fire] - Query your Firebase data right into your statically generated pages with Gatsby.
- 🔌 [Apollo Link Firebase][apollo-link-fb] - Provides a local GraphQL interface to RealtimeDB. DB syncs locally to device, Apollo Link provides querying into the local DB.
- 🔌 [BuckleScript Bindings for Firebase][bs-fb] - BuckleScript bindings for Firebase for use in ReasonML projects.
- 💡 [Angular Firebase PWA][ng-firestarter] - Is an Angular PWA powered by Firebase. It can serve as a foundation to learn this stack and roll out more complex features.
- 🔌 [FireSQL][firesql] - Query Firestore using SQL syntax. Issues the minimum amount of queries necessary in order to get the data that you request.
- 📖 [Hosting Version History][hosting-version-hist] - Automatic deletion of older versions of your site deployments.
- 🔌 [Firestorter][firestorter] - Use Firestore in React with zero effort, using MobX (also for react-native).

## Mobile

- 📖 [Firebase Flutter Documentation][fb-flutter] - Official Firebase Flutter Setup.
- 🔌 [NativeScript plugin Firebase][fb-nativescript] - NativeScript plugin for Firebase.
- 🔌 [FlutterFire][fb-flutter-fire] - Use Firebase services in your cross-platform [Flutter][flutter] application.
- 🔌 [React Native Firebase][rn-fb] - Well-tested feature rich modular Firebase implementation for React Native. Supports both iOS & Android platforms.
- 🔌 [React Native Firebase Cloud Messaging][rn-fb-fcm] -
  React Native module for Firebase Cloud Messaging and local notification.
- 💡 [Expo Native Firebase][expo-fb] - Native Firebase Expo App (iOS, Android) Demo for Firestore, Notifications, Analytics, Storage, Messaging, Database.
- 💡 [Flutter Calendar App][flutter-cal] -
  New Flutter application implementing a simple mobile calendar app for storing basic events into Firebase cloud database.

### Android

- 🔌 [GeoFire for Java][geofire-java] - Realtime location queries with Firebase.
- 🔌 [Firebase UI][fb-ui-android] - Optimized UI components for Firebase.
- 🔌 [FireXtensions][android-firextensions] - Unofficial Kotlin Extensions for the Firebase Android SDK.

### iOS

- 🔌 [GeoFire for Objective-C][geofire-objc] - Realtime location queries with Firebase.
- 🔌 [Firebase UI][fb-ui-ios] - iOS UI bindings for Firebase.
- 💡 [MLKit - ARCore][mlkit-arcore] - Example detecting objects and tags them with 3D labels in Augmented Reality. Uses Firebase ML Kit, ARCore and Firebase RTDB.
- 💡 [MLKit - ARKit][mlkit-arkit] - Example detecting objects using Firebase ML Kit and tags them with 3D labels in Augmented Reality.

## Server-side (Cloud Functions, BigQuery etc)

- 📖 [Firebase Admin Documentation][server-1] - Official Firebase Admin SDK Server Setup.
- 💡 [Functions Samples][server-2] - Collection of sample apps showcasing popular use cases using Cloud Functions for Firebase.
- 💡 [Express Server on Cloud Functions][server-3] - Host an Express server on Cloud Functions.
- 📝 [GraphQL Server on Cloud Functions][server-4] - Host an Express server with GraphQL middleware on Cloud Functions.
- 💡 [Compiled Code with Cloud Functions][server-5] - Compile your Flow, TypeScript or ReasonML to the correct Node runtime using Babel, TypeScript Compiler or ParcelJS.
- 📝 [BigQuery & Google Analytics][server-6] - How Do I Create a Closed Funnel in Google Analytics for Firebase Using BigQuery.
- 📹 [Official Cloud Function #Firecasts][server-7] - YouTube video series about understanding how Cloud Functions work.
- 📝 [Firebase Hosting for Cloud Run Services][cloud-run-rewrites] - Dynamic content with Hosting Rewrites & Cloud Run Services.

## CLI & Editor

- 🔧 [Firebase Tools][cli-editor-1] - The Firebase Command Line Tools.
- 🔧 [Firebase CI][cli-editor-2] - Simplified Firebase interaction for continuous integration.
- 🔧 [VSFire][cli-editor-3] - VSCode extension for syntax highlighting & code completions with Firestore security rules & indexes.
- 🔧 [Firebase Firestore Snippets][cli-editor-4] - Contains the snippet for both Firebase and Firestore in VS Code editor.
- 🔧 [Fuego][cli-editor-5] - Firestore client CLI supporting document add/update/query with filtering and pagination.
- 🔧 [Firestore Rules Generator][cli-editor-6] - Official (but experimental) Firebase Rules Generator for Cloud Firestore based on Google's Protocol Buffer format.
- 🔧 [Firepit][firepit] - Firepit is a standalone, portable version of the Firebase CLI which has no depedencies (including Node.js).

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

- 📹 [Fireship - AngularFirebase][angular-firebase]
- 📹 ru [@firebase_ru - Telegram friendly chat][ru-telegram-chat]

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

<!-- Featured (new releases) -->

[cron-cloud-functions]: https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html
[cloud-run-rewrites]: https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html
[integrify]: https://github.com/anishkny/integrify
[vscode-firebase-explorer]: https://github.com/jsayol/vscode-firebase-explorer
[react-firebase-hooks]: https://github.com/CSFrequency/react-firebase-hooks

<!-- Official Firebase Docs & Quickstarts -->

[fb-docs]: https://firebase.google.com/docs
[fb-quickstarts]: https://github.com/firebase?utf8=%E2%9C%93&q=quickstart&type=&language=
[google-codelabs]: https://codelabs.developers.google.com/?cat=Firebase

<!-- Web -->

[firebase-ui]: https://github.com/firebase/firebaseui-web
[fb-ui-react]: https://github.com/firebase/firebaseui-web-react
[geofire]: https://github.com/firebase/geofire-js
[firepad]: https://github.com/FirebaseExtended/firepad
[ember-fire]: https://github.com/firebase/emberFire
[fb-dart]: https://github.com/FirebaseExtended/firebase-dart
[polymer-fire]: https://github.com/FirebaseExtended/polymerfire
[vue-fire]: https://github.com/vuejs/vuefire
[ng-fire]: https://github.com/angular/angularfire2
[rebase]: https://github.com/tylermcginnis/re-base
[react-redux-fb]: https://github.com/prescottprue/react-redux-firebase
[gatsby-fire]: https://www.gatsbyjs.org/packages/gatsby-source-firebase/#gatsby-firebase-source
[apollo-link-fb]: https://github.com/Canner/apollo-link-firebase
[bs-fb]: https://github.com/avohq/bs-firebase
[ng-firestarter]: https://github.com/codediodeio/angular-firestarter
[firesql]: https://github.com/jsayol/FireSQL
[firestorter]: https://github.com/IjzerenHein/firestorter
[hosting-version-hist]: https://firebase.google.com/docs/hosting/deploying#set_limit_for_retained_versions

<!-- Mobile -->

[fb-flutter]: https://firebase.google.com/docs/flutter/setup
[fb-nativescript]: https://github.com/EddyVerbruggen/nativescript-plugin-firebase
[fb-flutter-fire]: https://github.com/flutter/plugins/blob/master/FlutterFire.md
[flutter]: https://flutter.io/
[rn-fb]: https://github.com/invertase/react-native-firebase
[rn-fb-fcm]: https://github.com/evollu/react-native-fcm
[expo-fb]: https://github.com/EvanBacon/expo-native-firebase
[flutter-cal]: https://github.com/mattgraham1/FlutterCalendar

<!-- Mobile: Android -->

[geofire-java]: https://github.com/firebase/geofire-java
[fb-ui-android]: https://github.com/firebase/firebaseui-android
[android-firextensions]: https://github.com/rosariopfernandes/firextensions

<!-- Movile: iOS -->

[geofire-objc]: https://github.com/firebase/geofire-objc
[fb-ui-ios]: https://github.com/firebase/firebaseui-ios
[mlkit-arcore]: https://github.com/FirebaseExtended/MLKit-ARCore
[mlkit-arkit]: https://github.com/FirebaseExtended/MLKit-ARKit

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
[firepit]: https://github.com/abehaskins/firepit
[fireward]: https://github.com/bijoutrouvaille/fireward

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
[angular-firebase]: https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA
[ru-telegram-chat]: https://t.me/firebase_ru

<!-- Contributors -->

[contributors]: https://github.com/jthegedus/awesome-firebase/graphs/contributors

<!-- License -->

[license]: https://github.com/jthegedus/awesome-firebase/blob/master/LICENSE
