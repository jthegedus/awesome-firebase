<!-- badges -->
<div align="center">

<!-- title -->

# Awesome Firebase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- subtitle -->

Самый актуальный список документов, докладов, инструментов, примеров &amp; статей о [Firebase][firebase], которые может предложить Интернет.

<!-- image -->

<a href="https://firebase.google.com/docs/" target="_blank" rel="noopener noreferrer">
  <img src="images/firebase-services.gif" />
</a>

<!-- translations -->
переводы: [🇬🇧 en](README.md) · [🇷🇺 ru](README_RU.md) <!-- · [🇪🇸 es](README_ES.md) · [🇮🇩 id](README_ID.md) · [🇯🇵 ja](README_JA.md) · [🇰🇷 ko](README_KO.md) · [🇵🇹 pt](README_PT.md) · [🇨🇳 zh](README_ZH.md) -->

[Firebase][firebase] - это платформа для разработчиков приложений, основанная на [Google Cloud Platform][gcp-products], предоставляющая сервисы и кроссплатформенные SDK!

</div>

<!-- toc -->

## Содержание

- [Избранное (новые выпуски)](#избранное-новые-выпуски)
- [Официальная документация и быстрый старт](#официальная-документация-и-быстрый-старт)
- [Веб](#веб)
- [Для мобильных устройств](#для-мобильных-устройств)
- [Серверная часть (Cloud Functions, BigQuery и т.д.)](#серверная-часть-cloud-functions-bigquery-и-тд)
- [Интерфейс комадной строки и редактор](#Интерфейс-комадной-строки-и-редактор)
- [Прочее](#прочее)
- [Источники информации](#Источники-информации)

**Обозначения**: 📝 сообщения в блогах · 💡 примеры · 📖 документы · 🔌 библиотеки · 🔧 инструменты · 📹 беседы/видео 

<!-- START content -->

## Избранное (новые выпуски)

- 🔧 [Fireward][fireward] - Простой в использовании язык для правил Firestore, похожий на Firebase Bolt.
- 📝 [Scheduled (Cron) Cloud Functions for Firebase][cron-cloud-functions] - Firebase-native триггеры Cron для облачных функций Firebase.
- 🔌 [Integrify][new-2] - Обеспечение ссылочной целостности и целостности данных в Firestore с помощью предварительно настроенных триггеров Cloud Functions.
- 🔧 [VSCode Firebase Explorer][new-4] - Исследуйте и управляйте своими проектами Firebase.
- 🔌 [React Firebase Hooks][new-5] - React Hooks для сервисов Firebase.

## Официальная документация и быстрый старт

- 📖 [Firebase Documentation][docs-1] - Официальная документация по Firebase.
- 💡 [Firebase Quickstarts][docs-2] - Официальные примеры для быстрого старта с Firebase.

## Веб

- 🔌 [Firebase UI][web-1] - FirebaseUI - это библиотека JavaScript с открытым исходным кодом для Web, которая предоставляет простые связи пользовательского интерфейса поверх SDK Firebase для сокрытия стандартного кода и применения лучших практик.
- 🔌 [Firebase UI for React][web-2] - React обертка для firebaseUI Web.
- 🔌 [GeoFire for JavaScript][web-3] - Запросы местоположения в реальном времени с Firebase.
- 💡 [FirePad][web-4] - Многопользовательский текстовый редактор на Firebase.
- 🔌 [Ember Fire][web-5] - Официально поддерживаемый адаптер для использования Firebase с Ember.
- 🔌 [Firebase Dart][web-6] - Dart обертка для Firebase.
- 🔌 [PolymerFire][web-7] - Polymer веб-компоненты для Firebase.
- 🔌 [VueFire][web-8] - Связывает Firebase и Vue.js.
- 🔌 [Angular Fire 2][web-9] - Официальная библиотека для Firebase и Angular.
- 🔌 [Re-base][web-10] - Библиотека вдохновленная Relay для создания React.js + Firebase приложений.
- 🔌 [React Redux Firebase][web-11] - Redux связи для Firebase. Содержит компонент высшего порядка для использования с React.
- 🔌 [GatsbyJS Firebase Data Source][web-12] - Получение ваших данных Firebase прямо на статически сгенерированные страницы с помощью Gatsby.
- 🔌 [Apollo Link Firebase][web-13] - Предоставляет локальный интерфейс GraphQL для RealtimeDB. БД синхронизируется локально с устройством, Apollo Link обеспечивает запросы в локальную БД.
- 🔌 [BuckleScript Bindings for Firebase][web-14] - Привязки BuckleScript для Firebase для использования в проектах ReasonML.
- 💡 [Angular Firebase PWA][web-15] - Angular PWA работает на Firebase. Это может послужить основой для изучения этого стека и развертывания более сложных функций.
- 🔌 [FireSQL][web-16] - Запросы к Firestore с использованием синтаксиса SQL. Выдает минимальное количество запросов, необходимое для получения запрашиваемых вами данных.
- 📖 [Hosting Version History][hosting-version-hist] - Автоматическое удаление старых версий вашего сайта.
- 🔌 [Firestorter][firestorter] - Используйте Firestore в React с нулевым усилием, используя MobX (также для react-native).

## Для мобильных устройств

- 📖 [Firebase Flutter Documentation][mobile-1] - Официальная документация Firebase Flutter.
- 🔌 [NativeScript plugin Firebase][mobile-2] - NativeScript плагин для Firebase.
- 🔌 [FlutterFire][mobile-3] - Используйте Firebase сервисы в своем кросс-платформенном [Flutter][mobile-3-flutter] приложении.
- 🔌 [React Native Firebase][mobile-4] - Проверенная многофункциональная модульная реализация Firebase для React Native. Поддерживает платформы iOS и Android.
- 🔌 [React Native Firebase Cloud Messaging][mobile-5] -
  Модуль React Native для Firebase Cloud Messaging и локальных уведомлений.
- 💡 [Expo Native Firebase][mobile-6] - Native Firebase Expo приложение (iOS, Android) демо для Firestore, Notifications, Analytics, Storage, Messaging, Database.
- 💡 [Flutter Calendar App][mobile-7] -
  Новое приложение Flutter, реализующее простое мобильное приложение календаря для хранения основных событий в облачной базе данных Firebase.

### Android

- 🔌 [GeoFire for Java][android-1] - Запросы местоположения в реальном времени с Firebase.
- 🔌 [Firebase UI][android-2] - Оптимизированные UI компоненты для Firebase.
- 🔌 [FireXtensions][android-3] - Неофициальные Kotlin расширения для Firebase Android SDK.

### iOS

- 🔌 [GeoFire for Objective-C][ios-1] - Запросы местоположения в реальном времени с Firebase.
- 🔌 [Firebase UI][ios-2] - iOS UI связи для Firebase.
- 💡 [MLKit - ARCore][ios-3] - Пример обнаружения объектов и обозначение их с помощью 3D-меток в дополненной реальности. Использует Firebase ML Kit, ARCore и Firebase RTDB.
- 💡 [MLKit - ARKit][ios-4] - Пример обнаружения объектов с помощью Firebase ML Kit и обозначение их 3D-метками в дополненной реальности.

## Серверная часть (Cloud Functions, BigQuery и т.д.)

- 📖 [Firebase Admin Documentation][server-1] - Официальная документация Firebase Admin SDK.
- 💡 [Functions Samples][server-2] - Коллекция примеров приложений, демонстрирующих популярные варианты с использованием Cloud Functions для Firebase.
- 💡 [Express Server on Cloud Functions][server-3] - Хостинг Express сервера на Cloud Functions.
- 📝 [GraphQL Server on Cloud Functions][server-4] - Хостинг Express сервера с промежуточным слоем GraphQL на Cloud Functions.
- 💡 [Compiled Code with Cloud Functions][server-5] - Скомпилируйте ваш Flow, TypeScript или ReasonML для среды выполнения Node, используя Babel, TypeScript Compiler или ParcelJS.
- 📝 [BigQuery & Google Analytics][server-6] - Как создать закрытую воронку в Google Analytics для Firebase с помощью BigQuery.
- 📹 [Official Cloud Function #Firecasts][server-7] - Серия видеороликов на YouTube о понимании работы облачных функций.
- 📝 [Firebase Hosting for Cloud Run Services][cloud-run-rewrites] - Динамический контент на основе особенностей Firebase Hosting (rewrites) и Cloud Run.

## Интерфейс комадной строки и редактор

- 🔧 [Firebase Tools][cli-editor-1] - Инструменты командной строки Firebase.
- 🔧 [Firebase CI][cli-editor-2] - Упрощенное взаимодействие с Firebase для непрерывной интеграции.
- 🔧 [VSFire][cli-editor-3] - Расширение VSCode для подсветки синтаксиса и дополнений кода для правил безопасности и индексов Firestore.
- 🔧 [Firebase Firestore Snippets][cli-editor-4] - Содержит фрагменты для Firebase и Firestore в редакторе VSCode.
- 🔧 [Fuego][cli-editor-5] - Клиентский интерфейс командной строки Firestore с возможностью добавить/обновить/выбрать записи с фильтрацией и разбиением на страницы.
- 🔧 [Firestore Rules Generator][cli-editor-6] - Официальный (но экспериментальный) генератор правил Firebase для Cloud Firestore основанный на формате Google's Protocol Buffer.
- 🔧 [Firepit][firepit] - Firepit - это автономная, портативная версия Firebase CLI, которая не имеет зависимостей (включая Node.js).

## Прочее

- 🔌 [FireDrill][other-1] - Находите, изменяте, добавляйте, удаляйте, импортируйте, экспортиртируйте и создавайте отчеты на основе данных Firebase.
- 💡 [Unity Solutions][other-2] - Используйте инструменты Firebase для включения общих функций в ваши игры.
- 🔌 [Firebase AIR Native Extension][other-3] - Коллекция Firebase ANE предоставляет вам доступ к проекту Google Firebase в ваших проектах AdobeAir, поддерживаемых как на Android, так и на iOS, со 100% идентичным ActionScript API.
- 🔌 [QtFirebase][other-4] - Попытка вывести Google Firebase C++ API на Qt+ QML.
- 📝 [StackBlitz to Firebase Hosting Deployments][other-5] - StackBlitz (онлайн-редактор кода) для статического развертывания Firebase Hosting.
- 🔧 [Flamelink][other-6] - CMS для Firebase. Поддерживает Firestore, RealtimeDatabase & Storage.
- 🔧 [Canner CMS][other-7] - CMS для разработчиков, поддерживающих источники данных, такие как Firebase/Firestore, GraphQL и Restful API.
- 📹 [Firebase Summit 2018][other-8] - Все доклады Firebase Summit 2018.
- 📹 [Firebase @ Google Cloud Next '18][other-9] - Все доклады Firebase @ Google Cloud Next 2018.
- 📹 [Firebase @ Google IO '18][other-10] - Все доклады Firebase @ Google IO 2018.
- 📹 [#AskFirebase YouTube Playlist][other-11] - Официальный плейлист #AskFirebase на YouTube.

<!-- END content -->

## Источники информации

### Официальные

📹 [Firebase YouTube][official-1] 📝 [Firebase блог][official-2] 🐦 [@firebase][official-3] 🐦 [@bestoffirebase][official-4]

### Сообщество

- 📹 [Fireship - AngularFirebase][angular-firebase]
- 📹 ru [@firebase_ru - Telegram friendly chat][ru-telegram-chat]

За кем еще мы должны последовать!?

## Поддержка проекта

[Поддержка любого рода приветствуются, просто следуйте инструкциям](contributing.md)!

### Участники

[Спасибо этим участникам][contributors]!

## License

[CC0 License][license]

<!-- Links -->

[firebase]: https://firebase.google.com
[gcp-products]: https://cloud.google.com/products

<!-- Featured (new releases) -->

[cron-cloud-functions]: https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html
[cloud-run-rewrites]: https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html
[new-2]: https://github.com/anishkny/integrify
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
[firestorter]: https://github.com/IjzerenHein/firestorter
[hosting-version-hist]: https://firebase.google.com/docs/hosting/deploying#set_limit_for_retained_versions

<!-- Mobile -->

[mobile-1]: https://firebase.google.com/docs/flutter/setup
[mobile-2]: https://github.com/EddyVerbruggen/nativescript-plugin-firebase
[mobile-3]: https://github.com/flutter/plugins/blob/master/FlutterFire.md
[mobile-3-flutter]: https://flutter.io/
[mobile-4]: https://github.com/invertase/react-native-firebase
[mobile-5]: https://github.com/evollu/react-native-fcm
[mobile-6]: https://github.com/EvanBacon/expo-native-firebase
[mobile-7]: https://github.com/mattgraham1/FlutterCalendar

<!-- Mobile: Android -->

[android-1]: https://github.com/firebase/geofire-java
[android-2]: https://github.com/firebase/firebaseui-android
[android-3]: https://github.com/rosariopfernandes/firextensions

<!-- Movile: iOS -->

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
