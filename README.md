systematize.scss: normalize styles across browsers
===

Like normalize.css, but with system fonts.

[![npm][npm-image]][npm-url] ![][size-image]

---

**This project is an SCSS version of normalize.css** (`7.0.0` at the time of this writing.)
They share the following functionality:

* Normalize styles across browsers
* Preserve useful browser defaults, rather than erasing them
* Correct bugs and common browser inconsistencies
* Improve usability with subtle changes

Additionally, systematize.scss aims to do the following:

* Default to system fonts, and better typography in general
* Be slightly more opinionated while retaining clear focus

**Installation**

    npm install --save systematize

**System Fonts**

| Font family name | Why
| --- | ---
| `-apple-system` | Apple
| `BlinkMacSystemFont` | Chromium for macOS
| `Segoe UI` | Windows
| `system-ui` | Generic font family
| `Roboto` | Android
| `Droid Sans` | Old Android
| `Helvetica Neue` | Old Apple
| `sans-serif` | Catch-all

Segoe UI comes before system-ui for [reasons][system-ui-reasons].

**Monospaced Fonts**

| Font family name | Why
| --- | ---
| `SFMono-Regular` | Apple
| `Ubuntu Mono` | Ubuntu
| `Consolas` | Windows
| `DejaVu Sans Mono` | Bitstream Vera Sans Mono (Linux)
| `Menlo` | Bitstream Vera Sans Mono (Apple)
| `monospace` | Generic font family

There is no Monaco because Menlo shipped with Mac OS X 10.6 Snow Leopard in 1917.

[npm-image]: https://img.shields.io/npm/v/systematize.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/systematize
[size-image]: https://img.shields.io/github/size/mvasilkov/systematize/systematize.min.css.svg?style=flat-square
[system-ui-reasons]: https://infinnie.github.io/blog/2017/systemui.html
