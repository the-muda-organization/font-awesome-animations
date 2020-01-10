# Font Awesome Animations
CSS animations for Font Awesome (and other icon libraries!).


********************************************************************************
## Status
[![Latest Stable Version](https://poser.pugx.org/the-muda-organization/font-awesome-animations/version)](https://packagist.org/packages/the-muda-organization/font-awesome-animations)
[![Latest Unstable Version](https://poser.pugx.org/the-muda-organization/font-awesome-animations/v/unstable)](https://packagist.org/packages/the-muda-organization/font-awesome-animations)

[![Total Downloads](https://poser.pugx.org/the-muda-organization/font-awesome-animations/downloads)](https://packagist.org/packages/the-muda-organization/font-awesome-animations)
[![Monthly Downloads](https://poser.pugx.org/the-muda-organization/font-awesome-animations/d/monthly)](https://packagist.org/packages/the-muda-organization/font-awesome-animations)
[![Daily Downloads](https://poser.pugx.org/the-muda-organization/font-awesome-animations/d/daily)](https://packagist.org/packages/the-muda-organization/font-awesome-animations)

[![CSS gzip size](https://img.badgesize.io/the-muda-organization/font-awesome-animations/master/fa-animations/1.0.0/fa-animations.min.css?compression=gzip&label=CSS+gzip+size)](https://github.com/the-muda-organization/font-awesome-animations/blob/master/fa-animations/1.0.0/fa-animations.min.css)

[![License Code](https://poser.pugx.org/the-muda-organization/font-awesome-animations/license)](https://packagist.org/packages/the-muda-organization/font-awesome-animations)


## [View Preview](https://rawcdn.githack.com/the-muda-organization/font-awesome-animations/82044da336ac003f93052ddbb617c57b52d093c5/DEMO.html)
<img src="https://github.com/the-muda-organization/font-awesome-animations/blob/master/PREVIEW.jpg?raw=true" alt="" style="width:100%;display:block;">


********************************************************************************
## Table of contents
- [Status](#status)
- [Quick Start](#quick-start)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Versioning](#versioning)
- [Changelog](#changelog)
- [Team](#team)
- [Code of Conduct](#code-of-conduct)
- [Copyright and License](#copyright-and-license)


********************************************************************************
## Quick Start

Several options are available:
- [Download the latest release.](https://github.com/the-muda-organization/font-awesome-animations/archive/master.zip)
- Clone the repo: `git clone https://github.com/the-muda-organization/font-awesome-animations.git`
- Install with [Composer](https://getcomposer.org/): `composer require the-muda-organization/font-awesome-animations`


********************************************************************************
## What's included
Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

There are no dependencies. Library is designed for Font Awesome 5. See below for [Installation Guide](#installation) and [How to Use](#how-to-use)
```
fa-animations/
 │
 └─ 1.x.x/
    │
    ├── fa-animations.css
    └── fa-animations.min.css
```


********************************************************************************
## Bugs and feature requests
Have a bug or a feature request? Before opening a new issue search for existing and closed issues. If your problem or idea is not addressed yet, [open a new issue](https://github.com/the-muda-organization/font-awesome-animations/issues/new).


********************************************************************************
## Installation

1. Download and copy files to your project
2. Add CSS to your project:
```html
    <link href="https://example.com/fa-animations/1.x.x/fa-animations.min.css" rel="stylesheet">
```
3. Ready to use!


********************************************************************************
## How to Use

Animations work with any Font Awesome prefix `fad`, `fal`, `far` and `fas`. Not tested on other icon librairies but it should work with little or no customization.

This library does not include default Font Awesome animations: `fa-spin` and `fa-pulse`.

Font Awesome Animations uses custom classes `.faa` or `.faa-parent` and custom prefix `faa-`.

There are 2 types of animations: **regular** and **on hover**.

### A) Regular animations
Add `faa` and `faa-animation-name` classess to the icon.
```html
<i class="fad fa-camera faa faa-bounce"></i>
<i class="fal fa-camera faa faa-pulse"></i>
<i class="far fa-camera faa faa-shake-x"></i>
<i class="fas fa-camera faa faa-tada"></i>
```

### B) On hover animations
Add `faa-animation-name` class to the icon and `faa-parent` class to any ancestor element. Hover over to start animation.
```html
<div class="faa-parent">
    <i class="fas fa-camera faa-bounce"></i>
</div>

<div class="faa-parent">
    
    <!--ICON 1-->
    <div class="some-class">
        <i class="fas fa-camera faa-bounce"></i>
    </div>
    
    <!--ICON 2-->
    <i class="fas fa-angle-double-right faa-slide-right"></i>
 
</div>
```

### Available animations:
* `faa-bounce`
* `faa-burst`
* `faa-falling`
* `faa-flash`
* `faa-flip-x`
* `faa-flip-y`
* `faa-float`
* `faa-pulse`
* `faa-ring`
* `faa-rubber-band`
* `faa-slide-left`
* `faa-slide-right`
* `faa-shake-x`
* `faa-shake-y`
* `faa-swing`
* `faa-tada`

+ Default Font Awesome animations `fa-spin` and `fa-pulse`.


********************************************************************************
## Versioning
Font Awesome Animations will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered with the following format:
```<major>.<minor>.<patch>```


********************************************************************************
## Changelog
For last releases see detailed [CHANGELOG](https://github.com/the-muda-organization/font-awesome-animations/blob/master/CHANGELOG.md).


********************************************************************************
## Team
-  [Jakub Muda](https://github.com/jakubmuda)


********************************************************************************
## Code of conduct
We will behave ourselves if you behave yourselves. For more details see our
[CODE OF CONDUCT](https://github.com/the-muda-organization/font-awesome-animations/blob/master/CODE_OF_CONDUCT.md).


********************************************************************************
## Copyright and license
Code and documentation copyright 2017-2020 [The MUDA Organization](https://muda.pl).

Code released under the [MIT License](https://github.com/the-muda-organization/font-awesome-animations/blob/master/LICENSE).


********************************************************************************


