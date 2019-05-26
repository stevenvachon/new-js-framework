# new-js-framework
> No name yet

**Server First?** Meaning, configurable (template engine, routes, etc) from express.

Will use:
* [InfernoJS](https://github.com/trueadm/inferno) for Virtual DOM
* [handlebars-html-parser](https://github.com/stevenvachon/handlebars-html-parser) (and vdom compiler) for templates
* `::event="code"` (attributes) for adding event listeners via markup
* [Proxy](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy) ([polyfill?](https://github.com/GoogleChrome/proxy-polyfill)) for view models
* [Shadow DOM v1](http://w3c.github.io/webcomponents/spec/shadow/) and [Custom Elements v1](https://html.spec.whatwg.org/multipage/scripting.html#custom-elements)

May use:
* [Modella](https://github.com/modella/modella) or [Ento](https://github.com/rstacruz/ento) for models
* [gibon](https://github.com/tunnckoCore/gibon), [page.js](https://github.com/visionmedia/page.js) or [crossroads.js](https://github.com/millermedeiros/crossroads.js) for routing

Inspirations:
* [aurelia](http://aurelia.io)
* [bram](https://github.com/matthewp/bram)
* [react-redux](https://react-redux.js.org)
