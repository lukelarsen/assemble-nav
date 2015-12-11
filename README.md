[Assemble]:                http://assemblecss.com
[Assemble Base]:           https://github.com/lukelarsen/assemble-base

# Assemble Navs
Assemble Navs is a component of the [Assemble] CSS Framework. It will give you a solid base for using media players in your project. It has some default styles that can easily be overridden so you can add your own look.

## Requirements
Assemble Navs requires [Assemble Base].

## Installation
npm install assemble-navs --save-dev

## Usage
Import the _assemble-lists.css file from your css file.
```css
@import '../node_modules/assemble-base/base';

/*
Override variables here before the Assemble Components are loaded.
*/

@import '../node_modules/assemble-lists/assemble-lists';
```

### HTML
```html
<ul class="nav">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

## Options
Options are set with variables. These variables are already set with their default values so they will just work out of the box. If you wish to change them just define the variable you want to change before you load the _assemble-navs.css file. You may wish you see [Assemble Base] for more examples and directions for setting up a Assemble project.

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
Usage
```html
<ul class="nav  nav--fit">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--stacked
- Turn on/off stacked navigations in your application. If set to true you can use the class .nav--stacked. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--stacked: true;
```
Usage
```html
<ul class="nav  nav--stacked">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--center
- Turn on/off center navigations in your application. If set to true you can use the class .nav--center. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--center: true;
```
Usage
```html
<ul class="nav  nav--center">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--right
- Turn on/off right navigations in your application. If set to true you can use the class .nav--right. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--right: true;
```
Usage
```html
<ul class="nav  nav--right">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--left
- Turn on/off left navigations in your application. If set to true you can use the class .nav--left. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--left: true;
```
Usage
```html
<ul class="nav  nav--left">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--space-between
- Turn on/off space between navigations in your application. If set to true you can use the class .nav--space-between. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--space-between: true;
```
Usage
```html
<ul class="nav  nav--space-between">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--space-around
- Turn on/off space around navigations in your application. If set to true you can use the class .nav--space-around. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--space-around: true;
```
Usage
```html
<ul class="nav  nav--space-around">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--keywords
- Turn on/off keyword navigations in your application. If set to true you can use the class .nav--keywords. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--keywords: true;
```
Usage
```html
<ul class="nav  nav--keywords">
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Search</a></li>
</ul>
```

##### $nav--pagination
- Turn on/off pagination navigations in your application. If set to true you can use the class .nav--pagination. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--pagination: true;
```
Usage
```html
<ul class="nav  nav--pagination">
    <li class="nav--pagination__first"><a href="#">Prev</a></li>
    <li><a href="#">7</a></li>
    <li><a href="#">8</a></li>
    <li><a href="#">9</a></li>
    <li><a href="#">10</a></li>
    <li class="nav--pagination__last"><a href="#">Next</a></li>
</ul>
```

##### $nav--breadcrumb
- Turn on/off breadcrumb navigations in your application. If set to true you can use the class .nav--breadcrumb. It requires .nav.
- Default: false;
- Type: Boolean
```css
$nav--breadcrumb: true;
```
Usage
```html
<ul class="nav  nav--breadcrumb">
    <li><a href="#">Prodcut Page</a></li>
    <li><a href="#">Prodcut Sub Page</a></li>
    <li><a href="#">Checkout Page</a></li>
</ul>
```

##### $nav--breadcrumb--path
- Turn on/off breadcrumb path navigations in your application. If set to true you can use the class .nav--breadcrumb--path. It requires .nav & .nav--breadcrumb.
- Default: false;
- Type: Boolean
```css
$nav--breadcrumb--path: true;
```
Usage
```html
<ul class="nav  nav--breadcrumb  nav--breadcrumb--path">
    <li><a href="#">Prodcut Page</a></li>
    <li><a href="#">Prodcut Sub Page</a></li>
    <li><a href="#">Checkout Page</a></li>
</ul>
```

##### $nav--breadcrumb--custom
- Turn on/off custom breadcrumb navigations in your application. If set to true you can use the class .nav--breadcrumb--custom. It requires .nav & .nav--breadcrumb.
- Default: false;
- Type: Boolean
```css
$nav--breadcrumb--custom: true;
```
Usage
```html
<ul class="nav  nav--breadcrumb  nav--breadcrumb--custom">
    <li><a href="#">Prodcut Page</a></li>
    <li data-breadcrumb="_"><a href="#">Prodcut Sub Page</a></li>
    <li data-breadcrumb="--"><a href="#">Checkout Page</a></li>
</ul>
```