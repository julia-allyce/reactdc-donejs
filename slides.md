title: DoneJS - Your app. Done.
output: index.html
theme: theme
controls: false
logo: theme/logo.png
style: style.css

-- centered hero

<img src="img/donejs-logo-white.svg" style="width: 80%; margin-top: 3em;" alt="Donejs">

# ReactDC, March 8, 2016

-- color dark-grey hero centered
<div style="margin-top:3em">
<h1>Performance</h1>
<h1>Maintainability</h1>
<h1>Usability</h1>
</div>

-- color light-grey hero

## <small>Better</small> Performance

- _Server Side Rendered (Isomorphic)_
- Progressive Loading
- Minimal Data Requests
- Minimal DOM Updates
- Worker Thread Rendering
- Deploy to a CDN

-- color blue hero

## <small>More</small> Maintainable

- Comprehensive Testing
- Documentation
- Continuous Integration & Deployment
- _NPM Packages_
- ES6 Modules
- Modlets
- Custom HTML Elements
- MVVM Architecture
- _Hot Module Swapping_
- Generators

-- color dark-grey hero

## <small>Improved App</small> Usability

- _Real Time_
- Two-way Routing
- IE8+
- _iOS, Android_
- _Desktop_


-- centered

## With a History

<img src="img/framework-timeline.png" style="width: 70%;" alt="Framework Timeline">

-- centered

## Why is History Important?

<img src="img/release-history.jpg" style="width: 70%;" alt="Release History">

<small>Source: <em>[Longevity (or Lack Thereof) in JavaScript Frameworks](http://blog.bitovi.com/longevity-or-lack-thereof-in-javascript-frameworks/)</em></small>

-- hero color blue wide-list

## How Do We Do It?

- It's our business model
 - Building amazing applications for our clients<br> using our tools!
- Enterprise Clients
 - Want long term stability and reliability
- Hard work and persistence

-- color light-grey hero wide-list

## In the box

- Open Source JavaScript framework (MIT)
- Backend services agnostic
- Windows, Linux, OSX
- Comes with
  - [StealJS](http://stealjs.com) - ES6, CJS, and AMD module loader and builder
  - [CanJS](http://canjs.com) - Custom elements and Model-View-ViewModel utilities
  - [jQuery](http://jquery.com) - DOM helpers
  - [FuncUnit](http://funcunit.com) - Functional tests
  - [Testee](https://github.com/bitovi/testee) - QUnit, Mocha and Jasmine Test runner
  - [DocumentJS](http://documentjs.com) - Documentation
  - [can-ssr](http://github.com/canjs/ssr) - Server-Side Rendering Utilities for CanJS
  - [can-connect](https://github.com/canjs/can-connect) - Assemble real-time, high performance, restful data connections.

-- color dark-grey hero

## Why React?
- React is 🔥
- Lower the barrier to entry
- Let's be honest...a client asked for it.

-- color light-grey hero wide-list

## What's Goin On

- React replaces CanJS's [`can.Component`](https://canjs.com/docs/can.Component.html) and [`stache`](https://canjs.com/docs/can.stache.html) templates
  - CanJS is DoneJS's MVVM framework
- This is not Flux...
- This is react baked into our MVVM paradigm

-- hero color blue folder-list wide-list
## App Structure

- `/src`
  - `/models` (data layer)
  - `/components` (reusable modules)
  - `/pages`
  - `app.js` (initializes the app and routing)

-- hero color light-grey folder-list wide-list
## Component Structure

- `/src/components/input`
  - `viewmodel.js` (business logic for component)
  - `input.js` (component class)
  - `input.jsx` (template)
  - `input.less/scss` (styles)
  - `demo.html` (fully functioning demo)
  - `input_test.js` (unit and functional tests)

-- hero color dark-grey
## The Struggle is Real

- Building nested components that need to modify the body
- Managing async data with synchronous rendering ( + ssr )
- className 😭 😭

-- hero color light-grey
## However

- JSX is awesome
- Learning so much 😁
- React is fun

-- hero color blue centered
## Learn More

[<i class="fa fa-link"></i> can-react github (where the magic happens)](https://github.com/canjs/can-react)

[<i class="fa fa-link"></i> High Performance Apps with DoneJS](https://youtu.be/24U0kvpMVWQ)

[<i class="fa fa-link"></i> donejs.com](http://donejs.com)

-- hero color light-grey
<div style="margin-top: 3em"></div>
# DoneJS Training!
## julia at bitovi.com


-- presenter hero color dark-grey wide-list
## The End.
<div>
<div class="bio">


![DoneJS](/img/flag.png)

<h2>DoneJS</h2>
<ul>
  <li>[<i class="fa fa-github"></i> donejs](https://github.com/donejs/donejs)</li>
  <li>[<i class="fa fa-twitter"></i> @donejs](http://twitter.com/donejs)</li>
</ul>
<ul>
  <li>[<i class="fa fa-comment"></i> gitter.im/donejs/donejs](https://gitter.im/donejs/donejs)</li>
</ul>
</div>

<div class="bio">

![Julia Allyce](http://gravatar.com/avatar/51d3dd361a66507e9f4e8232e69b7d99?s=200)

<h2>Julia Allyce</h2>
<ul>
  <li>[<i class="fa fa-github"></i> julia-allyce](https://github.com/julia-allyce)</li>
  <li>[<i class="fa fa-twitter"></i> @julia_allyce](http://twitter.com/julia_allyce)</li>
</ul>
</div>
</div>
<h2 style="margin-top: 1em; clear:both">[http://julia-allyce.github.io/reactdc-donejs/](http://julia-allyce.github.io/reactdc-donejs/)</h2>
