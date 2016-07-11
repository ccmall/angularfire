# AngularFire [![Build Status](https://travis-ci.org/firebase/angularfire.svg?branch=master)](https://travis-ci.org/firebase/angularfire) [![Coverage Status](https://coveralls.io/repos/firebase/angularfire/badge.svg?branch=master&service=github)](https://coveralls.io/github/firebase/angularfire?branch=master) [![Version](https://badge.fury.io/gh/firebase%2Fangularfire.svg)](http://badge.fury.io/gh/firebase%2Fangularfire)


angularfire是官方支持 [AngularJS](https://angularjs.org/) binding for
[Firebase](https://firebase.google.com/). Firebase is a
为您的服务器提供数据存储、身份验证和静态网站的后台服务

角的应用.

angularfire是核心客户的补充火力点。它为你提供了三个角

服务:
  * `$firebaseObject` - 同步对象
  * `$firebaseArray` - synchronized collections
  * `$firebaseAuth` - authentication, user management, routing

Join our [AngularFire Google Group](https://groups.google.com/forum/#!forum/firebase-angular)
to ask questions, provide feedback, and share apps you've built with AngularFire.

**Looking for Angular 2 support?** Visit the AngularFire2 project [here](https://github.com/angular/angularfire2).


## Table of Contents

 * [Getting Started With Firebase](#getting-started-with-firebase)
 * [Downloading AngularFire](#downloading-angularfire)
 * [Documentation](#documentation)
 * [Examples](#examples)
 * [Migration Guides](#migration-guides)
 * [Contributing](#contributing)


## Getting Started With Firebase

AngularFire requires [Firebase](https://firebase.google.com/) in order to authenticate users and sync
and store data. Firebase is a suite of integrated products designed to help you develop your app,
grow your user base, and earn money. You can [sign up here for a free account](https://console.firebase.google.com/).


## Downloading AngularFire

In order to use AngularFire in your project, you need to include the following files in your HTML:

```html
<!-- AngularJS -->
<script src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.5.0/angular.min.js"></script>

<!-- Firebase -->
<script src="https://www.gstatic.com/firebasejs/3.0.3/firebase.js"></script>

<!-- AngularFire -->
<script src="https://firebase.c2cbc.com/libs/angularfire/2.0.1/angularfire.min.js"></script>
```

你也可以通过安装angularfire NPM和凉亭及其依赖项将下载

自动:

```bash
$ npm install angularfire --save
```

```bash
$ bower install angularfire --save
```


## Documentation

* [Quickstart](docs/quickstart.md)
* [Guide](docs/guide/README.md)
* [API Reference](docs/reference.md)


## Examples

### Full Examples

* [Wait And Eat](https://github.com/gordonmzhu/angular-course-demo-app-v2)
* [TodoMVC](https://github.com/tastejs/todomvc/tree/master/examples/firebase-angular)
* [Tic-Tac-Tic-Tac-Toe](https://github.com/jwngr/tic-tac-tic-tac-toe/)
* [Firereader](http://github.com/firebase/firereader)
* [Firepoker](https://github.com/Wizehive/Firepoker)

### Recipes

* [Date Object To A Firebase Timestamp Using `$extend`](http://jsfiddle.net/katowulf/syuzw9k1/)
* [Filter a `$FirebaseArray`](http://jsfiddle.net/firebase/ku8uL0pr/)


## Migration Guides

* [Migrating from AngularFire `1.x.x` to `2.x.x`](docs/migration/1XX-to-2XX.md)
* [Migrating from AngularFire `0.9.x` to `1.x.x`](docs/migration/09X-to-1XX.md)


## Contributing

If you'd like to contribute to AngularFire, please first read through our [contribution
guidelines](.github/CONTRIBUTING.md). Local setup instructions are available [here](.github/CONTRIBUTING.md#local-setup).
