# awesome-state

Collection of state management lib

![bg](https://raw.githubusercontent.com/fantasticsoul/assets/master/img/astate2.jpg)

State management refers to the management of the state of one or more user interface controls such as text fields, OK buttons, radio buttons, etc. in a graphical user interface. In this user interface programming technique, the state of one UI control depends on the state of other UI controls. For example, a state managed UI control such as a button will be in the enabled state when input fields have valid input values and the button will be in the disabled state when the input fields are empty or have invalid values. As applications grow, this can end up becoming one of the most complex problems in user interface development.[1]

This is especially the case when the state of any particular message or form on the page depends on factors outside of the current page, or available throughout several pages. For example, consider a user who is logged in and sees the 'welcome' message on their first visit to any page, but not on subsequent page visits. Does each page manage the state of the user being logged in? That would create too much copy pasting and duplication of code. Instead, you can use a state management pattern for handling messages (this may also include handling error messages and informative messages, along with the described welcome message) and then call this to receive a message as it becomes available.


## cross framework

- [redux](https://github.com/reduxjs/redux) Predictable state container for JavaScript apps
- [mobx](https://github.com/mobxjs/mobx) Simple, scalable state management.
- [mobx-keystone](https://github.com/xaviergonz/mobx-keystone) A MobX powered state management solution based on data trees with first class support for TypeScript, support for snapshots, patches and much more
- [akita](https://github.com/datorama/akita) 🚀 State Management Tailored-Made for JS Applications
- [effector](https://github.com/zerobias/effector) The state manager ☄️
- [usm](https://github.com/unadlib/usm) 🏖A concise & flexible state model for Redux/MobX/Vuex, etc.
- [storeon](https://github.com/storeon/storeon) 🌩 A tiny (167 bytes) event-based Redux-like state manager for React, Preact, Angular, Vue, and Svelte
- [xsm](https://github.com/peterluhub/xsm) State Management made eXtraordinarily simple and effective for Angular, React, and Vue
___
## react

- [eventrix](https://github.com/rstgroup/eventrix) Scaling and predictable JS library for state managing and centralizing application global state.
- [flux](https://github.com/facebook/flux) Application Architecture for Building User Interfaces
- [reflux](https://github.com/reflux/refluxjs) A simple library for uni-directional dataflow application architecture with React extensions inspired by Flux
- [react-redux](https://github.com/reduxjs/react-redux) Official React bindings for [Redux](https://github.com/reduxjs/redux).
- [mobx-react](https://github.com/mobxjs/mobx-react) Official React bindings for [Mobx](https://github.com/mobxjs/mobx)
- [concent](https://github.com/concentjs/concent) State management tailored for react, it is simple、predictable、progressive and efficient.
- [rematch](https://github.com/rematch/rematch) REmatch, a complete binary diffing framework that is free and strives to be open source and community driven.
- [constate](https://github.com/diegohaz/constate) React Context + State
- [unstated](https://github.com/jamiebuilds/unstated) State so simple, it goes without saying
- [zustand](https://github.com/react-spring/zustand) 🐻 Bear necessities for state management in React
- [easy-peasy](https://github.com/ctrlplusb/easy-peasy) Vegetarian friendly state for React
- [react-easy-state](https://github.com/RisingStack/react-easy-state) Simple React state management. Made with ❤️ and ES6 Proxies.
- [redux-observable](https://github.com/redux-observable/redux-observable) RxJS middleware for action side effects in Redux using "Epics"
- [react-automata](https://github.com/MicheleBertoli/react-automata) A state machine abstraction for React
- [dva](https://github.com/dvajs/dva) Lightweight front-end framework based on redux, redux-saga and react-router.
- [react-copy-write](https://github.com/aweary/react-copy-write) ✍️ Immutable state with a mutable API
- [unistore](https://github.com/developit/unistore) 🌶 350b / 650b state container with component actions for Preact & React
- [kea](https://github.com/keajs/kea) Production Ready State Management for React
- [undux](https://github.com/bcherny/undux) ⚡️ Dead simple state for React. Now with Hooks support.
- [moreartyjs](https://github.com/moreartyjs/moreartyjs) centralized state management for React in pure JavaScript
- [hox](https://github.com/umijs/hox) The next-generation state manager for React.
- [use-persisted-state](https://github.com/donavon/use-persisted-state) A custom React Hook that provides a multi-instance, multi-tab/browser shared and persistent state.
- [marty](https://github.com/martyjs/marty) A Javascript library for state management in React applications
- [TNG-Hooks](https://github.com/getify/TNG-Hooks) Provides React-inspired 'hooks' like useState(..) for stand-alone functions
- [react-hooks-global-state](https://github.com/dai-shi/react-hooks-global-state)
- [react-hooks-global-state](https://github.com/dai-shi/react-hooks-global-state) Simple global state for React with Hooks API
- [redux-arena](https://github.com/hapood/redux-arena) Bundling reducers, actions, saga and react-component when using Redux
- [dob-react](https://github.com/dobjs/dob-react) React bindings for [dob](https://github.com/dobjs/dob)
- [doux](https://github.com/yisar/doux) Simple reactivity system with composition API.
- [react-tracked](https://github.com/dai-shi/react-tracked) Simple and fast global state with React Context. Eliminate unnecessary re-renders without hassle.
- [icestore](https://github.com/ice-lab/icestore) 🌩 Simple and friendly state for React
- [overmind](https://github.com/cerebral/overmind) Overmind - Frictionless state management
- [outstated](https://github.com/yamalight/outstated) Simple hooks-based state management for React
- [pure-store](https://github.com/gunn/pure-store) A tiny immutable store with type safety.
- [react-broadcast](https://github.com/ReactTraining/react-broadcast) Reliably communicate state changes to deeply nested React elements
- [react-nano-state](https://github.com/kof/react-nano-state) Fast state that can be shared across components outside of the React tree
- [react-sweet-state](https://github.com/atlassian/react-sweet-state) Shared state management solution for React
- [stamen](https://github.com/forsigner/stamen) A React state management library based on Hooks
- [rex-state](https://github.com/daniakash/rex-state) The simplest state management tool for React
- [statux](https://github.com/franciscop/statux) ⚛️ A minimal state management library for React with Hooks and immutable state
- [reworm](https://github.com/pedronauck/reworm) 🍫 the simplest way to manage state
- [remx](https://github.com/wix/remx) Opinionated mobx
- [vuex-redux](https://github.com/qinjialei24/vuex-redux) Make Redux as simple as Vuex
- [linkstate](https://github.com/developit/linkstate) Bind events to state. Works with Preact and React.
- [statty](https://github.com/vesparny/statty) A tiny and unobtrusive state management library for React and Preact apps
- [freactal](https://github.com/FormidableLabs/freactal) Clean and robust state management for React and React-like libs.
- [react-3ducks](https://github.com/smakazmi/react-3ducks) Simple state management solution for React
- [teaful](https://github.com/teafuljs/teaful) Tiny, easy and powerful React state management

___
## vue

- [vuex](https://github.com/vuejs/vuex) Centralized State Management for Vue.js.
- [mobx-vue](https://github.com/mobxjs/mobx-vue) Vue bindings for [Mobx](https://github.com/mobxjs/mobx)
- [vuet](https://github.com/medatc/vuet) 允许你定义飙车过程的集中式状态管理模式
- [VueFlux](https://github.com/ra1028/VueFlux) ♻️ Unidirectional State Management Architecture for Swift - Inspired by Vuex and Flux
- [vue-rx](https://github.com/vuejs/vue-rx) 👁️ RxJS integration for Vue.js.
- [vuex-observable](https://github.com/vuejs/vuex-observable) Consume Vuex actions as Observables using RxJS 5
- [vue-reactive-store](https://github.com/mdartic/vue-reactive-store) A VueX alternative : declarative + reactive + centralized way to structure your data store. Inspired by VueX and Vue.js . Compatible with vue-devtools.
- [vuex-stores](https://github.com/ElMassimo/vuex-stores) 🗄 Store objects for Vuex, a simple and more fluid API for state-management.
- [Vuex-Alt](https://github.com/ejfrancis/Vuex-Alt) An alternative approach to Vuex helpers for accessing state, getters and actions that doesn't rely on string constants.
- [vue-entity-adapter](https://github.com/imanubhardwaj/vue-entity-adapter) Package to maintain entities in Vuex.

___
## mini-programe

- [westore](https://github.com/Tencent/westore) 微信小程序解决方案 - 1KB javascript 覆盖状态管理、跨页通讯、插件开发和云数据库开发
- [minii](https://github.com/wwayne/minii) State management for Wechat Mini App
- [herculex](https://github.com/herculesJS/herculex) Predictable state container for alipay mini-program inspired by vuex, redux, immutableJS,elm,rxjs
- [mp-store](https://github.com/imtaotao/mp-store) 轻量级的小程序状态管理库
- [wxMiniStore](https://github.com/xiaoyao96/wxMiniStore)一个基于微信小程序的mini全局状态管理库
- [mobx-wxapp](https://github.com/b5156/mobx-wxapp) 在小程序中使用mobx
- [mobx-miniprogram-bindings](https://github.com/wechat-miniprogram/mobx-miniprogram-bindings) 小程序的 MobX 绑定辅助库
- [Wepy-Redux](https://github.com/Chris-wei/Wepy-Redux) 微信小程序wepy框架接入 Redux 状态管理
- [weapp_expressTime](https://github.com/super456/weapp_expressTime)微信小程序之物流状态时间轴简单模板样式
- [mp-store](https://github.com/imtaotao/mp-store) 轻量级的小程序状态管理库
- [wxappStore](https://github.com/SBDavid/wxappStore) 微信小程序全局状态管理，并提供Vuex的开发体验
- [wxMiniStore](https://github.com/xiaoyao96/wxMiniStore) 一个基于微信小程序的mini全局状态管理库

___
## angular

- [ng-redux](https://github.com/angular-redux/ng-redux) Angular bindings for [Redux](https://github.com/reduxjs/redux).
- [redux-rx](https://github.com/acdlite/redux-rx) RxJS utilities for Redux.
- [ngxs](https://github.com/ngxs/store) 🚀 NGXS - State Management for Angular
- [mobx-angular](https://github.com/mobxjs/mobx-angular) MobX connector to Angular
- [RxEmitter](https://github.com/drawcall/RxEmitter) RxEmitter combines the characteristics of Rxjs and eventBus
- [angular-model](https://github.com/angular-extensions/model) Simple state management with minimalist API, one way data flow, multiple model support and immutable data exposed as RxJS Observable.
- [ngx-model](https://github.com/tomastrajan/ngx-model) Angular Model. Simple state management with minimalistic API, one way data flow, multiple model support and immutable data exposed as RxJS Observable.
- [tinystate](https://github.com/SebastianM/tinystate) A tiny, yet powerful state management library for Angular
- [ng-simple-state](https://www.npmjs.com/package/ng-simple-state) Simplex state management based on Rxjs and service

## other

- [fish-redux](https://github.com/alibaba/fish-redux) An assembled flutter application framework.
- [RxAndroid](https://github.com/ReactiveX/RxAndroid) Reactive Extensions for Android
- [flutter-provide](https://github.com/google/flutter-provide) A simple framework for state management in Flutter.
- [bloc](https://github.com/felangel/bloc) A predictable state management library that helps implement the BLoC design pattern
- [mobx.dart](https://github.com/mobxjs/mobx.dart) MobX for the Dart language. Hassle-free, reactive state-management for your Dart and Flutter apps.
- [multiple-counters-flutter](https://github.com/bizz84/multiple-counters-flutter) Flutter State Management [ setState ❖ StreamBuilder ❖ scoped_model ❖ redux ]
- [flutter-native-state](https://github.com/littlerobots/flutter-native-state) Flutter plugin to help restoring state after the app process was killed
- [easy](https://github.com/jonataslaw/easy) The easiest state manager for Flutter.
- [Reflow](https://github.com/Zepo/Reflow) A unidirectional data flow framework for Objective-C inspired by Flux, Redux and Vue
- [rebloc](https://github.com/RedBrogdon/rebloc) A state management library for Flutter that combines aspects of Redux and BLoC.
