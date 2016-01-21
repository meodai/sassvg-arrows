# sassvg-arrows
generates SVG-Arrows with sass. Large ones, Small ones, red ones. [Demo](http://codepen.io/meodai/pen/GoyBJe?editors=010)

## Setup
Install with npm or simply checkout the project.
```shell
npm install sassvg-arrows --save
```
Import **sassvg-arrows.scss** into your main scss/sass file.

```sass
@import 'sassvg-arrows';
```

PS: node-sass (libsass) for example lets you [add the NPM directory as an import path.](https://github.com/sass/node-sass#user-content-importer--v200---experimental)

## Usage
```scss
@include arrow($direction: down, $weight: 2, $width: .8em, $height: .45em, $fill: red);
```

## Credits
The awesome super clean arrow SVG was provided by [Simon Raess](https://twitter.com/simonraess)
