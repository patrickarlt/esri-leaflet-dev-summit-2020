<!-- .slide: data-background="./img/2020/devsummit/bg-1.png" -->

<h1 style="text-align: left; font-size: 80px; margin-top: -90px;"><b>JavaScript</b> and <b>CSS</b> <i>for Geographers</i></h1>
    <p style="text-align: left; font-size: 1.5em;">Patrick Arlt, Allison Davis & Nate Bedortha</p>
    <p style="text-align: left; font-size: 1.5em;">Slides: <a href="http://bit.ly/2T4zaKJ" style="font-family: monospace;">http://bit.ly/2PLJft4</a>

<aside class="notes">
(Allison, Nate, Pat)

@TODO verify names and slide link
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-4.png" -->

## This talk is all fundamentals.

<aside class="notes">
(Allison)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-1.png" -->

## First Some Notes

Lots of supplemental info in these slides.

Designed to help you keep learning beyond this talk.

Pretty much everything is a link.

Slides <a href="http://bit.ly/2T4zaKJ" style="font-family: monospace;">http://bit.ly/2PLJft4</a>

<aside class="notes">
(Allison)

@TODO review, check slide link
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-1.png" -->

## Web Development is Hard

You're more equipped than you think!

* Scripted with ArcPy?
* Scripted with Python?
* Configured an app?
* Used Arcade?
* Used Model Builder?

Don't Feel Overwhelmed!

<aside class="notes">
(Allison)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-4.png" -->

## HTML

* A basic HTML file
* Where does it go? Web Server https://gist.github.com/jgravois/5e73b56fa7756fd00b89
* Install Node > Terminal/Command Line/Windows Bash/Powershell > `npx http-server .`
* HTML CSS and JS all go in your web server

<aside class="notes">
(Allison)

@TODO make demo html (codepen/stack blizt), review slide, potentially split to more slides html demo/server/ect...
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-4.png" -->

## CSS

<aside class="notes">
(Nate)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### Where does CSS go?

* Inside a `<style>` tag.
  ```html
  <style>/* Put CSS here*/</style>
  ```
* Inside a `.css` file that is loaded with a `<link>` tag.
  ```html
  <link href="my-css-file.css" rel="stylesheet" type="text/css">
  ```
* In the `<head>` tag of your `.html` files.

<aside class="notes">
(Nate)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### What does CSS look like?

<pre style="font-size: 125%;"><code class="ss">html, body, #map {
  margin: 0;
  width: 100%;
  height: 100%;
}</code></pre>

<aside class="notes">
(Nate)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

## The "C" is for Cascading<p>

Styles _cascade_ into the final styles for the HTML elements that match their selectors.

* Browser and user styles
* <code>&lt;link rel="stylesheet"&gt;</code>
* <code>&lt;style&gt;</code> tags
* Style attributes <code>&lt;div style="..."&gt;</code>

<aside class="notes">
(Nate)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### CSS Specificity

When properties collide specificity determines which property wins.

1. Rules with `!important`
2. Inline styles `<div style="...">`
3. `<style>` and `<link>` tags
4. Selector specificity
   1. `#id-attribute` - &lt;div id="..."&gt;
   2. `.class-attribute` - &lt;div class="..."&gt;
   3. `div` - &lt;div&gt;

<aside class="notes">
(Nate)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### Lets inspect some CSS

Right click on something you want to change click "Inspect Element"

