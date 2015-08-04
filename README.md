Sublime Text Editor 3 - JavaScript Snippets
==================================

A collection of javascript snippets can be used in sublime text as a plugin



## Install ##

### Mac OS X ###

```Shell
git clone git@github.com:leftstick/sublime-javascript-snippets-plugin.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/sublime-javascript-snippets
```

### Linux ###

```Shell
git clone git@github.com:leftstick/sublime-javascript-snippets-plugin.git ~/.config/sublime-text-3/Packages/sublime-javascript-snippets
```

### Windows ###

#### Git hash ####

```Shell
git clone git@github.com:leftstick/sublime-javascript-snippets-plugin.git ~/AppData/Roaming/Sublime\ Text\ 3/Packages/sublime-javascript-snippets
```

## Snippet description ###

### [ars] Angular $rootScope

```javascript
$rootScope
```

### [ato] Angular $timeout expression

```javascript
$timeout(function(){
    ${2://body...}
}, ${1:0});
```

### [cd] console.dir

```javascript
console.dir(${1:obj});
```

### [ce] console.error

```javascript
console.error(${1:error});
```

### [cl] console.log

```javascript
console.log(${1:msg});
```

### [ct] console.trace

```javascript
console.trace(${1:error});
```

### [afn] Anoynmous Function

```javascript
function() {
    ${0:// body...}
}
```

### [ii] Immediately-invoked function expression

```javascript
(function() {
	${0: // body...}
}());
```

### [me] module.exports

```javascript
module.exports = ${1};
```

### [pe] process.exit

```javascript
process.exit();
```

### [proto] Prototype

```javascript
${1:ClassName}.prototype.${2:methodName} = function(${3}) {
    ${0:// body...}
};
```

### [req] require

```javascript
require('${0:package}');
```

### [def] Requirejs define module

```javascript
define([${1}], function(${2}){
    ${3://body...}
});
```

### [rmd] Requirejs style module definition

```javascript
(function() {
	define([${1}], function(${2}){
        ${3://body...}
    });
}());
```

### [sti] setInterval

```javascript
setInterval(function() {
    ${2:// body...}
}, ${1:millis});
```

### [sto] setTimeout

```javascript
setTimeout(function() {
    ${2:// body...}
}, ${1:millis});
```

### [us] use strict

```javascript
'use strict';
```


## LICENSE ##

[MIT License](https://raw.githubusercontent.com/leftstick/sublime-javascript-snippets-plugin/master/LICENSE)
