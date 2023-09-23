<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# PHI

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [Golden ratio][phi].

<section class="intro">

The [golden ratio][phi] can be defined algebraically as

<!-- <equation class="equation" label="eq:golden_ratio" align="center" raw="\phi = \frac{1 + \sqrt{5}}{2}" alt="Golden ratio"> -->

```math
\phi = \frac{1 + \sqrt{5}}{2}
```

<!-- <div class="equation" align="center" data-raw-text="\phi = \frac{1 + \sqrt{5}}{2}" data-equation="eq:golden_ratio">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@5d87cc7cb2c58aeb732872f89562d2c89571cc8a/lib/node_modules/@stdlib/constants/float64/phi/docs/img/equation_golden_ratio.svg" alt="Golden ratio">
    <br>
</div> -->

<!-- </equation> -->

</section>

<!-- /.intro -->



<section class="usage">

## Usage

To use in Observable,

```javascript
PHI = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-phi@umd/browser.js' )
```
The previous example will load the latest bundled code from the umd branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/constants-float64-phi/tags). For example,

```javascript
PHI = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-phi@v0.1.0-umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var PHI = require( 'path/to/vendor/umd/constants-float64-phi/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-phi@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.PHI;
})();
</script>
```

#### PHI

The [golden ratio][phi-value].

```javascript
var bool = ( PHI === 1.618033988749895 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example using Fibonacci(?) -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-phi@umd/browser.js"></script>
<script type="text/javascript">
(function () {

console.log( PHI );
// => 1.618033988749895

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- C interface documentation. -->



<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float64-phi.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float64-phi

[test-image]: https://github.com/stdlib-js/constants-float64-phi/actions/workflows/test.yml/badge.svg?branch=v0.1.0
[test-url]: https://github.com/stdlib-js/constants-float64-phi/actions/workflows/test.yml?query=branch:v0.1.0

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float64-phi/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float64-phi?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float64-phi.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float64-phi/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-float64-phi/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-float64-phi/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-float64-phi/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-float64-phi/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-float64-phi/main/LICENSE

[phi]: https://en.wikipedia.org/wiki/Golden_ratio

[phi-value]: http://oeis.org/A001622

</section>

<!-- /.links -->
