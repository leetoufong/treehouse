# The Parts and Pieces of an Angular Application

+ Angular utilizes modern EcmaScript
+ Made up of a collection of modules
+ Written in **Typescript**, a static type checker that lets you focus more on the actual code
+ **Typescript** is written by the Angular team @ Google and the preferred language to use in Angular
+ **Typescript** helps you avoid mistakes in your code
+ Needs one root module
+ Made up of
  - Services
  - Components
  - Modules (3rd party too)
+ ***Services*** are the way your app can perform actions behind the scenes
  - Long running functionality
  - Sending and receiving information from a database
+ **Components** are a collection of templates, styles, business logic to make up your application
  - Can include a large portion of the UI
  - Or as simple as a button
+ **NgModule** is a container for your app
+ **Ng** is the namespace that short for Angular (Note: we'll be using this) 
+ **Webpack** is a open-source module loader and has become the standard way to package Ng apps