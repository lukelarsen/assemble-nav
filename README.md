[Assemble]:                http://assemblecss.com
[Assemble Core]:           https://github.com/lukelarsen/assemble-core

# Assemble Navs
Assemble Navs is a component of the [Assemble] CSS Framework. It will give you a solid base for using media players in your project. It has some default styles that can easily be overridden so you can add your own look.

## Requirements
Assemble Navs requires [Assemble Core].

## Installation
npm install assemble-navs --save-dev

## Usage
### Gulp
```js
var gulp = require('gulp');
var postcss = require('gulp-postcss');
var assembleCore = require('assemble-core');
var assembleNavs = require('assemble-navs');

gulp.task('css', function () {
    var processors = [
        assembleCore,
        assembleNavs
    ];
    return gulp.src('./src/*.css')
        .pipe(postcss(processors))
        .pipe(gulp.dest('./dest'));
});
```

## Options
Options are set with variables. These variables are already set with their default values so they will just work out of the box. If you wish to change them just define the variable you want to change before you load the _assemble-navs.css file. You may wish you see [Assemble Core] for more examples and directions for setting up a Assemble project.

### Design Variables

##### $pagination-li-padding
- Set pagination padding.
- Default: 12px;
- Type: Number
```css
$pagination-li-padding: 5px;
```

##### $pagination-a-spacing
- Set pagination link spacing.
- Default: 12px;
- Type: Number
```css
$pagination-a-spacing: 5px;
```

##### $breadcrumb-a-right
- Set breadcrumb right margin.
- Default: 10px;
- Type: Number
```css
$breadcrumb-a-right: 5px;
```

##### $breadcrumb-a-left
- Set breadcrumb left margin.
- Default: 13px;
- Type: Number
```css
$breadcrumb-a-left: 5px;
```


### Modifier Variables

##### $nav--fit
- Turn on/off fit navigations in your application. If set to true you can use the class .nav--fit. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--fit: true;
```

##### $nav--stacked
- Turn on/off stacked navigations in your application. If set to true you can use the class .nav--stacked. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--stacked: true;
```

##### $nav--center
- Turn on/off center navigations in your application. If set to true you can use the class .nav--center. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--center: true;
```

##### $nav--right
- Turn on/off right navigations in your application. If set to true you can use the class .nav--right. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--right: true;
```

##### $nav--left
- Turn on/off left navigations in your application. If set to true you can use the class .nav--left. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--left: true;
```

##### $nav--space-between
- Turn on/off space between navigations in your application. If set to true you can use the class .nav--space-between. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--space-between: true;
```

##### $nav--space-around
- Turn on/off space around navigations in your application. If set to true you can use the class .nav--space-around. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--space-around: true;
```

##### $nav--keywords
- Turn on/off keyword navigations in your application. If set to true you can use the class .nav--keywords. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--keywords: true;
```

##### $nav--pagination
- Turn on/off pagination navigations in your application. If set to true you can use the class .nav--pagination. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--pagination: true;
```

##### $nav--breadcrumb
- Turn on/off breadcrumb navigations in your application. If set to true you can use the class .nav--breadcrumb. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--breadcrumb: true;
```

##### $nav--breadcrumb--path
- Turn on/off breadcrumb path navigations in your application. If set to true you can use the class .nav--breadcrumb--path. It requires .nav & .nav--breadcrumb.
- Default: false;
- Type: Boolean
```css
$nav--breadcrumb--path: true;
```

##### $nav--breadcrumb--custom
- Turn on/off custom breadcrumb navigations in your application. If set to true you can use the class .nav--breadcrumb--custom. It requires .nav & .nav--breadcrumb.
- Default: false;
- Type: Boolean
```css
$nav--breadcrumb--custom: true;
```