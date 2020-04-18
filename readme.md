<!-- badges -->
<div align="center">

<!-- title -->
<!--lint ignore no-dead-urls-->
# Awesome Firebase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Lint Awesome List](https://github.com/jthegedus/awesome-firebase/workflows/Lint%20Awesome%20List/badge.svg)

<!-- subtitle -->

The most **up to date** list of [Firebase](https://firebase.google.com) docs, talks, tools, examples & articles the internet has to offer.

<!-- image -->

<a href="https://firebase.google.com/docs/" target="_blank" rel="noopener noreferrer">
  <img src="images/firebase-services.gif" />
</a>

<!-- translations -->

Translations: [🇬🇧 en](readme.md) · [🇷🇺 ru](readme_ru.md) <!-- · [🇪🇸 es](readme_es.md) · [🇮🇩 id](readme_id.md) · [🇯🇵 ja](readme_ja.md) · [🇰🇷 ko](readme_ko.md) · [🇵🇹 pt](readme_pt.md) · [🇨🇳 zh](readme_zh.md) -->

[Firebase](https://firebase.google.com) is an app dev platform built on the [Google Cloud Platform](https://cloud.google.com/products) providing services and cross-platform SDKs!

</div>

<!-- toc -->

## Contents

- [Featured (new releases)](#featured-new-releases)
- [Official Firebase Docs & Quickstarts](#official-firebase-docs--quickstarts)
- [Web](#web)
- [Mobile](#mobile)
- [Games](#games)
- [Server-side (Cloud Functions, BigQuery etc)](#server-side-cloud-functions-bigquery-etc)
- [CLI & Editor](#cli--editor)
- [Other](#other)
- [Follow](#follow)

**Legend**: 📝 blog posts · 💡 examples · 📖 docs · 🔌 libraries · 🔧 tools · 📹 talks/video

<!-- START content -->

## Featured (new releases)

- 📖 [Firebase Tools UI](https://github.com/firebase/firebase-tools-ui) - Web UI for Firebase Emulator Suite.
- 🔧 [Typesaurus](https://github.com/kossnocorp/typesaurus) - Type-safe TypeScript-first ODM for Firestore.
- 🔧 [asdf-firebase](https://github.com/jthegedus/asdf-firebase) - An [asdf-vm](https://asdf-vm.com/) plugin for `firebase-tools`. Manage your Firebase CLI without Node.js or `npm`! Great for `python`, `golang`, `c++` & `java` Firebase projects.
- 🔧 [Remote Styles with Remote Config](https://github.com/firebaseextended/remote-styles/) - Dynamic/Conditional loading of CSS stored in Remote Config. ([Launch post](https://medium.com/firebase-developers/introducing-remote-styles-conditional-css-loading-made-easy-daddbbcce050)).
- 🔧 [Firebase Extensions](https://firebase.google.com/products/extensions) - Firebase Extensions provide extended functionality to your apps without the need to research, write, or debug code on your own.

## Official Firebase Docs & Quickstarts

- 📖 [Firebase Documentation](https://firebase.google.com/docs) - Official Firebase Documentation.
- 🔧 [Firebase Status Dashboard](https://status.firebase.google.com) - This page provides status information on the services that are part of Firebase.
- 💡 [Firebase Quickstarts](https://github.com/firebase?utf8=%E2%9C%93&q=quickstart&type=&language=) - Official Firebase Quickstarts.
- 💡 [Google Codelabs | Firebase](https://codelabs.developers.google.com/?cat=Firebase) - Google Developers Codelabs provide a guided, tutorial, hands-on coding experience.
- 📖 [Firebase for Games](https://firebase.google.com/games) - New Firebase for Games landing page with links to Firebase/Google resources for game developers.

## Web

- 🔌 [React Fire](https://github.com/FirebaseExtended/reactfire) - Official Firebase React library with Hooks, Context Providers, and Components that make it easy to interact with Firebase.
- 🔌 [React Firebase Hooks](https://github.com/CSFrequency/react-firebase-hooks) - React Hooks for Firebase services.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-web) - FirebaseUI is an open-source JavaScript library for Web that provides simple, customizable UI bindings on top of Firebase SDKs to eliminate boilerplate code and promote best practices.
- 🔌 [Firebase UI for React](https://github.com/firebase/firebaseui-web-react) - React Wrapper for firebaseUI Web.
- 🔌 [GeoFire for JavaScript](https://github.com/firebase/geofire-js) - Realtime location queries with Firebase.
- 💡 [FirePad](https://github.com/FirebaseExtended/firepad) - Collaborative Text Editor Powered by Firebase.
- 🔌 [Ember Fire](https://github.com/firebase/emberFire) - Official Ember data adapter for Firebase.
- 🔌 [Firebase Dart](https://github.com/FirebaseExtended/firebase-dart) - Dart wrapper for Firebase.
- 🔌 [PolymerFire](https://github.com/FirebaseExtended/polymerfire) - Polymer Web Components for Firebase.
- 🔌 [VueFire](https://github.com/vuejs/vuefire) - Firebase bindings for Vue.js.
- 🔌 [Angular Fire 2](https://github.com/angular/angularfire2) - Official library for Firebase and Angular.
- 🔌 [Re-base](https://github.com/tylermcginnis/re-base) - Relay inspired library for building React.js + Firebase applications.
- 🔌 [React Redux Firebase](https://github.com/prescottprue/react-redux-firebase) - Redux bindings for Firebase. Includes Higher Order Component for use with React.
- 🔌 [GatsbyJS Firebase Data Source](https://www.gatsbyjs.org/packages/) - Query your Firebase data right into your statically generated pages with Gatsby.
- 🔌 [Apollo Link Firebase](https://github.com/Canner/apollo-link-firebase) - Provides a local GraphQL interface to RealtimeDB. DB syncs locally to device, Apollo Link provides querying into the local DB.
- 🔌 [BuckleScript Bindings for Firebase](https://github.com/avohq/bs-firebase) - BuckleScript bindings for Firebase for use in ReasonML projects.
- 💡 [Angular Firebase PWA](https://github.com/codediodeio/angular-firestarter) - Is an Angular PWA powered by Firebase. It can serve as a foundation to learn this stack and roll out more complex features.
- 🔌 [FireSQL](https://github.com/jsayol/FireSQL) - Query Firestore using SQL syntax. Issues the minimum amount of queries necessary in order to get the data that you request.
- 📖 [Hosting Version History](https://firebase.google.com/docs/hosting/deploying#set_limit_for_retained_versions) - Automatic deletion of older versions of your site deployments.
- 🔌 [Firestorter](https://github.com/IjzerenHein/firestorter) - Use Firestore in React with zero effort, using MobX (also for react-native).
- 💡 [Nextbase](https://github.com/martyan/nextbase) - Boilerplate of Next.js, Redux & Firebase for developers who want a quick start project.

## Mobile

- 📖 [Firebase Flutter Documentation](https://firebase.google.com/docs/flutter/setup) - Official Firebase Flutter Setup.
- 🔌 [NativeScript plugin Firebase](https://github.com/EddyVerbruggen/nativescript-plugin-firebase) - NativeScript plugin for Firebase.
- 🔌 [FlutterFire](https://github.com/flutter/plugins/blob/master/FlutterFire.md) - Use Firebase services in your cross-platform [Flutter](https://flutter.io/) application.
- 🔌 [React Native Firebase](https://github.com/invertase/react-native-firebase) - Well-tested feature rich modular Firebase implementation for React Native. Supports both iOS & Android platforms.
- 🔌 [React Native Firebase Cloud Messaging](https://github.com/evollu/react-native-fcm) -
  React Native module for Firebase Cloud Messaging and local notification.
- 💡 [Expo Native Firebase](https://github.com/EvanBacon/expo-native-firebase) - Native Firebase Expo App (iOS, Android) Demo for Firestore, Notifications, Analytics, Storage, Messaging, Database.
- 💡 [Flutter Calendar App](https://github.com/mattgraham1/FlutterCalendar) -
  New Flutter application implementing a simple mobile calendar app for storing basic events into Firebase cloud database.
- 🔧 [Firebase App Distribution](https://firebase.google.com/products/app-distribution/) - Distribute pre-release versions of your app to your trusted testers.

### Android

- 🔌 [GeoFire for Java](https://github.com/firebase/geofire-java) - Realtime location queries with Firebase.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-android) - Optimized UI components for Firebase.
- 🔌 [FireXtensions](https://github.com/rosariopfernandes/firextensions) - Unofficial Kotlin Extensions for the Firebase Android SDK.
- 🔌 [Firecoil](https://github.com/rosariopfernandes/firecoil) - Load images from GCS in your Android app using the image loading library Coil.

### iOS

- 🔌 [GeoFire for Objective-C](https://github.com/firebase/geofire-objc) - Realtime location queries with Firebase.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-ios) - iOS UI bindings for Firebase.
- 💡 [MLKit - ARCore](https://github.com/FirebaseExtended/MLKit-ARCore) - Example detecting objects and tags them with 3D labels in Augmented Reality. Uses Firebase ML Kit, ARCore and Firebase RTDB.
- 💡 [MLKit - ARKit](https://github.com/FirebaseExtended/MLKit-ARKit) - Example detecting objects using Firebase ML Kit and tags them with 3D labels in Augmented Reality.

## Games

- 📖 [Firestore for C++ and Unity](https://firebase.google.com/docs/firestore) - C++ and Unity SDKs for C++ and Unity (with Firebase Unity SDKs available via Unity Package Manager).

## Server-side (Cloud Functions, BigQuery etc)

- 📖 [Firebase Admin Documentation](https://firebase.google.com/docs/admin/setup) - Official Firebase Admin SDK Server Setup.
- 💡 [Functions Samples](https://github.com/firebase/functions-samples) - Collection of sample apps showcasing popular use cases using Cloud Functions for Firebase.
- 💡 [Express Server on Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/master/functions-express) - Host an Express server on Cloud Functions.
- 📝 [GraphQL Server on Cloud Functions](https://codeburst.io/graphql-server-on-cloud-functions-for-firebase-ae97441399c0) - Host an Express server with GraphQL middleware on Cloud Functions.
- 💡 [Compiled Code with Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/master/functions-w-parcel) - Compile your Flow, TypeScript or ReasonML to the correct Node runtime using Babel, TypeScript Compiler or ParcelJS.
- 📝 [BigQuery & Google Analytics](https://medium.com/firebase-developers/how-do-i-create-a-closed-funnel-in-google-analytics-for-firebase-using-bigquery-6eb2645917e1) - How Do I Create a Closed Funnel in Google Analytics for Firebase Using BigQuery.
- 📹 [Official Cloud Function #Firecasts](https://www.youtube.com/watch?v=2mjfI0FYP7Y&list=PLl-K7zZEsYLm9A9rcHb1IkyQUu6QwbjdM) - YouTube video series about understanding how Cloud Functions work.
- 📝 [Firebase Hosting for Cloud Run Services](https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html) - Dynamic content with Hosting Rewrites & Cloud Run Services.
- 📝 [Scheduled (Cron) Cloud Functions for Firebase](https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html) - Firebase-native Cron triggers for Firebase Cloud Functions.
- 🔌 [Integrify](https://github.com/anishkny/integrify) - Enforce referential and data integrity in Firestore using pre-canned Cloud Functions triggers.
- 🔌 [Free Product Analytics with Firebase + BigQuery + Rakam](https://rakam.io/blog/free-product-analytics-with-firebase---bigquery---rakam/) - How to do behavioral & segmentation analysis on Firebase event data via BigQuery Export and Rakam.

## CLI & Editor

- 🔧 [VSCode Firebase Explorer](https://github.com/jsayol/vscode-firebase-explorer) - Explore and manage your Firebase projects.
- 🔧 [Firebase Tools](https://github.com/firebase/firebase-tools) - The Firebase Command Line Tools.
- 🔧 [Firebase CI](https://github.com/prescottprue/firebase-ci) - Simplified Firebase interaction for continuous integration.
- 🔧 [VSFire](https://github.com/toba/vsfire) - VSCode extension for syntax highlighting & code completions with Firestore security rules & indexes.
- 🔧 [Firebase Firestore Snippets](https://github.com/peterhdd/firebase-firestore-snippets) - Contains the snippet for both Firebase and Firestore in VS Code editor.
- 🔧 [Fuego](https://github.com/sgarciac/fuego) - Firestore client CLI supporting document add/update/query with filtering and pagination.
- 🔧 [Firestore Rules Generator](https://github.com/FirebaseExtended/protobuf-rules-gen) - Official (but experimental) Firebase Rules Generator for Cloud Firestore based on Google's Protocol Buffer format.
- 🔧 [Firepit](https://github.com/abehaskins/firepit) - Firepit is a standalone, portable version of the Firebase CLI which has no depedencies (including Node.js).
- 🔧 [Fireward](https://github.com/bijoutrouvaille/fireward) - Easy to use language for Firestore rules, similar to Firebase Bolt.
- 🔧 [Svarog](https://github.com/dantothefuture/svarog) - Cloud Firestore schema validation with JSON Schema generated Security Rule helper functions.

## Other

- 🔌 [Firestore Query Browser](https://firestore-query-browser.firebaseapp.com) - WebApp to Query, (Batch-)Edit & Export documents with app & user switching.
- 🔌 [FireDrill](https://github.com/scottlepp/fire-drill) - Find, Edit, Add, Remove, Import, Export, and Report on your Firebase data.
- 💡 [Unity Solutions](https://github.com/FirebaseExtended/unity-solutions) - Use Firebase tools to incorporate common features into your games.
- 🔌 [Firebase AIR Native Extension](https://github.com/myflashlab/Firebase-ANE) - Firebase ANE collection give you access to the Google Firebase project in your AdobeAir projects supported on both Android and iOS with 100% identical ActionScript API.
- 🔌 [QtFirebase](https://github.com/Larpon/QtFirebase) - An effort to bring Google's Firebase C++ API to Qt + QML.
- 📝 [StackBlitz to Firebase Hosting Deployments](https://medium.com/@ericsimons/announcing-split-second-static-deploys-for-firebase-7440d8e84879) - StackBlitz (online code editor) to Firebase Hosting static deployments.
- 🔧 [Flamelink](https://flamelink.io/) - CMS for Firebase. Supports Firestore, RealtimeDatabase & Storage.
- 🔧 [Canner CMS](https://github.com/Canner/canner) - CMS for developers supporting data sources such as Firebase/Firestore, GraphQL and Restful APIs.
- 📹 [Firebase Summit 2018](https://www.youtube.com/watch?v=lN0VXVXsj9k&list=PLl-K7zZEsYLnqdlmz7iFe9Lb6cRU3Nv4R) - All Firebase Summit 2018 talks.
- 📹 [Firebase @ Google Cloud Next '18](https://www.youtube.com/watch?v=OPj26MY16F8&list=PLl-K7zZEsYLmYx3MkJRIUPH_JVFHLTlwL) - All Firebase talks @ Google Cloud Next 2018.
- 📹 [Firebase @ Google IO '18](https://www.youtube.com/watch?v=e-8fiv-vteQ&list=PLl-K7zZEsYLn1omgx_VUhCDFsQMA7PRDd) - All Firebase talks @ Google IO 2018.
- 📹 [#AskFirebase YouTube Playlist](https://www.youtube.com/watch?v=TSzhzR4wzSE&list=PLl-K7zZEsYLkkCFs6T9mlqG8v6NCs38pA) - Official #AskFirebase playlist on YouTube.
- 📝 [State of Firebase (mid 2019)](https://codeburst.io/the-state-of-firebase-mid-2019-2b002c458d70) - Cloud Next & Google I/O 2019 updates!
- 📹 [Firebase @ Google IO '19](https://www.youtube.com/playlist?list=PLl-K7zZEsYLlo2L4rfPds-fFLEtOWheoO) - All Firebase talks @ Google IO 2019.
- 📹 [Firebase Summit 2019](https://www.youtube.com/watch?v=YKZ6rP4kwV8&list=PLl-K7zZEsYLk2OolaVXVyYrFErctrZXSX) - All Firebase talks @ the Firebase Summit 2019.

<!-- END content -->

## Follow

### Official

📹 [Firebase YouTube](https://www.youtube.com/user/Firebase) 📝 [Firebase Blog](https://firebase.googleblog.com/) 🐦 [@firebase](https://twitter.com/firebase) 🐦 [@bestoffirebase](https://twitter.com/bestoffirebase) 👤 [Firebase Facebook](https://www.facebook.com/Firebase)

### Community

- 📹 [Fireship - AngularFirebase](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA)
- 📹 ru [@firebase_ru - Telegram friendly chat](https://t.me/firebase_ru)

Who else should we be following!?

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/jthegedus/awesome-firebase/graphs/contributors)!

## License

[CC0 License](license)
