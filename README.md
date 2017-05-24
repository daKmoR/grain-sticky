[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/daKmoR/grain-sticky)
[![Polymer Version](https://img.shields.io/badge/polymer-v2-blue.svg)](https://www.polymer-project.org)

# \<grain-sticky\>

Adds a sticky element that is usually only shown after you scroll a little down

## Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="grain-sticky.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<grain-sticky show-from="10vh">
  I'm only visible after you scroll a little (10%) down.
</grain-sticky>
```

## Installation

```sh
$ bower install --save daKmoR/grain-sticky
```

## Getting Started

Import the package.

```html
<link rel="import" href="/bower_components/grain-sticky/grain-sticky.html">
```

*For more information, see the API documentation.*

## Working on the Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
* View the Element via `polymer serve`
* Run tests via `polymer test`
