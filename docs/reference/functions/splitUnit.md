---
layout: default
---

<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

<h1 id="function-splitunit">Function splitUnit <a href="#function-splitunit" title="Permalink">#</a></h1>

Split a unit in an array of units whose sum is equal to the original unit.


<h2 id="syntax">Syntax <a href="#syntax" title="Permalink">#</a></h2>

```js
splitUnit(unit: Unit, parts: Array.<Unit>)
```

<h3 id="parameters">Parameters <a href="#parameters" title="Permalink">#</a></h3>

Parameter | Type | Description
--------- | ---- | -----------
`parts` | Array | An array of strings or valueless units.

<h3 id="returns">Returns <a href="#returns" title="Permalink">#</a></h3>

Type | Description
---- | -----------
Array | An array of units.


<h2 id="examples">Examples <a href="#examples" title="Permalink">#</a></h2>

```js
math.splitUnit(new Unit(1, 'm'), ['feet', 'inch']);
// [ 3 feet, 3.3700787401575 inch ]
```


<h2 id="see-also">See also <a href="#see-also" title="Permalink">#</a></h2>

[unit](unit.html)