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

- 📹 [Firebase @ Google IO '19][fb-io-19] - Все доклады Firebase @ Google IO 2019.
- 📝 [Scheduled (Cron) Cloud Functions for Firebase][cron-cloud-functions] - Firebase-native триггеры Cron для облачных функций Firebase.
- 🔌 [Integrify][integrify] - Обеспечение ссылочной целостности и целостности данных в Firestore с помощью предварительно настроенных триггеров Cloud Functions.
- 🔧 [VSCode Firebase Explorer][vscode-firebase-explorer] - Исследуйте и управляйте своими проектами Firebase.
- 🔌 [React Firebase Hooks][react-firebase-hooks] - React Hooks для сервисов Firebase.

## Официальная документация и быстрый старт

- 📖 [Firebase Documentation][fb-docs] - Официальная документация по Firebase.
- 🔧 [Firebase Status Dashboard][fb-status-dashboard] - Эта страница предоставляет информацию о состоянии сервисов, которые являются частью Firebase.
- 💡 [Firebase Quickstarts][fb-quickstarts] - Официальные примеры для быстрого старта с Firebase.
- 💡 [Google Codelabs | Firebase][google-codelabs] - Codelabs для разработчиков Google предоставляют практическое руководство по написанию кода.

## Веб

- 🔌 [Firebase UI][firebase-ui] - FirebaseUI - это библиотека JavaScript с открытым исходным кодом для Web, которая предоставляет простые связи пользовательского интерфейса поверх SDK Firebase для сокрытия стандартного кода и применения лучших практик.
- 🔌 [Firebase UI for React][fb-ui-react] - React обертка для firebaseUI Web.
- 🔌 [GeoFire for JavaScript][geofire] - Запросы местоположения в реальном времени с Firebase.
- 💡 [FirePad][firepad] - Многопользовательский текстовый редактор на Firebase.
- 🔌 [Ember Fire][ember-fire] - Официально поддерживаемый адаптер для использования Firebase с Ember.
- 🔌 [Firebase Dart][fb-dart] - Dart обертка для Firebase.
- 🔌 [PolymerFire][polymer-fire] - Polymer веб-компоненты для Firebase.
- 🔌 [VueFire][vue-fire] - Связывает Firebase и Vue.js.
- 🔌 [Angular Fire 2][ng-fire] - Официальная библиотека для Firebase и Angular.
- 🔌 [Re-base][rebase] - Библиотека вдохновленная Relay для создания React.js + Firebase приложений.
- 🔌 [React Redux Firebase][react-redux-fb] - Redux связи для Firebase. Содержит компонент высшего порядка для использования с React.
- 🔌 [GatsbyJS Firebase Data Source][gatsby-fire] - Получение ваших данных Firebase прямо на статически сгенерированные страницы с помощью Gatsby.
- 🔌 [Apollo Link Firebase][apollo-link-fb] - Предоставляет локальный интерфейс GraphQL для RealtimeDB. БД синхронизируется локально с устройством, Apollo Link обеспечивает запросы в локальную БД.
- 🔌 [BuckleScript Bindings for Firebase][bs-fb] - Привязки BuckleScript для Firebase для использования в проектах ReasonML.
- 💡 [Angular Firebase PWA][ng-firestarter] - Angular PWA работает на Firebase. Это может послужить основой для изучения этого стека и развертывания более сложных функций.
- 🔌 [FireSQL][firesql] - Запросы к Firestore с использованием синтаксиса SQL. Выдает минимальное количество запросов, необходимое для получения запрашиваемых вами данных.
- 📖 [Hosting Version History][hosting-version-hist] - Автоматическое удаление старых версий вашего сайта.
- 🔌 [Firestorter][firestorter] - Используйте Firestore в React с нулевым усилием, используя MobX (также для react-native).

## Для мобильных устройств

- 📖 [Firebase Flutter Documentation][fb-flutter] - Официальная документация Firebase Flutter.
- 🔌 [NativeScript plugin Firebase][fb-nativescript] - NativeScript плагин для Firebase.
- 🔌 [FlutterFire][fb-flutter-fire] - Используйте Firebase сервисы в своем кросс-платформенном [Flutter][flutter] приложении.
- 🔌 [React Native Firebase][rn-fb] - Проверенная многофункциональная модульная реализация Firebase для React Native. Поддерживает платформы iOS и Android.
- 🔌 [React Native Firebase Cloud Messaging][rn-fb-fcm] -
  Модуль React Native для Firebase Cloud Messaging и локальных уведомлений.
- 💡 [Expo Native Firebase][expo-fb] - Native Firebase Expo приложение (iOS, Android) демо для Firestore, Notifications, Analytics, Storage, Messaging, Database.
- 💡 [Flutter Calendar App][flutter-cal] -
  Новое приложение Flutter, реализующее простое мобильное приложение календаря для хранения основных событий в облачной базе данных Firebase.

### Android

- 🔌 [GeoFire for Java][geofire-java] - Запросы местоположения в реальном времени с Firebase.
- 🔌 [Firebase UI][fb-ui-android] - Оптимизированные UI компоненты для Firebase.
- 🔌 [FireXtensions][android-firextensions] - Неофициальные Kotlin расширения для Firebase Android SDK.

### iOS

- 🔌 [GeoFire for Objective-C][geofire-objc] - Запросы местоположения в реальном времени с Firebase.
- 🔌 [Firebase UI][fb-ui-ios] - iOS UI связи для Firebase.
- 💡 [MLKit - ARCore][mlkit-arcore] - Пример обнаружения объектов и обозначение их с помощью 3D-меток в дополненной реальности. Использует Firebase ML Kit, ARCore и Firebase RTDB.
- 💡 [MLKit - ARKit][mlkit-arkit] - Пример обнаружения объектов с помощью Firebase ML Kit и обозначение их 3D-метками в дополненной реальности.

## Серверная часть (Cloud Functions, BigQuery и т.д.)

- 📖 [Firebase Admin Documentation][fb-admin-docs] - Официальная документация Firebase Admin SDK.
- 💡 [Functions Samples][fb-func-samples] - Коллекция примеров приложений, демонстрирующих популярные варианты с использованием Cloud Functions для Firebase.
- 💡 [Express Server on Cloud Functions][fb-func-express] - Хостинг Express сервера на Cloud Functions.
- 📝 [GraphQL Server on Cloud Functions][fb-func-graphql] - Хостинг Express сервера с промежуточным слоем GraphQL на Cloud Functions.
- 💡 [Compiled Code with Cloud Functions][fb-func-compiled-code] - Скомпилируйте ваш Flow, TypeScript или ReasonML для среды выполнения Node, используя Babel, TypeScript Compiler или ParcelJS.
- 📝 [BigQuery & Google Analytics][bq-fb-analytics] - Как создать закрытую воронку в Google Analytics для Firebase с помощью BigQuery.
- 📹 [Official Cloud Function #Firecasts][fb-func-firecasts] - Серия видеороликов на YouTube о понимании работы облачных функций.
- 📝 [Firebase Hosting for Cloud Run Services][cloud-run-rewrites] - Динамический контент на основе особенностей Firebase Hosting (rewrites) и Cloud Run.

## Интерфейс комадной строки и редактор

- 🔧 [Firebase Tools][fb-tools] - Инструменты командной строки Firebase.
- 🔧 [Firebase CI][fb-ci] - Упрощенное взаимодействие с Firebase для непрерывной интеграции.
- 🔧 [VSFire][vsfire] - Расширение VSCode для подсветки синтаксиса и дополнений кода для правил безопасности и индексов Firestore.
- 🔧 [Firebase Firestore Snippets][fb-firestore-snippets] - Содержит фрагменты для Firebase и Firestore в редакторе VSCode.
- 🔧 [Fuego][fuego] - Клиентский интерфейс командной строки Firestore с возможностью добавить/обновить/выбрать записи с фильтрацией и разбиением на страницы.
- 🔧 [Firestore Rules Generator][firestore-rules-gen] - Официальный (но экспериментальный) генератор правил Firebase для Cloud Firestore основанный на формате Google's Protocol Buffer.
- 🔧 [Firepit][firepit] - Firepit - это автономная, портативная версия Firebase CLI, которая не имеет зависимостей (включая Node.js).
- 🔧 [Fireward][fireward] - Простой в использовании язык для правил Firestore, похожий на Firebase Bolt.

## Прочее

- 🔌 [FireDrill][fire-drill] - Находите, изменяте, добавляйте, удаляйте, импортируйте, экспортиртируйте и создавайте отчеты на основе данных Firebase.
- 💡 [Unity Solutions][unity-solns] - Используйте инструменты Firebase для включения общих функций в ваши игры.
- 🔌 [Firebase AIR Native Extension][fb-ane] - Коллекция Firebase ANE предоставляет вам доступ к проекту Google Firebase в ваших проектах AdobeAir, поддерживаемых как на Android, так и на iOS, со 100% идентичным ActionScript API.
- 🔌 [QtFirebase][qt-fb] - Попытка вывести Google Firebase C++ API на Qt+ QML.
- 📝 [StackBlitz to Firebase Hosting Deployments][fb-stackblitz] - StackBlitz (онлайн-редактор кода) для статического развертывания Firebase Hosting.
- 🔧 [Flamelink][flamelink] - CMS для Firebase. Поддерживает Firestore, RealtimeDatabase & Storage.
- 🔧 [Canner CMS][canner] - CMS для разработчиков, поддерживающих источники данных, такие как Firebase/Firestore, GraphQL и Restful API.
- 📹 [Firebase Summit 2018][fb-summit-18] - Все доклады Firebase Summit 2018.
- 📹 [Firebase @ Google Cloud Next '18][fb-next-18] - Все доклады Firebase @ Google Cloud Next 2018.
- 📹 [Firebase @ Google IO '18][fb-io-18] - Все доклады Firebase @ Google IO 2018.
- 📹 [#AskFirebase YouTube Playlist][fb-ask-fb] - Официальный плейлист #AskFirebase на YouTube.

<!-- END content -->

## Источники информации

### Официальные

📹 [Firebase YouTube][fb-yt] 📝 [Firebase блог][fb-blog] 🐦 [@firebase][fb-twitter] 🐦 [@bestoffirebase][bof-twitter]

### Сообщество

- 📹 [Fireship - AngularFirebase][angular-firebase]
- 📹 ru [@firebase_ru - русскоговорящее сообщество. Дружественный Telegram-чат][ru-telegram-chat]

За кем еще мы должны последовать!?

## Поддержка проекта

[Поддержка любого рода приветствуются, просто следуйте инструкциям](contributing.md)!

### Участники

[Спасибо этим участникам][contributors]!

## Лицензия

[CC0 License][license]

<!-- Links -->

[firebase]: https://firebase.google.com
[gcp-products]: https://cloud.google.com/products

<!-- Featured (new releases) -->

[cron-cloud-functions]: https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html
[integrify]: https://github.com/anishkny/integrify
[vscode-firebase-explorer]: https://github.com/jsayol/vscode-firebase-explorer
[react-firebase-hooks]: https://github.com/CSFrequency/react-firebase-hooks

<!-- Official Firebase Docs & Quickstarts -->

[fb-docs]: https://firebase.google.com/docs
[fb-status-dashboard]: https://status.firebase.google.com
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

[fb-admin-docs]: https://firebase.google.com/docs/admin/setup
[fb-func-samples]: https://github.com/firebase/functions-samples
[fb-func-express]: https://github.com/jthegedus/firebase-gcp-examples/tree/master/fb-functions-express
[fb-func-graphql]: https://codeburst.io/graphql-server-on-cloud-functions-for-firebase-ae97441399c0
[fb-func-compiled-code]: https://github.com/jthegedus/firebase-gcp-examples/tree/master/fb-functions-compiled_code
[bq-fb-analytics]: https://medium.com/firebase-developers/how-do-i-create-a-closed-funnel-in-google-analytics-for-firebase-using-bigquery-6eb2645917e1
[fb-func-firecasts]: https://www.youtube.com/watch?v=2mjfI0FYP7Y&list=PLl-K7zZEsYLm9A9rcHb1IkyQUu6QwbjdM
[cloud-run-rewrites]: https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html

<!-- CLI & Editor -->

[fb-tools]: https://github.com/firebase/firebase-tools
[fb-ci]: https://github.com/prescottprue/firebase-ci
[vsfire]: https://github.com/toba/vsfire
[fb-firestore-snippets]: https://github.com/peterhdd/firebase-firestore-snippets
[fuego]: https://github.com/sgarciac/fuego
[firestore-rules-gen]: https://github.com/FirebaseExtended/protobuf-rules-gen
[firepit]: https://github.com/abehaskins/firepit
[fireward]: https://github.com/bijoutrouvaille/fireward

<!-- Other -->

[fire-drill]: https://github.com/scottlepp/fire-drill
[unity-solns]: https://github.com/FirebaseExtended/unity-solutions
[fb-ane]: https://github.com/myflashlab/Firebase-ANE
[qt-fb]: https://github.com/Larpon/QtFirebase
[fb-stackblitz]: https://medium.com/@ericsimons/announcing-split-second-static-deploys-for-firebase-7440d8e84879
[flamelink]: https://flamelink.io/
[canner]: https://github.com/Canner/canner
[fb-summit-18]: https://www.youtube.com/watch?v=lN0VXVXsj9k&list=PLl-K7zZEsYLnqdlmz7iFe9Lb6cRU3Nv4R
[fb-next-18]: https://www.youtube.com/watch?v=OPj26MY16F8&list=PLl-K7zZEsYLmYx3MkJRIUPH_JVFHLTlwL
[fb-io-18]: https://www.youtube.com/watch?v=e-8fiv-vteQ&list=PLl-K7zZEsYLn1omgx_VUhCDFsQMA7PRDd
[fb-io-19]: https://www.youtube.com/playlist?list=PLl-K7zZEsYLlo2L4rfPds-fFLEtOWheoO
[fb-ask-fb]: https://www.youtube.com/watch?v=TSzhzR4wzSE&list=PLl-K7zZEsYLkkCFs6T9mlqG8v6NCs38pA

<!-- Follow -->

[fb-yt]: https://www.youtube.com/user/Firebase
[fb-blog]: https://firebase.googleblog.com/
[fb-twitter]: https://twitter.com/firebase
[bof-twitter]: https://twitter.com/bestoffirebase
[angular-firebase]: https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA
[ru-telegram-chat]: https://t.me/firebase_ru

<!-- Contributors -->

[contributors]: https://github.com/jthegedus/awesome-firebase/graphs/contributors

<!-- License -->

[license]: https://github.com/jthegedus/awesome-firebase/blob/master/LICENSE
