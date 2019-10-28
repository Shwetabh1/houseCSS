Polyfills & Shims

#What are they? How are they Different?
"So while shims are used for covering up old sins, polyfills are used for bringing future enhancements back in time."

What is a polyfill and what is a shim?

Both are used for Cross Browser Compatibility.
A polyfill is a piece of code that implements the features that you expect the browser to support natively.

Polyfills usually emulate a newer API that provides fallback functionality to older browsers. Polyfills can also make a feature that different browsers implement differently work the same way in each browser.

example is the JSON library, which implements JSON.stringify and JSON.parse on older browsers that do not already support the global JSON object.

#Feature Detection.

Use tools like modernizer or other methods to achieve the same.

Let's create a polyfill.

filter method was introduced in ES5 so old browsers such as Internet Explorer don't support it.

The best way is to check for the feature and then add the method in the prototype.
if(typeof Array.prototype.filter !== "function") {
  Array.prototype.filter = function() {
    // implementation goes here
  };
}

A polyfill is a type of shim that retrofits legacy browsers with modern HTML5/CSS3 features usually using Javascript or Flash.
Polyfilling is really just a specialized version of shimming.

The generic version is shims:
Shims intercepts API calls and creates an abstract layer between the caller and the target. Typically shims are used for backward compability. For instance the es5-shim npm package will let you write ECMAScript 5 (ES5) syntax and not care if the browser is running ES5 or not. Take Date.now as an example. This is a new function in ES5 where the syntax in ES3 would be new Date().getTime(). If you use the es5-shim you can write Date.now and if the browser you’re running in supports ES5 it will just run. However, if the browser is running the ES3 engine es5-shim will intercept the call.

