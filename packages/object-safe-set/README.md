## just-safe-get

Part of a [library](../../../../) of zero-dependency npm modules that do just do one thing.  
Guilt-free utilities for every occasion.

[Try it now](http://anguscroll.com/just/just-safe-set)

```js
import set from 'just-safe-set';

const obj1 = {};
set(obj1, 'a.aa.aaa', 4}); // true
obj1; // {a: {aa: {aaa: 4}}}

const obj2 = {};
set(obj2, [a, aa, aaa], 4}); // true
obj2; // {a: {aa: {aaa: 4}}}

const obj3 = {a: {aa: {aaa: 2}}};
set(obj3, 'a.aa.aaa', 3); // true
obj3; // {a: {aa: {aaa: 3}}}

const obj4 = {a: {aa: {aaa: 2}}};
set(obj4, 'a.aa', {bbb: 7}); // true
obj4; // {a: {aa: {bbb: 7}}}
```
