# user-profile
[![Build status][travis-badge]][travis-url] ![Size][size-badge] [![Version][tag-badge]][releases-url] [![Published][webcomponents-badge]][webcomponents-url]

Componente para criação de perfil de usuário com sidenav

## Installation & usage

Install user-profile with Bower

```sh
$ bower i https://github.com/edvardp/userprofile.git/user-profile --save
```

Import it into the `<head>` of your page

```html
<link rel="import" href="/bower_components/user-profile/user-profile.html">
```

Then use user-profile in your project

```html
<user-profile></user-profile>
```

### Polyfills for cross-browser support

user-profile relies on emerging standards, for full cross-browser support include the [WebComponentsJS](https://github.com/webcomponents/webcomponentsjs) polyfill on your page.

```html
<script src="https://unpkg.com/@webcomponents/webcomponentsjs@^1.0.0/webcomponents-loader.js"></script>
```

### Transpiling for IE11 support

Web Components like user-profile are distributed as ES6 classes, which are supported in all evergreen browsers. To support Internet Explorer 11 you should transpile user-profile to ES5 and use the `webcomponentsjs` `custom-elements-es5-adapter.js` shim. 

The easiest way to do this is by including [polymer-build][polymer-build] in your buildstep of choice. Then just include the ES5 adapter on your page

```html
<script src="https://unpkg.com/@webcomponents/webcomponentsjs@^1.0.0/custom-elements-es5-adapter.js"></script>
```

***

MIT © Edvard Pereira

[tag-badge]: https://img.shields.io/github/tag/https://github.com/edvardp/userprofile.git/user-profile.svg
[releases-url]: https://github.com/https://github.com/edvardp/userprofile.git/user-profile/releases
[travis-badge]: https://img.shields.io/travis/https://github.com/edvardp/userprofile.git/user-profile.svg
[travis-url]: https://travis-ci.org/https://github.com/edvardp/userprofile.git/user-profile
[size-badge]: http://img.badgesize.io/https://github.com/edvardp/userprofile.git/user-profile/master/props.name .html?compression=gzip&label=size%20%28unminified%29
[webcomponents-badge]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[webcomponents-url]: https://www.webcomponents.org/element/https://github.com/edvardp/userprofile.git/user-profile
[polymer-build]: https://github.com/Polymer/polymer-build
