angular-chroma
===================================

Simple wrapper of [chroma-js](https://github.com/gka/chroma.js) to use chroma-js in angular.

# Installation

`bower install --save angular-chroma`

# Usage

1. include in your app dependencies Chroma

```
angular.module('YourApp',[
	'chroma.angularChroma'
])
```

2. then you can use it in your angular modules/controllers/services/directives

```
var scale=chroma.chroma.scale(['black','white']).domain([0,100],10);
scale(10).hex();
```

