# web-dev-glossary

- [web-dev-glossary](#web-dev-glossary)
  - [Angular](#angular)
  - [Angular 2+](#angular-2)
  - [Apollo](#apollo)
  - [CSS preprocessor](#css-preprocessor)
  - [CSS](#css)
  - [ECMAScript 6](#ecmascript-6)
  - [ECMAScript 2015](#ecmascript-2015)
  - [ES6](#es6)
  - [GraphQL](#graphql)
  - [HTML5](#html5)
  - [Jest](#jest)
  - [Less](#less)
  - [Node](#node)
  - [React-Testing-Library](#react-testing-library)
  - [React](#react)
  - [Sass](#sass)
  - [SCSS](#scss)
  - [Vue](#vue)

## Angular

<https://angular.io/>

Angular (also referred to as Angular2+) is a TypeScript-based open-source web application framework designed and maintained by Google.

[Angular vs React](https://www.interviewbit.com/blog/angular-vs-react/)

## Angular 2+

See [Angular](#angular).

## Apollo

<https://www.apollographql.com/>

Apollo is an open-source implementation of [GraphQL](#graphql).

## CSS preprocessor

<https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor>

A CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax.

Examples of CSS preprocessors include [Sass](#sass) and [Less](#less).

## CSS

<https://developer.mozilla.org/en-US/docs/Glossary/CSS>

CSS (Cascading Style Sheets) is a declarative language that controls how webpages look in the browser.

The browser applies CSS style declarations to selected elements to display them properly. A style declaration contains the properties and their values, which determine how a webpage looks.

CSS is one of the three core Web technologies, along with HTML and JavaScript.

## ECMAScript 6

See [ES6](#es6).

## ECMAScript 2015

See [ES6](#es6).

## ES6

<https://www.w3schools.com/js/js_es6.asp>

ECMAScript 2015 (also known as ECMAScript 6 or ES6) was the second major revision to JavaScript.  

<https://www.tutorialrepublic.com/javascript-tutorial/javascript-es6-features.php>

New features introduced in this revision include the following:

- block-scoped variables `let` and `const` (`{}`)
- default values for function parameters
- arrow functions (`=>`)
- classes
- file-based modules (`import` and `export` statements)
- the rest parameter (`...`)
- the spread operator (`...`)
- array destructuring assignment
- object destructuring assignment

## GraphQL

<https://graphql.org/>

GraphQL is an open-source data query and manipulation language for APIs, and a runtime for fulfilling those queries with existing data.  

GraphQL provides an approach to developing web APIs and has been compared and contrasted with REST and other web service architectures.  
It allows clients to define the structure of the data required, and the same structure of the data is returned from the server.  
This prevents excessively large amounts of data from being returned, giving the API's users the power to ask for exactly what they need and nothing more. 

## HTML5

<https://developer.mozilla.org/en-US/docs/Glossary/HTML5>

The term HTML5 is essentially a buzzword that refers to a set of modern web technologies.  
This includes the [HTML Living Standard](https://html.spec.whatwg.org/), along with JavaScript APIs to enhance storage, multimedia, and hardware access.

## Jest

<https://jestjs.io/>

Jest is a JavaScript testing framework that works with projects using Node, React, Angular, Vue, and more.  

## Less

<https://lesscss.org/>

Less (which stands for Leaner Style Sheets) is a CSS preprocessor -- a backwards-compatible language extension for CSS.  
It allows you to use variables, nested rules, mixins, functions, and more, all with a fully CSS-compatible syntax.  

## Node

<https://nodejs.org/>

Node.js is an open-source, cross-platform, back-end JavaScript runtime environment.  
It executes JavaScript code outside of a web browser.

## React-Testing-Library

<https://testing-library.com/docs/react-testing-library/intro/>

The React-Testing-Library is a JavaScript testing utility built specifically to test React components.  
It simulates user interactions on isolated components and asserts their outpus to ensure the UI is behaving correctly.

[React Testing Library vs Jest](https://blog.logrocket.com/testing-react-apps-jest-react-testing-library/#react-testing-library-vs-jest)

React Testing Library is not an alternative to Jest.  
Jest is a test runner that finds tests, runs the tests, and determines whether the tests passed or failed.  
React Testing Library provides the virtual DOMs where the React components are actually tested -- Any time we run tests without a web browser, we must have a virtual DOM to render the app, interact with the elements, and observe if the virtual DOM behaves like it should (like changing the width of a div on a button click).  
Jest finds, runs, and reports on the tests; React Testing Library runs the tests themselves.  
By default `create-react-app` uses Jest and React Testing Library together when generating test files.

## React

<https://reactjs.org/>

React is an open-source front-end JavaScript library for building user interfaces based on UI components.  
It was developed and is maintained by Facebook.

## Sass

<https://sass-lang.com/>

Sass is a CSS preprocessor -- a stylesheet language that gets compiled to CSS.  
It allows you to use variables, nested rules, mixins, functions, and more, all with a fully CSS-compatible syntax.  
Sass helps keep large stylesheets well-organized and makes it easy to share design within and across projects.  

<https://sass-lang.com/documentation/syntax>

Sass supports two different syntaxes: SCSS (file extension `.scss`) and Indented Syntax (file extension `.sass`).  

## SCSS

See [Sass](#sass).

## Vue

Vue.js is an open-source model-view-viewmodel front-end JavaSript framework for building user interfaces and single-page applications.  

<https://vuejs.org/>

[Vue vs React](https://v2.vuejs.org/v2/guide/comparison.html)