[Explore a Storymap](https://story.maps.arcgis.com/apps/Cascade/index.html?appid=46daf1304a0c4ad69a8935c7ed2ab692)

<aside class="notes">
(Nate)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-6.png" -->

## Lets Build an App!

<img src="app.png" alt="A Simple Mapping App" style="border: none; background: transparent; box-shadow: none;">

<aside class="notes">
(Nate)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/revage/edit?html,output">Block</a> vs <a href="http://jsbin.com/josuba/edit?html,output">Inline</a></h2>

<ul>
  <li><a href="http://www.impressivewebs.com/difference-block-inline-css/">The Difference Between “Block” and “Inline”</a></li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements">Block-level elements</a></li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements">Inline elements</a></li>
  <li><a href="http://learnlayout.com/display.html">Learn CSS Layout: the "display" property</a></li>
</ul>

<aside class="notes">
(Nate)

@TODO review, clone demos to new URLs, review link resources
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/ficatu/edit?html,output">Units</h2>

<ul>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/length">Full unit reference</a></li>
  <li><a href="https://css-tricks.com/the-lengths-of-css/">The Lengths of CSS</a></li>
  <li><a href="http://www.quirksmode.org/css/units-values/">Unit and Values - QuirksMode</a></li>
</ul>

<aside class="notes">
(Nate)

@TODO review, clone demos to new URLs, review link resources
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/livofev/8/edit?html,output">Flexbox</a></h2>

<ul>
  <li><a href="http://flexboxfroggy.com/">Flexbox Froggy</a></li>
  <li><a href="https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties">A Visual Guide to CSS3 Flexbox Properties</a></li>
  <li><a href="http://learnlayout.com/flexbox.html">Learn CSS Layout: flexbox</a></li>
  <li><a href="http://caniuse.com/#feat=flexbox">Can I Use: flexbox</a></li>
  <li><a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">A Complete Guide to Flexbox</a></li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes">Using CSS flexible boxes</a></li>
</ul>

<aside class="notes">
(Nate)

@TODO review, clone demos to new URLs, review link resources
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/joziniv/edit?html,output">CSS Grid</a></h2>

<ul>
  <li><a href="http://cssgridgarden.com/">Grid Garden</a></li>
  <li><a href="https://css-tricks.com/snippets/css/complete-guide-grid/">A Complete Guide to Grid</a></li>
    <li><a href="https://gridbyexample.com/">Grid by Example</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector/How_to/Examine_grid_layouts">Debugging Grid Layouts</a></li>
    <li><a href="https://labs.jensimmons.com/">Intro to CSS Grid: Jen Simmons</a></li>

</ul>

<p><a href="http://jsbin.com/zuwarus/edit?html,output">Bonus Demo: CSS 
Grid Template Areas</a></p>

<aside class="notes">
(Nate)

@TODO review, clone demos to new URLs, review link resources
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/gibuhe/edit?html,output">Media Queries and Responsive Design</a></h2>

<ul>
  <li><a href="http://mediaqueri.es/">Responsive design gallery</a></li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries">Using media queries</a></li>
  <li><a href="https://css-tricks.com/snippets/css/media-queries-for-standard-devices/">Media Queries for Standard Devices</a></li>
  <li><a href="http://learnlayout.com/media-queries.html">Learn CSS Layout: media queries</a></li>
</ul>

<aside class="notes">
(Nate)

@TODO review, clone demos to new URLs, review link resources
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/gerexud/3/edit">Typography (Choosing Fonts)</a></h2>

<ul>
  <li><a href="https://www.google.com/fonts">Google Fonts</a></li>
  <li><a href="http://femmebot.github.io/google-type/">Google Web Fonts Typographic Project</a></li>
  <li><a href="http://fontpair.co/">Font Pair</a></li>
  <li><a href="http://www.labnol.org/internet/best-google-font-combinations/28987/">Font tool roundup</a></li>
</ul>

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/dugapa/7/edit">Typography (Sizing Type)</a></h2>

<ul>
  <li><a href="http://type-scale.com/">TypeScale</a></li>
  <li><a href="http://typecast.com/blog/a-more-modern-scale-for-web-typography">A More Modern Scale for Web Typography</a></li>
</ul>

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/jafeza/6/edit?html,output">Adding Color</a></h2>

<ul>
  <li><a href="https://flatuicolors.com/">Flat UI Colors</a></li>
  <li><a href="http://esri.github.io/calcite-web/documentation/color/">Calcite Web Colors</a></li>
  <li><a href="http://jxnblk.com/colorable/demos/matrix/">Color Pairing Matrix</a></li>
  <li><a href="https://color.adobe.com/create/color-wheel/">Adobe Kuler</a></li>
  <li><a href="http://www.colourlovers.com/palettes">Color Lovers</a></li>
</ul>

<aside class="notes">
(Nate)

@TODO condense to 1 slide, new combined demo, review link resources
</aside>

---
<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

<h2><a href="http://jsbin.com/babiwa/4/edit?html,output">Positioning</a></h2>

<ul>
  <li><a href="http://learnlayout.com/position.html">Learn CSS Layout: position</a></li>
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/position">position</a></li>
</ul>

<aside class="notes">
(Nate)

@TODO review, clone demos to new URLs, review link resources
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

## JavaScript

<aside class="notes">
(Allison)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### Where does JavaScript go?

* Inside a `<script>` tag.
  ```html
  <script>/* Put JS here*/</script>
  ```
* Inside a `.js` file.
  ```html
  <script src="app.js"></script>
  ```
* In your browsers DevTools

<aside class="notes">
(Allison)

@TODO review
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### [Variables](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var), [arithmetic](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators), [comparison](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators) & [logic](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators)

```js
var dog;
let nifty;
const notGonnaChange;

> undefined

var dogName = 'spot';
var age = 21;
var canBark = true;
// value type is **not** explicitly declared

```

```js
(age / 7) // 3

5 + 5 // 10

3 - 2 // 1

3 * 2 // 6

12 % 5 // 2 (modulus)

age++ // 22

age-- // 20

'high' + 'five' // 'highfive'

```

```js
3 === 3   // true
3 === '3' // false

'dog' != 'cat' // true

3 > 2 // true
3 >= 2 // true

// logical 'and'
true && anotherTruthy
> true

// 'or'
true || somethingFalsy
> true

// 'not'
!somethingTruthy
> false
```

<aside class="notes">
(Allison)

@TODO condense to 1 slide
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

## [functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

```js
function dogYears(age) {
  return age * 7;
}

dogYears(3);
> 21
```

```js
age => {
  return age * 7
}

age => age * 7
// these are the same!
```

<aside class="notes">
(Allison)

@TODO review
</aside>

---

## [Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) and [objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

```js
var dogs = ['Spot', 'Lassie'];

dogs[0] // 'Spot'

dogs.push('Fido');

dogs.length // 3

dogs.forEach(dog => {
  console.log(dog);
});
> undefined

dogs.map(dog => dog.toUpperCase());
> ['SPOT', 'LASSIE', 'FIDO']
```


```js
let dog = {
  age: 7,
  canBark: true,
  _ssshhh: 'top secret',
  ageInDogYears: function(age) {
    return age * 7;
  }
}

> Object {age: 7, canBark: true, _ssshhh: 'top secret', ageInDogYears: ageInDogYears() }

dog.ageInDogYears(dog.age);
> 49
```

<aside class="notes">
(Allison)

@TODO condense to 1 slide
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-4.png" -->

## JavaScript Patterns

<aside class="notes">
Pat
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### JavaScript is _Asynchronous_

* JavaScript is _single threaded_
* Runs one function in its entirety
* Then run the next function
* This is the "Event Loop"
* "Callback functions" define thing that happen *later*

[Event Loop and Callbacks Demo](https://codepen.io/patrickarlt/pen/eYNGjVJ?editors=0010)

<aside class="notes">
Pat
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### Promises

```js
function processResponse (response) {
  return response.json();
}

function doSomethingWithUser (user) {
  console.log(user); // prints a bunch of user info
}

function anyErrors (error) {
  console.error('what have you done!', error);
}

let user = fetch('https://randomuser.me/api/')
  .then(processResponse)
  .then(doSomethingWithUser)
  .catch(anyErrors);
```

Promises represent values that will be set in the future.

i.e. _I `Promise` to be a useful value in the future._

[Demo](https://codepen.io/patrickarlt/pen/XWbeBEj?editors=0010)

<aside class="notes">
(Pat)
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### The [DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model) and HTML

JavaScript can interact with your HTML. The HTML on your page is represented by the DOM (**D**ocument **O**bject **M**odel).

* Select HTML elements
* Listen for events & user interactions
* Change HTML elements 

[Demo](https://stackblitz.com/edit/js-8kewfg)

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### [JavaScript Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)

```
import { something } from 'some-file.js';
```

The future! You will encounter this more often.

[Demo](https://stackblitz.com/edit/js-jczbky)

<aside class="notes">
(Pat)
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### AMD Modules (JS API)

```
require([
  "esri/Map",
  "esri/views/MapView",
], function (Map, MapView) {
  // Map and MapView have been loaded!
});
```

`require` is a fancy way of adding `<script>` tags to load code on demand.

[Demo](https://codepen.io/patrickarlt/pen/PoqJBrg)

<aside class="notes">
(Pat)
</aside>

---

### <a href="https://jsbin.com/xuxavejuqe/edit?html,js,output">Lets finish our app</a>

~120 lines of CSS, ~30 lines of JS.

<aside class="notes">
(Pat)
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

### A more complex app

[Chaining Promises JS API Sample](https://developers.arcgis.com/javascript/latest/sample-code/sandbox/index.html?sample=chaining-promises)

<aside class="notes">
(Pat)
</aside>

---

## Tools & Frameworks

<aside class="notes">
(Pat)
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

## Don't jump into tools

* The JS API is MORE then enough for simple mapping apps 
* Add tools when you **KNOW** you will benefit from using them
* Too many tools === Lots of complexity to manage
* Don't touch tools until you feel limited

<aside class="notes">
(Pat)
</aside>

---

## Types of tools

* Modules - Formats for splitting up and sharing code
* Compilers - Transform code often adding extra features
* Bundlers - Combine modules and other assets
* Frameworks - Architecture and structure for large apps/teams

<aside class="notes">
(Pat)
</aside>

---

## Examples of tools

* Modules - *JS Modules*, *AMD*, CommonJS, CSS Modules
* Compilers - Babel, TypeScript, SASS, LESS
* Bundlers - WebPack, Parcel, Rollup
* Frameworks - React, Angular, Vue, Ember, Dojo, Tailwind, Bootstrap

<aside class="notes">
(Pat)
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

## Node JS and NPM

* [Node JS](https://nodejs.org/en/) - Run JavaScript on a server or desktop. Build web servers, APIs and CLI tools.
* [NPM](https://www.npmjs.com/) - Package manager and distribution system for JS code. Analogous to Pip or Conda in Python.

[Learn Node JS at NodeSchool](https://nodeschool.io/)

<aside class="notes">
(Pat)
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-2.png" -->

## Development tools

* Set up your local dev environment: [Do I have a web server running?](https://gist.github.com/jgravois/5e73b56fa7756fd00b89)
* Prototype with [CodePen](https://codepen.io), [JSBin](https://jsbin.com) or [StackBlitz](https://stackblitz.com/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools/javascript/)
* [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools)
* [ArcGIS JS CLI](https://github.com/Esri/arcgis-js-cli)

<aside class="notes">
(Pat)
</aside>

---

## Keep learning

* [ArcGIS Developer Tutorials](https://developers.arcgis.com/labs/?product=JavaScript&topic=any)
* [MDN: Learn web development](https://developer.mozilla.org/en-US/docs/Learn)
* [CSS Tricks Beginner Guide](https://css-tricks.com/guides/beginner/)
* [Eloquent JavaScript](http://eloquentjavascript.net/)
* [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)
* [JavaScript 30](https://javascript30.com/)
* [NodeSchool](https://nodeschool.io/)
* [Command Line Power User](https://commandlinepoweruser.com/)
* [Front End Handbook](https://frontendmasters.com/books/front-end-handbook/2018/)

<aside class="notes">
(Pat)
</aside>

---

<!-- .slide: data-background="./img/2020/devsummit/bg-rating.png" -->


<br><br><br><br><br><br><br><br><br><br><br><br>

Slides at <a href="http://bit.ly/2T4zaKJ" style="font-family: monospace;">http://bit.ly/2PLJft4</a>

<aside class="notes">
(Pat)

@TODO review, check slide link
</aside>
