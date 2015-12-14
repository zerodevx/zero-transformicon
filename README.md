v0.1.0

# `<zero-transformicon>`

Animated icon buttons! A Polymer port of [Transformicons](http://transformicons.com).

All of Transformicon goodness encapsulated in one incredibly easy-to-use web
component.


### Let's get this money

1. Import dependencies.
  ```html
  <head>

    <!-- Load webcomponents-lite polyfill -->
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>

    <!-- Import Polymer framework -->
    <link rel="import" href="bower_components/polymer/polymer.html">

    <!-- Import `<zero-transformicon>` -->
    <link rel="import" href="bower_components/zero-transformicon/zero-transformicon.html">

  </head>
  ```

2. Use anywhere.
  ```html
  <body>

    <!-- Most basic usage -->
    <zero-transformicon icon="menu-xcross"></zero-transformicon>

    <!-- In red color -->
    <zero-transformicon icon="grid-collapse" color="red"></zero-transformicon>

    <!-- Default to 'open' state -->
    <zero-transformicon icon="plus-minus" color="#222" active></zero-transformicon>

  </body>
  ```


### Demo

Check out the demo site: https://zerodevx.github.com/zero-transformicon


### Included icons

| Icon name           | Transition description |
|---------------------|------------------------|
| menu-xbutterfly     | Hamburger to X in two stages |
| menu-minus          | Hamburger to Minus sign |
| menu-xcross         | Hamburger to X in one stage |
| menu-arrowup        | Hamburger to Up Arrow |
| menu-arrow360left   | Hamburger to Left Arrow in psychedelic 360° madness |
| menu-arrowleft      | Hamburger to Left Arrow |
| grid-collapse       | Grid symbol that collapses to a small X |
| grid-rearrange      | Grid symbol that rearranges to a large X |
| plus-check          | Plus sign to to Check symbol |
| plus-minus          | Plus sign to Minus sign |
| remove-check        | X to to Check symbol |
| remove-chevronleft  | X to Left Chevron |
| remove-chevronright | X to Right Chevron |
| remove-chevrondown  | X to Down Chevron |
| remove-chevronup    | X to Up Chevron |
| main-envelope       | Opened Mail icon to Closed Mail icon |
| search-xcross       | Search icon to X |


### Published properties

| Property | Type    | Description |
|----------|---------|-------------|
| icon     | String  | *Icon name* as defined in [included icons](#Included_icons). |
| color    | String  | CSS color property applied to this instance. Defaults to "black". |
| active   | Boolean | Sets initial state of icon - `true` displays icon in "opened" state. Defaults to `false`. Fires an `active-changed` custom event when state changes. |


### Installation

**Install through Bower**

    bower install --save zerodevx/zero-md#^0.2.0

Alternatively, download the project as a ZIP file and unpack into your
components directory. Note that `<zero-transformicon>` depends on:
  * `Polymer`: https://github.com/Polymer/polymer

Source provided as-is - no assumptions are made on your production build
workflow.

**Load from [Rawgit CDN](https://rawgit.com)**

If you're not using Polymer,

```html
<head>
  <!-- Load webcomponents-lite polyfill -->
  <script src="https://cdn.rawgit.com/webcomponents/webcomponentsjs/v0.7.19/webcomponents-lite.min.js"></script>
  <!-- Import `<zero-transformicon>` bundle -->
  <link rel="import" href="https://cdn.rawgit.com/zerodevx/zero-transformicon/v0.1.0/build/zero-transformicon.build.html">
</head>
```


### Credits

Big thank you to the kind folks at [Grey Ghost Visuals](https://github.com/grayghostvisuals/transformicons),
[Bennett Feely](http://bennettfeely.com) and [Sara Soueidan](http://sarasoueidan.com)
for creating these awesome UI pieces. This is simply their work wrapped in some
Polymer magic.


### License

MIT, though I'll greatly appreciate a note if you find this useful.


### Version history

1. 2015-12-13: v0.1.0
  * Initial commit.

