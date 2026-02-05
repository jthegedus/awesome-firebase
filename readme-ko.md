<!--lint disable awesome-toc-->
<!-- badges -->
<div align="center">

<!-- title -->
<!--lint ignore no-dead-urls-->
# Awesome Firebase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Lint Awesome List](https://github.com/jthegedus/awesome-firebase/workflows/lint/badge.svg)

<!-- subtitle -->

인터넷에서 제공하는 가장 **최신** 목록의 Firebase 관련 문서, 강연, 도구, 예제와 기사들 입니다.

<!-- image -->

<a href="https://firebase.google.com/docs/" target="_blank" rel="noopener noreferrer">
  <img src="images/firebase-services.gif" />
</a>

<!-- translations -->

번역: [🇬🇧 en](readme.md) · [🇷🇺 ru](readme-ru.md) · [🇰🇷 ko](readme-ko.md) <!-- · [🇪🇸 es](readme-es.md) · [🇮🇩 id](readme-id.md) · [🇯🇵 ja](readme-ja.md) · [🇵🇹 pt](readme-pt.md) · [🇨🇳 zh](readme-zh.md) -->

[Firebase](https://firebase.google.com)는 [Google Cloud Platform](https://cloud.google.com/products) 에서 제공하는 앱 개발 플랫폼으로, 서비스와 크로스 플랫폼 SDK를 제공합니다.
</div>

<!-- toc -->
<!--lint disable awesome-list-item-->
## 목차

- [특집 (신간)](#featured-new-releases)
- [공식 문서 & 빠른 시작](#official-docs--quickstarts)
- [Firebase 확장 프로그램](#firebase-extensions)
- [웹](#web)
- [모바일](#mobile)
- [게임](#games)
- [서버 사이드 (Cloud Functions, BigQuery 등)](#server-side-cloud-functions-bigquery-etc)
- [CLI & 에디터](#cli--editor)
- [기타](#other)
- [팔로우](#follow)
<!--lint enable awesome-list-item-->

**범례**: 📝 블로그 포스트 · 💡 예제 · 📖 문서 · 🔌 라이브러리 · 🔧 도구 · 📹 강연/비디오 · 🔊 팟캐스트

<!-- START content -->

## 특집 (신간)

- 🔌 [GeoFirestore](https://github.com/MichaelSolati/geofirestore-js) - Firebase Firestore를 사용한 위치 기반 쿼리 및 필터링 라이브러리입니다.
- 📹 [Firebase Summit 2020](https://goo.gle/firebasesummit2020) - Firebase 기술 강연 @ the Firebase Summit 2020.
- 🔊 [The Firebase Podcast](https://podcasts.google.com/feed/aHR0cDovL2ZpcmViYXNlcG9kY2FzdC5nb29nbGVkZXZlbG9wZXJzLmxpYnN5bnByby5jb20vcnNz) - Firebase 제품에 대해 깊게 탐구하고, 그 과정에서 새로운 팁과 요령을 배울 수 있는 곳입니다.
- 🔌 [Pyrebase](https://github.com/thisbejim/Pyrebase) - Firebase API를 위한 심플한 Python 래퍼 라이브러리입니다.
- 🔧 [asdf-firebase](https://github.com/jthegedus/asdf-firebase) - `firebase-tools`를 위한 [asdf-vm](https://asdf-vm.com/) 플러그인입니다. 당신의 Firebase CLI를 Node.js나 `npm` 없이 관리해보세요! `python`, `golang`, `c++` & `java`로 이루어진 Firebase 프로젝트에 적합합니다.

## 공식 문서 & 빠른 시작

- 📖 [Firebase Documentation](https://firebase.google.com/docs) - 공식 Firebase 문서입니다.
- 🔧 [Firebase Status Dashboard](https://status.firebase.google.com) - Firebase의 일부 서비스에 대한 상태 정보를 제공합니다.
- 💡 [Firebase Quickstarts](https://github.com/firebase?utf8=%E2%9C%93&q=quickstart&type=&language=) - Firebase의 빠른 시작 예제를 배울 수 있는 공식 GitHub입니다. 
- 💡 [Google Codelabs | Firebase](https://codelabs.developers.google.com/?cat=Firebase) - Google Developers Codelabs는 가이드가 있는 튜토리얼과 실습 코딩 경험을 제공합니다.
- 📖 [Firebase for Games](https://firebase.google.com/games) - 게임 개발자를 위한 Firebase/Google 리소스에 대한 링크가 포함된, 게임 개발을 위한 Firebase 랜딩 페이지입니다.

## Firebase 확장 프로그램

- 🔧 [Firebase Extensions](https://firebase.google.com/products/extensions) - Firebase 확장 프로그램은 개발자가 코드를 분석하고, 작성 또는 디버그할 필요 없이 앱에 확장된 기능을 제공합니다.
- 🔧 [Stripe Firebase Extensions](https://github.com/stripe/stripe-firebase-extensions/) - 공식 Stripe 확장 프로그램으로, 구독과 인보이스 기능을 제공합니다.

## 웹

- 🔌 [Firestore Lite](https://github.com/samuelgozi/firebase-firestore-lite) - 브라우저를 위한 경량 Cloud Firestore 라이브러리 입니다.
- 🔌 [SvelteFire](https://github.com/codediodeio/sveltefire) - Svelte를 위한 Firebase 라이브러리입니다. (Svelte 태그라인 : Cybernetically enhanced Firebase apps.)
- 🔌 [React Fire](https://github.com/FirebaseExtended/reactfire) - Firebase와 쉽게 상호 작용할 수 있는 Hooks, Context Provider 및 Components를 갖춘 공식 Firebase React 라이브러리입니다.
- 🔧 [Remote Styles with Remote Config](https://github.com/firebaseextended/remote-styles/) - Firebase Remote Config에 저장된 CSS를 동적/조건부로 불러올 수 있는 라이브러리입니다. ([포스트 이동](https://medium.com/firebase-developers/introducing-remote-styles-conditional-css-loading-made-easy-daddbbcce050)).
- 🔌 [React Firebase Hooks](https://github.com/CSFrequency/react-firebase-hooks) - Firebase 서비스를 위한 React Hooks 라이브러리입니다.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-web) - FirebaseUI는 웹용 오픈 소스 JavaScript 라이브러리로서, Firebase SDK 위에 간단한 사용자 지정 가능한 UI 바인딩을 제공하여 보일러 플레이트 코드를 제거하고 모범 사례를 홍보합니다.
- 🔌 [Firebase UI for React](https://github.com/firebase/firebaseui-web-react) - firebaseUI Web을 위한 React 래퍼 라이브러리입니다.
- 🔌 [GeoFire for JavaScript](https://github.com/firebase/geofire-js) - Firebase를 사용한 실시간 위치 쿼리 라이브러리입니다.
- 💡 [FirePad](https://github.com/FirebaseExtended/firepad) - Firebase를 기반으로 한 공동 작업 텍스트 에디터입니다.
- 🔌 [Ember Fire](https://github.com/firebase/emberFire) - Firebase를 위한 공식 Ember data 어댑터입니다.
- 🔌 [Firebase Dart](https://github.com/FirebaseExtended/firebase-dart) - 파이어 베이스를 위한 Dart 래퍼 라이브러리입니다.
- 🔌 [PolymerFire](https://github.com/FirebaseExtended/polymerfire) - 파이어 베이스를 위한 Polymer 웹 컴포넌트입니다.
- 🔌 [VueFire](https://github.com/vuejs/vuefire) - Vue.js를 위한 Firebase 바인딩 라이브러리입니다.
- 🔌 [Angular Fire 2](https://github.com/angular/angularfire2) - Angular를 위한 공식 Firebase 라이브러리입니다.
- 🔌 [Re-base](https://github.com/tylermcginnis/re-base) - Relay에서 영감을 받아 만들어진 React.js + Firebase 애플리케이션 번들링 라이브러리입니다.
- 🔌 [React Redux Firebase](https://github.com/prescottprue/react-redux-firebase) - Firebase를 위한 Redux 바인딩 라이브러리입니다. React와 함께 사용하기위한 Higher Order Component (HOC)를 제공합니다.
- 🔌 [GatsbyJS Firebase Data Source](https://www.gatsbyjs.org/packages/) - Gatsby를 이용해서 만들어진 정적 페이지에 Firebase 데이터를 쿼리할 수 있게 해주는 라이브러리입니다.
- 🔌 [Apollo Link Firebase](https://github.com/Canner/apollo-link-firebase) - RealtimeDB에 로컬 GraphQL 인터페이스를 제공합니다. DB는 장치에 로컬로 동기화되고 Apollo Link는 로컬 DB에 대한 쿼리를 제공합니다.
- 🔌 [BuckleScript Bindings for Firebase](https://github.com/avohq/bs-firebase) - ReasonML 프로젝트에서 사용하기위한 Firebase 용 BuckleScript 바인딩 라이브러리입니다.
- 💡 [Angular Firebase PWA](https://github.com/codediodeio/angular-firestarter) - Firebase에서 제공하는 Angular PWA입니다. 스택을 학습하고 보다 복잡한 기능을 롤아웃할 수 있는 기반이 될 수 있습니다.
- 🔌 [FireSQL](https://github.com/jsayol/FireSQL) - Firestore에 SQL 구문으로 쿼리를 요청 해보세요. 요청한 데이터를 가져 오는 데 최소한의 쿼리로 실행하는 똑똑한 라이브러리입니다.
- 📖 [Hosting Version History](https://firebase.google.com/docs/hosting/deploying#set_limit_for_retained_versions) - 사이트 배포의 이전 버전을 자동으로 삭제해주는 라이브러리입니다.
- 🔌 [Firestorter](https://github.com/IjzerenHein/firestorter) - 사이드 이펙트 없이 MobX를 이용하여 React에서 Firestore를 사용할 수 있는 라이브러립니다. (react-native에도 사용가능)
- 💡 [Nextbase](https://github.com/martyan/nextbase) - 프로젝트를 빠르게 시작하기 원하는 개발자를 위한 Next.js, Redux 및 Firebase 구성의 보일러 플레이트입니다.
- 🔧 [Typesaurus](https://github.com/kossnocorp/typesaurus) - Firestore에 타입 세이프를 위한 TypeScript 최초 라이브러리입니다.
- 🔌 [firebase-kotlin-sdk](https://github.com/GitLiveApp/firebase-kotlin-sdk/) - 멀티 플랫폼 프로젝트를 지원하는 Firebase용 Kotlin 최초 SDK입니다. (`ios`, `android` & `js` 지원)

## 모바일

- 📖 [Firebase Flutter Documentation](https://firebase.google.com/docs/flutter/setup) - 공식 Firebase Flutter 설치 문서입니다.
- 🔌 [NativeScript plugin Firebase](https://github.com/EddyVerbruggen/nativescript-plugin-firebase) - Firebase를 위한 NativeScript 플러그인입니다.
- 🔌 [FlutterFire](https://github.com/FirebaseExtended/flutterfire) - [Flutter](https://flutter.io/) 앱을 위한 Firebase 플러그인 모음입니다.
- 🔌 [React Native Firebase](https://github.com/invertase/react-native-firebase) - React Native를 위한 검증 된 모듈 식 Firebase 구현체입니다. iOS 및 Android 플랫폼을 모두 지원합니다.
- 🔌 [React Native Firebase Cloud Messaging](https://github.com/evollu/react-native-fcm) -
  Firebase 클라우드 메시징 및 로컬 알림을 위한 React Native 모듈입니다.
- 💡 [Expo Native Firebase](https://github.com/EvanBacon/expo-native-firebase) - Firestore, Notifications, Analytics, Storage, Messaging, Database 데모를 위한 네이티브 Firebase Expo 앱 입니다. (iOS, Android)
- 💡 [Flutter Calendar App](https://github.com/mattgraham1/FlutterCalendar) -
  간단한 이벤트를 Firebase 클라우드 데이터 베이스에 저장하기 위한 Flutter로 만들어진 간단한 캘린더 앱 입니다.
- 🔧 [Firebase App Distribution](https://firebase.google.com/products/app-distribution/) - 앱의 출시 전 버전을 신뢰할 수 있는 테스터에게 배포할 수 있습니다.
- 🔌 [Flamingo](https://github.com/hukusuke1007/flamingo) - Dart를 위한 Firebase Firestore 모델 프레임 워크입니다.

### Android

- 🔌 [GeoFire for Java](https://github.com/firebase/geofire-java) - Firebase를 사용한 실시간 위치 쿼리 라이브러리입니다.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-android) - Firebase에 최적화 된 UI 구성 요소 라이브러리입니다.
- 🔌 [FireXtensions](https://github.com/rosariopfernandes/firextensions) - Firebase Android SDK를 위한 비공식 Kotlin 확장 프로그램입니다.
- 🔌 [Firecoil](https://github.com/rosariopfernandes/firecoil) - 이미지 로딩 라이브러리 Coil을 사용하여 Android 앱의 GCS에서 이미지를 로드할 수 있는 라이브러리입니다.
- 🔌 [FireFlow](https://github.com/Zhigaras/FireFlow) - 타입 안전성을 보장하고 코루틴 기반으로 작동하는 Firebase Realtime Database용 래퍼로, Kotlin Flow를 기본적으로 지원합니다.

### iOS

- 🔌 [GeoFire for Objective-C](https://github.com/firebase/geofire-objc) - Firebase를 사용한 실시간 위치 쿼리 라이브러리입니다.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-ios) - Firebase를 위한 iOS UI 바인딩 라이브러리입니다.
- 💡 [MLKit - ARCore](https://github.com/FirebaseExtended/MLKit-ARCore) - 증강 현실에서 물체를 감지하고 3D 레이블로 태그를 지정하는 예제 입니다. Firebase ML Kit, ARCore 및 Firebase RTDB를 사용합니다.
- 💡 [MLKit - ARKit](https://github.com/FirebaseExtended/MLKit-ARKit) - Firebase ML Kit를 사용하여 객체를 감지하고 증강 현실에서 3D 라벨로 태그를 지정하는 예제 입니다.

## 게임

- 📖 [Firestore for C++ and Unity](https://firebase.google.com/docs/firestore) - C++와 Unity를 위한 C++와 Unity SDK입니다. (Unity 패키지 관리자를 통해 제공되는 Firebase Unity SDK)

## 서버 사이드 (Cloud Functions, BigQuery 등)

- 📖 [Firebase Admin Documentation](https://firebase.google.com/docs/admin/setup) - 서버 설정을 위한 공식 Firebase Admin SDK입니다.
- 💡 [Functions Samples](https://github.com/firebase/functions-samples) - Firebase 용 Cloud Functions를 사용하는 인기 사용 예제를 보여주는 샘플 앱 모음입니다.
- 💡 [Express Server on Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/main/functions-express) - Cloud Functions에서 Express 서버를 호스팅합니다.
- 📝 [GraphQL Server on Cloud Functions](https://codeburst.io/graphql-server-on-cloud-functions-for-firebase-ae97441399c0) - Cloud Functions에서 GraphQL 미들웨어로 Express 서버를 호스팅합니다.
- 💡 [Compiled Code with Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/main/functions-w-parcel) - Babel, TypeScript Compiler 또는 ParcelJS를 사용하여 Flow, TypeScript 또는 ReasonML을 올바른 노드 런타임으로 컴파일합니다.
- 📝 [BigQuery & Google Analytics](https://medium.com/firebase-developers/how-do-i-create-a-closed-funnel-in-google-analytics-for-firebase-using-bigquery-6eb2645917e1) - Firebase BigQuery를 사용하여 Google 애널리틱스에서 폐쇄형 유입 경로를 만들려면 어떻게 해야 합니까?
<!--lint ignore double-link-->
- 📹 [Official Cloud Function #Firecasts](https://www.youtube.com/watch?v=2mjfI0FYP7Y&list=PLl-K7zZEsYLm9A9rcHb1IkyQUu6QwbjdM) - Cloud Functions의 작동 방식 이해에 관한 YouTube 동영상 시리즈입니다.
- 📝 [Firebase Hosting for Cloud Run Services](https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html) - Hosting Rewrites & Cloud Run Services를 통한 동적 콘텐츠를 생성하는 방법을 소개합니다.
- 📝 [Scheduled (Cron) Cloud Functions for Firebase](https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html) - Firebase Cloud Functions 용 Firebase 네이티브 크론(Cron) 트리거입니다.
- 🔌 [Integrify](https://github.com/anishkny/integrify) - 미리 준비된 Cloud Functions 트리거를 사용하여 Firestore에서 참조 및 데이터 무결성을 시행합니다.
- 🔌 [Free Product Analytics with Firebase + BigQuery + Rakam](https://rakam.io/blog/free-product-analytics-with-firebase---bigquery---rakam/) - BigQuery Export 및 Rakam을 통해 Firebase 이벤트 데이터에 대한 행동 및 세분화 분석을 수행하는 방법을 소개합니다.
- 🔌 [Firestore Queue System](https://github.com/sbarbat/firestore-queuer) - Firestore 및 Cloud Functions를 이용한 간단한 대기열 시스템입니다.

## CLI & 에디터

- 📖 [Firebase Tools UI](https://github.com/firebase/firebase-tools-ui) - Firebase Emulator Suite 용 웹 UI입니다.
- 🔧 [VSCode Firebase Explorer](https://github.com/jsayol/vscode-firebase-explorer) - 당신의 Firebase 프로젝트를 vscode를 통해 탐색하고 관리하세요.
- 🔧 [Firebase Tools](https://github.com/firebase/firebase-tools) - Firebase 용 커맨드 라인 도구입니다.
- 🔧 [Firebase CI](https://github.com/prescottprue/firebase-ci) - Firebase의 지속적인 통합(CI)을 위한 간단한 firebase-ci 플랫폼 입니다.
- 🔧 [Firecode](https://github.com/ChFlick/firecode) -  VS Code를 위한 Firestore 규칙 확장입니다.
- 🔧 [Firebase Firestore Snippets](https://github.com/peterhdd/firebase-firestore-snippets) - VS Code 편집기에 Firebase 및 Firestore의 대한 모든 snippet을 제공합니다.
- 🔧 [Fuego](https://github.com/sgarciac/fuego) - Firestore client CLI로 문서 필터링, 페이지네이션과 add/update/query를 지원합니다.
- 🔧 [Firestore Rules Generator](https://github.com/FirebaseExtended/protobuf-rules-gen) - Google의 프로토콜 버퍼 형식을 기반으로하는 Cloud Firestore 용 공식 (실험적) Firebase 룰 생성기입니다.
- 🔧 [Firepit](https://github.com/abehaskins/firepit) - Firepit은 독립적 포터블 버전의 Firebase CLI로 Node.js 포함하여 어떠한 다른 종속 설치도 필요없습니다.
- 🔧 [Fireward](https://github.com/bijoutrouvaille/fireward) - Firebase Bolt와 유사한 Firestore 룰에 사용하기 쉬운 언어입니다.
- 🔧 [Svarog](https://github.com/dantothefuture/svarog) - JSON 스키마 생성 보안 규칙 도우미 함수를 사용한 Cloud Firestore 스키마 유효성 검사 라이브러리입니다.
- 🔧 [Firetable](https://github.com/AntlerVC/firetable) - Firebase/Firestore에 Excel/Google Sheets와 유사한 관리 UI를 제공합니다. 더이상 관리 포털이 필요없습니다!
- 🔧 [VSFire](https://github.com/toba/vsfire) - 앞으로 사용하지 않음 ~Firestore 보안 규칙 및 인덱스의 구문 강조 및 코드 완성을 위한 VSCode 확장 프로그램입니다.~
- 📝 [Refi App](https://refiapp.io/) - Firestore DB와 상호 작용할 때 개발자의 고통을 덜어주는 GUI 도구입니다.
- 🔧 [Firefoo](https://firefoo.app) - JSON / CSV 내보내기 및 자바 스크립트 쿼리 쉘을 제공하는 Cloud Firestore GUI 관리 도구입니다.

## 기타

- 🔧 [Flank](https://github.com/flank/flank/) - Firebase Test Lab을 위한 Android 및 iOS 용 대규모 병렬 테스트 실행기입니다.
- 🔌 [Firestore Query Browser](https://firestore-query-browser.firebaseapp.com) - 앱과 유저를 변경하며 쿼리와 문서 (일괄-)편집 & 내보내기를 할 수 있는 웹 앱입니다.
- 🔌 [FireDrill](https://github.com/scottlepp/fire-drill) - 당신의 Firebase 데이터를 찾기, 편집, 추가, 제거, 가져오기, 내보내기 및 보고를 할 수 있습니다.
- 💡 [Unity Solutions](https://github.com/FirebaseExtended/unity-solutions) - Firebase 도구를 사용하여 일반적인 기능을 게임에 통합할 수 있습니다.
- 🔌 [Firebase AIR Native Extension](https://github.com/myflashlab/Firebase-ANE) - Firebase ANE 컬렉션을 사용하면 100 % 동일한 ActionScript API를 사용하여 Android와 iOS 모두에서 지원되는 AdobeAir 프로젝트의 Google Firebase 프로젝트에 액세스 할 수 있습니다.
- 🔌 [QtFirebase](https://github.com/Larpon/QtFirebase) - Google의 Firebase C++ API를 Qt + QML로 전환하기 위한 노력으로 만들어진 라이브러리입니다.
- 📝 [StackBlitz to Firebase Hosting Deployments](https://medium.com/@ericsimons/announcing-split-second-static-deploys-for-firebase-7440d8e84879) - StackBliz(온라인 코드 편집기)에서 Firebase Hosting 정적 배포 하는 방법을 알려드립니다.
- 🔧 [Flamelink](https://flamelink.io/) - Firebase 용 CMS입니다. Firestore와 Realtime Database & Storage를 지원합니다.
- 📹 [Firebase Summit 2018](https://www.youtube.com/watch?v=lN0VXVXsj9k&list=PLl-K7zZEsYLnqdlmz7iFe9Lb6cRU3Nv4R) - Firebase 기술 강연 @ Firebase Summit 2018
- 📹 [Firebase @ Google Cloud Next '18](https://www.youtube.com/watch?v=OPj26MY16F8&list=PLl-K7zZEsYLmYx3MkJRIUPH_JVFHLTlwL) - Firebase 기술 강연 @ Google Cloud Next 2018.
- 📹 [Firebase @ Google IO '18](https://www.youtube.com/watch?v=e-8fiv-vteQ&list=PLl-K7zZEsYLn1omgx_VUhCDFsQMA7PRDd) - Firebase 기술 강연 @ Google IO 2018.
- 📹 [#AskFirebase YouTube Playlist](https://www.youtube.com/watch?v=TSzhzR4wzSE&list=PLl-K7zZEsYLkkCFs6T9mlqG8v6NCs38pA) - 공식 #AskFirebase YouTube 재생목록입니다.
- 📝 [State of Firebase (mid 2019)](https://codeburst.io/the-state-of-firebase-mid-2019-2b002c458d70) - Cloud Next & Google I/O 2019 업데이트!
- 📹 [Firebase @ Google IO '19](https://www.youtube.com/playlist?list=PLl-K7zZEsYLlo2L4rfPds-fFLEtOWheoO) - Firebase 기술 강연 @ Google IO 2019.
- 📹 [Firebase Summit 2019](https://www.youtube.com/watch?v=YKZ6rP4kwV8&list=PLl-K7zZEsYLk2OolaVXVyYrFErctrZXSX) - Firebase 기술 강연 @ the Firebase Summit 2019.
- 📹 [Firebase Live 2020](https://www.youtube.com/playlist?list=PLl-K7zZEsYLnw0-bXz2f9zo6745VQ_2ep) - Firebase Live는 생산성, 지식 및 협업을 목적으로 하는 토크, 팁 및 기술 튜토리얼로 구성된 앱 개발자를 위한 웹 시리즈입니다.

<!-- END content -->

## 팔로우

### 공식

📹 [Firebase YouTube](https://www.youtube.com/user/Firebase) 📝 [Firebase 블로그](https://firebase.googleblog.com/) 🐦 [@firebase](https://twitter.com/firebase) 👤 [Firebase Facebook](https://www.facebook.com/Firebase)

### 커뮤니티

- :fire: [Firebase Developers Discord](https://discord.gg/BN2cgc3) - 전 세계의 다른 웹 및 앱 개발자와 어울리고, 도움을 줄 수있는 Firebase 및 Firebase 관련 서비스 전용 공개 커뮤니티입니다.
- 📹 [Fireship - AngularFirebase](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA)
- 📹 ru [@firebase_ru - Telegram friendly chat](https://t.me/firebase_ru)

또 누구를 팔로우 할까요?

## 기여

[어떤 종류의 기여도 환영합니다. 그저 가이드라인만 지켜주세요](contributing.md)!

### 기여자들

[이 기여자들에게 감사드립니다](https://github.com/jthegedus/awesome-firebase/graphs/contributors)!
