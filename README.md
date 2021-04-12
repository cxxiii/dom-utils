# dom-utils (WIP)

This is a small library of utility functions for interacting with the DOM in a quicker and less verbose manner.

## Examples

```javascript
hide(qA('main :not(.content)'));
// Hide everything in a main element that doesn't have the class content
```

```javascript
remove(id("popup"))
// remove an element with the id of popup from the DOM
remove(qA(".popups"))
// Works when selecting multiple elements
```

```javascript
generate(4, el, ["section", "content"], q("main"))
// Create four section elements with a class of content and append to main
```
