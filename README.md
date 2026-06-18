# Jstn's CSS Reset
My personal CSS reset, hosted for quick access.
## How to use it
There are a few ways to use this file in your projects, listed below.
### CDN / URL
If you want a direct link to attach it somewhere immediately, you can use this URL that uses jsDelivr's CDN.</br>
This is useful for places like Codepen.io, etc.
```
https://cdn.jsdelivr.net/gh/jstnpr/jstn-css-reset/reset.min.css
```
Note, the `min` in `reset.min.css` tells jsDelivr to minify the file on the fly. If you want to link a non-minified version, simply remove this, as shown below
```html
https://cdn.jsdelivr.net/gh/jstnpr/jstn-css-reset/reset.css
```
*Note: If you are building a site, there are better methods that save on load speed*
### HTML Link
You can link it in your HTML file's `<head>` to be pulled with your other stylesheets
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jstnpr/jstn-css-reset/reset.min.css">
```
### Node.js / npm Install
If you're already using node.js, you can install the **un-minified** version using
```bash
npm install github:JstnPr/jstn-css-reset
```
Once installed, you can use it in a couple of ways, depending on your stack.
#### JavaScript Stack
You can import it at the top of your primary JavaScript file `eg. index.js` , so your bundler can package and minify it
```javascript
import 'jstn-css-reset/reset.css';
```
#### Local Compilation
If you use a static site generator like 11ty, or a preprocessor like Less, you can `@import` it directly into your stylesheets
```css
@import (inline) "node_modules/jstn-css-reset/reset.css";
```
From there, you can compile and minify it however you see fit, using your pipeline.
### Direct Download
If you want to have complete control over using the file, you can download the ZIP directly, below.</br></br>
[![Download ZIP](https://img.shields.io/badge/Download-ZIP-green?style=for-the-badge&logo=github)](https://github.com/JstnPr/jstn-css-reset/archive/refs/heads/main.zip)
## License
This project is open-source software licensed under the **MIT License**. You are completely free to use, modify, and distribute this CSS reset in personal and commercial applications.
