(function(){'use strict';var p;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function u(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
var fa=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},ia=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=fa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ja;
if(typeof Object.setPrototypeOf=="function")ja=Object.setPrototypeOf;else{var ka;a:{var la={a:!0},ma={};try{ma.__proto__=la;ka=ma.a;break a}catch(a){}ka=!1}ja=ka?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var na=ja;
function v(a,b){a.prototype=fa(b.prototype);a.prototype.constructor=a;if(na)na(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function y(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function A(a){if(!(a instanceof Array)){a=y(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function oa(a){return pa(a,a)}
function pa(a,b){a.raw=b;Object.freeze&&(Object.freeze(a),Object.freeze(b));return a}
function qa(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ra=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)qa(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||ra});
function sa(){this.A=!1;this.u=null;this.i=void 0;this.h=1;this.o=this.H=0;this.P=this.j=null}
function ta(a){if(a.A)throw new TypeError("Generator is already running");a.A=!0}
sa.prototype.G=function(a){this.i=a};
function ua(a,b){a.j={exception:b,zd:!0};a.h=a.H||a.o}
sa.prototype.return=function(a){this.j={return:a};this.h=this.o};
sa.prototype.yield=function(a,b){this.h=b;return{value:a}};
sa.prototype.B=function(a){this.h=a};
function va(a,b,c){a.H=b;c!=void 0&&(a.o=c)}
function wa(a,b){a.h=b;a.H=0}
function xa(a){a.H=0;var b=a.j.exception;a.j=null;return b}
function ya(a){var b=a.P.splice(0)[0];(b=a.j=a.j||b)?b.zd?a.h=a.H||a.o:b.B!=void 0&&a.o<b.B?(a.h=b.B,a.j=null):a.h=a.o:a.h=0}
function za(a){this.h=new sa;this.i=a}
function Aa(a,b){ta(a.h);var c=a.h.u;if(c)return Ba(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ca(a)}
function Ba(a,b,c,d){try{var e=b.call(a.h.u,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.A=!1,e;var f=e.value}catch(g){return a.h.u=null,ua(a.h,g),Ca(a)}a.h.u=null;d.call(a.h,f);return Ca(a)}
function Ca(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.A=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ua(a.h,c)}a.h.A=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.zd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Da(a){this.next=function(b){ta(a.h);a.h.u?b=Ba(a,a.h.u.next,b,a.h.G):(a.h.G(b),b=Ca(a));return b};
this.throw=function(b){ta(a.h);a.h.u?b=Ba(a,a.h.u["throw"],b,a.h.G):(ua(a.h,b),b=Ca(a));return b};
this.return=function(b){return Aa(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ea(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function B(a){return Ea(new Da(new za(a)))}
function C(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("globalThis",function(a){return a||da});
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return ia});
u("Reflect.setPrototypeOf",function(a){return a?a:na?function(b,c){try{return na(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.X=0;this.bb=void 0;this.h=[];this.u=!1;var h=this.i();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.u()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.u=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.o(l)}}}this.h=null};
c.prototype.o=function(g){this.j(function(){throw g;})};
b.prototype.i=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.U),reject:g(this.j)}};
b.prototype.U=function(g){if(g===this)this.j(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.Z(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.P(g):this.o(g)}};
b.prototype.P=function(g){var h=void 0;try{h=g.then}catch(k){this.j(k);return}typeof h=="function"?this.ha(h,g):this.o(g)};
b.prototype.j=function(g){this.H(2,g)};
b.prototype.o=function(g){this.H(1,g)};
b.prototype.H=function(g,h){if(this.X!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.X);this.X=g;this.bb=h;this.X===2&&this.Y();this.A()};
b.prototype.Y=function(){var g=this;e(function(){if(g.G()){var h=da.console;typeof h!=="undefined"&&h.error(g.bb)}},1)};
b.prototype.G=function(){if(this.u)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.bb;return k(g)};
b.prototype.A=function(){if(this.h!=null){for(var g=0;g<this.h.length;++g)f.i(this.h[g]);this.h=null}};
var f=new c;b.prototype.Z=function(g){var h=this.i();g.kc(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.i();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,t){return typeof r=="function"?function(w){try{l(r(w))}catch(x){m(x)}}:t}
var l,m,n=new b(function(r,t){l=r;m=t});
this.kc(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.kc=function(g,h){function k(){switch(l.X){case 1:g(l.bb);break;case 2:h(l.bb);break;default:throw Error("Unexpected state: "+l.X);}}
var l=this;this.h==null?f.i(k):this.h.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=y(g),m=l.next();!m.done;m=l.next())d(m.value).kc(h,k)})};
b.all=function(g){var h=y(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(w){return function(x){r[w]=x;t--;t==0&&l(r)}}
var r=[],t=0;do r.push(void 0),t++,d(k.value).kc(n(r.length-1),m),k=h.next();while(!k.done)})};
return b});
u("Object.setPrototypeOf",function(a){return a||na});
u("Symbol.dispose",function(a){return a?a:Symbol("Symbol.dispose")});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=y(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!qa(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(m.get(k)!=2||m.get(l)!=3)return!1;m.delete(k);m.set(l,4);return!m.has(k)&&m.get(l)==4}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!qa(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&qa(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&qa(k,g)&&qa(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&qa(k,g)&&qa(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ea(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&qa(h[0],l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,entry:n}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=y(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(y([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||m.value[1]!="s")return!1;m=l.next();return m.done||m.value[0].x!=4||m.value[1]!="t"||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=h===0?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=y(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(y([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
function Fa(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.entries",function(a){return a?a:function(){return Fa(this,function(b,c){return[b,c]})}});
u("Array.prototype.keys",function(a){return a?a:function(){return Fa(this,function(b){return b})}});
function Ga(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
u("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)qa(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return Ga(this,b,"includes").indexOf(b,c||0)!==-1}});
u("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)qa(b,d)&&c.push([d,b[d]]);return c}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.MIN_SAFE_INTEGER",function(){return-9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
u("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
u("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
u("Array.prototype.values",function(a){return a?a:function(){return Fa(this,function(b,c){return c})}});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Ha=Ha||{},D=this||self;function E(a,b,c){a=a.split(".");c=c||D;for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Ka(a){var b=F("CLOSURE_FLAGS");a=b&&b[a];return a!=null?a:!1}
function F(a,b){a=a.split(".");b=b||D;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function La(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Ma(a){var b=La(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Oa(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Pa(a){return Object.prototype.hasOwnProperty.call(a,Qa)&&a[Qa]||(a[Qa]=++Ra)}
var Qa="closure_uid_"+(Math.random()*1E9>>>0),Ra=0;function Sa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ta(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ua(a,b,c){Ua=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Sa:Ta;return Ua.apply(null,arguments)}
function Va(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Ya(){return Date.now()}
function Za(a){return a}
function $a(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
;function ab(a,b){return(a=(new RegExp("[^#]*[?&]"+b+"=([^&#]*)")).exec(a))?a[1]:null}
function bb(a){var b=C.apply(1,arguments).filter(Boolean).join("&");if(!b)return a;var c=a.match(/[?&]adurl=/);return c?a.slice(0,c.index+1)+b+"&"+a.slice(c.index+1):a+(a.indexOf("?")<0?"?":"&")+b}
function cb(a,b){return b?"&"+a+"="+encodeURIComponent(b):""}
function db(a){var b=a.url;a=a.mi;this.h=b;this.j=a;this.i=(new Date).getTime()-17040672E5}
function eb(a){a=a.j;if(!a)return"";var b=cb("uap",a.platform)+cb("uapv",a.platformVersion)+cb("uafv",a.uaFullVersion)+cb("uaa",a.architecture)+cb("uam",a.model)+cb("uab",a.bitness);a.fullVersionList&&(b+="&uafvl="+encodeURIComponent(a.fullVersionList.map(function(c){return encodeURIComponent(c.brand)+";"+encodeURIComponent(c.version)}).join("|")));
a.wow64!=null&&(b+="&uaw="+Number(a.wow64));return b.slice(1)}
;function fb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,fb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
$a(fb,Error);fb.prototype.name="CustomError";var gb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};/*

 Copyright Google LLC
 SPDX-License-Identifier: Apache-2.0
*/
var hb=globalThis.trustedTypes,ib;function jb(){var a=null;if(!hb)return a;try{var b=function(c){return c};
a=hb.createPolicy("goog#html",{createHTML:b,createScript:b,createScriptURL:b})}catch(c){}return a}
function kb(){ib===void 0&&(ib=jb());return ib}
;function lb(a){this.h=a}
lb.prototype.toString=function(){return this.h+""};
function nb(a){var b=kb();a=b?b.createScriptURL(a):a;return new lb(a)}
function ob(a){if(a instanceof lb)return a.h;throw Error("");}
;var pb=oa([""]),qb=pa(["\x00"],["\\0"]),rb=pa(["\n"],["\\n"]),sb=pa(["\x00"],["\\u0000"]);function tb(a){return a.toString().indexOf("`")===-1}
tb(function(a){return a(pb)})||tb(function(a){return a(qb)})||tb(function(a){return a(rb)})||tb(function(a){return a(sb)});function ub(a){this.h=a}
ub.prototype.toString=function(){return this.h};
var vb=new ub("about:invalid#zClosurez");function wb(a){this.Ge=a}
function xb(a){return new wb(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var yb=[xb("data"),xb("http"),xb("https"),xb("mailto"),xb("ftp"),new wb(function(a){return/^[^:]*([/?#]|$)/.test(a)})],zb=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function Ab(a){if(a instanceof ub)if(a instanceof ub)a=a.h;else throw Error("");else a=zb.test(a)?a:void 0;return a}
;function Bb(a,b){b=Ab(b);b!==void 0&&(a.href=b)}
;function Cb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;function Eb(a){this.h=a}
Eb.prototype.toString=function(){return this.h+""};function Fb(a){a=a===void 0?document:a;var b,c;a=(c=(b=a).querySelector)==null?void 0:c.call(b,"script[nonce]");return a==null?"":a.nonce||a.getAttribute("nonce")||""}
;function Gb(a){this.h=a}
Gb.prototype.toString=function(){return this.h+""};
function Hb(a){var b=kb();a=b?b.createScript(a):a;return new Gb(a)}
function Ib(a){if(a instanceof Gb)return a.h;throw Error("");}
;function Jb(a){var b=Fb(a.ownerDocument);b&&a.setAttribute("nonce",b)}
function Kb(a,b){a.src=ob(b);Jb(a)}
;function Lb(){this.h=Mb[0].toLowerCase()}
Lb.prototype.toString=function(){return this.h};function Nb(a){var b="true".toString(),c=[new Lb];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof Lb)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;var Ob="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Pb(a,b){if(b instanceof lb)a.href=ob(b).toString(),a.rel="stylesheet";else{if(Ob.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=Ab(b);b!==void 0&&(a.href=b,a.rel="stylesheet")}}
;var Qb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Rb=Array.prototype.forEach?function(a,b){Array.prototype.forEach.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)e in d&&b.call(void 0,d[e],e,a)},Tb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Ub=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Vb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Rb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Wb(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Xb(a,b){b=Qb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Yb(a){var b=a.length;if(b>0){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function Zb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ma(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
function $b(a,b){if(!Ma(a)||!Ma(b)||a.length!=b.length)return!1;for(var c=a.length,d=ac,e=0;e<c;e++)if(!d(a[e],b[e]))return!1;return!0}
function bc(a,b){return a>b?1:a<b?-1:0}
function ac(a,b){return a===b}
;function cc(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function dc(a){var b=F("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||D.$googDebugFname||b}catch(g){e="Not available",c=!0}b=ec(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,fc[c])c=fc[c];else{c=String(c);if(!fc[c]){var f=/function\s+([^\(]+)/m.exec(c);fc[c]=f?f[1]:"[Anonymous]"}c=fc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function ec(a,b){b||(b={});b[hc(a)]=!0;var c=a.stack||"",d=a.cause;d&&!b[hc(d)]&&(c+="\nCaused by: ",d.stack&&d.stack.indexOf(d.toString())==0||(c+=typeof d==="string"?d:d.message+"\n"),c+=ec(d,b));a=a.errors;if(Array.isArray(a)){d=1;var e;for(e=0;e<a.length&&!(d>4);e++)b[hc(a[e])]||(c+="\nInner error "+d++ +": ",a[e].stack&&a[e].stack.indexOf(a[e].toString())==0||(c+=typeof a[e]==="string"?a[e]:a[e].message+"\n"),c+=ec(a[e],b));e<a.length&&(c+="\n... "+(a.length-e)+" more inner errors")}return c}
function hc(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var fc={};function ic(a){return decodeURIComponent(a.replace(/\+/g," "))}
function jc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var kc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function lc(a){return a?decodeURI(a):a}
function mc(a){return lc(a.match(kc)[3]||null)}
function nc(a){return lc(a.match(kc)[5]||null)}
function oc(a){var b=a.match(kc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function pc(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function qc(a,b){if(a){a=a.split("&");for(var c=0;c<a.length;c++){var d=a[c].indexOf("="),e=null;if(d>=0){var f=a[c].substring(0,d);e=a[c].substring(d+1)}else f=a[c];b(f,e?ic(e):"")}}}
function rc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)rc(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function sc(a){var b=[],c;for(c in a)rc(c,a[c],b);return b.join("&")}
function tc(a,b){b=sc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function uc(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var vc=/#|$/,wc=/[?&]($|#)/;function xc(a,b){for(var c=a.search(vc),d=0,e,f=[];(e=uc(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(wc,"$1")}
;function yc(){try{var a,b;return!!((a=window)==null?0:(b=a.top)==null?0:b.location.href)&&!1}catch(c){return!0}}
;function zc(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function Ac(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ma(d)?Ac.apply(null,d):zc(d)}}
;function I(){this.ea=this.ea;this.H=this.H}
I.prototype.ea=!1;I.prototype.dispose=function(){this.ea||(this.ea=!0,this.ba())};
I.prototype[Symbol.dispose]=function(){this.dispose()};
function Bc(a,b){a.addOnDisposeCallback(Va(zc,b))}
I.prototype.addOnDisposeCallback=function(a,b){this.ea?b!==void 0?a.call(b):a():(this.H||(this.H=[]),b&&(a=a.bind(b)),this.H.push(a))};
I.prototype.ba=function(){if(this.H)for(;this.H.length;)this.H.shift()()};function Cc(){var a=Dc();a=a===void 0?"bevasrsg":a;return new Promise(function(b){var c=window===window.top?window:yc()?window:window.top,d=c[a],e;((e=d)==null?0:e.bevasrs)?b(new Ec(d.bevasrs)):(d||(d={},d=(d.nqfbel=[],d),c[a]=d),d.nqfbel.push(function(f){b(new Ec(f))}))})}
function Ec(a){I.call(this);var b=this;this.vm=a;this.i="keydown keypress keyup input focusin focusout select copy cut paste change click dblclick auxclick pointerover pointerdown pointerup pointermove pointerout dragenter dragleave drag dragend mouseover mousedown mouseup mousemove mouseout touchstart touchend touchmove wheel".split(" ");this.h=void 0;this.cd=this.vm.p;this.j=this.o.bind(this);this.addOnDisposeCallback(function(){return void Fc(b)})}
v(Ec,I);Ec.prototype.snapshot=function(a){return this.vm.s(Object.assign({},a.wb&&{c:a.wb},a.ed&&{s:a.ed},a.gd!==void 0&&{p:a.gd}))};
Ec.prototype.o=function(a){this.vm.e(a)};
function Fc(a){a.h!==void 0&&(a.i.forEach(function(b){var c;(c=a.h)==null||c.removeEventListener(b,a.j)}),a.h=void 0)}
;function Gc(a){var b=b===void 0?49:b;var c=[];Hc(a,Ic,6).forEach(function(d){Jc(d,2)<=b&&c.push(Jc(d,1))});
return c}
function Kc(a){var b=b===void 0?49:b;var c=[];Hc(a,Ic,6).forEach(function(d){Jc(d,2)>b&&c.push(Jc(d,1))});
return c}
;var Lc;function Mc(){I.apply(this,arguments);this.o=1;this[Lc]=this.dispose}
v(Mc,I);Mc.prototype.share=function(){if(this.ea)throw Error("E:AD");this.o++;return this};
Mc.prototype.dispose=function(){--this.o||I.prototype.dispose.call(this)};
Lc=Symbol.dispose;function Nc(a){return{fieldType:2,fieldName:a}}
function Oc(a){return{fieldType:3,fieldName:a}}
;function Pc(a){this.h=a;a.Jc("/client_streamz/bg/frs",Oc("mk"))}
Pc.prototype.record=function(a,b){this.h.record("/client_streamz/bg/frs",a,b)};
function Qc(a){this.h=a;a.Jc("/client_streamz/bg/wrl",Oc("mn"),Nc("ac"),Nc("sc"),Oc("rk"),Oc("mk"))}
Qc.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function Rc(a){this.h=a;a.Nb("/client_streamz/bg/ec",Oc("en"),Oc("mk"))}
Rc.prototype.kb=function(a,b){this.h.Kb("/client_streamz/bg/ec",a,b)};
function Sc(a){this.h=a;a.Jc("/client_streamz/bg/el",Oc("en"),Oc("mk"))}
Sc.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/el",a,b,c)};
function Tc(a){this.h=a;a.Nb("/client_streamz/bg/cec",Nc("ec"),Oc("mk"))}
Tc.prototype.kb=function(a,b){this.h.Kb("/client_streamz/bg/cec",a,b)};
function Uc(a){this.h=a;a.Nb("/client_streamz/bg/po/csc",Nc("cs"),Oc("mk"))}
Uc.prototype.kb=function(a,b){this.h.Kb("/client_streamz/bg/po/csc",a,b)};
function Vc(a){this.h=a;a.Nb("/client_streamz/bg/po/ctav",Oc("av"),Oc("mk"))}
Vc.prototype.kb=function(a,b){this.h.Kb("/client_streamz/bg/po/ctav",a,b)};
function Wc(a){this.h=a;a.Nb("/client_streamz/bg/po/cwsc",Oc("su"),Oc("mk"))}
Wc.prototype.kb=function(a,b){this.h.Kb("/client_streamz/bg/po/cwsc",a,b)};function Xc(a){D.setTimeout(function(){throw a;},0)}
;var Yc=Ka(610401301),Zc=Ka(513659523),$c=Ka(568333945);function ad(){var a=D.navigator;return a&&(a=a.userAgent)?a:""}
var bd,cd=D.navigator;bd=cd?cd.userAgentData||null:null;function dd(a){if(!Yc||!bd)return!1;for(var b=0;b<bd.brands.length;b++){var c=bd.brands[b].brand;if(c&&c.indexOf(a)!=-1)return!0}return!1}
function J(a){return ad().indexOf(a)!=-1}
;function ed(){return Yc?!!bd&&bd.brands.length>0:!1}
function fd(){return ed()?!1:J("Opera")}
function gd(){return J("Firefox")||J("FxiOS")}
function hd(){return ed()?dd("Chromium"):(J("Chrome")||J("CriOS"))&&!(ed()?0:J("Edge"))||J("Silk")}
;function id(){return Yc?!!bd&&!!bd.platform:!1}
function jd(){return J("iPhone")&&!J("iPod")&&!J("iPad")}
;function kd(a){kd[" "](a);return a}
kd[" "]=function(){};var ld=fd(),md=ed()?!1:J("Trident")||J("MSIE"),nd=J("Edge"),od=J("Gecko")&&!(ad().toLowerCase().indexOf("webkit")!=-1&&!J("Edge"))&&!(J("Trident")||J("MSIE"))&&!J("Edge"),pd=ad().toLowerCase().indexOf("webkit")!=-1&&!J("Edge");pd&&J("Mobile");id()||J("Macintosh");id()||J("Windows");(id()?bd.platform==="Linux":J("Linux"))||id()||J("CrOS");var qd=id()?bd.platform==="Android":J("Android");jd();J("iPad");J("iPod");jd()||J("iPad")||J("iPod");ad().toLowerCase().indexOf("kaios");gd();var rd=jd()||J("iPod"),sd=J("iPad");!J("Android")||hd()||gd()||fd()||J("Silk");hd();var td=J("Safari")&&!(hd()||(ed()?0:J("Coast"))||fd()||(ed()?0:J("Edge"))||(ed()?dd("Microsoft Edge"):J("Edg/"))||(ed()?dd("Opera"):J("OPR"))||gd()||J("Silk")||J("Android"))&&!(jd()||J("iPad")||J("iPod"));var ud={},vd=null;function wd(a,b){Ma(a);b===void 0&&(b=0);xd();b=ud[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function yd(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;zd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function zd(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),m=vd[l];if(m!=null)return m;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
xd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function xd(){if(!vd){vd={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));ud[c]=d;for(var e=0;e<d.length;e++){var f=d[e];vd[f]===void 0&&(vd[f]=e)}}}}
;var Ad=typeof Uint8Array!=="undefined",Bd=!md&&typeof btoa==="function",Cd=/[-_.]/g,Dd={"-":"+",_:"/",".":"="};function Ed(a){return Dd[a]||""}
var Fd={};function Gd(a,b){Hd(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
Gd.prototype.sizeBytes=function(){Hd(Fd);var a=this.h;if(!(a==null||Ad&&a!=null&&a instanceof Uint8Array))if(typeof a==="string")if(Bd){a=Cd.test(a)?a.replace(Cd,Ed):a;a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=yd(a);else La(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};
var Id;function Hd(a){if(a!==Fd)throw Error("illegal external caller");}
;var Jd=void 0;function Kd(a){a=Error(a);cc(a,"warning");return a}
function Ld(a,b){if(a!=null){var c;var d=(c=Jd)!=null?c:Jd={};c=d[a]||0;c>=b||(d[a]=c+1,a=Error(),cc(a,"incident"),Xc(a))}}
;var Md=typeof Symbol==="function"&&typeof Symbol()==="symbol";function Nd(a,b,c){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?(c===void 0?0:c)&&Symbol.for&&a?Symbol.for(a):a!=null?Symbol(a):Symbol():b}
var Od=Nd("jas",void 0,!0),Pd=Nd(void 0,"1oa"),Qd=Nd(void 0,Symbol()),Rd=Nd(void 0,"0ub"),Sd=Nd(void 0,"0ubs"),Td=Nd(void 0,"0actk"),Ud=Nd("m_m","Vh",!0),Vd=Nd(void 0,"vps"),Wd=Nd();Math.max.apply(Math,A(Object.values({nh:1,mh:2,lh:4,qh:8,sh:16,oh:32,Of:64,jh:128,Tf:256,rh:512,Uf:1024,kh:2048,ph:4096})));var Xd={Fe:{value:0,configurable:!0,writable:!0,enumerable:!1}},Yd=Object.defineProperties,K=Md?Od:"Fe",Zd,$d=[];ae($d,7);Zd=Object.freeze($d);function be(a,b){Md||K in a||Yd(a,Xd);a[K]|=b}
function ae(a,b){Md||K in a||Yd(a,Xd);a[K]=b}
;function ce(){return typeof BigInt==="function"}
;var de={};function ee(a,b){if(b===void 0){if(b=a.h!==fe)b=!!(2&(a.F[K]|0));return b}return!!(2&b)&&a.h!==fe}
var fe={},ge=Object.freeze({}),he={};function ie(a){a.Qh=!0;return a}
;var je=ie(function(a){return typeof a==="number"}),ke=ie(function(a){return typeof a==="string"}),le=ie(function(a){return typeof a==="boolean"});
function me(){var a=ne;return ie(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
var oe=ie(function(a){return a!=null&&typeof a==="object"&&typeof a.then==="function"});var pe=typeof D.BigInt==="function"&&typeof D.BigInt(0)==="bigint";function qe(a){var b=a;if(ke(b)){if(!/^\s*(?:-?[1-9]\d*|0)?\s*$/.test(b))throw Error(String(b));}else if(je(b)&&!Number.isSafeInteger(b))throw Error(String(b));return pe?BigInt(a):a=le(a)?a?"1":"0":ke(a)?a.trim()||"0":String(a)}
var we=ie(function(a){return pe?a>=re&&a<=se:a[0]==="-"?te(a,ue):te(a,ve)}),ue=Number.MIN_SAFE_INTEGER.toString(),re=pe?BigInt(Number.MIN_SAFE_INTEGER):void 0,ve=Number.MAX_SAFE_INTEGER.toString(),se=pe?BigInt(Number.MAX_SAFE_INTEGER):void 0;
function te(a,b){if(a.length>b.length)return!1;if(a.length<b.length||a===b)return!0;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(d>e)return!1;if(d<e)return!0}}
;var xe=0,ye=0;function ze(a){var b=a>>>0;xe=b;ye=(a-b)/4294967296>>>0}
function Ae(a){if(a<0){ze(0-a);var b=y(Be(xe,ye));a=b.next().value;b=b.next().value;xe=a>>>0;ye=b>>>0}else ze(a)}
function Ce(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else ce()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=a/1E7>>>0,a%=1E7),c>=1E7&&(b+=c/1E7>>>0,c%=1E7),c=b+De(c)+De(a));return c}
function De(a){a=String(a);return"0000000".slice(a.length)+a}
function Ee(){var a=xe,b=ye;b&2147483648?ce()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=y(Be(a,b)),a=b.next().value,b=b.next().value,a="-"+Ce(a,b)):a=Ce(a,b);return a}
function Be(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function Fe(a){return Array.prototype.slice.call(a)}
;var Ge=typeof BigInt==="function"?BigInt.asIntN:void 0,He=Number.isSafeInteger,Ie=Number.isFinite,Je=Math.trunc;function Ke(a){return a.displayName||a.name||"unknown type name"}
function Le(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+La(a)+": "+a);return a}
var Me=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function Ne(a){switch(typeof a){case "bigint":return!0;case "number":return Ie(a);case "string":return Me.test(a);default:return!1}}
function Oe(a){if(typeof a!=="number")throw Kd("int32");if(!Ie(a))throw Kd("int32");return a|0}
function Pe(a){return a==null?a:Oe(a)}
function Qe(a){if(a==null)return a;if(typeof a==="string"&&a)a=+a;else if(typeof a!=="number")return;return Ie(a)?a|0:void 0}
function Re(a){var b=0;b=b===void 0?0:b;if(!Ne(a))throw Kd("int64");var c=typeof a;switch(b){case 512:switch(c){case "string":return Se(a);case "bigint":return String(Ge(64,a));default:return Te(a)}case 1024:switch(c){case "string":return Ue(a);case "bigint":return qe(Ge(64,a));default:return Ve(a)}case 0:switch(c){case "string":return Se(a);case "bigint":return qe(Ge(64,a));default:return We(a)}default:return Cb(b,"Unknown format requested type for int64")}}
function Xe(a){return a==null?a:Re(a)}
function Ye(a){var b=a.length;return a[0]==="-"?b<20?!0:b===20&&Number(a.substring(0,7))>-922337:b<19?!0:b===19&&Number(a.substring(0,6))<922337}
function Ze(a){a.indexOf(".");if(Ye(a))return a;if(a.length<16)Ae(Number(a));else if(ce())a=BigInt(a),xe=Number(a&BigInt(4294967295))>>>0,ye=Number(a>>BigInt(32)&BigInt(4294967295));else{var b=+(a[0]==="-");ye=xe=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),ye*=1E6,xe=xe*1E6+d,xe>=4294967296&&(ye+=Math.trunc(xe/4294967296),ye>>>=0,xe>>>=0);b&&(b=y(Be(xe,ye)),a=b.next().value,b=b.next().value,xe=a,ye=b)}return Ee()}
function We(a){Ne(a);a=Je(a);if(!He(a)){Ae(a);var b=xe,c=ye;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);var d=c*4294967296+(b>>>0);b=Number.isSafeInteger(d)?d:Ce(b,c);a=typeof b==="number"?a?-b:b:a?"-"+b:b}return a}
function Te(a){Ne(a);a=Je(a);if(He(a))a=String(a);else{var b=String(a);Ye(b)?a=b:(Ae(a),a=Ee())}return a}
function Se(a){Ne(a);var b=Je(Number(a));if(He(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return Ze(a)}
function Ue(a){var b=Je(Number(a));if(He(b))return qe(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return ce()?qe(Ge(64,BigInt(a))):qe(Ze(a))}
function Ve(a){return He(a)?qe(We(a)):qe(Te(a))}
function $e(a){if(typeof a!=="string")throw Error();return a}
function af(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function bf(a){return a==null||typeof a==="string"?a:void 0}
function cf(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Ke(b)+" but got "+(a&&Ke(a.constructor)));}
function df(a,b,c){if(a!=null&&a[Ud]===de)return a;if(Array.isArray(a)){var d=a[K]|0;c=d|c&32|c&2;c!==d&&ae(a,c);return new b(a)}}
;var ef={};function ff(a){return a}
;var gf={fi:!0};function hf(a,b,c,d){var e=d!==void 0;d=!!d;var f=Za(Qd),g;!e&&Md&&f&&(g=a[f])&&g.Nh(jf);f=[];var h=a.length;g=4294967295;var k=!1,l=!!(b&64),m=l?b&128?0:-1:void 0;if(!(b&1)){var n=h&&a[h-1];n!=null&&typeof n==="object"&&n.constructor===Object?(h--,g=h):n=void 0;if(l&&!(b&128)&&!e){k=!0;var r;g=((r=kf)!=null?r:ff)(g-m,m,a,n)+m}}b=void 0;for(e=0;e<h;e++)if(r=a[e],r!=null&&(r=c(r,d))!=null)if(l&&e>=g){var t=e-m,w=void 0;((w=b)!=null?w:b={})[t]=r}else f[e]=r;if(n)for(var x in n)a=n[x],a!=null&&(a=c(a,
d))!=null&&(h=+x,e=void 0,l&&!Number.isNaN(h)&&(e=h+m)<g?f[e]=a:(h=void 0,((h=b)!=null?h:b={})[x]=a));b&&(k?f.push(b):f[g]=b);return f}
function lf(a){switch(typeof a){case "number":return Number.isFinite(a)?a:""+a;case "bigint":return we(a)?Number(a):""+a;case "boolean":return a?1:0;case "object":if(Array.isArray(a)){var b=a[K]|0;return a.length===0&&b&1?void 0:hf(a,b,lf)}if(a!=null&&a[Ud]===de)return mf(a);if(a instanceof Gd){b=a.h;if(b==null)a="";else if(typeof b==="string")a=b;else{if(Bd){for(var c="",d=0,e=b.length-10240;d<e;)c+=String.fromCharCode.apply(null,b.subarray(d,d+=10240));c+=String.fromCharCode.apply(null,d?b.subarray(d):
b);b=btoa(c)}else b=wd(b);a=a.h=b}return a}return}return a}
var kf;function nf(a,b){if(b){kf=b==null||b===ff||b[Vd]!==ef?ff:b;try{return mf(a)}finally{kf=void 0}}return mf(a)}
function mf(a){a=a.F;return hf(a,a[K]|0,lf)}
function jf(a,b){b<500||Ld(Sd,1)}
;function L(a,b,c){var d=d===void 0?0:d;if(a==null){var e=32;c?(a=[c],e|=128):a=[];b&&(e=e&-8380417|(b&1023)<<13)}else{if(!Array.isArray(a))throw Error("narr");e=a[K]|0;2048&e&&!(2&e)&&of();if(e&256)throw Error("farr");if(e&64)return d!==0||e&2048||ae(a,e|2048),a;if(c&&(e|=128,c!==a[0]))throw Error("mid");a:{c=a;e|=64;var f=c.length;if(f){var g=f-1,h=c[g];if(h!=null&&typeof h==="object"&&h.constructor===Object){b=e&128?0:-1;g-=b;if(g>=1024)throw Error("pvtlmt");for(var k in h)f=+k,f<g&&(c[f+b]=h[k],
delete h[k]);e=e&-8380417|(g&1023)<<13;break a}}if(b){k=Math.max(b,f-(e&128?0:-1));if(k>1024)throw Error("spvt");e=e&-8380417|(k&1023)<<13}}}e|=64;d===0&&(e|=2048);ae(a,e);return a}
function of(){Ld(Td,5)}
;function pf(a,b){if(typeof a!=="object")return a;if(Array.isArray(a)){var c=a[K]|0;a.length===0&&c&1?a=void 0:c&2||(!b||4096&c||16&c?a=qf(a,c,!1,b&&!(c&16)):(be(a,34),c&4&&Object.freeze(a)));return a}if(a!=null&&a[Ud]===de)return b=a.F,c=b[K]|0,ee(a,c)?a:qf(b,c);if(a instanceof Gd)return a}
function qf(a,b,c,d){d!=null||(d=!!(34&b));a=hf(a,b,pf,d);d=32;c&&(d|=2);b=b&8380609|d;ae(a,b);return a}
function rf(a){var b=a.F,c=b[K]|0;return ee(a,c)?new a.constructor(qf(b,c,!1)):a}
function sf(a){if(a.h!==fe)return!1;var b=a.F;b=qf(b,b[K]|0);be(b,2048);a.F=b;a.h=void 0;a.i=void 0;return!0}
function tf(a){if(!sf(a)&&ee(a,a.F[K]|0))throw Error();}
;var uf=qe(0),vf={};function wf(a,b,c,d){Object.isExtensible(a);b=xf(a.F,b,c);if(b!==null||d&&a.i!==fe)return b}
function xf(a,b,c,d){if(b===-1)return null;var e=b+(c?0:-1),f=a.length-1;if(!(f<1+(c?0:-1))){if(e>=f){var g=a[f];if(g!=null&&typeof g==="object"&&g.constructor===Object){c=g[b];var h=!0}else if(e===f)c=g;else return}else c=a[e];if(d&&c!=null){d=d(c);if(d==null)return d;if(!Object.is(d,c))return h?g[b]=d:a[e]=d,d}return c}}
function yf(a,b,c,d){tf(a);var e=a.F;zf(e,e[K]|0,b,c,d);return a}
function zf(a,b,c,d,e){var f=c+(e?0:-1),g=a.length-1;if(g>=1+(e?0:-1)&&f>=g){var h=a[g];if(h!=null&&typeof h==="object"&&h.constructor===Object)return h[c]=d,b}if(f<=g)return a[f]=d,b;if(d!==void 0){var k;g=((k=b)!=null?k:b=a[K]|0)>>13&1023||536870912;c>=g?d!=null&&(f={},a[g+(e?0:-1)]=(f[c]=d,f)):a[f]=d}return b}
function Af(a){return!!(2&a)&&!!(4&a)||!!(256&a)}
function Bf(a,b,c){tf(a);var d=a.F,e=d[K]|0;if(b==null)return zf(d,e,3),a;if(!Array.isArray(b))throw Kd();var f=b===Zd?7:b[K]|0,g=f,h=Af(f),k=h||Object.isFrozen(b);h||(f=0);k||(b=Fe(b),g=0,f=Cf(f,e),k=!1);f|=5;h=4&f?512&f?512:1024&f?1024:0:void 0;h=h!=null?h:0;for(var l=0;l<b.length;l++){var m=b[l],n=c(m,h);Object.is(m,n)||(k&&(b=Fe(b),g=0,f=Cf(f,e),k=!1),b[l]=n)}f!==g&&(k&&(b=Fe(b),f=Cf(f,e)),ae(b,f));zf(d,e,3,b);return a}
function Df(a,b,c,d){tf(a);a=a.F;var e=a[K]|0;if(d==null){var f=Ef(a);if(Ff(f,a,e,c)===b)f.set(c,0);else return}else{c.includes(b);f=Ef(a);var g=Ff(f,a,e,c);g!==b&&(g&&(e=zf(a,e,g)),f.set(c,b))}zf(a,e,b,d)}
function Ef(a){if(Md){var b;return(b=a[Pd])!=null?b:a[Pd]=new Map}if(Pd in a)return a[Pd];b=new Map;Object.defineProperty(a,Pd,{value:b});return b}
function Ff(a,b,c,d){var e=a.get(d);if(e!=null)return e;for(var f=e=0;f<d.length;f++){var g=d[f];xf(b,g)!=null&&(e!==0&&(c=zf(b,c,e)),e=g)}a.set(d,e);return e}
function Gf(a,b,c,d,e){var f=!1;a=xf(a,d,e,function(g){var h=df(g,c,b);f=h!==g&&h!=null;return h});
if(a!=null)return f&&ee(a),a}
function Hf(a,b,c,d){var e=a.F,f=e[K]|0;b=Gf(e,f,b,c,d);if(b==null)return b;f=e[K]|0;if(!ee(a,f)){var g=rf(b);g!==b&&(sf(a)&&(e=a.F,f=e[K]|0),b=g,zf(e,f,c,b,d))}return b}
function Hc(a,b,c){var d=void 0===ge?2:4;var e=a.F,f=e,g=e[K]|0;e=!1;var h=ee(a,g);d=h?1:d;e=!!e||d===3;var k=!h;(d===2||k)&&sf(a)&&(f=a.F,g=f[K]|0);a=xf(f,c);h=Array.isArray(a)?a:Zd;var l=h===Zd?7:h[K]|0;a=l;2&g&&(a|=2);var m=a|1;if(a=!(4&m)){var n=h,r=g,t=!!(2&m);t&&(r|=2);for(var w=!t,x=!0,z=0,G=0;z<n.length;z++){var H=df(n[z],b,r);if(H instanceof b){if(!t){var S=ee(H);w&&(w=!S);x&&(x=S)}n[G++]=H}}G<z&&(n.length=G);m|=4;m=x?m&-4097:m|4096;m=w?m|8:m&-9}m!==l&&(ae(h,m),2&m&&Object.freeze(h));if(k&&
!(8&m||!h.length&&(d===1||(d!==4?0:2&m||!(16&m)&&32&g)))){Af(m)&&(h=Fe(h),m=Cf(m,g),g=zf(f,g,c,h));b=h;k=m;for(l=0;l<b.length;l++)n=b[l],m=rf(n),n!==m&&(b[l]=m);k|=8;m=k=b.length?k|4096:k&-4097;ae(h,m)}b=h;k=h=m;d===1||(d!==4?0:2&h||!(16&h)&&32&g)?Af(h)||(h|=!b.length||a&&!(4096&h)||32&g&&!(4096&h||16&h)?2:256,h!==k&&ae(b,h),Object.freeze(b)):(d===2&&Af(h)&&(b=Fe(b),k=0,h=Cf(h,g),zf(f,g,c,b)),Af(h)||(e||(h|=16),h!==k&&ae(b,h)));return b}
function If(a,b,c,d,e){d!=null?cf(d,b):d=void 0;yf(a,c,d,e);d&&ee(d);return a}
function Jf(a,b,c,d){tf(a);var e=a.F,f=e[K]|0;if(d==null)return zf(e,f,c),a;if(!Array.isArray(d))throw Kd();for(var g=d===Zd?7:d[K]|0,h=g,k=Af(g),l=k||Object.isFrozen(d),m=!0,n=!0,r=0;r<d.length;r++){var t=d[r];cf(t,b);k||(t=ee(t),m&&(m=!t),n&&(n=t))}k||(g=m?13:5,g=n?g&-4097:g|4096);l&&g===h||(d=Fe(d),h=0,g=Cf(g,f));g!==h&&ae(d,g);zf(e,f,c,d);return a}
function Cf(a,b){return a=(2&b?a|2:a&-3)&-273}
function Jc(a,b,c){c=c===void 0?0:c;a=Qe(wf(a,b));return a!=null?a:c}
function Kf(a,b,c){c=c===void 0?uf:c;a=wf(a,b);b=typeof a;a=a==null?a:b==="bigint"?qe(Ge(64,a)):Ne(a)?b==="string"?Ue(a):Ve(a):void 0;return a!=null?a:c}
function Lf(a,b,c,d){c=c===void 0?"":c;var e;return(e=bf(wf(a,b,d)))!=null?e:c}
function Mf(a){var b=b===void 0?0:b;a=wf(a,1);a=a==null?a:Ie(a)?a|0:void 0;return a!=null?a:b}
function Nf(a,b,c){return yf(a,b,af(c))}
function Of(a,b,c){c=af(c);tf(a);a=a.F;zf(a,a[K]|0,b,c===""?void 0:c,he)}
function Pf(a,b,c){if(c!=null){if(!Ie(c))throw Kd("enum");c|=0}return yf(a,b,c)}
;function M(a,b,c){this.F=L(a,b,c)}
M.prototype.toJSON=function(){return nf(this)};
M.prototype.serialize=function(a){return JSON.stringify(nf(this,a))};
function Qf(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");be(b,32);return new a(b)}
M.prototype.clone=function(){var a=this.F;return new this.constructor(qf(a,a[K]|0,!1))};
M.prototype[Ud]=de;M.prototype.toString=function(){return this.F.toString()};function Rf(){var a=Sf;this.ctor=Tf;this.isRepeated=0;this.h=Hf;this.defaultValue=void 0;this.i=a.Me!=null?he:void 0}
Rf.prototype.register=function(){kd(this)};function Uf(a){return function(b){return Qf(a,b)}}
;function Vf(a){this.F=L(a)}
v(Vf,M);function Wf(a,b){return Bf(a,b,Oe)}
;function Xf(a){this.F=L(a)}
v(Xf,M);var Yf=[1,2,3];function Zf(a){this.F=L(a)}
v(Zf,M);var $f=[1,2,3];function ag(a){this.F=L(a)}
v(ag,M);function bg(a){this.F=L(a)}
v(bg,M);function cg(a){this.F=L(a)}
v(cg,M);function dg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function eg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var r=g,t=0;t<64;t+=4)r[t/4]=n[t]<<24|n[t+1]<<16|n[t+2]<<8|n[t+3];for(t=16;t<80;t++)n=r[t-3]^r[t-8]^r[t-14]^r[t-16],r[t]=(n<<1|n>>>31)&4294967295;n=e[0];var w=e[1],x=e[2],z=e[3],G=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var H=z^w&(x^z);var S=1518500249}else H=w^x^z,S=1859775393;else t<60?(H=w&x|z&(w|x),S=2400959708):(H=w^x^z,S=3395469782);H=((n<<5|n>>>27)&4294967295)+H+G+S+r[t]&4294967295;G=z;z=x;x=(w<<30|w>>>2)&4294967295;w=n;n=H}e[0]=e[0]+n&4294967295;e[1]=e[1]+w&4294967295;e[2]=
e[2]+x&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+G&4294967295}
function c(n,r){if(typeof n==="string"){n=unescape(encodeURIComponent(n));for(var t=[],w=0,x=n.length;w<x;++w)t.push(n.charCodeAt(w));n=t}r||(r=n.length);t=0;if(l==0)for(;t+64<r;)b(n.slice(t,t+64)),t+=64,m+=64;for(;t<r;)if(f[l++]=n[t++],m++,l==64)for(l=0,b(f);t+64<r;)b(n.slice(t,t+64)),t+=64,m+=64}
function d(){var n=[],r=m*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=r&255,r>>>=8;b(f);for(t=r=0;t<5;t++)for(var w=24;w>=0;w-=8)n[r++]=e[t]>>w&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,je:function(){for(var n=d(),r="",t=0;t<n.length;t++)r+="0123456789ABCDEF".charAt(Math.floor(n[t]/16))+"0123456789ABCDEF".charAt(n[t]%16);return r}}}
;function fg(a,b,c){var d=String(D.location.href);return d&&a&&b?[b,gg(dg(d),a,c||null)].join(" "):null}
function gg(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Rb(d,function(h){e.push(h)}),hg(e.join(" "));
var f=[],g=[];Rb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Rb(d,function(h){e.push(h)});
a=hg(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function hg(a){var b=eg();b.update(a);return b.je().toLowerCase()}
;function ig(a){this.h=a||{cookie:""}}
p=ig.prototype;p.isEnabled=function(){if(!D.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Xb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
p.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.cf;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Xb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
p.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=gb(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
p.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Xb:0,path:b,domain:c});return d};
p.Tb=function(){return jg(this).keys};
p.Wa=function(){return jg(this).values};
p.clear=function(){for(var a=jg(this).keys,b=a.length-1;b>=0;b--)this.remove(a[b])};
function jg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=gb(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var kg=new ig(typeof document=="undefined"?null:document);function lg(){var a=D.__SAPISID||D.__APISID||D.__3PSAPISID||D.__1PSAPISID||D.__OVERRIDE_SID;if(a)return!0;typeof document!=="undefined"&&(a=new ig(document),a=a.get("SAPISID")||a.get("APISID")||a.get("__Secure-3PAPISID")||a.get("__Secure-1PAPISID"));return!!a}
function mg(a,b,c,d){(a=D[a])||typeof document==="undefined"||(a=(new ig(document)).get(b));return a?fg(a,c,d):null}
function ng(a){var b=dg(String(D.location.href)),c=[];if(lg()){b=b.indexOf("https:")==0||b.indexOf("chrome-extension:")==0||b.indexOf("chrome-untrusted://new-tab-page")==0||b.indexOf("moz-extension:")==0;var d=b?D.__SAPISID:D.__APISID;d||typeof document==="undefined"||(d=new ig(document),d=d.get(b?"SAPISID":"APISID")||d.get("__Secure-3PAPISID"));(d=d?fg(d,b?"SAPISIDHASH":"APISIDHASH",a):null)&&c.push(d);b&&((b=mg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&c.push(b),(a=mg("__3PSAPISID",
"__Secure-3PAPISID","SAPISID3PHASH",a))&&c.push(a))}return c.length==0?null:c.join(" ")}
;function og(){}
og.prototype.compress=function(a){var b,c,d,e;return B(function(f){switch(f.h){case 1:return b=new CompressionStream("gzip"),c=(new Response(b.readable)).arrayBuffer(),d=b.writable.getWriter(),f.yield(d.write((new TextEncoder).encode(a)),2);case 2:return f.yield(d.close(),3);case 3:return e=Uint8Array,f.yield(c,4);case 4:return f.return(new e(f.i))}})};
og.prototype.isSupported=function(a){return a<1024?!1:typeof CompressionStream!=="undefined"};function pg(a){this.F=L(a)}
v(pg,M);function qg(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return Ya()};
this.i=this.h()}
qg.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
qg.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
qg.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
qg.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function rg(a){this.F=L(a)}
v(rg,M);function sg(a){this.F=L(a)}
v(sg,M);function tg(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
p=tg.prototype;p.clone=function(){return new tg(this.x,this.y)};
p.equals=function(a){return a instanceof tg&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
p.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
p.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
p.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
p.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function ug(a,b){this.width=a;this.height=b}
p=ug.prototype;p.clone=function(){return new ug(this.width,this.height)};
p.aspectRatio=function(){return this.width/this.height};
p.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
p.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
p.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
p.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function vg(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function wg(a){var b=[],c=0,d;for(d in a)b[c++]=a[d];return b}
function xg(a){var b=yg,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function zg(a){for(var b in a)return!1;return!0}
function Ag(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function Bg(a){return a!==null&&"privembed"in a?a.privembed:!1}
function Cg(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function Dg(a){var b={},c;for(c in a)b[c]=a[c];return b}
function Eg(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=Eg(a[c]);return b}
var Fg="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function Gg(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<Fg.length;f++)c=Fg[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function Hg(a,b){this.h=a===Ig&&b||""}
Hg.prototype.toString=function(){return this.h};
var Ig={};new Hg(Ig,"");"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function Jg(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function Kg(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function Lg(a){a&&a.parentNode&&a.parentNode.removeChild(a)}
function Mg(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Ng(a){this.F=L(a)}
v(Ng,M);Ng.prototype.qc=function(){return Mf(this)};function Og(a){this.F=L(a)}
v(Og,M);function Pg(a){this.F=L(a)}
v(Pg,M);function Qg(a){Jf(Rg,Og,1,a)}
var Sg=Uf(Pg);function Tg(a){this.F=L(a)}
v(Tg,M);var Ug=["platform","platformVersion","architecture","model","uaFullVersion"],Rg=new Pg,Vg=null;function Wg(a,b){b=b===void 0?Ug:b;if(!Vg){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));Qg((a.brands||[]).map(function(e){var f=new Og;f=Nf(f,1,e.brand);return Nf(f,2,e.version)}));
typeof a.mobile==="boolean"&&yf(Rg,2,Le(a.mobile));Vg=a.getHighEntropyValues(b)}var d=new Set(b);return Vg.then(function(e){var f=Rg.clone();d.has("platform")&&Nf(f,3,e.platform);d.has("platformVersion")&&Nf(f,4,e.platformVersion);d.has("architecture")&&Nf(f,5,e.architecture);d.has("model")&&Nf(f,6,e.model);d.has("uaFullVersion")&&Nf(f,7,e.uaFullVersion);return f.serialize()}).catch(function(){return Rg.serialize()})}
;function Xg(a){this.F=L(a)}
v(Xg,M);function Yg(a){return Pf(a,1,1)}
;function Zg(a){this.F=L(a,4)}
v(Zg,M);function $g(a){this.F=L(a,36)}
v($g,M);function ah(a){this.F=L(a,19)}
v(ah,M);ah.prototype.ac=function(a){return Pf(this,2,a)};function bh(a,b){this.Oa=b=b===void 0?!1:b;this.j=this.locale=null;this.i=0;this.isFinal=!1;this.h=new ah;Number.isInteger(a)&&this.h.ac(a);b||(this.locale=document.documentElement.getAttribute("lang"));ch(this,new Xg)}
bh.prototype.ac=function(a){this.h.ac(a);return this};
function ch(a,b){If(a.h,Xg,1,b);Mf(b)||Yg(b);a.Oa||(b=dh(a),Lf(b,5)||Nf(b,5,a.locale));a.j&&(b=dh(a),Hf(b,Pg,9)||If(b,Pg,9,a.j))}
function eh(a,b){a.i=b}
function fh(a){var b=b===void 0?Ug:b;var c=a.Oa?void 0:window;c?Wg(c,b).then(function(d){a.j=Sg(d!=null?d:"[]");d=dh(a);If(d,Pg,9,a.j);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function dh(a){a=Hf(a.h,Xg,1);var b=Hf(a,Tg,11);b||(b=new Tg,If(a,Tg,11,b));return b}
function gh(a,b,c,d,e,f,g){c=c===void 0?0:c;d=d===void 0?0:d;e=e===void 0?null:e;f=f===void 0?0:f;g=g===void 0?0:g;if(!a.Oa){var h=dh(a);var k=new Ng;k=Pf(k,1,a.i);k=yf(k,2,Le(a.isFinal));d=yf(k,3,Pe(d>0?d:void 0));d=yf(d,4,Pe(f>0?f:void 0));d=yf(d,5,Pe(g>0?g:void 0));f=d.F;g=f[K]|0;d=ee(d,g)?d:new d.constructor(qf(f,g,!0));If(h,Ng,10,d)}a=a.h.clone();h=Date.now().toString();a=yf(a,4,Xe(h));b=b.slice();b=Jf(a,$g,3,b);e&&(a=new rg,e=yf(a,13,Pe(e)),a=new sg,e=If(a,rg,2,e),a=new Zg,e=If(a,sg,1,e),e=
Pf(e,2,9),If(b,Zg,18,e));c&&yf(b,14,Xe(c));return b}
;var hh=function(){if(!D.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
D.addEventListener("test",c,b);D.removeEventListener("test",c,b)}catch(d){}return a}();function ih(a){this.h=this.i=this.j=a}
ih.prototype.reset=function(){this.h=this.i=this.j};
ih.prototype.getValue=function(){return this.i};function Sf(a){this.F=L(a,8)}
v(Sf,M);var jh=Uf(Sf);function Tf(a){this.F=L(a)}
v(Tf,M);var kh;kh=new Rf;function lh(a){I.call(this);var b=this;this.componentId="";this.h=[];this.Ra="";this.pageId=null;this.fb=this.ma=-1;this.G=this.experimentIds=null;this.A=this.o=0;this.U=null;this.Z=this.ha=0;this.Lb=1;this.timeoutMillis=0;this.xa=!1;this.logSource=a.logSource;this.yb=a.yb||function(){};
this.j=new bh(a.logSource,a.Oa);this.network=a.network||null;this.ob=a.ob||null;this.bufferSize=1E3;this.P=a.Af||null;this.sessionIndex=a.sessionIndex||null;this.Rb=a.Rb||!1;this.logger=null;this.withCredentials=!a.sd;this.Oa=a.Oa||!1;this.Y=!this.Oa&&!!window&&!!window.navigator&&window.navigator.sendBeacon!==void 0;this.Qa=typeof URLSearchParams!=="undefined"&&!!(new URL(mh())).searchParams&&!!(new URL(mh())).searchParams.set;var c=Yg(new Xg);ch(this.j,c);this.u=new ih(1E4);a=nh(this,a.od);this.i=
new qg(this.u.getValue(),a);this.Fa=new qg(6E5,a);this.Rb||this.Fa.start();this.Oa||(document.addEventListener("visibilitychange",function(){if(document.visibilityState==="hidden"){oh(b);var d;(d=b.U)==null||d.flush()}}),document.addEventListener("pagehide",function(){oh(b);
var d;(d=b.U)==null||d.flush()}))}
v(lh,I);function nh(a,b){return a.Qa?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
lh.prototype.ba=function(){oh(this);this.i.stop();this.Fa.stop();I.prototype.ba.call(this)};
function ph(a){a.P||(a.P=mh());try{return(new URL(a.P)).toString()}catch(b){return(new URL(a.P,window.location.origin)).toString()}}
function qh(a,b,c){a.U&&a.U.kb(b,c)}
lh.prototype.log=function(a){qh(this,2,1);if(this.Qa){a=a.clone();var b=this.Lb++;a=yf(a,21,Xe(b));this.componentId&&Nf(a,26,this.componentId);b=a;var c=wf(b,1);var d=d===void 0?!1:d;var e=typeof c;d=c==null?c:e==="bigint"?String(Ge(64,c)):Ne(c)?e==="string"?Se(c):d?Te(c):We(c):void 0;d==null&&(d=Date.now(),d=Number.isFinite(d)?d.toString():"0",yf(b,1,Xe(d)));d=wf(b,15);d!=null&&(typeof d==="bigint"?we(d)?d=Number(d):(d=Ge(64,d),d=we(d)?Number(d):String(d)):d=Ne(d)?typeof d==="number"?We(d):Se(d):
void 0);d==null&&yf(b,15,Xe((new Date).getTimezoneOffset()*60));this.experimentIds&&(d=this.experimentIds.clone(),If(b,pg,16,d));qh(this,1,1);b=this.h.length-this.bufferSize+1;b>0&&(this.h.splice(0,b),this.o+=b,qh(this,3,b));this.h.push(a);this.Rb||this.i.enabled||this.i.start()}};
lh.prototype.flush=function(a,b){var c=this;if(this.h.length===0)a&&a();else if(this.xa&&this.Y)this.j.i=3,rh(this);else{var d=Date.now();if(this.fb>d&&this.ma<d)b&&b("throttled");else{this.network&&(typeof this.network.qc==="function"?eh(this.j,this.network.qc()):this.j.i=0);var e=this.h.length,f=gh(this.j,this.h,this.o,this.A,this.ob,this.ha,this.Z),g=this.yb();if(g&&this.Ra===g)b&&b("stale-auth-token");else{this.h=[];this.i.enabled&&this.i.stop();this.o=0;d=f.serialize();var h;this.G&&this.G.isSupported(d.length)&&
(h=this.G.compress(d));var k=th(this,d,g),l=function(r){c.u.reset();c.i.setInterval(c.u.getValue());if(r){var t=null;try{var w=JSON.stringify(JSON.parse(r.replace(")]}'\n","")));t=jh(w)}catch(G){}if(t){r=Number(Kf(t,1,qe("-1")));r>0&&(c.ma=Date.now(),c.fb=c.ma+r);r=Za(Qd);var x;Md&&r&&((x=t.F[r])==null?void 0:x[175237375])!=null&&Ld(Rd,3);a:{var z=z===void 0?!1:z;if(Za(Wd)&&Za(Qd)&&void 0===Wd){x=t.F;r=x[Qd];if(!r)break a;if(r=r.gi)try{r(x,175237375,gf);break a}catch(G){Xc(G)}}z&&(z=t.F,(x=Za(Qd))&&
x in z&&(z=z[x])&&delete z[175237375])}z=kh.ctor?kh.h(t,kh.ctor,175237375,kh.i):kh.h(t,175237375,null,kh.i);if(z=z===null?void 0:z)z=Jc(z,1,-1),z!==-1&&(c.u=new ih(z<1?1:z),c.i.setInterval(c.u.getValue()))}}a&&a();c.A=0},m=function(r,t){var w=Hc(f,$g,3);
var x=Number(Kf(f,14)),z=c.u;z.h=Math.min(3E5,z.h*2);z.i=Math.min(3E5,z.h+Math.round(.1*(Math.random()-.5)*2*z.h));c.i.setInterval(c.u.getValue());r===401&&g&&(c.Ra=g);x&&(c.o+=x);t===void 0&&(t=c.isRetryable(r));t&&(c.h=w.concat(c.h),c.Rb||c.i.enabled||c.i.start());qh(c,7,1);b&&b("net-send-failed",r);++c.A},n=function(){c.network&&c.network.send(k,l,m)};
h?h.then(function(r){qh(c,5,e);k.Ec["Content-Encoding"]="gzip";k.Ec["Content-Type"]="application/binary";k.body=r;k.ce=2;n()},function(){qh(c,6,e);
n()}):n()}}}};
function th(a,b,c){c=c===void 0?null:c;var d=d===void 0?a.withCredentials:d;var e={},f=new URL(ph(a));c&&(e.Authorization=c);a.sessionIndex&&(e["X-Goog-AuthUser"]=a.sessionIndex,f.searchParams.set("authuser",a.sessionIndex));a.pageId&&(Object.defineProperty(e,"X-Goog-PageId",{value:a.pageId}),f.searchParams.set("pageId",a.pageId));return{url:f.toString(),body:b,ce:1,Ec:e,requestType:"POST",withCredentials:d,timeoutMillis:a.timeoutMillis}}
function oh(a){a.j.isFinal=!0;a.flush();a.j.isFinal=!1}
function rh(a){uh(a,function(b,c){b=new URL(b);b.searchParams.set("format","json");var d=!1;try{d=window.navigator.sendBeacon(b.toString(),c.serialize())}catch(e){}d||(a.Y=!1);return d})}
function uh(a,b){if(a.h.length!==0){var c=new URL(ph(a));c.searchParams.delete("format");var d=a.yb();d&&c.searchParams.set("auth",d);c.searchParams.set("authuser",a.sessionIndex||"0");for(d=0;d<10&&a.h.length;++d){var e=a.h.slice(0,32),f=gh(a.j,e,a.o,a.A,a.ob,a.ha,a.Z);if(!b(c.toString(),f)){++a.A;break}a.o=0;a.A=0;a.ha=0;a.Z=0;a.h=a.h.slice(e.length)}a.i.enabled&&a.i.stop()}}
lh.prototype.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function mh(){return"https://play.google.com/log?format=json&hasfast=true"}
;function vh(){this.Wd=typeof AbortController!=="undefined"}
vh.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,m,n,r,t;return B(function(w){switch(w.h){case 1:return f=(e=d.Wd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,va(w,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.Ec)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),w.yield(fetch(a.url,g),5);case 5:h=w.i;if(h.status!==200){(k=c)==null||k(h.status);w.B(3);break}if((l=b)==null){w.B(7);break}return w.yield(h.text(),8);case 8:l(w.i);case 7:case 3:w.P=[w.j];w.H=0;w.o=0;clearTimeout(f);ya(w);break;case 2:m=xa(w);switch((n=m)==null?void 0:n.name){case "AbortError":(r=c)==null||r(408);break;default:(t=c)==null||t(400)}w.B(3)}})};
vh.prototype.qc=function(){return 4};function wh(a,b){b=b===void 0?"0":b;I.call(this);this.logSource=a;this.sessionIndex=b;this.Va="https://play.google.com/log?format=json&hasfast=true";this.i=null;this.o=!1;this.network=null;this.componentId="";this.h=this.ob=null;this.j=!1;this.pageId=null;this.bufferSize=void 0}
v(wh,I);function xh(a,b){a.i=b;return a}
function yh(a,b){a.network=b;return a}
function zh(a,b){a.h=b}
function Ah(a){a.j=!0;return a}
wh.prototype.sd=function(){this.u=!0;return this};
function Bh(a){a.network||(a.network=new vh);var b=new lh({logSource:a.logSource,yb:a.yb?a.yb:ng,sessionIndex:a.sessionIndex,Af:a.Va,Oa:a.o,Rb:!1,sd:a.u,od:a.od,network:a.network});Bc(a,b);if(a.i){var c=a.i,d=dh(b.j);Nf(d,7,c)}b.G=new og;a.componentId&&(b.componentId=a.componentId);a.ob&&(b.ob=a.ob);a.pageId&&(b.pageId=a.pageId);a.h&&((d=a.h)?(b.experimentIds||(b.experimentIds=new pg),c=b.experimentIds,d=d.serialize(),Nf(c,4,d)):b.experimentIds&&yf(b.experimentIds,4));a.j&&(b.xa=b.Y);fh(b.j);a.bufferSize&&
(b.bufferSize=a.bufferSize);a.network.ac&&a.network.ac(a.logSource);a.network.pf&&a.network.pf(b);return b}
;function Ch(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;I.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new wh(a,"0"),a.componentId=b,Bc(this,a),c!==""&&(a.Va=c),d&&(a.o=!0),e&&xh(a,e),g&&yh(a,g),b=Bh(a));this.h=b}
v(Ch,I);
Ch.prototype.flush=function(a){var b=a||[];if(b.length){a=new cg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=new bg;f=Nf(f,1,e.i);var g=Dh(e);f=Bf(f,g,$e);g=[];var h=[];for(var k=y(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var m=e.o;for(var n=e.Nc(l)||[],r=[],t=0;t<n.length;t++){var w=n[t],x=w&&w.h;w=new Zf;switch(m){case 3:x=Number(x);Number.isFinite(x)&&Df(w,1,$f,Xe(x));break;case 2:x=Number(x);if(x!=null&&typeof x!=="number")throw Error("Value of float/double field must be a number, found "+typeof x+
": "+x);Df(w,2,$f,x)}r.push(w)}m=r;for(n=0;n<m.length;n++){r=m[n];t=new ag;r=If(t,Zf,2,r);t=l;w=[];x=Eh(e);for(var z=0;z<x.length;z++){var G=x[z],H=t[z],S=new Xf;switch(G){case 3:Df(S,1,Yf,af(String(H)));break;case 2:G=Number(H);Number.isFinite(G)&&Df(S,2,Yf,Pe(G));break;case 1:Df(S,3,Yf,Le(H==="true"))}w.push(S)}Jf(r,Xf,1,w);g.push(r)}}Jf(f,ag,4,g);c.push(f);e.clear()}Jf(a,bg,1,c);b=this.h;if(a instanceof $g)b.log(a);else try{var Z=new $g,mb=a.serialize();var Sb=Nf(Z,8,mb);b.log(Sb)}catch(Wa){qh(b,
4,1)}this.h.flush()}};function Fh(a){this.h=a}
;function Gh(a,b,c){this.i=a;this.o=b;this.fields=c||[];this.h=new Map}
function Eh(a){return a.fields.map(function(b){return b.fieldType})}
function Dh(a){return a.fields.map(function(b){return b.fieldName})}
p=Gh.prototype;p.Xd=function(a){var b=C.apply(1,arguments),c=this.Nc(b);c?c.push(new Fh(a)):this.Kd(a,b)};
p.Kd=function(a){var b=this.nd(C.apply(1,arguments));this.h.set(b,[new Fh(a)])};
p.Nc=function(){var a=this.nd(C.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
p.we=function(){var a=this.Nc(C.apply(0,arguments));return a&&a.length?a[0]:void 0};
p.clear=function(){this.h.clear()};
p.nd=function(){var a=C.apply(0,arguments);return a?a.join(","):"key"};function Hh(a,b){Gh.call(this,a,3,b)}
v(Hh,Gh);Hh.prototype.j=function(a){var b=C.apply(1,arguments),c=0,d=this.we(b);d&&(c=d.h);this.Kd(c+a,b)};function Ih(a,b){Gh.call(this,a,2,b)}
v(Ih,Gh);Ih.prototype.record=function(a){this.Xd(a,C.apply(1,arguments))};function Jh(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Jh.prototype.stopPropagation=function(){this.j=!0};
Jh.prototype.preventDefault=function(){this.defaultPrevented=!0};function Kh(a,b){Jh.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
$a(Kh,Jh);
Kh.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;b=a.relatedTarget;b||(c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement));this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==
void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=a.pointerType;this.state=a.state;this.i=a;a.defaultPrevented&&Kh.Aa.preventDefault.call(this)};
Kh.prototype.stopPropagation=function(){Kh.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Kh.prototype.preventDefault=function(){Kh.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Lh="closure_listenable_"+(Math.random()*1E6|0);var Mh=0;function Nh(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.uc=e;this.key=++Mh;this.Zb=this.jc=!1}
function Oh(a){a.Zb=!0;a.listener=null;a.proxy=null;a.src=null;a.uc=null}
;function Ph(a){this.src=a;this.listeners={};this.h=0}
Ph.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Qh(a,b,d,e);g>-1?(b=a[g],c||(b.jc=!1)):(b=new Nh(b,this.src,f,!!d,e),b.jc=c,a.push(b));return b};
Ph.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Qh(e,b,c,d);return b>-1?(Oh(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function Rh(a,b){var c=b.type;c in a.listeners&&Xb(a.listeners[c],b)&&(Oh(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function Qh(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Zb&&f.listener==b&&f.capture==!!c&&f.uc==d)return e}return-1}
;var Sh="closure_lm_"+(Math.random()*1E6|0),Th={},Uh=0;function Vh(a,b,c,d,e){if(d&&d.once)Wh(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Vh(a,b[f],c,d,e);else c=Xh(c),a&&a[Lh]?a.listen(b,c,Oa(d)?!!d.capture:!!d,e):Yh(a,b,c,!1,d,e)}
function Yh(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Oa(e)?!!e.capture:!!e,h=Zh(a);h||(a[Sh]=h=new Ph(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=$h();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)hh||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(ai(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Uh++}}
function $h(){function a(c){return b.call(a.src,a.listener,c)}
var b=bi;return a}
function Wh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Wh(a,b[f],c,d,e);else c=Xh(c),a&&a[Lh]?ci(a,b,c,Oa(d)?!!d.capture:!!d,e):Yh(a,b,c,!0,d,e)}
function di(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)di(a,b[f],c,d,e);else(d=Oa(d)?!!d.capture:!!d,c=Xh(c),a&&a[Lh])?a.i.remove(String(b),c,d,e):a&&(a=Zh(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Qh(b,c,d,e)),(c=a>-1?b[a]:null)&&ei(c))}
function ei(a){if(typeof a!=="number"&&a&&!a.Zb){var b=a.src;if(b&&b[Lh])Rh(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(ai(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Uh--;(c=Zh(b))?(Rh(c,a),c.h==0&&(c.src=null,b[Sh]=null)):Oh(a)}}}
function ai(a){return a in Th?Th[a]:Th[a]="on"+a}
function bi(a,b){if(a.Zb)a=!0;else{b=new Kh(b,this);var c=a.listener,d=a.uc||a.src;a.jc&&ei(a);a=c.call(d,b)}return a}
function Zh(a){a=a[Sh];return a instanceof Ph?a:null}
var fi="__closure_events_fn_"+(Math.random()*1E9>>>0);function Xh(a){if(typeof a==="function")return a;a[fi]||(a[fi]=function(b){return a.handleEvent(b)});
return a[fi]}
;function gi(){I.call(this);this.i=new Ph(this);this.xa=this;this.Z=null}
$a(gi,I);gi.prototype[Lh]=!0;p=gi.prototype;p.addEventListener=function(a,b,c,d){Vh(this,a,b,c,d)};
p.removeEventListener=function(a,b,c,d){di(this,a,b,c,d)};
function hi(a,b){var c=a.Z;if(c){var d=[];for(var e=1;c;c=c.Z)d.push(c),++e}a=a.xa;c=b.type||b;typeof b==="string"?b=new Jh(b,a):b instanceof Jh?b.target=b.target||a:(e=b,b=new Jh(c,a),Gg(b,e));e=!0;var f;if(d)for(f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=ii(g,c,!0,b)&&e}b.j||(g=b.h=a,e=ii(g,c,!0,b)&&e,b.j||(e=ii(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=ii(g,c,!1,b)&&e}
p.ba=function(){gi.Aa.ba.call(this);this.removeAllListeners();this.Z=null};
p.listen=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function ci(a,b,c,d,e){a.i.add(String(b),c,!0,d,e)}
p.removeAllListeners=function(a){if(this.i){var b=this.i;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,Oh(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function ii(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Zb&&g.capture==c){var h=g.listener,k=g.uc||g.src;g.jc&&Rh(a.i,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;var ji=typeof AsyncContext!=="undefined"&&typeof AsyncContext.Snapshot==="function"?function(a){return a&&AsyncContext.Snapshot.wrap(a)}:function(a){return a};function ki(a,b){this.j=a;this.o=b;this.i=0;this.h=null}
ki.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function li(a,b){a.o(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function mi(){this.i=this.h=null}
mi.prototype.add=function(a,b){var c=ni.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
mi.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var ni=new ki(function(){return new oi},function(a){return a.reset()});
function oi(){this.next=this.scope=this.h=null}
oi.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
oi.prototype.reset=function(){this.next=this.scope=this.h=null};var pi,qi=!1,ri=new mi;function si(a,b){pi||ti();qi||(pi(),qi=!0);ri.add(a,b)}
function ti(){var a=Promise.resolve(void 0);pi=function(){a.then(ui)}}
function ui(){for(var a;a=ri.remove();){try{a.h.call(a.scope)}catch(b){Xc(b)}li(ni,a)}qi=!1}
;function vi(){}
function wi(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;function xi(a){this.X=0;this.bb=void 0;this.vb=this.Ta=this.parent_=null;this.sc=this.Mc=!1;if(a!=vi)try{var b=this;a.call(void 0,function(c){yi(b,2,c)},function(c){yi(b,3,c)})}catch(c){yi(this,3,c)}}
function zi(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
zi.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Ai=new ki(function(){return new zi},function(a){a.reset()});
function Bi(a,b,c){var d=Ai.get();d.i=a;d.h=b;d.context=c;return d}
function Ci(a){return new xi(function(b,c){c(a)})}
xi.prototype.then=function(a,b,c){return Di(this,ji(typeof a==="function"?a:null),ji(typeof b==="function"?b:null),c)};
xi.prototype.$goog_Thenable=!0;function Ei(a,b,c,d){Fi(a,Bi(b||vi,c||null,d))}
p=xi.prototype;p.finally=function(a){var b=this;a=ji(a);return new Promise(function(c,d){Ei(b,function(e){a();c(e)},function(e){a();
d(e)})})};
p.Gc=function(a,b){return Di(this,null,ji(a),b)};
p.catch=xi.prototype.Gc;p.cancel=function(a){if(this.X==0){var b=new Gi(a);si(function(){Hi(this,b)},this)}};
function Hi(a,b){if(a.X==0)if(a.parent_){var c=a.parent_;if(c.Ta){for(var d=0,e=null,f=null,g=c.Ta;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.X==0&&d==1?Hi(c,b):(f?(d=f,d.next==c.vb&&(c.vb=d),d.next=d.next.next):Ii(c),Ji(c,e,3,b)))}a.parent_=null}else yi(a,3,b)}
function Fi(a,b){a.Ta||a.X!=2&&a.X!=3||Ki(a);a.vb?a.vb.next=b:a.Ta=b;a.vb=b}
function Di(a,b,c,d){var e=Bi(null,null,null);e.child=new xi(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof Gi?g(h):f(k)}catch(l){g(l)}}:g});
e.child.parent_=a;Fi(a,e);return e.child}
p.yf=function(a){this.X=0;yi(this,2,a)};
p.zf=function(a){this.X=0;yi(this,3,a)};
function yi(a,b,c){if(a.X==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.X=1;a:{var d=c,e=a.yf,f=a.zf;if(d instanceof xi){Ei(d,e,f,a);var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Oa(d))try{var k=d.then;if(typeof k==="function"){Li(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.bb=c,a.X=b,a.parent_=null,Ki(a),b!=3||c instanceof Gi||Mi(a,c))}}
function Li(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Ki(a){a.Mc||(a.Mc=!0,si(a.qe,a))}
function Ii(a){var b=null;a.Ta&&(b=a.Ta,a.Ta=b.next,b.next=null);a.Ta||(a.vb=null);return b}
p.qe=function(){for(var a;a=Ii(this);)Ji(this,a,this.X,this.bb);this.Mc=!1};
function Ji(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.sc;a=a.parent_)a.sc=!1;if(b.child)b.child.parent_=null,Ni(b,c,d);else try{b.j?b.i.call(b.context):Ni(b,c,d)}catch(e){Oi.call(null,e)}li(Ai,b)}
function Ni(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function Mi(a,b){a.sc=!0;si(function(){a.sc&&Oi.call(null,b)})}
var Oi=Xc;function Gi(a){fb.call(this,a)}
$a(Gi,fb);Gi.prototype.name="cancel";function Pi(a,b){gi.call(this);this.j=a||1;this.h=b||D;this.o=Ua(this.uf,this);this.u=Ya()}
$a(Pi,gi);p=Pi.prototype;p.enabled=!1;p.Ea=null;p.setInterval=function(a){this.j=a;this.Ea&&this.enabled?(this.stop(),this.start()):this.Ea&&this.stop()};
p.uf=function(){if(this.enabled){var a=Ya()-this.u;a>0&&a<this.j*.8?this.Ea=this.h.setTimeout(this.o,this.j-a):(this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null),hi(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
p.start=function(){this.enabled=!0;this.Ea||(this.Ea=this.h.setTimeout(this.o,this.j),this.u=Ya())};
p.stop=function(){this.enabled=!1;this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null)};
p.ba=function(){Pi.Aa.ba.call(this);this.stop();delete this.h};function Qi(a){I.call(this);this.G=a;this.j=0;this.o=100;this.u=!1;this.i=new Map;this.A=new Set;this.flushInterval=3E4;this.h=new Pi(this.flushInterval);this.h.listen("tick",this.dc,!1,this);Bc(this,this.h)}
v(Qi,I);p=Qi.prototype;p.sendIsolatedPayload=function(a){this.u=a;this.o=1};
function Ri(a){a.h.enabled||a.h.start();a.j++;a.j>=a.o&&a.dc()}
p.dc=function(){var a=this.i.values();a=[].concat(A(a)).filter(function(b){return b.h.size});
a.length&&this.G.flush(a,this.u);Si(a);this.j=0;this.h.enabled&&this.h.stop()};
p.Nb=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new Hh(a,b))};
p.Jc=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new Ih(a,b))};
function Ti(a,b){return a.A.has(b)?void 0:a.i.get(b)}
p.Kb=function(a){this.Vd(a,1,C.apply(1,arguments))};
p.Vd=function(a,b){var c=C.apply(2,arguments),d=Ti(this,a);d&&d instanceof Hh&&(d.j(b,c),Ri(this))};
p.record=function(a,b){var c=C.apply(2,arguments),d=Ti(this,a);d&&d instanceof Ih&&(d.record(b,c),Ri(this))};
function Si(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Ui(){}
Ui.prototype.serialize=function(a){var b=[];Vi(this,a,b);return b.join("")};
function Vi(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Vi(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),Wi(d,c),c.push(":"),Vi(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Wi(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Xi={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Yi=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Wi(a,b){b.push('"',a.replace(Yi,function(c){var d=Xi[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Xi[c]=d);return d}),'"')}
;function Zi(){gi.call(this);this.headers=new Map;this.h=!1;this.K=null;this.o=this.Y="";this.j=this.U=this.A=this.P=!1;this.G=0;this.u=null;this.ma="";this.ha=!1}
$a(Zi,gi);var $i=/^https?$/i,aj=["POST","PUT"],bj=[];function cj(a,b,c,d,e,f,g){var h=new Zi;bj.push(h);b&&h.listen("complete",b);ci(h,"ready",h.ee);f&&(h.G=Math.max(0,f));g&&(h.ha=g);h.send(a,c,d,e)}
p=Zi.prototype;p.ee=function(){this.dispose();Xb(bj,this)};
p.send=function(a,b,c,d){if(this.K)throw Error("[goog.net.XhrIo] Object is active with another request="+this.Y+"; newUri="+a);b=b?b.toUpperCase():"GET";this.Y=a;this.o="";this.P=!1;this.h=!0;this.K=new XMLHttpRequest;this.K.onreadystatechange=ji(Ua(this.Dd,this));try{this.getStatus(),this.U=!0,this.K.open(b,String(a),!0),this.U=!1}catch(g){this.getStatus();dj(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,d[e]);else if(typeof d.keys===
"function"&&typeof d.get==="function"){e=y(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=D.FormData&&a instanceof D.FormData;!(Qb(aj,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=y(c);for(d=b.next();!d.done;d=b.next())c=y(d.value),d=c.next().value,c=c.next().value,this.K.setRequestHeader(d,c);this.ma&&(this.K.responseType=this.ma);"withCredentials"in this.K&&this.K.withCredentials!==this.ha&&(this.K.withCredentials=this.ha);try{this.u&&(clearTimeout(this.u),this.u=null),this.G>0&&(this.getStatus(),this.u=setTimeout(this.xf.bind(this),this.G)),
this.getStatus(),this.A=!0,this.K.send(a),this.A=!1}catch(g){this.getStatus(),dj(this,g)}};
p.xf=function(){typeof Ha!="undefined"&&this.K&&(this.o="Timed out after "+this.G+"ms, aborting",this.getStatus(),hi(this,"timeout"),this.abort(8))};
function dj(a,b){a.h=!1;a.K&&(a.j=!0,a.K.abort(),a.j=!1);a.o=b;ej(a);fj(a)}
function ej(a){a.P||(a.P=!0,hi(a,"complete"),hi(a,"error"))}
p.abort=function(){this.K&&this.h&&(this.getStatus(),this.h=!1,this.j=!0,this.K.abort(),this.j=!1,hi(this,"complete"),hi(this,"abort"),fj(this))};
p.ba=function(){this.K&&(this.h&&(this.h=!1,this.j=!0,this.K.abort(),this.j=!1),fj(this,!0));Zi.Aa.ba.call(this)};
p.Dd=function(){this.ea||(this.U||this.A||this.j?gj(this):this.Oe())};
p.Oe=function(){gj(this)};
function gj(a){if(a.h&&typeof Ha!="undefined")if(a.A&&(a.K?a.K.readyState:0)==4)setTimeout(a.Dd.bind(a),0);else if(hi(a,"readystatechange"),a.isComplete()){a.getStatus();a.h=!1;try{if(hj(a))hi(a,"complete"),hi(a,"success");else{try{var b=(a.K?a.K.readyState:0)>2?a.K.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";ej(a)}}finally{fj(a)}}}
function fj(a,b){if(a.K){a.u&&(clearTimeout(a.u),a.u=null);var c=a.K;a.K=null;b||hi(a,"ready");try{c.onreadystatechange=null}catch(d){}}}
p.isActive=function(){return!!this.K};
p.isComplete=function(){return(this.K?this.K.readyState:0)==4};
function hj(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=String(a.Y).match(kc)[1]||null,!a&&D.self&&D.self.location&&(a=D.self.location.protocol.slice(0,-1)),b=!$i.test(a?a.toLowerCase():"");c=b}return c}
p.getStatus=function(){try{return(this.K?this.K.readyState:0)>2?this.K.status:-1}catch(a){return-1}};
p.getLastError=function(){return typeof this.o==="string"?this.o:String(this.o)};function ij(){}
ij.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
cj(a.url,function(d){d=d.target;if(hj(d)){try{var e=d.K?d.K.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Ec,a.timeoutMillis,a.withCredentials)};
ij.prototype.qc=function(){return 1};function jj(a,b){this.logger=a;this.event=b;this.startTime=kj()}
jj.prototype.done=function(){this.logger.Wb(this.event,kj()-this.startTime)};
function lj(){Mc.apply(this,arguments)}
v(lj,Mc);function mj(a,b){var c=kj();b=b();a.Wb("n",kj()-c);return b}
function nj(){lj.apply(this,arguments)}
v(nj,lj);p=nj.prototype;p.Rc=function(){};
p.Db=function(){};
p.Wb=function(){};
p.Ha=function(){};
p.Dc=function(){};
p.Pd=function(){};
function oj(a){return{sf:new Pc(a),errorCount:new Tc(a),eventCount:new Rc(a),pe:new Sc(a),ri:new Qc(a),ti:new Uc(a),xh:new Vc(a),si:new Wc(a)}}
function pj(a,b,c,d){a=Ah(yh(xh(new wh(1828,"0"),a),new ij));b.length&&zh(a,Wf(new Vf,b));d!==void 0&&(a.Va=d);var e=new Ch(1828,"","",!1,"",Bh(a));Bc(e,a);var f=new Qi({flush:function(g){try{e.flush(g)}catch(h){c(h)}}});
f.addOnDisposeCallback(function(){setTimeout(function(){try{f.dc()}finally{e.dispose()}})});
f.o=1E5;f.flushInterval=3E4;f.h.setInterval(3E4);return f}
function qj(a,b){I.call(this);var c=this;this.callback=a;this.i=b;this.h=-b;this.addOnDisposeCallback(function(){return void clearTimeout(c.timer)})}
v(qj,I);function rj(a){if(a.timer===void 0){var b=Math.max(0,a.h+a.i-kj());a.timer=setTimeout(function(){try{a.callback()}finally{a.h=kj(),a.timer=void 0}},b)}}
function sj(a,b){lj.call(this);this.metrics=a;this.Da=b}
v(sj,lj);sj.prototype.Rc=function(a){this.metrics.sf.record(a,this.Da)};
sj.prototype.Db=function(a){this.metrics.eventCount.kb(a,this.Da)};
sj.prototype.Wb=function(a,b){this.metrics.pe.record(b,a,this.Da)};
sj.prototype.Ha=function(a){this.metrics.errorCount.kb(a,this.Da)};
function tj(a,b){b=b===void 0?[]:b;var c={Da:a.Da||"_",pc:a.pc||[],xc:a.xc|0,Va:a.Va,yc:a.yc||function(){},
Jb:a.Jb||function(f,g){return pj(f,g,c.yc,c.Va)}},d=c.Jb("49",c.pc.concat(b));
sj.call(this,oj(d),c.Da);var e=this;this.options=c;this.service=d;this.i=!a.Jb;this.h=new qj(function(){return void e.service.dc()},c.xc);
this.addOnDisposeCallback(function(){e.h.dispose();e.i&&e.service.dispose()});
(this.j=b.slice()).sort(bc)}
v(tj,sj);tj.prototype.Pd=function(a){var b=this;a=a.slice();a.sort(bc);$b(a,this.j)||(this.h.dispose(),this.i&&this.service.dispose(),this.service=this.options.Jb("49",this.options.pc.concat(a)),this.h=new qj(function(){return void b.service.dc()},this.options.xc),this.metrics=oj(this.service),this.j=a)};
tj.prototype.Dc=function(){rj(this.h)};
function kj(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function uj(a){this.F=L(a)}
v(uj,M);function vj(a){this.F=L(a)}
v(vj,M);function wj(a){this.F=L(a,0,"bfkj")}
v(wj,M);var xj=function(a){return ie(function(b){return b instanceof a&&!ee(b)})}(wj);
wj.Me="bfkj";function Ic(a){this.F=L(a)}
v(Ic,M);function yj(a){this.F=L(a)}
v(yj,M);var zj=Uf(yj);function Aj(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Bj(a,b,c){if(a.disable)return new nj;b=b?Gc(b):[];if(c)return c.Pd(b),c.share();a={Da:a.Da,pc:a.Lh,xc:a.Xh,Va:a.Va,yc:a.yc,Jb:a.Jb};c=b;c=c===void 0?[]:c;return new tj(a,c)}
function Cj(a){function b(w,x,z,G){Promise.resolve().then(function(){k.done();h.Dc();h.dispose();g.resolve({Zd:w,rf:x,Se:z,zh:G})})}
function c(w,x,z,G){if(!d.logger.ea){var H="k";x?H="h":z&&(H="u");H!=="k"?G!==0&&(d.logger.Db(H),d.logger.Wb(H,w)):d.i<=0?(d.logger.Db(H),d.logger.Wb(H,w),d.i=Math.floor(Math.random()*200)):d.i--}}
I.call(this);var d=this;this.i=Math.floor(Math.random()*200);this.h=new yj;if("challenge"in a&&xj(a.challenge)){var e=Lf(a.challenge,4,void 0,he);var f=Lf(a.challenge,5,void 0,he);Lf(a.challenge,7,void 0,he)&&(this.h=zj(Lf(a.challenge,7,void 0,he)))}else e=a.program,f=a.globalName;this.addOnDisposeCallback(function(){var w,x,z;return B(function(G){if(G.h==1)return G.yield(d.j,2);w=G.i;x=w.rf;(z=x)==null||z();G.h=0})});
this.logger=Bj(a.Bd||{},this.h,a.Ah);Bc(this,this.logger);var g=new Aj;this.j=g.promise;this.logger.Db("t");var h=this.logger.share(),k=new jj(h,"t");if(!D[f])throw this.logger.Ha(25),Error("EGOU");if(!D[f].a)throw this.logger.Ha(26),Error("ELIU");try{var l=D[f].a;f=[];for(var m=[],n=Gc(this.h),r=0;r<n.length;r++)f.push(n[r]),m.push(1);var t=Kc(this.h);for(n=0;n<t.length;n++)f.push(t[n]),m.push(2);this.u=y(l(e,b,!0,a.oi,c,[f,m],Lf(this.h,5))).next().value;this.cd=g.promise.then(function(){})}catch(w){throw this.logger.Ha(28),
w;
}}
v(Cj,I);Cj.prototype.snapshot=function(a){if(this.ea)throw Error("Already disposed");this.logger.Db("n");var b=this.logger.share();return this.j.then(function(c){var d=c.Zd;return new Promise(function(e){var f=new jj(b,"n");d(function(g){f.done();b.Rc(g.length);b.Dc();b.dispose();e(g)},[a.wb,
a.ed,a.Cf,a.gd])})})};
Cj.prototype.hd=function(a){var b=this;if(this.ea)throw Error("Already disposed");this.logger.Db("n");var c=mj(this.logger,function(){return b.u([a.wb,a.ed,a.Cf,a.gd])});
this.logger.Rc(c.length);this.logger.Dc();return c};
Cj.prototype.o=function(a){this.j.then(function(b){var c;(c=b.Se)==null||c(a)})};function Dj(a){if(!a)return null;a=bf(wf(a,4,void 0,vf));return a===null||a===void 0?null:nb(a)}
;function Ej(){this.promises={};this.h=null}
function Fj(){Ej.instance||(Ej.instance=new Ej);return Ej.instance}
function Gj(a,b){return Hj(a,Hf(b,uj,1,he),Hf(b,vj,2,he),Lf(b,3,void 0,he))}
function Hj(a,b,c,d){if(!b&&!c)return Promise.resolve();if(!d)return Ij(b,c);var e;(e=a.promises)[d]||(e[d]=new Promise(function(f,g){Ij(b,c).then(function(){a.h=d;f()},function(h){delete a.promises[d];
g(h)})}));
return a.promises[d]}
function Ij(a,b){return b?Jj(b):a?Kj(a):Promise.resolve()}
function Jj(a){return new Promise(function(b,c){var d=Kg("SCRIPT"),e=Dj(a);Kb(d,e);d.onload=function(){Lg(d);b()};
d.onerror=function(){Lg(d);c(Error("EWLS"))};
(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(d)})}
function Kj(a){return new Promise(function(b){var c=Kg("SCRIPT");if(a){var d=bf(wf(a,6,void 0,vf));d=d===null||d===void 0?null:Hb(d)}else d=null;c.textContent=Ib(d);Jb(c);(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(c);Lg(c);b()})}
;var Lj=window;function Mj(a){var b=Nj;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Oj(){var a=[];Mj(function(b){a.push(b)});
return a}
var Nj={Df:"allow-forms",Ef:"allow-modals",Ff:"allow-orientation-lock",Gf:"allow-pointer-lock",Hf:"allow-popups",If:"allow-popups-to-escape-sandbox",Jf:"allow-presentation",Kf:"allow-same-origin",Lf:"allow-scripts",Mf:"allow-top-navigation",Nf:"allow-top-navigation-by-user-activation"},Pj=wi(function(){return Oj()});
function Qj(){var a=Rj(),b={};Rb(Pj(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Rj(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Sj(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Tj=(new Date).getTime();Object.assign({},{attributes:{},handleError:function(a){throw a;}},{Eh:!0,
Gh:!0,Hh:Zc,Ih:$c,Jh:!1,vh:!1,Fh:!0,Dh:!1});function Uj(a){gi.call(this);var b=this;this.A=this.j=0;this.Ca=a!=null?a:{pa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.h=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.o=function(){return B(function(e){return e.yield(Vj(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.A||Wj(this)}
v(Uj,gi);function Xj(){var a=Yj;Uj.instance||(Uj.instance=new Uj(a));return Uj.instance}
Uj.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Ca.qa(this.A);delete Uj.instance};
Uj.prototype.ta=function(){return this.h};
function Wj(a){a.A=a.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return a.h?((b=window.navigator)==null?0:b.onLine)?c.B(3):c.yield(Vj(a),3):c.yield(Vj(a),3);Wj(a);c.h=0})},3E4)}
function Vj(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f,g;return B(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,va(h,2,3),d&&(a.j=a.Ca.pa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.P=[h.j];h.H=0;h.o=0;a.u=void 0;a.j&&(a.Ca.qa(a.j),a.j=0);g!==a.h&&(a.h=g,a.h?hi(a,"networkstatus-online"):hi(a,"networkstatus-offline"));c(g);ya(h);break;case 2:xa(h),g=!1,h.B(3)}})})}
;function Zj(){this.data=[];this.h=-1}
Zj.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Zj.prototype.get=function(a){return!!this.data[a]};
function ak(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function bk(){this.blockSize=-1}
;function ck(){this.blockSize=-1;this.blockSize=64;this.h=[];this.u=[];this.H=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.o=this.i=0;this.reset()}
$a(ck,bk);ck.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.o=this.i=0};
function dk(a,b,c){c||(c=0);var d=a.H;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(b=16;b<80;b++)c=d[b-3]^d[b-8]^d[b-14]^d[b-16],d[b]=(c<<1|c>>>31)&4294967295;b=a.h[0];c=a.h[1];e=a.h[2];for(var f=a.h[3],g=a.h[4],h,k,l=0;l<80;l++)l<40?l<20?(h=f^c&(e^f),k=1518500249):(h=c^e^f,k=1859775393):l<60?(h=c&e|f&(c|e),k=2400959708):(h=c^e^f,k=3395469782),
h=(b<<5|b>>>27)+h+g+k+d[l]&4294967295,g=f,f=e,e=(c<<30|c>>>2)&4294967295,c=b,b=h;a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+e&4294967295;a.h[3]=a.h[3]+f&4294967295;a.h[4]=a.h[4]+g&4294967295}
ck.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.u,f=this.i;d<b;){if(f==0)for(;d<=c;)dk(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){dk(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){dk(this,e);f=0;break}}this.i=f;this.o+=b}};
ck.prototype.digest=function(){var a=[],b=this.o*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.u[c]=b&255,b/=256;dk(this,this.u);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function ek(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function fk(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function gk(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:ek(a).match(/\S+/g)||[],b=Qb(a,b)>=0);return b}
function hk(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):gk(a,"inverted-hdpi")&&fk(a,Array.prototype.filter.call(a.classList?a.classList:ek(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function ik(){}
ik.prototype.next=function(){return jk};
var jk={done:!0,value:void 0};ik.prototype.tb=function(){return this};function kk(a){if(a instanceof lk||a instanceof mk||a instanceof nk)return a;if(typeof a.next=="function")return new lk(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new lk(function(){return a[Symbol.iterator]()});
if(typeof a.tb=="function")return new lk(function(){return a.tb()});
throw Error("Not an iterator or iterable.");}
function lk(a){this.h=a}
lk.prototype.tb=function(){return new mk(this.h())};
lk.prototype[Symbol.iterator]=function(){return new nk(this.h())};
lk.prototype.i=function(){return new nk(this.h())};
function mk(a){this.h=a}
v(mk,ik);mk.prototype.next=function(){return this.h.next()};
mk.prototype[Symbol.iterator]=function(){return new nk(this.h)};
mk.prototype.i=function(){return new nk(this.h)};
function nk(a){lk.call(this,function(){return a});
this.j=a}
v(nk,lk);nk.prototype.next=function(){return this.j.next()};function N(a){I.call(this);this.u=1;this.j=[];this.o=0;this.h=[];this.i={};this.A=!!a}
$a(N,I);p=N.prototype;p.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.u;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.u=e+3;d.push(e);return e};
p.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.fc(a)}return!1};
p.fc=function(a){var b=this.h[a];if(b){var c=this.i[b];this.o!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Xb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
p.sb=function(a,b){var c=this.i[a];if(c){var d=Array(arguments.length-1),e=arguments.length,f;for(f=1;f<e;f++)d[f-1]=arguments[f];if(this.A)for(f=0;f<c.length;f++)e=c[f],ok(this.h[e+1],this.h[e+2],d);else{this.o++;try{for(f=0,e=c.length;f<e&&!this.ea;f++){var g=c[f];this.h[g+1].apply(this.h[g+2],d)}}finally{if(this.o--,this.j.length>0&&this.o==0)for(;c=this.j.pop();)this.fc(c)}}return f!=0}return!1};
function ok(a,b,c){si(function(){a.apply(b,c)})}
p.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.fc,this),delete this.i[a])}else this.h.length=0,this.i={}};
p.ba=function(){N.Aa.ba.call(this);this.clear();this.j.length=0};function pk(a){this.h=a}
pk.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new Ui).serialize(b))};
pk.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
pk.prototype.remove=function(a){this.h.remove(a)};function qk(a){this.h=a}
$a(qk,pk);function rk(a){this.data=a}
function sk(a){return a===void 0||a instanceof rk?a:new rk(a)}
qk.prototype.set=function(a,b){qk.Aa.set.call(this,a,sk(b))};
qk.prototype.i=function(a){a=qk.Aa.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
qk.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function tk(a){this.h=a}
$a(tk,qk);tk.prototype.set=function(a,b,c){if(b=sk(b)){if(c){if(c<Ya()){tk.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Ya()}tk.Aa.set.call(this,a,b)};
tk.prototype.i=function(a){var b=tk.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Ya()||c&&c>Ya())tk.prototype.remove.call(this,a);else return b}};function uk(){}
;function vk(){}
$a(vk,uk);vk.prototype[Symbol.iterator]=function(){return kk(this.tb(!0)).i()};
vk.prototype.clear=function(){var a=Array.from(this);a=y(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function wk(a){this.h=a;this.i=null}
$a(wk,vk);p=wk.prototype;p.isAvailable=function(){if(this.i===null){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;this.i=b}return this.i};
p.set=function(a,b){xk(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
p.get=function(a){xk(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
p.remove=function(a){xk(this);this.h.removeItem(a)};
p.tb=function(a){xk(this);var b=0,c=this.h,d=new ik;d.next=function(){if(b>=c.length)return jk;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
p.clear=function(){xk(this);this.h.clear()};
p.key=function(a){xk(this);return this.h.key(a)};
function xk(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");a.isAvailable()||Xc(Error("Storage mechanism: Storage unavailable"))}
;function yk(){var a=null;try{a=D.localStorage||null}catch(b){}wk.call(this,a)}
$a(yk,wk);function zk(a,b){this.i=a;this.h=b+"::"}
$a(zk,vk);zk.prototype.set=function(a,b){this.i.set(this.h+a,b)};
zk.prototype.get=function(a){return this.i.get(this.h+a)};
zk.prototype.remove=function(a){this.i.remove(this.h+a)};
zk.prototype.tb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new ik;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
return d};function Ak(a){if(a.Wa&&typeof a.Wa=="function")return a.Wa();if(typeof Map!=="undefined"&&a instanceof Map||typeof Set!=="undefined"&&a instanceof Set)return Array.from(a.values());if(typeof a==="string")return a.split("");if(Ma(a)){for(var b=[],c=a.length,d=0;d<c;d++)b.push(a[d]);return b}return wg(a)}
function Bk(a){if(a.Tb&&typeof a.Tb=="function")return a.Tb();if(!a.Wa||typeof a.Wa!="function"){if(typeof Map!=="undefined"&&a instanceof Map)return Array.from(a.keys());if(!(typeof Set!=="undefined"&&a instanceof Set)){if(Ma(a)||typeof a==="string"){var b=[];a=a.length;for(var c=0;c<a;c++)b.push(c);return b}b=[];c=0;for(var d in a)b[c++]=d;return b}}}
function Ck(a,b,c){if(a.forEach&&typeof a.forEach=="function")a.forEach(b,c);else if(Ma(a)||typeof a==="string")Array.prototype.forEach.call(a,b,c);else for(var d=Bk(a),e=Ak(a),f=e.length,g=0;g<f;g++)b.call(c,e[g],d&&d[g],a)}
;function Dk(a){this.i=this.A=this.j="";this.G=null;this.u=this.h="";this.o=!1;var b;a instanceof Dk?(this.o=a.o,Ek(this,a.j),this.A=a.A,this.i=a.i,Fk(this,a.G),this.h=a.h,Gk(this,a.H.clone()),this.u=a.u):a&&(b=String(a).match(kc))?(this.o=!1,Ek(this,b[1]||"",!0),this.A=Hk(b[2]||""),this.i=Hk(b[3]||"",!0),Fk(this,b[4]),this.h=Hk(b[5]||"",!0),Gk(this,b[6]||"",!0),this.u=Hk(b[7]||"")):(this.o=!1,this.H=new Ik(null,this.o))}
Dk.prototype.toString=function(){var a=[],b=this.j;b&&a.push(Jk(b,Kk,!0),":");var c=this.i;if(c||b=="file")a.push("//"),(b=this.A)&&a.push(Jk(b,Kk,!0),"@"),a.push(encodeURIComponent(String(c)).replace(/%25([0-9a-fA-F]{2})/g,"%$1")),c=this.G,c!=null&&a.push(":",String(c));if(c=this.h)this.i&&c.charAt(0)!="/"&&a.push("/"),a.push(Jk(c,c.charAt(0)=="/"?Lk:Mk,!0));(c=this.H.toString())&&a.push("?",c);(c=this.u)&&a.push("#",Jk(c,Nk));return a.join("")};
Dk.prototype.resolve=function(a){var b=this.clone(),c=!!a.j;c?Ek(b,a.j):c=!!a.A;c?b.A=a.A:c=!!a.i;c?b.i=a.i:c=a.G!=null;var d=a.h;if(c)Fk(b,a.G);else if(c=!!a.h){if(d.charAt(0)!="/")if(this.i&&!this.h)d="/"+d;else{var e=b.h.lastIndexOf("/");e!=-1&&(d=b.h.slice(0,e+1)+d)}e=d;if(e==".."||e==".")d="";else if(e.indexOf("./")!=-1||e.indexOf("/.")!=-1){d=e.lastIndexOf("/",0)==0;e=e.split("/");for(var f=[],g=0;g<e.length;){var h=e[g++];h=="."?d&&g==e.length&&f.push(""):h==".."?((f.length>1||f.length==1&&
f[0]!="")&&f.pop(),d&&g==e.length&&f.push("")):(f.push(h),d=!0)}d=f.join("/")}else d=e}c?b.h=d:c=a.H.toString()!=="";c?Gk(b,a.H.clone()):c=!!a.u;c&&(b.u=a.u);return b};
Dk.prototype.clone=function(){return new Dk(this)};
function Ek(a,b,c){a.j=c?Hk(b,!0):b;a.j&&(a.j=a.j.replace(/:$/,""))}
function Fk(a,b){if(b){b=Number(b);if(isNaN(b)||b<0)throw Error("Bad port number "+b);a.G=b}else a.G=null}
function Gk(a,b,c){b instanceof Ik?(a.H=b,Ok(a.H,a.o)):(c||(b=Jk(b,Pk)),a.H=new Ik(b,a.o))}
function Hk(a,b){return a?b?decodeURI(a.replace(/%25/g,"%2525")):decodeURIComponent(a):""}
function Jk(a,b,c){return typeof a==="string"?(a=encodeURI(a).replace(b,Qk),c&&(a=a.replace(/%25([0-9a-fA-F]{2})/g,"%$1")),a):null}
function Qk(a){a=a.charCodeAt(0);return"%"+(a>>4&15).toString(16)+(a&15).toString(16)}
var Kk=/[#\/\?@]/g,Mk=/[#\?:]/g,Lk=/[#\?]/g,Pk=/[#\?@]/g,Nk=/#/g;function Ik(a,b){this.i=this.h=null;this.j=a||null;this.o=!!b}
function Rk(a){a.h||(a.h=new Map,a.i=0,a.j&&qc(a.j,function(b,c){a.add(ic(b),c)}))}
p=Ik.prototype;p.add=function(a,b){Rk(this);this.j=null;a=Sk(this,a);var c=this.h.get(a);c||this.h.set(a,c=[]);c.push(b);this.i=this.i+1;return this};
p.remove=function(a){Rk(this);a=Sk(this,a);return this.h.has(a)?(this.j=null,this.i=this.i-this.h.get(a).length,this.h.delete(a)):!1};
p.clear=function(){this.h=this.j=null;this.i=0};
function Tk(a,b){Rk(a);b=Sk(a,b);return a.h.has(b)}
p.forEach=function(a,b){Rk(this);this.h.forEach(function(c,d){c.forEach(function(e){a.call(b,e,d,this)},this)},this)};
p.Tb=function(){Rk(this);for(var a=Array.from(this.h.values()),b=Array.from(this.h.keys()),c=[],d=0;d<b.length;d++)for(var e=a[d],f=0;f<e.length;f++)c.push(b[d]);return c};
p.Wa=function(a){Rk(this);var b=[];if(typeof a==="string")Tk(this,a)&&(b=b.concat(this.h.get(Sk(this,a))));else{a=Array.from(this.h.values());for(var c=0;c<a.length;c++)b=b.concat(a[c])}return b};
p.set=function(a,b){Rk(this);this.j=null;a=Sk(this,a);Tk(this,a)&&(this.i=this.i-this.h.get(a).length);this.h.set(a,[b]);this.i=this.i+1;return this};
p.get=function(a,b){if(!a)return b;a=this.Wa(a);return a.length>0?String(a[0]):b};
p.toString=function(){if(this.j)return this.j;if(!this.h)return"";for(var a=[],b=Array.from(this.h.keys()),c=0;c<b.length;c++){var d=b[c],e=encodeURIComponent(String(d));d=this.Wa(d);for(var f=0;f<d.length;f++){var g=e;d[f]!==""&&(g+="="+encodeURIComponent(String(d[f])));a.push(g)}}return this.j=a.join("&")};
p.clone=function(){var a=new Ik;a.j=this.j;this.h&&(a.h=new Map(this.h),a.i=this.i);return a};
function Sk(a,b){b=String(b);a.o&&(b=b.toLowerCase());return b}
function Ok(a,b){b&&!a.o&&(Rk(a),a.j=null,a.h.forEach(function(c,d){var e=d.toLowerCase();d!=e&&(this.remove(d),this.remove(e),c.length>0&&(this.j=null,this.h.set(Sk(this,e),Yb(c)),this.i=this.i+c.length))},a));
a.o=b}
p.extend=function(a){for(var b=0;b<arguments.length;b++)Ck(arguments[b],function(c,d){this.add(d,c)},this)};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var O={},Uk=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";O.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
O.dd=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var Vk={ub:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
ud:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},Wk={ub:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
ud:function(a){return[].concat.apply([],a)}};
O.qf=function(){Uk?(O.rb=Uint8Array,O.Ja=Uint16Array,O.Ud=Int32Array,O.assign(O,Vk)):(O.rb=Array,O.Ja=Array,O.Ud=Array,O.assign(O,Wk))};
O.qf();var Xk=!0;try{new Uint8Array(1)}catch(a){Xk=!1}
function Yk(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new O.rb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var Zk={};Zk=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var $k={},al,bl=[],cl=0;cl<256;cl++){al=cl;for(var dl=0;dl<8;dl++)al=al&1?3988292384^al>>>1:al>>>1;bl[cl]=al}$k=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^bl[(a^b[d])&255];return a^-1};var el={};el={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function fl(a){for(var b=a.length;--b>=0;)a[b]=0}
var gl=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],hl=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],il=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],jl=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],kl=Array(576);fl(kl);var ll=Array(60);fl(ll);var ml=Array(512);fl(ml);var nl=Array(256);fl(nl);var ol=Array(29);fl(ol);var pl=Array(30);fl(pl);function ql(a,b,c,d,e){this.Md=a;this.te=b;this.se=c;this.le=d;this.Le=e;this.xd=a&&a.length}
var rl,sl,tl;function ul(a,b){this.td=a;this.Fb=0;this.cb=b}
function vl(a,b){a.aa[a.pending++]=b&255;a.aa[a.pending++]=b>>>8&255}
function wl(a,b,c){a.ia>16-c?(a.oa|=b<<a.ia&65535,vl(a,a.oa),a.oa=b>>16-a.ia,a.ia+=c-16):(a.oa|=b<<a.ia&65535,a.ia+=c)}
function xl(a,b,c){wl(a,c[b*2],c[b*2+1])}
function yl(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function zl(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=yl(d[e]++,e))}
function Al(a){var b;for(b=0;b<286;b++)a.ra[b*2]=0;for(b=0;b<30;b++)a.hb[b*2]=0;for(b=0;b<19;b++)a.ja[b*2]=0;a.ra[512]=1;a.Pa=a.Ib=0;a.ya=a.matches=0}
function Bl(a){a.ia>8?vl(a,a.oa):a.ia>0&&(a.aa[a.pending++]=a.oa);a.oa=0;a.ia=0}
function Cl(a,b,c){Bl(a);vl(a,c);vl(a,~c);O.ub(a.aa,a.window,b,c,a.pending);a.pending+=c}
function Dl(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function El(a,b,c){for(var d=a.da[c],e=c<<1;e<=a.Na;){e<a.Na&&Dl(b,a.da[e+1],a.da[e],a.depth)&&e++;if(Dl(b,d,a.da[e],a.depth))break;a.da[c]=a.da[e];c=e;e<<=1}a.da[c]=d}
function Fl(a,b,c){var d=0;if(a.ya!==0){do{var e=a.aa[a.Qb+d*2]<<8|a.aa[a.Qb+d*2+1];var f=a.aa[a.Qc+d];d++;if(e===0)xl(a,f,b);else{var g=nl[f];xl(a,g+256+1,b);var h=gl[g];h!==0&&(f-=ol[g],wl(a,f,h));e--;g=e<256?ml[e]:ml[256+(e>>>7)];xl(a,g,c);h=hl[g];h!==0&&(e-=pl[g],wl(a,e,h))}}while(d<a.ya)}xl(a,256,b)}
function Gl(a,b){var c=b.td,d=b.cb.Md,e=b.cb.xd,f=b.cb.le,g,h=-1;a.Na=0;a.Ab=573;for(g=0;g<f;g++)c[g*2]!==0?(a.da[++a.Na]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.Na<2;){var k=a.da[++a.Na]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Pa--;e&&(a.Ib-=d[k*2+1])}b.Fb=h;for(g=a.Na>>1;g>=1;g--)El(a,c,g);k=f;do g=a.da[1],a.da[1]=a.da[a.Na--],El(a,c,1),d=a.da[1],a.da[--a.Ab]=g,a.da[--a.Ab]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.da[1]=k++,El(a,c,1);while(a.Na>=
2);a.da[--a.Ab]=a.da[1];g=b.td;k=b.Fb;d=b.cb.Md;e=b.cb.xd;f=b.cb.te;var l=b.cb.se,m=b.cb.Le,n,r=0;for(n=0;n<=15;n++)a.Ka[n]=0;g[a.da[a.Ab]*2+1]=0;for(b=a.Ab+1;b<573;b++){var t=a.da[b];n=g[g[t*2+1]*2+1]+1;n>m&&(n=m,r++);g[t*2+1]=n;if(!(t>k)){a.Ka[n]++;var w=0;t>=l&&(w=f[t-l]);var x=g[t*2];a.Pa+=x*(n+w);e&&(a.Ib+=x*(d[t*2+1]+w))}}if(r!==0){do{for(n=m-1;a.Ka[n]===0;)n--;a.Ka[n]--;a.Ka[n+1]+=2;a.Ka[m]--;r-=2}while(r>0);for(n=m;n!==0;n--)for(t=a.Ka[n];t!==0;)d=a.da[--b],d>k||(g[d*2+1]!==n&&(a.Pa+=(n-g[d*
2+1])*g[d*2],g[d*2+1]=n),t--)}zl(c,h,a.Ka)}
function Hl(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ja[l*2]+=g:l!==0?(l!==e&&a.ja[l*2]++,a.ja[32]++):g<=10?a.ja[34]++:a.ja[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Il(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do xl(a,l,a.ja);while(--g!==0)}else l!==0?(l!==e&&(xl(a,l,a.ja),g--),xl(a,16,a.ja),wl(a,g-3,2)):g<=10?(xl(a,17,a.ja),wl(a,g-3,3)):(xl(a,18,a.ja),wl(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Jl(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.ra[c*2]!==0)return 0;if(a.ra[18]!==0||a.ra[20]!==0||a.ra[26]!==0)return 1;for(c=32;c<256;c++)if(a.ra[c*2]!==0)return 1;return 0}
var Kl=!1;function Ll(a,b,c){a.aa[a.Qb+a.ya*2]=b>>>8&255;a.aa[a.Qb+a.ya*2+1]=b&255;a.aa[a.Qc+a.ya]=c&255;a.ya++;b===0?a.ra[c*2]++:(a.matches++,b--,a.ra[(nl[c]+256+1)*2]++,a.hb[(b<256?ml[b]:ml[256+(b>>>7)])*2]++);return a.ya===a.Vb-1}
;function Ml(a,b){a.msg=el[b];return b}
function Nl(a){for(var b=a.length;--b>=0;)a[b]=0}
function Ol(a){var b=a.state,c=b.pending;c>a.S&&(c=a.S);c!==0&&(O.ub(a.output,b.aa,b.Yb,c,a.Gb),a.Gb+=c,b.Yb+=c,a.jd+=c,a.S-=c,b.pending-=c,b.pending===0&&(b.Yb=0))}
function Pl(a,b){var c=a.va>=0?a.va:-1,d=a.v-a.va,e=0;if(a.level>0){a.M.Lc===2&&(a.M.Lc=Jl(a));Gl(a,a.wc);Gl(a,a.nc);Hl(a,a.ra,a.wc.Fb);Hl(a,a.hb,a.nc.Fb);Gl(a,a.qd);for(e=18;e>=3&&a.ja[jl[e]*2+1]===0;e--);a.Pa+=3*(e+1)+5+5+4;var f=a.Pa+3+7>>>3;var g=a.Ib+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)wl(a,b?1:0,3),Cl(a,c,d);else if(a.strategy===4||g===f)wl(a,2+(b?1:0),3),Fl(a,kl,ll);else{wl(a,4+(b?1:0),3);c=a.wc.Fb+1;d=a.nc.Fb+1;e+=1;wl(a,c-257,5);wl(a,d-1,5);wl(a,e-4,4);for(f=0;f<e;f++)wl(a,
a.ja[jl[f]*2+1],3);Il(a,a.ra,c-1);Il(a,a.hb,d-1);Fl(a,a.ra,a.hb)}Al(a);b&&Bl(a);a.va=a.v;Ol(a.M)}
function P(a,b){a.aa[a.pending++]=b}
function Ql(a,b){a.aa[a.pending++]=b>>>8&255;a.aa[a.pending++]=b&255}
function Rl(a,b){var c=a.Ad,d=a.v,e=a.wa,f=a.Cd,g=a.v>a.la-262?a.v-(a.la-262):0,h=a.window,k=a.eb,l=a.Ia,m=a.v+258,n=h[d+e-1],r=h[d+e];a.wa>=a.wd&&(c>>=2);f>a.D&&(f=a.D);do{var t=b;if(h[t+e]===r&&h[t+e-1]===n&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<m;);t=258-(m-d);d=m-258;if(t>e){a.Eb=b;e=t;if(t>=f)break;n=h[d+e-1];r=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.D?e:a.D}
function Sl(a){var b=a.la,c;do{var d=a.Sd-a.D-a.v;if(a.v>=b+(b-262)){O.ub(a.window,a.window,b,b,0);a.Eb-=b;a.v-=b;a.va-=b;var e=c=a.vc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(a.M.na===0)break;e=a.M;c=a.window;f=a.v+a.D;var g=e.na;g>d&&(g=d);g===0?c=0:(e.na-=g,O.ub(c,e.input,e.nb,g,f),e.state.wrap===1?e.J=Zk(e.J,c,g,f):e.state.wrap===2&&(e.J=$k(e.J,c,g,f)),e.nb+=g,e.qb+=g,c=g);a.D+=c;if(a.D+a.sa>=3)for(d=a.v-a.sa,a.R=a.window[d],
a.R=(a.R<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.R=(a.R<<a.Ma^a.window[d+3-1])&a.La,a.Ia[d&a.eb]=a.head[a.R],a.head[a.R]=d,d++,a.sa--,a.D+a.sa<3););}while(a.D<262&&a.M.na!==0)}
function Tl(a,b){for(var c;;){if(a.D<262){Sl(a);if(a.D<262&&b===0)return 1;if(a.D===0)break}c=0;a.D>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.eb]=a.head[a.R],a.head[a.R]=a.v);c!==0&&a.v-c<=a.la-262&&(a.T=Rl(a,c));if(a.T>=3)if(c=Ll(a,a.v-a.Eb,a.T-3),a.D-=a.T,a.T<=a.Sc&&a.D>=3){a.T--;do a.v++,a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.eb]=a.head[a.R],a.head[a.R]=a.v;while(--a.T!==0);a.v++}else a.v+=a.T,a.T=0,a.R=a.window[a.v],a.R=(a.R<<a.Ma^a.window[a.v+1])&a.La;else c=Ll(a,0,
a.window[a.v]),a.D--,a.v++;if(c&&(Pl(a,!1),a.M.S===0))return 1}a.sa=a.v<2?a.v:2;return b===4?(Pl(a,!0),a.M.S===0?3:4):a.ya&&(Pl(a,!1),a.M.S===0)?1:2}
function Ul(a,b){for(var c,d;;){if(a.D<262){Sl(a);if(a.D<262&&b===0)return 1;if(a.D===0)break}c=0;a.D>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.eb]=a.head[a.R],a.head[a.R]=a.v);a.wa=a.T;a.Fd=a.Eb;a.T=2;c!==0&&a.wa<a.Sc&&a.v-c<=a.la-262&&(a.T=Rl(a,c),a.T<=5&&(a.strategy===1||a.T===3&&a.v-a.Eb>4096)&&(a.T=2));if(a.wa>=3&&a.T<=a.wa){d=a.v+a.D-3;c=Ll(a,a.v-1-a.Fd,a.wa-3);a.D-=a.wa-1;a.wa-=2;do++a.v<=d&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.eb]=a.head[a.R],a.head[a.R]=a.v);
while(--a.wa!==0);a.lb=0;a.T=2;a.v++;if(c&&(Pl(a,!1),a.M.S===0))return 1}else if(a.lb){if((c=Ll(a,0,a.window[a.v-1]))&&Pl(a,!1),a.v++,a.D--,a.M.S===0)return 1}else a.lb=1,a.v++,a.D--}a.lb&&(Ll(a,0,a.window[a.v-1]),a.lb=0);a.sa=a.v<2?a.v:2;return b===4?(Pl(a,!0),a.M.S===0?3:4):a.ya&&(Pl(a,!1),a.M.S===0)?1:2}
function Vl(a,b){for(var c,d,e,f=a.window;;){if(a.D<=258){Sl(a);if(a.D<=258&&b===0)return 1;if(a.D===0)break}a.T=0;if(a.D>=3&&a.v>0&&(d=a.v-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.v+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.T=258-(e-d);a.T>a.D&&(a.T=a.D)}a.T>=3?(c=Ll(a,1,a.T-3),a.D-=a.T,a.v+=a.T,a.T=0):(c=Ll(a,0,a.window[a.v]),a.D--,a.v++);if(c&&(Pl(a,!1),a.M.S===0))return 1}a.sa=0;return b===4?(Pl(a,!0),a.M.S===0?3:4):
a.ya&&(Pl(a,!1),a.M.S===0)?1:2}
function Wl(a,b){for(var c;;){if(a.D===0&&(Sl(a),a.D===0)){if(b===0)return 1;break}a.T=0;c=Ll(a,0,a.window[a.v]);a.D--;a.v++;if(c&&(Pl(a,!1),a.M.S===0))return 1}a.sa=0;return b===4?(Pl(a,!0),a.M.S===0?3:4):a.ya&&(Pl(a,!1),a.M.S===0)?1:2}
function Xl(a,b,c,d,e){this.ye=a;this.Ke=b;this.Ne=c;this.Je=d;this.ue=e}
var Yl;Yl=[new Xl(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(a.D<=1){Sl(a);if(a.D===0&&b===0)return 1;if(a.D===0)break}a.v+=a.D;a.D=0;var d=a.va+c;if(a.v===0||a.v>=d)if(a.D=a.v-d,a.v=d,Pl(a,!1),a.M.S===0)return 1;if(a.v-a.va>=a.la-262&&(Pl(a,!1),a.M.S===0))return 1}a.sa=0;if(b===4)return Pl(a,!0),a.M.S===0?3:4;a.v>a.va&&Pl(a,!1);return 1}),
new Xl(4,4,8,4,Tl),new Xl(4,5,16,8,Tl),new Xl(4,6,32,32,Tl),new Xl(4,4,16,16,Ul),new Xl(8,16,32,32,Ul),new Xl(8,16,128,128,Ul),new Xl(8,32,128,256,Ul),new Xl(32,128,258,1024,Ul),new Xl(32,258,258,4096,Ul)];
function Zl(){this.M=null;this.status=0;this.aa=null;this.wrap=this.pending=this.Yb=this.za=0;this.I=null;this.Ba=0;this.method=8;this.Cb=-1;this.eb=this.md=this.la=0;this.window=null;this.Sd=0;this.head=this.Ia=null;this.Cd=this.wd=this.strategy=this.level=this.Sc=this.Ad=this.wa=this.D=this.Eb=this.v=this.lb=this.Fd=this.T=this.va=this.Ma=this.La=this.Oc=this.vc=this.R=0;this.ra=new O.Ja(1146);this.hb=new O.Ja(122);this.ja=new O.Ja(78);Nl(this.ra);Nl(this.hb);Nl(this.ja);this.qd=this.nc=this.wc=
null;this.Ka=new O.Ja(16);this.da=new O.Ja(573);Nl(this.da);this.Ab=this.Na=0;this.depth=new O.Ja(573);Nl(this.depth);this.ia=this.oa=this.sa=this.matches=this.Ib=this.Pa=this.Qb=this.ya=this.Vb=this.Qc=0}
function $l(a,b){if(!a||!a.state||b>5||b<0)return a?Ml(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.na!==0||c.status===666&&b!==4)return Ml(a,a.S===0?-5:-2);c.M=a;var d=c.Cb;c.Cb=b;if(c.status===42)if(c.wrap===2)a.J=0,P(c,31),P(c,139),P(c,8),c.I?(P(c,(c.I.text?1:0)+(c.I.Xa?2:0)+(c.I.extra?4:0)+(c.I.name?8:0)+(c.I.comment?16:0)),P(c,c.I.time&255),P(c,c.I.time>>8&255),P(c,c.I.time>>16&255),P(c,c.I.time>>24&255),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,c.I.os&255),c.I.extra&&c.I.extra.length&&
(P(c,c.I.extra.length&255),P(c,c.I.extra.length>>8&255)),c.I.Xa&&(a.J=$k(a.J,c.aa,c.pending,0)),c.Ba=0,c.status=69):(P(c,0),P(c,0),P(c,0),P(c,0),P(c,0),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,3),c.status=113);else{var e=8+(c.md-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.v!==0&&(e|=32);c.status=113;Ql(c,e+(31-e%31));c.v!==0&&(Ql(c,a.J>>>16),Ql(c,a.J&65535));a.J=1}if(c.status===69)if(c.I.extra){for(e=c.pending;c.Ba<(c.I.extra.length&65535)&&(c.pending!==c.za||
(c.I.Xa&&c.pending>e&&(a.J=$k(a.J,c.aa,c.pending-e,e)),Ol(a),e=c.pending,c.pending!==c.za));)P(c,c.I.extra[c.Ba]&255),c.Ba++;c.I.Xa&&c.pending>e&&(a.J=$k(a.J,c.aa,c.pending-e,e));c.Ba===c.I.extra.length&&(c.Ba=0,c.status=73)}else c.status=73;if(c.status===73)if(c.I.name){e=c.pending;do{if(c.pending===c.za&&(c.I.Xa&&c.pending>e&&(a.J=$k(a.J,c.aa,c.pending-e,e)),Ol(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ba<c.I.name.length?c.I.name.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.I.Xa&&c.pending>
e&&(a.J=$k(a.J,c.aa,c.pending-e,e));f===0&&(c.Ba=0,c.status=91)}else c.status=91;if(c.status===91)if(c.I.comment){e=c.pending;do{if(c.pending===c.za&&(c.I.Xa&&c.pending>e&&(a.J=$k(a.J,c.aa,c.pending-e,e)),Ol(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ba<c.I.comment.length?c.I.comment.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.I.Xa&&c.pending>e&&(a.J=$k(a.J,c.aa,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.I.Xa?(c.pending+2>c.za&&Ol(a),c.pending+2<=c.za&&(P(c,
a.J&255),P(c,a.J>>8&255),a.J=0,c.status=113)):c.status=113);if(c.pending!==0){if(Ol(a),a.S===0)return c.Cb=-1,0}else if(a.na===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return Ml(a,-5);if(c.status===666&&a.na!==0)return Ml(a,-5);if(a.na!==0||c.D!==0||b!==0&&c.status!==666){d=c.strategy===2?Wl(c,b):c.strategy===3?Vl(c,b):Yl[c.level].ue(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.S===0&&(c.Cb=-1),0;if(d===2&&(b===1?(wl(c,2,3),xl(c,256,kl),c.ia===16?(vl(c,c.oa),c.oa=0,c.ia=0):c.ia>=
8&&(c.aa[c.pending++]=c.oa&255,c.oa>>=8,c.ia-=8)):b!==5&&(wl(c,0,3),Cl(c,0,0),b===3&&(Nl(c.head),c.D===0&&(c.v=0,c.va=0,c.sa=0))),Ol(a),a.S===0))return c.Cb=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(P(c,a.J&255),P(c,a.J>>8&255),P(c,a.J>>16&255),P(c,a.J>>24&255),P(c,a.qb&255),P(c,a.qb>>8&255),P(c,a.qb>>16&255),P(c,a.qb>>24&255)):(Ql(c,a.J>>>16),Ql(c,a.J&65535));Ol(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var am={};am=function(){this.input=null;this.qb=this.na=this.nb=0;this.output=null;this.jd=this.S=this.Gb=0;this.msg="";this.state=null;this.Lc=2;this.J=0};var bm=Object.prototype.toString;
function cm(a){if(!(this instanceof cm))return new cm(a);a=this.options=O.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.M=new am;this.M.S=0;var b=this.M;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=Ml(b,-2);else{e===8&&(e=9);var k=new Zl;b.state=k;k.M=b;k.wrap=h;k.I=null;k.md=e;k.la=1<<k.md;k.eb=k.la-1;k.Oc=f+7;k.vc=1<<k.Oc;k.La=k.vc-1;k.Ma=~~((k.Oc+3-1)/3);k.window=new O.rb(k.la*2);k.head=new O.Ja(k.vc);k.Ia=new O.Ja(k.la);k.Vb=1<<f+6;k.za=k.Vb*4;k.aa=new O.rb(k.za);k.Qb=1*k.Vb;k.Qc=3*k.Vb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.qb=b.jd=0;b.Lc=2;c=b.state;c.pending=0;c.Yb=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.J=c.wrap===2?
0:1;c.Cb=0;if(!Kl){d=Array(16);for(f=g=0;f<28;f++)for(ol[f]=g,e=0;e<1<<gl[f];e++)nl[g++]=f;nl[g-1]=f;for(f=g=0;f<16;f++)for(pl[f]=g,e=0;e<1<<hl[f];e++)ml[g++]=f;for(g>>=7;f<30;f++)for(pl[f]=g<<7,e=0;e<1<<hl[f]-7;e++)ml[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)kl[e*2+1]=8,e++,d[8]++;for(;e<=255;)kl[e*2+1]=9,e++,d[9]++;for(;e<=279;)kl[e*2+1]=7,e++,d[7]++;for(;e<=287;)kl[e*2+1]=8,e++,d[8]++;zl(kl,287,d);for(e=0;e<30;e++)ll[e*2+1]=5,ll[e*2]=yl(e,5);rl=new ql(kl,gl,257,286,15);sl=new ql(ll,
hl,0,30,15);tl=new ql([],il,0,19,7);Kl=!0}c.wc=new ul(c.ra,rl);c.nc=new ul(c.hb,sl);c.qd=new ul(c.ja,tl);c.oa=0;c.ia=0;Al(c);c=0}else c=Ml(b,-2);c===0&&(b=b.state,b.Sd=2*b.la,Nl(b.head),b.Sc=Yl[b.level].Ke,b.wd=Yl[b.level].ye,b.Cd=Yl[b.level].Ne,b.Ad=Yl[b.level].Je,b.v=0,b.va=0,b.D=0,b.sa=0,b.T=b.wa=2,b.lb=0,b.R=0);b=c}}else b=-2;if(b!==0)throw Error(el[b]);a.header&&(b=this.M)&&b.state&&b.state.wrap===2&&(b.state.I=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=Yk(a.dictionary):
bm.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.M;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.D)b=-2;else{b===1&&(a.J=Zk(a.J,f,g,0));l.wrap=0;g>=l.la&&(b===0&&(Nl(l.head),l.v=0,l.va=0,l.sa=0),c=new O.rb(l.la),O.ub(c,f,g-l.la,l.la,0),f=c,g=l.la);c=a.na;d=a.nb;e=a.input;a.na=g;a.nb=0;a.input=f;for(Sl(l);l.D>=3;){f=l.v;g=l.D-2;do l.R=(l.R<<l.Ma^l.window[f+3-1])&l.La,l.Ia[f&l.eb]=l.head[l.R],l.head[l.R]=f,f++;while(--g);
l.v=f;l.D=2;Sl(l)}l.v+=l.D;l.va=l.v;l.sa=l.D;l.D=0;l.T=l.wa=2;l.lb=0;a.nb=d;a.input=e;a.na=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(el[b]);this.th=!0}}
cm.prototype.push=function(a,b){var c=this.M,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=Yk(a):bm.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.nb=0;c.na=c.input.length;do{c.S===0&&(c.output=new O.rb(d),c.Gb=0,c.S=d);a=$l(c,e);if(a!==1&&a!==0)return dm(this,a),this.ended=!0,!1;if(c.S===0||c.na===0&&(e===4||e===2))if(this.options.to==="string"){var f=O.dd(c.output,c.Gb);b=f;f=f.length;if(f<65537&&(b.subarray&&Xk||!b.subarray))b=
String.fromCharCode.apply(null,O.dd(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=O.dd(c.output,c.Gb),this.chunks.push(b)}while((c.na>0||c.S===0)&&a!==1);if(e===4)return(c=this.M)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=Ml(c,-2):(c.state=null,a=d===113?Ml(c,-3):0)):a=-2,dm(this,a),this.ended=!0,a===0;e===2&&(dm(this,0),c.S=0);return!0};
function dm(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):O.ud(a.chunks));a.chunks=[];a.err=b;a.msg=a.M.msg}
function em(a,b){b=b||{};b.gzip=!0;b=new cm(b);b.push(a,!0);if(b.err)throw b.msg||el[b.err];return b.result}
;function fm(a){return a?(a=a.privateDoNotAccessOrElseSafeScriptWrappedValue)?Hb(a):null:null}
function gm(a){return a?(a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue)?nb(a):null:null}
;function hm(a){return nb(a===null?"null":a===void 0?"undefined":a)}
;function im(a){this.name=a}
;var jm=new im("rawColdConfigGroup");var km=new im("rawHotConfigGroup");function lm(a){this.F=L(a)}
v(lm,M);function mm(a){this.F=L(a)}
v(mm,M);mm.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new Gd(a,Fd):Id||(Id=new Gd(null,Fd));else if(a.constructor!==Gd)if(Ad&&a!=null&&a instanceof Uint8Array)a instanceof Uint8Array||Array.isArray(a),a=a.length?new Gd(new Uint8Array(a),Fd):Id||(Id=new Gd(null,Fd));else throw Error();return yf(this,1,a)};var nm=new im("continuationCommand");var om=new im("webCommandMetadata");var pm=new im("signalServiceEndpoint");var qm={Sf:"EMBEDDED_PLAYER_MODE_UNKNOWN",Pf:"EMBEDDED_PLAYER_MODE_DEFAULT",Rf:"EMBEDDED_PLAYER_MODE_PFP",Qf:"EMBEDDED_PLAYER_MODE_PFL"};var rm=new im("feedbackEndpoint");var ne={Xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",Hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",Pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",Wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",Zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",Og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
bh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",ah:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",Kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",Rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",gh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",fh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",eh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",Sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
Mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",hh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",Qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",ih:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",Dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",Cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",Fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
dh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",Gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",Eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
Bg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED",Ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_LACT_THRESHOLD_EXCEEDED",qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MATCHED_ON_REMOTE_CONNECTION",sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHABLE_ON_REMOTE_CONNECTION",rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MISATTRIBUTED_ON_REMOTE_CONNECTION",vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_TV_IS_SIGNED_IN_ON_REMOTE_CONNECTION",Ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_COLD_ON_REMOTE_CONNECTION",
Vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_NON_COLD_ON_REMOTE_CONNECTION",yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ON_REMOTE_CONNECTION",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_VALID",ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_INVALID",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_UNDEFINED",Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_DEFINED",xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_LACT_THRESHOLD_EXCEEDED",
Lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROUND_TRIP_HANDLING_ON_REMOTE_CONNECTION",ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_BEFORE_APP_RELOAD",tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_AFTER_APP_RELOAD",jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_INELIGIBLE",Tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TVHTML5_MID_ROLL_THRESHOLD_REACHED",ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_PENDING",
mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_ACTIVATED",kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_M2_ELIGIBLE",Ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_LANDSCAPE",Jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_PORTRAIT",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMBEDS_FACEOFF_UI_EVENT",og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_RECEIVED",gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ELIGIBLE_TO_SUPPRESS_TRANSPORT_CONTROLS_BUTTONS",
Yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_USER_HAS_THEATER_MODE_COOKIE_ENABLED",fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DOCUMENT_PICTURE_IN_PICTURE_SUPPORTED",Ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHORTS_NON_DEFAULT_ASPECT_RATIO",zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_PLAYER_IN_SQUEEZEBACK"};var sm=new im("shareEndpoint"),tm=new im("shareEntityEndpoint"),um=new im("shareEntityServiceEndpoint"),wm=new im("webPlayerShareEntityServiceEndpoint");var xm=new im("playlistEditEndpoint");var ym=new im("modifyChannelNotificationPreferenceEndpoint");var zm=new im("undoFeedbackEndpoint");var Am=new im("unsubscribeEndpoint");var Bm=new im("subscribeEndpoint");function Cm(){var a=Dm;F("yt.ads.biscotti.getId_")||E("yt.ads.biscotti.getId_",a)}
function Em(a){E("yt.ads.biscotti.lastId_",a)}
;function Fm(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var Gm=D.window,Hm,Im,Jm=(Gm==null?void 0:(Hm=Gm.yt)==null?void 0:Hm.config_)||(Gm==null?void 0:(Im=Gm.ytcfg)==null?void 0:Im.data_)||{};E("yt.config_",Jm);function Km(){Fm(Jm,arguments)}
function R(a,b){return a in Jm?Jm[a]:b}
function Lm(a){var b=Jm.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var Mm=[];function Nm(a){Mm.forEach(function(b){return b(a)})}
function Om(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Pm(b)}}:a}
function Pm(a){var b=F("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Km("ERRORS",b));Nm(a)}
function Qm(a,b,c,d,e){var f=F("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=R("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Km("ERRORS",f))}
;var Rm=/^[\w.]*$/,Sm={q:!0,search_query:!0};function Tm(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=Um(f[0]||""),h=Um(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Zb(k,h):c[g]=[k,h]}else c[g]=h}catch(r){var l=r,m=f[0],n=String(Tm);l.args=[{key:m,value:f[1],query:a,method:Vm===n?"unchanged":n}];Sm.hasOwnProperty(m)||Qm(l)}}return c}
var Vm=String(Tm);function Wm(a){var b=[];vg(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Rb(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function Xm(a){a.charAt(0)==="?"&&(a=a.substring(1));return Tm(a,"&")}
function Ym(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),Xm(a.length>1?a[1]:a[0])):{}}
function Zm(a,b){return $m(a,b||{},!0)}
function $m(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Xm(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return tc(a,e)+d}
function an(a){if(!b)var b=window.location.href;var c=a.match(kc)[1]||null,d=mc(a);c&&d?(a=a.match(kc),b=b.match(kc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?mc(b)===d&&(Number(b.match(kc)[4]||null)||null)===(Number(a.match(kc)[4]||null)||null):!0;return a}
function Um(a){return a&&a.match(Rm)?a:ic(a)}
;function bn(a){var b=cn;a=a===void 0?F("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Tj;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ia){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?Lj:g;try{var h=g.history.length}catch(Ia){h=0}e.u_his=h;var k;e.u_h=(k=Lj.screen)==null?void 0:k.height;var l;e.u_w=(l=Lj.screen)==null?void 0:l.width;var m;e.u_ah=(m=Lj.screen)==null?void 0:m.availHeight;var n;e.u_aw=
(n=Lj.screen)==null?void 0:n.availWidth;var r;e.u_cd=(r=Lj.screen)==null?void 0:r.colorDepth}catch(Ia){}var t;h=b.h;try{var w=h.screenX;var x=h.screenY}catch(Ia){}try{var z=h.outerWidth;var G=h.outerHeight}catch(Ia){}try{var H=h.innerWidth;var S=h.innerHeight}catch(Ia){}try{var Z=h.screenLeft;var mb=h.screenTop}catch(Ia){}try{H=h.innerWidth,S=h.innerHeight}catch(Ia){}try{var Sb=h.screen.availWidth;var Wa=h.screen.availTop}catch(Ia){}w=[Z,mb,w,x,Sb,Wa,z,G,H,S];try{var Db=(b.h.top||window).document,
Xa=Db.compatMode=="CSS1Compat"?Db.documentElement:Db.body;var Na=(new ug(Xa.clientWidth,Xa.clientHeight)).round()}catch(Ia){Na=new ug(-12245933,-12245933)}Db=Na;Na={};var Ja=Ja===void 0?D:Ja;Xa=new Zj;"SVGElement"in Ja&&"createElementNS"in Ja.document&&Xa.set(0);x=Qj();x["allow-top-navigation-by-user-activation"]&&Xa.set(1);x["allow-popups-to-escape-sandbox"]&&Xa.set(2);Ja.crypto&&Ja.crypto.subtle&&Xa.set(3);"TextDecoder"in Ja&&"TextEncoder"in Ja&&Xa.set(4);Ja=ak(Xa);Na.bc=Ja;Na.bih=Db.height;Na.biw=
Db.width;Na.brdim=w.join();b=b.i;b=b.prerendering?3:(t={visible:1,hidden:2,prerender:3,preview:4,unloaded:5,"":0}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""])!=null?t:0;t=(Na.vis=b,Na.wgl=!!Lj.WebGLRenderingContext,Na);c=d.call(c,e,t);c.ca_type="image";a&&(c.bid=a);return c}
var cn=new function(){var a=window.document;this.h=window;this.i=a};
E("yt.ads_.signals_.getAdSignalsString",function(a){return Wm(bn(a))});Ya();navigator.userAgent.indexOf(" (CrKey ");var dn="XMLHttpRequest"in D?function(){return new XMLHttpRequest}:null;
function en(){if(!dn)return null;var a=dn();return"open"in a?a:null}
function fn(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function gn(a,b){typeof a==="function"&&(a=Om(a));return window.setTimeout(a,b)}
;var hn="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(A(hn),["client_dev_set_cookie"]);function T(a){a=jn(a);return typeof a==="string"&&a==="false"?!1:!!a}
function kn(a,b){a=jn(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function jn(a){return R("EXPERIMENT_FLAGS",{})[a]}
function ln(){for(var a=[],b=R("EXPERIMENTS_FORCED_FLAGS",{}),c=y(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=R("EXPERIMENT_FLAGS",{});d=y(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var mn={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},nn="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(A(hn)),on=!1;function pn(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&Om(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=en();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;T("debug_forward_web_query_parameters")&&(a=qn(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=rn(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"===m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(n){Qm(n)}}l.send(d);return l}
function rn(a,b){b=b===void 0?{}:b;var c=an(a),d=R("INNERTUBE_CLIENT_NAME"),e=T("web_ajax_ignore_global_headers_if_set"),f;for(f in mn){var g=R(mn[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=R("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||(mc(a)?!1:!0))){k=a;var l;if(l=T("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=mc(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=nc(k)||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!mc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!mc(a)){try{var m=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(n){}m&&
(b["X-YouTube-Time-Zone"]=m)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&mc(a)||(b["X-YouTube-Ad-Signals"]=Wm(bn()));return b}
function sn(a,b){b.method="POST";b.postParams||(b.postParams={});return tn(a,b)}
function tn(a,b){var c=b.format||"JSON";a=un(a,b);var d=vn(a,b),e=!1,f=wn(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=fn(k),m=null,n=400<=k.status&&k.status<500,r=500<=k.status&&k.status<600;if(l||n||r)m=xn(a,c,k,b.convertToSafeHtml);l&&(l=yn(c,k,m));m=m||{};n=b.context||D;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=gn(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||D,f))},d)}return f}
function un(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Zm(a,b);return a}
function vn(a,b){var c=R("XSRF_FIELD_NAME"),d=R("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||mc(a)&&!b.withCredentials&&mc(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(T("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=Xm(e),Gg(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):sc(e));f=e||f&&!zg(f);!on&&f&&b.method!=="POST"&&(on=!0,Pm(Error("AJAX request with postData should use POST")));return e}
function xn(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Qm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?zn(a):null)e={},Rb(a.getElementsByTagName("*"),function(g){e[g.tagName]=An(g)})}d&&Bn(e);
return e}
function Bn(a){if(Oa(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=a[b];var d=kb();c=d?d.createHTML(c):c;a[b]=new Eb(c)}else Bn(a[b])}}
function yn(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function zn(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function An(a){var b="";Rb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function qn(a){var b=window.location.search,c=mc(a);T("debug_handle_relative_url_for_query_forward_killswitch")||!c&&an(a)&&(c=document.location.hostname);var d=nc(a);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Xm(b),f={};Rb(nn,function(g){e[g]&&(f[g]=e[g])});
return $m(a,f||{},!1)}
var wn=pn;var Cn=[{Tc:function(a){return"Cannot read property '"+a.key+"'"},
zc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Tc:function(a){return"Cannot call '"+a.key+"'"},
zc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Tc:function(a){return a.key+" is not defined"},
zc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var En={Za:[],Ua:[{callback:Dn,weight:500}]};function Dn(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Fn(){this.Ua=[];this.Za=[]}
var Gn;function Hn(){if(!Gn){var a=Gn=new Fn;a.Za.length=0;a.Ua.length=0;En.Za&&a.Za.push.apply(a.Za,En.Za);En.Ua&&a.Ua.push.apply(a.Ua,En.Ua)}return Gn}
;var In=new N;function Jn(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Kn(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=Kn(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=Kn(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function Kn(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function Ln(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Mn(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=Jn(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?Mn(f+".ve",g,h,k):0;d+=f;d+=Mn(e,a[e],b,c);if(d>500)break}}else c[b]=Nn(a),d+=c[b].length;else c[b]=Nn(a),d+=c[b].length;return d}
function Mn(a,b,c,d){c+="."+a;a=Nn(b);d[c]=a;return c.length+a.length}
function Nn(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function On(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function Pn(){if(!D.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return D.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":D.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":D.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":D.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function Qn(){this.Nd=!0}
function Rn(){Qn.instance||(Qn.instance=new Qn);return Qn.instance}
function Sn(a,b){a={};var c=[];"USER_SESSION_ID"in Jm&&c.push({key:"u",value:R("USER_SESSION_ID")});if(c=ng(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(R("SESSION_INDEX",0)),c=isNaN(c)?0:c),T("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Jm||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in Jm&&(a["X-Goog-PageId"]=R("DELEGATED_SESSION_ID"));return a}
;var Tn={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function Un(a,b,c,d,e){kg.set(""+a,b,{Xb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function Vn(a){return kg.get(""+a,void 0)}
function Wn(a,b,c){kg.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function Xn(){if(T("embeds_web_enable_cookie_detection_fix")){if(!D.navigator.cookieEnabled)return!1}else if(!kg.isEnabled())return!1;if(kg.h.cookie)return!0;T("embeds_web_enable_cookie_detection_fix")?kg.set("TESTCOOKIESENABLED","1",{Xb:60,cf:"none",secure:!0}):kg.set("TESTCOOKIESENABLED","1",{Xb:60});if(kg.get("TESTCOOKIESENABLED")!=="1")return!1;kg.remove("TESTCOOKIESENABLED");return!0}
;var Yn=F("ytglobal.prefsUserPrefsPrefs_")||{};E("ytglobal.prefsUserPrefsPrefs_",Yn);function Zn(){this.h=R("ALT_PREF_COOKIE_NAME","PREF");this.i=R("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Vn(this.h);a&&this.parse(a)}
var $n;function ao(){$n||($n=new Zn);return $n}
p=Zn.prototype;p.get=function(a,b){bo(a);co(a);a=Yn[a]!==void 0?Yn[a].toString():null;return a!=null?a:b?b:""};
p.set=function(a,b){bo(a);co(a);if(b==null)throw Error("ExpectedNotNull");Yn[a]=b.toString()};
function eo(a){return!!((fo("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
p.remove=function(a){bo(a);co(a);delete Yn[a]};
p.clear=function(){for(var a in Yn)delete Yn[a]};
function co(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function bo(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function fo(a){a=Yn[a]!==void 0?Yn[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
p.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Yn[d]=c.toString())}};var go={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},ho={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function io(){var a=D.navigator;return a?a.connection:void 0}
function jo(){var a=io();if(a){var b=go[a.type||"unknown"]||"CONN_UNKNOWN";a=go[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function ko(){var a=io();if(a!=null&&a.effectiveType)return ho.hasOwnProperty(a.effectiveType)?ho[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function U(a){var b=C.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(A(b));Object.setPrototypeOf(this,this.constructor.prototype)}
v(U,Error);function lo(){try{return mo(),!0}catch(a){return!1}}
function mo(a){if(R("DATASYNC_ID")!==void 0)return R("DATASYNC_ID");throw new U("Datasync ID not set",a===void 0?"unknown":a);}
;function no(){}
function oo(a,b){return Yj.Sa(a,0,b)}
no.prototype.pa=function(a,b){return this.Sa(a,1,b)};
no.prototype.Mb=function(a){var b=F("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var po=kn("web_emulated_idle_callback_delay",300),qo=1E3/60-3,ro=[8,5,4,3,2,1,0];
function so(a){a=a===void 0?{}:a;I.call(this);this.i=[];this.j={};this.Z=this.h=0;this.Y=this.u=!1;this.P=[];this.U=this.ha=!1;for(var b=y(ro),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.o=0;this.Ic=a.timeout||1;this.G=qo;this.A=0;this.xa=this.Pe.bind(this);this.Lb=this.wf.bind(this);this.Qa=this.Yd.bind(this);this.Ra=this.ze.bind(this);this.fb=this.We.bind(this);this.Fa=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!T("disable_scheduler_requestIdleCallback");(this.ma=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.xa)}
v(so,I);p=so.prototype;p.Mb=function(a){var b=Ya();to(this,a);a=Ya()-b;this.u||(this.G-=a)};
p.Sa=function(a,b,c){++this.Z;if(b===10)return this.Mb(a),this.Z;var d=this.Z;this.j[d]=a;this.u&&!c?this.P.push({id:d,priority:b}):(this.i[b].push(d),this.Y||this.u||(this.h!==0&&uo(this)!==this.A&&this.stop(),this.start()));return d};
p.qa=function(a){delete this.j[a]};
function vo(a){a.P.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
p.isHidden=function(){return!!document.hidden||!1};
function wo(a){return!a.isHidden()&&a.ma}
function uo(a){if(a.i[8].length){if(a.U)return 4;if(wo(a))return 3}for(var b=5;b>=a.o;b--)if(a.i[b].length>0)return b>0?wo(a)?3:2:1;return 0}
p.Ha=function(a){var b=F("yt.logging.errors.log");b&&b(a)};
function to(a,b){try{b()}catch(c){a.Ha(c)}}
function xo(a){for(var b=y(ro),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
p.ze=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ha=!0;yo(this,b);this.ha=!1};
p.wf=function(){yo(this)};
p.Yd=function(){zo(this)};
p.We=function(a){this.U=!0;var b=uo(this);b===4&&b!==this.A&&(this.stop(),this.start());yo(this,void 0,a);this.U=!1};
p.Pe=function(){this.isHidden()||zo(this);this.h&&(this.stop(),this.start())};
function zo(a){a.stop();a.u=!0;for(var b=Ya(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&to(a,e)}Ao(a);a.u=!1;xo(a)&&a.start();b=Ya()-b;a.G-=b}
function Ao(a){for(var b=0,c=a.P.length;b<c;b++){var d=a.P[b];a.i[d.priority].push(d.id)}a.P.length=0}
function yo(a,b,c){a.U&&a.A===4&&a.h||a.stop();a.u=!0;b=Ya()+(b||a.G);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ha(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&to(a,f);d=a.ha?0:1;d=a.o>d?a.o:d;if(!(Ya()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&to(a,c)}while(c&&Ya()<b)}a.u=!1;Ao(a);a.G=qo;xo(a)&&a.start()}
p.start=function(){this.Y=!1;if(this.h===0)switch(this.A=uo(this),this.A){case 1:var a=this.Ra;this.h=this.Fa?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,po);break;case 2:this.h=window.setTimeout(this.Lb,this.Ic);break;case 3:this.h=window.requestAnimationFrame(this.fb);break;case 4:this.h=window.setTimeout(this.Qa,0)}};
p.pause=function(){this.stop();this.Y=!0};
p.stop=function(){if(this.h){switch(this.A){case 1:var a=this.h;this.Fa?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
p.ba=function(){vo(this);this.stop();this.ma&&document.removeEventListener("visibilitychange",this.xa);I.prototype.ba.call(this)};var Bo=F("yt.scheduler.instance.timerIdMap_")||{},Co=kn("kevlar_tuner_scheduler_soft_state_timer_ms",800),Do=0,Eo=0;function Fo(){var a=F("ytglobal.schedulerInstanceInstance_");if(!a||a.ea)a=new so(R("scheduler")||{}),E("ytglobal.schedulerInstanceInstance_",a);return a}
function Go(){Ho();var a=F("ytglobal.schedulerInstanceInstance_");a&&(zc(a),E("ytglobal.schedulerInstanceInstance_",null))}
function Ho(){vo(Fo());for(var a in Bo)Bo.hasOwnProperty(a)&&delete Bo[Number(a)]}
function Io(a,b,c){if(!c)return c=c===void 0,-Fo().Sa(a,b,c);var d=window.setTimeout(function(){var e=Fo().Sa(a,b);Bo[d]=e},c);
return d}
function Jo(a){Fo().Mb(a)}
function Ko(a){var b=Fo();if(a<0)b.qa(-a);else{var c=Bo[a];c?(b.qa(c),delete Bo[a]):window.clearTimeout(a)}}
function Lo(){Mo()}
function Mo(){window.clearTimeout(Do);Fo().start()}
function No(){Fo().pause();window.clearTimeout(Do);Do=window.setTimeout(Lo,Co)}
function Oo(){window.clearTimeout(Eo);Eo=window.setTimeout(function(){Po(0)},Co)}
function Po(a){Oo();var b=Fo();b.o=a;b.start()}
function Qo(a){Oo();var b=Fo();b.o>a&&(b.o=a,b.start())}
function Ro(){window.clearTimeout(Eo);var a=Fo();a.o=0;a.start()}
;function So(){no.apply(this,arguments)}
v(So,no);function To(){So.instance||(So.instance=new So);return So.instance}
So.prototype.Sa=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=F("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):gn(a,c||0)};
So.prototype.qa=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=F("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
So.prototype.start=function(){var a=F("yt.scheduler.instance.start");a&&a()};
So.prototype.pause=function(){var a=F("yt.scheduler.instance.pause");a&&a()};
var Yj=To();
T("web_scheduler_auto_init")&&!F("yt.scheduler.initialized")&&(E("yt.scheduler.instance.dispose",Go),E("yt.scheduler.instance.addJob",Io),E("yt.scheduler.instance.addImmediateJob",Jo),E("yt.scheduler.instance.cancelJob",Ko),E("yt.scheduler.instance.cancelAllJobs",Ho),E("yt.scheduler.instance.start",Mo),E("yt.scheduler.instance.pause",No),E("yt.scheduler.instance.setPriorityThreshold",Po),E("yt.scheduler.instance.enablePriorityThreshold",Qo),E("yt.scheduler.instance.clearPriorityThreshold",Ro),E("yt.scheduler.initialized",
!0));function Uo(a){var b=new yk;this.h=(a=b.isAvailable()?a?new zk(b,a):b:null)?new tk(a):null;this.i=document.domain||window.location.hostname}
Uo.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new Ui).serialize(b))}catch(f){return}else e=escape(b);Un(a,e,c,this.i)};
Uo.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Vn(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Uo.prototype.remove=function(a){this.h&&this.h.remove(a);Wn(a,"/",this.i)};var Vo=function(){var a;return function(){a||(a=new Uo("ytidb"));return a}}();
function Wo(){var a;return(a=Vo())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Xo=[],Yo,Zo=!1;function $o(){var a={};for(Yo=new ap(a.handleError===void 0?bp:a.handleError,a.logEvent===void 0?cp:a.logEvent);Xo.length>0;)switch(a=Xo.shift(),a.type){case "ERROR":Yo.Ha(a.payload);break;case "EVENT":Yo.logEvent(a.eventType,a.payload)}}
function dp(a){Zo||(Yo?Yo.Ha(a):(Xo.push({type:"ERROR",payload:a}),Xo.length>10&&Xo.shift()))}
function ep(a,b){Zo||(Yo?Yo.logEvent(a,b):(Xo.push({type:"EVENT",eventType:a,payload:b}),Xo.length>10&&Xo.shift()))}
;function fp(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function gp(a){return a.substr(0,a.indexOf(":"))||a}
;var hp=rd||sd;function ip(a){var b=ad();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var jp={},kp=(jp.AUTH_INVALID="No user identifier specified.",jp.EXPLICIT_ABORT="Transaction was explicitly aborted.",jp.IDB_NOT_SUPPORTED="IndexedDB is not supported.",jp.MISSING_INDEX="Index not created.",jp.MISSING_OBJECT_STORES="Object stores not created.",jp.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",jp.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",jp.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
jp.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",jp.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",jp.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",jp.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",jp),lp={},mp=(lp.AUTH_INVALID="ERROR",lp.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",lp.EXPLICIT_ABORT="IGNORED",lp.IDB_NOT_SUPPORTED="ERROR",lp.MISSING_INDEX=
"WARNING",lp.MISSING_OBJECT_STORES="ERROR",lp.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",lp.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",lp.QUOTA_EXCEEDED="WARNING",lp.QUOTA_MAYBE_EXCEEDED="WARNING",lp.UNKNOWN_ABORT="WARNING",lp.INCOMPATIBLE_DB_VERSION="WARNING",lp),np={},op=(np.AUTH_INVALID=!1,np.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,np.EXPLICIT_ABORT=!1,np.IDB_NOT_SUPPORTED=!1,np.MISSING_INDEX=!1,np.MISSING_OBJECT_STORES=!1,np.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,np.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,np.QUOTA_EXCEEDED=!1,np.QUOTA_MAYBE_EXCEEDED=!0,np.UNKNOWN_ABORT=!0,np.INCOMPATIBLE_DB_VERSION=!1,np);function pp(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?kp[a]:c;d=d===void 0?mp[a]:d;e=e===void 0?op[a]:e;U.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,pp.prototype)}
v(pp,U);function qp(a,b){pp.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},kp.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,qp.prototype)}
v(qp,pp);function rp(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,rp.prototype)}
v(rp,Error);var sp=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function tp(a,b,c,d){b=gp(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof pp)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new pp("QUOTA_EXCEEDED",a);if(td&&e.name==="UnknownError")return new pp("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof rp)return new pp("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&sp.some(function(f){return e.message.includes(f)}))return new pp("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new pp("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Ed:e.name})];e.level="WARNING";return e}
function up(a,b,c){var d=Wo();return new pp("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function vp(a){if(!a)throw Error();throw a;}
function wp(a){return a}
function xp(a){this.h=a}
function yp(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=y(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=y(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
yp.all=function(a){return new yp(new xp(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={Bb:0};f.Bb<a.length;f={Bb:f.Bb},++f.Bb)yp.resolve(a[f.Bb]).then(function(g){return function(h){d[g.Bb]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
yp.resolve=function(a){return new yp(new xp(function(b,c){a instanceof yp?a.then(b,c):b(a)}))};
yp.reject=function(a){return new yp(new xp(function(b,c){c(a)}))};
yp.prototype.then=function(a,b){var c=this,d=a!=null?a:wp,e=b!=null?b:vp;return new yp(new xp(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){zp(c,c,d,f,g)}),c.i.push(function(){Ap(c,c,e,f,g)})):c.state.status==="FULFILLED"?zp(c,c,d,f,g):c.state.status==="REJECTED"&&Ap(c,c,e,f,g)}))};
yp.prototype.catch=function(a){return this.then(void 0,a)};
function zp(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof yp?Bp(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Ap(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof yp?Bp(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Bp(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof yp?Bp(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Cp(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Dp(a){return new Promise(function(b,c){Cp(a,b,c)})}
function Ep(a){return new yp(new xp(function(b,c){Cp(a,b,c)}))}
;function Fp(a,b){return new yp(new xp(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Gp=window,V=Gp.ytcsi&&Gp.ytcsi.now?Gp.ytcsi.now:Gp.performance&&Gp.performance.timing&&Gp.performance.now&&Gp.performance.timing.navigationStart?function(){return Gp.performance.timing.navigationStart+Gp.performance.now()}:function(){return(new Date).getTime()};function Hp(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(V());this.i=!1}
p=Hp.prototype;p.add=function(a,b,c){return Ip(this,[a],{mode:"readwrite",ka:!0},function(d){return d.objectStore(a).add(b,c)})};
p.clear=function(a){return Ip(this,[a],{mode:"readwrite",ka:!0},function(b){return b.objectStore(a).clear()})};
p.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
p.count=function(a,b){return Ip(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).count(b)})};
function Jp(a,b,c){a=a.h.createObjectStore(b,c);return new Kp(a)}
p.delete=function(a,b){return Ip(this,[a],{mode:"readwrite",ka:!0},function(c){return c.objectStore(a).delete(b)})};
p.get=function(a,b){return Ip(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).get(b)})};
function Lp(a,b,c){return Ip(a,[b],{mode:"readwrite",ka:!0},function(d){d=d.objectStore(b);return Ep(d.h.put(c,void 0))})}
p.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Ip(a,b,c,d){var e,f,g,h,k,l,m,n,r,t,w,x;return B(function(z){switch(z.h){case 1:var G={mode:"readonly",ka:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?G.mode=c:Object.assign(G,c);e=G;a.transactionCount++;f=e.ka?3:1;g=0;case 2:if(h){z.B(4);break}g++;k=Math.round(V());va(z,5);l=a.h.transaction(b,e.mode);G=z.yield;var H=new Mp(l);H=Np(H,d);return G.call(z,H,7);case 7:return m=z.i,n=Math.round(V()),Op(a,k,n,g,void 0,b.join(),e),z.return(m);case 5:r=xa(z);t=Math.round(V());w=tp(r,
a.h.name,b.join(),a.h.version);if((x=w instanceof pp&&!w.h)||g>=f)Op(a,k,t,g,w,b.join(),e),h=w;z.B(2);break;case 4:return z.return(Promise.reject(h))}})}
function Op(a,b,c,d,e,f,g){b=c-b;e?(e instanceof pp&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&ep("QUOTA_EXCEEDED",{dbName:gp(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof pp&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=2147483648&&(c=0),ep("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Pp(a,!1,d,f,b,g.tag),dp(e)):Pp(a,!0,d,f,b,g.tag)}
function Pp(a,b,c,d,e,f){ep("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
p.getName=function(){return this.h.name};
function Kp(a){this.h=a}
p=Kp.prototype;p.add=function(a,b){return Ep(this.h.add(a,b))};
p.autoIncrement=function(){return this.h.autoIncrement};
p.clear=function(){return Ep(this.h.clear()).then(function(){})};
function Qp(a,b,c){a.h.createIndex(b,c,{unique:!1})}
p.count=function(a){return Ep(this.h.count(a))};
function Rp(a,b){return Sp(a,{query:b},function(c){return c.delete().then(function(){return Tp(c)})}).then(function(){})}
p.delete=function(a){return a instanceof IDBKeyRange?Rp(this,a):Ep(this.h.delete(a))};
p.get=function(a){return Ep(this.h.get(a))};
p.index=function(a){try{return new Up(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new rp(a,this.h.name);throw b;}};
p.getName=function(){return this.h.name};
p.keyPath=function(){return this.h.keyPath};
function Sp(a,b,c){a=a.h.openCursor(b.query,b.direction);return Vp(a).then(function(d){return Fp(d,c)})}
function Mp(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=pp;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Np(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return y(d).next().value})}
Mp.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new pp("EXPLICIT_ABORT");};
Mp.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new Kp(a),this.i.set(a,b));return b};
function Up(a){this.h=a}
p=Up.prototype;p.count=function(a){return Ep(this.h.count(a))};
p.delete=function(a){return Wp(this,{query:a},function(b){return b.delete().then(function(){return Tp(b)})})};
p.get=function(a){return Ep(this.h.get(a))};
p.keyPath=function(){return this.h.keyPath};
p.unique=function(){return this.h.unique};
function Wp(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return Vp(a).then(function(d){return Fp(d,c)})}
function Xp(a,b){this.request=a;this.cursor=b}
function Vp(a){return Ep(a).then(function(b){return b?new Xp(a,b):null})}
function Tp(a){a.cursor.continue(void 0);return Vp(a.request)}
Xp.prototype.delete=function(){return Ep(this.cursor.delete()).then(function(){})};
Xp.prototype.getValue=function(){return this.cursor.value};
Xp.prototype.update=function(a){return Ep(this.cursor.update(a))};function Yp(a,b,c){return new Promise(function(d,e){function f(){r||(r=new Hp(g.result,{closed:n}));return r}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.be,k=c.blocking,l=c.tf,m=c.upgrade,n=c.closed,r;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&ep("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:gp(a)});var w=f(),x=new Mp(g.transaction);
m&&m(w,function(z){return t.oldVersion<z&&t.newVersion>=z},x);
x.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){ep("IDB_UNEXPECTEDLY_CLOSED",{dbName:gp(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Zp(a,b,c){c=c===void 0?{}:c;return Yp(a,b,c)}
function $p(a,b){b=b===void 0?{}:b;var c,d,e,f;return B(function(g){if(g.h==1)return va(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.be)&&c.addEventListener("blocked",function(){e()}),g.yield(Dp(c),4);
if(g.h!=2)return wa(g,0);f=xa(g);throw tp(f,a,"",-1);})}
;function aq(a,b){this.name=a;this.options=b;this.j=!0;this.u=this.o=0}
aq.prototype.i=function(a,b,c){c=c===void 0?{}:c;return Zp(a,b,c)};
aq.prototype.delete=function(a){a=a===void 0?{}:a;return $p(this.name,a)};
function bq(a,b){return new pp("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function cq(a,b){if(!b)throw up("openWithToken",gp(a.name));return a.open()}
aq.prototype.open=function(){function a(){var f,g,h,k,l,m,n,r,t,w;return B(function(x){switch(x.h){case 1:return g=(f=Error().stack)!=null?f:"",va(x,2),x.yield(c.i(c.name,c.options.version,e),4);case 4:for(var z=h=x.i,G=c.options,H=[],S=y(Object.keys(G.Hb)),Z=S.next();!Z.done;Z=S.next()){Z=Z.value;var mb=G.Hb[Z],Sb=mb.Xe===void 0?Number.MAX_VALUE:mb.Xe;!(z.h.version>=mb.Ob)||z.h.version>=Sb||z.h.objectStoreNames.contains(Z)||H.push(Z)}k=H;if(k.length===0){x.B(5);break}l=Object.keys(c.options.Hb);
m=h.objectStoreNames();if(c.u<kn("ytidb_reopen_db_retries",0))return c.u++,h.close(),dp(new pp("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());if(!(c.o<kn("ytidb_remake_db_retries",1))){x.B(6);break}c.o++;return x.yield(c.delete(),7);case 7:return dp(new pp("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());case 6:throw new qp(m,l);case 5:return x.return(h);case 2:n=xa(x);
if(n instanceof DOMException?n.name!=="VersionError":"DOMError"in self&&n instanceof DOMError?n.name!=="VersionError":!(n instanceof Object&&"message"in n)||n.message!=="An attempt was made to open a database using a lower version than the existing version."){x.B(8);break}return x.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:r=x.i;t=r.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw r.close(),c.j=!1,bq(c,t);return x.return(r);case 8:throw b(),n instanceof
Error&&!T("ytidb_async_stack_killswitch")&&(n.stack=n.stack+"\n"+g.substring(g.indexOf("\n")+1)),tp(n,c.name,"",(w=c.options.version)!=null?w:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw bq(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,tf:b,upgrade:this.options.upgrade};return this.h=d=a()};var dq=new aq("YtIdbMeta",{Hb:{databases:{Ob:1}},upgrade:function(a,b){b(1)&&Jp(a,"databases",{keyPath:"actualName"})}});
function eq(a,b){var c;return B(function(d){if(d.h==1)return d.yield(cq(dq,b),2);c=d.i;return d.return(Ip(c,["databases"],{ka:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Ep(f.h.put(a,void 0)).then(function(){})})}))})}
function fq(a,b){var c;return B(function(d){if(d.h==1)return a?d.yield(cq(dq,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function gq(a,b){var c,d;return B(function(e){return e.h==1?(c=[],e.yield(cq(dq,b),2)):e.h!=3?(d=e.i,e.yield(Ip(d,["databases"],{ka:!0,mode:"readonly"},function(f){c.length=0;return Sp(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return Tp(g)})}),3)):e.return(c)})}
function hq(a){return gq(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function iq(a,b,c){return gq(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function jq(a){var b,c;return B(function(d){if(d.h==1)return b=mo("YtIdbMeta hasAnyMeta other"),d.yield(gq(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var kq,lq=new function(){}(new function(){});
function mq(){var a,b,c,d;return B(function(e){switch(e.h){case 1:a=Wo();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=hp)f=/WebKit\/([0-9]+)/.exec(ad()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(ad()),f=!(f&&parseInt(f[1],10)>=602));if(f||nd)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
va(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(eq(d,lq),4);case 4:return e.yield(fq("yt-idb-test-do-not-use",lq),5);case 5:return e.return(!0);case 2:return xa(e),e.return(!1)}})}
function nq(){if(kq!==void 0)return kq;Zo=!0;return kq=mq().then(function(a){Zo=!1;var b;if((b=Vo())!=null&&b.h){var c;b={hasSucceededOnce:((c=Wo())==null?void 0:c.hasSucceededOnce)||a};var d;(d=Vo())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function oq(){return F("ytglobal.idbToken_")||void 0}
function pq(){var a=oq();return a?Promise.resolve(a):nq().then(function(b){(b=b?lq:void 0)&&E("ytglobal.idbToken_",b);return b})}
;var qq=0;function rq(a,b){qq||(qq=Yj.pa(function(){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:return h.yield(pq(),2);case 2:c=h.i;if(!c)return h.return();d=!0;va(h,3);return h.yield(iq(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.B(6);break}f=e[0];return h.yield($p(f.actualName),7);case 7:return h.yield(fq(f.actualName,c),6);case 6:wa(h,4);break;case 3:g=xa(h),dp(g),d=!1;case 4:Yj.qa(qq),qq=0,d&&rq(a,b),h.h=0}})}))}
function sq(){var a;return B(function(b){return b.h==1?b.yield(pq(),2):(a=b.i)?b.return(jq(a)):b.return(!1)})}
new Aj;function tq(a){if(!lo())throw a=new pp("AUTH_INVALID",{dbName:a}),dp(a),a;var b=mo();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function uq(a,b,c,d){var e,f,g,h,k,l;return B(function(m){switch(m.h){case 1:return f=(e=Error().stack)!=null?e:"",m.yield(pq(),2);case 2:g=m.i;if(!g)throw h=up("openDbImpl",a,b),T("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),dp(h),h;fp(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:tq(a);va(m,3);return m.yield(eq(k,g),5);case 5:return m.yield(Zp(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=xa(m),va(m,7),m.yield(fq(k.actualName,
g),9);case 9:wa(m,8);break;case 7:xa(m);case 8:throw l;}})}
function vq(a,b,c){c=c===void 0?{}:c;return uq(a,b,!1,c)}
function wq(a,b,c){c=c===void 0?{}:c;return uq(a,b,!0,c)}
function xq(a,b){b=b===void 0?{}:b;var c,d;return B(function(e){if(e.h==1)return e.yield(pq(),2);if(e.h!=3){c=e.i;if(!c)return e.return();fp(a);d=tq(a);return e.yield($p(d.actualName,b),3)}return e.yield(fq(d.actualName,c),0)})}
function yq(a,b,c){a=a.map(function(d){return B(function(e){return e.h==1?e.yield($p(d.actualName,b),2):e.yield(fq(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function zq(){var a=a===void 0?{}:a;var b,c;return B(function(d){if(d.h==1)return d.yield(pq(),2);if(d.h!=3){b=d.i;if(!b)return d.return();fp("LogsDatabaseV2");return d.yield(hq(b),3)}c=d.i;return d.yield(yq(c,a,b),0)})}
function Aq(a,b){b=b===void 0?{}:b;var c;return B(function(d){if(d.h==1)return d.yield(pq(),2);if(d.h!=3){c=d.i;if(!c)return d.return();fp(a);return d.yield($p(a,b),3)}return d.yield(fq(a,c),0)})}
;function Bq(a,b){aq.call(this,a,b);this.options=b;fp(a)}
v(Bq,aq);function Cq(a,b){var c;return function(){c||(c=new Bq(a,b));return c}}
Bq.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?wq:vq)(a,b,Object.assign({},c))};
Bq.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?Aq:xq)(this.name,a)};
function Dq(a,b){return Cq(a,b)}
;var Eq={},Fq=Dq("ytGcfConfig",{Hb:(Eq.coldConfigStore={Ob:1},Eq.hotConfigStore={Ob:1},Eq),shared:!1,upgrade:function(a,b){b(1)&&(Qp(Jp(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),Qp(Jp(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Gq(a){return cq(Fq(),a)}
function Hq(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:V()},g.yield(Gq(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(Lp(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Iq(a,b,c,d){var e,f,g;return B(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:V()},h.yield(Gq(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(Lp(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Jq(a){var b,c;return B(function(d){return d.h==1?d.yield(Gq(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Ip(b,["coldConfigStore"],{mode:"readwrite",ka:!0},function(e){return Wp(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Kq(a){var b,c;return B(function(d){return d.h==1?d.yield(Gq(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Ip(b,["hotConfigStore"],{mode:"readwrite",ka:!0},function(e){return Wp(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Lq(){I.call(this);this.i=[];this.h=[];var a=F("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(A(a)),this.h=a):(this.h=[],E("yt.gcf.config.hotUpdateCallbacks",this.h))}
v(Lq,I);Lq.prototype.ba=function(){for(var a=y(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;I.prototype.ba.call(this)};function Mq(){this.h=0;this.i=new Lq}
function Nq(){var a;return(a=F("yt.gcf.config.hotConfigGroup"))!=null?a:R("RAW_HOT_CONFIG_GROUP")}
function Oq(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:if(!T("start_client_gcf")){g.B(0);break}c&&(a.j=c,E("yt.gcf.config.hotConfigGroup",a.j||null));a.o(b);d=oq();if(!d){g.B(3);break}if(c){g.B(4);break}return g.yield(Kq(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(Hq(c,b,d),3);case 3:if(c)for(var h=c,k=y(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function Pq(a,b,c){var d,e,f,g;return B(function(h){if(h.h==1){if(!T("start_client_gcf"))return h.B(0);a.coldHashData=b;E("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=oq())?c?h.B(4):h.yield(Jq(d),5):h.B(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.B(0);g=c.configData;return h.yield(Iq(c,b,g,d),0)})}
function Qq(){if(!Mq.instance){var a=new Mq;Mq.instance=a}a=Mq.instance;var b=V()-a.h;if(!(a.h!==0&&b<kn("send_config_hash_timer"))){b=F("yt.gcf.config.coldConfigData");var c=F("yt.gcf.config.hotHashData"),d=F("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=V());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
Mq.prototype.o=function(a){this.hotHashData=a;E("yt.gcf.config.hotHashData",this.hotHashData||null)};function Rq(){return"INNERTUBE_API_KEY"in Jm&&"INNERTUBE_API_VERSION"in Jm}
function Sq(){return{innertubeApiKey:R("INNERTUBE_API_KEY"),innertubeApiVersion:R("INNERTUBE_API_VERSION"),Ae:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),yd:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Oh:R("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION"),Ce:R("INNERTUBE_CONTEXT_HL"),Be:R("INNERTUBE_CONTEXT_GL"),De:R("INNERTUBE_HOST_OVERRIDE")||"",Ee:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Ph:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Tq(a){var b={client:{hl:a.Ce,gl:a.Be,clientName:a.yd,clientVersion:a.innertubeContextClientVersion,configInfo:a.Ae}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=D.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=ln();c.length>0&&(b.request={internalExperimentFlags:c});c=a.yd;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=Pn()}(d=F("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(T("web_log_memory_total_kbytes")&&((e=D.navigator)==null?0:e.deviceMemory)){var f;e=(f=D.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=jo())&&b&&(b.client.connectionType=a);T("web_log_effective_connection_type")&&
(a=ko())&&b&&(b.client.effectiveConnectionType=a);T("start_client_gcf")&&(e=Qq())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));R("DELEGATED_SESSION_ID")&&!T("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});!T("fill_delegate_context_in_gel_killswitch")&&(a=R("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=R("INNERTUBE_CONTEXT");var g;if(T("enable_persistent_device_token")&&(a==null?0:(g=a.client)==null?0:g.rolloutToken)){var h;b.client.rolloutToken=a==null?void 0:(h=a.client)==null?void 0:h.rolloutToken}g=Object;h=g.assign;a=b.client;f={};e=y(Object.entries(Xm(R("DEVICE",""))));for(d=e.next();!d.done;d=e.next())c=y(d.value),d=c.next().value,c=c.next().value,d==="cbrand"?f.deviceMake=c:d==="cmodel"?f.deviceModel=c:d==="cbr"?f.browserName=
c:d==="cbrver"?f.browserVersion=c:d==="cos"?f.osName=c:d==="cosver"?f.osVersion=c:d==="cplatform"&&(f.platform=c);b.client=h.call(g,a,f);return b}
function Uq(a,b,c){c=c===void 0?{}:c;var d={};R("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":R("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||R("AUTHORIZATION");b||(a?b="Bearer "+F("gapi.auth.getToken")().uh:(a=Sn(Rn()),T("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var Vq=typeof TextEncoder!=="undefined"?new TextEncoder:null,Wq=Vq?function(a){return Vq.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};var Xq={next:"wn_s",browse:"br_s",search:"sr_s",reel:"r_wrs",player:"ps_s"},Yq={next:"wn_r",browse:"br_r",search:"sr_r",reel:"r_wrr",player:"ps_r"};function Zq(a,b){this.version=a;this.args=b}
Zq.prototype.serialize=function(){return{version:this.version,args:this.args}};function $q(a,b){this.topic=a;this.h=b}
$q.prototype.toString=function(){return this.topic};var ar=F("ytPubsub2Pubsub2Instance")||new N;N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.fc;N.prototype.publish=N.prototype.sb;N.prototype.clear=N.prototype.clear;E("ytPubsub2Pubsub2Instance",ar);var br=F("ytPubsub2Pubsub2SubscribedKeys")||{};E("ytPubsub2Pubsub2SubscribedKeys",br);var cr=F("ytPubsub2Pubsub2TopicToKeys")||{};E("ytPubsub2Pubsub2TopicToKeys",cr);var dr=F("ytPubsub2Pubsub2IsAsync")||{};E("ytPubsub2Pubsub2IsAsync",dr);
E("ytPubsub2Pubsub2SkipSubKey",null);function er(a,b){var c=fr();c&&c.publish.call(c,a.toString(),a,b)}
function gr(a){var b=hr,c=fr();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=F("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(br[d])try{if(f&&b instanceof $q&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Qd){var l=new h;h.Qd=l.version}var m=h.Qd}catch(n){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
Yb(k.args))}catch(n){throw n.message="yt.pubsub2.Data.deserialize(): "+n.message,n;}}catch(n){throw n.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+n.message,n;}a.call(window,f)}catch(n){Pm(n)}},dr[b.toString()]?F("yt.scheduler.instance")?Yj.pa(g):gn(g,0):g())});
br[d]=!0;cr[b.toString()]||(cr[b.toString()]=[]);cr[b.toString()].push(d);return d}
function ir(){var a=jr,b=gr(function(c){a.apply(void 0,arguments);kr(b)});
return b}
function kr(a){var b=fr();b&&(typeof a==="number"&&(a=[a]),Rb(a,function(c){b.unsubscribeByKey(c);delete br[c]}))}
function fr(){return F("ytPubsub2Pubsub2Instance")}
;function lr(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&er("meta_logging_csi_event",{timerName:a,li:b})}
;var mr=void 0,nr=void 0;function or(){nr||(nr=gm(R("WORKER_SERIALIZATION_URL")));return nr||void 0}
function pr(){var a=or();mr||a===void 0||(mr=new Worker(ob(a),void 0));return mr}
;var qr=kn("max_body_size_to_compress",5E5),rr=kn("min_body_size_to_compress",500),sr=!0,tr=0,ur=0,vr=kn("compression_performance_threshold_lr",250),wr=kn("slow_compressions_before_abandon_count",4),xr=!1,yr=new Map,zr=1,Ar=!0;function Br(){if(typeof Worker==="function"&&or()&&!xr){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=yr.get(c.key);d&&(Cr(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),yr.delete(c.key))}},b=pr();
b&&(b.addEventListener("message",a),b.onerror=function(){yr.clear()},xr=!0)}}
function Dr(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:V(),ticks:{},infos:{}};if(sr)try{var g=Er(b);if(g!=null&&(g>qr||g<rr))d(a,c);else{if(T("gzip_gel_with_worker")&&(T("initial_gzip_use_main_thread")&&!Ar||!T("initial_gzip_use_main_thread"))){xr||Br();var h=pr();if(h&&!e){yr.set(zr,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:zr});zr++;return}}var k=em(Wq(b));Cr(k,f,a,c,d)}}catch(l){Qm(l),d(a,c)}else d(a,c)}
function Cr(a,b,c,d,e){Ar=!1;var f=V();b.ticks.gelc=f;ur++;T("disable_compression_due_to_performance_degredation")&&f-b.startTime>=vr&&(tr++,T("abandon_compression_after_N_slow_zips")?ur===kn("compression_disable_point")&&tr>wr&&(sr=!1):sr=!1);Fr(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Gr(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=V(),e={startTime:d,ticks:{},infos:{}},f=b?F("yt.logging.gzipForFetch",!1):!0;if(sr&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=Er(g);if(h!=null&&(h>qr||h<rr))return a;c=b?{level:1}:void 0;f=em(Wq(g),c);var k=V();e.ticks.gelc=k;if(b){ur++;if((T("disable_compression_due_to_performance_degredation")||T("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=vr)if(tr++,T("abandon_compression_after_N_slow_zips")||T("abandon_compression_after_N_slow_zips_lr")){b=tr/ur;var l=wr/kn("compression_disable_point");ur>0&&ur%kn("compression_disable_point")===0&&b>=l&&(sr=!1)}else sr=!1;Fr(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(m){return Qm(m),a}}else return a}
function Er(a){try{return(new Blob(a.split(""))).size}catch(b){return Qm(b),null}}
function Fr(a){T("gel_compression_csi_killswitch")||!T("log_gel_compression_latency")&&!T("log_gel_compression_latency_lr")||lr("gel_compression",a,{sampleRate:.1})}
;function Hr(a){a=Object.assign({},a);delete a.Authorization;var b=ng();if(b){var c=new ck;c.update(R("INNERTUBE_API_KEY"));c.update(b);a.hash=wd(c.digest(),3)}return a}
;var Ir;function Jr(){Ir||(Ir=new Uo("yt.innertube"));return Ir}
function Kr(a,b,c,d){if(d)return null;d=Jr().get("nextId",!0)||1;var e=Jr().get("requests",!0)||{};e[d]={method:a,request:b,authState:Hr(c),requestTime:Math.round(V())};Jr().set("nextId",d+1,86400,!0);Jr().set("requests",e,86400,!0);return d}
function Lr(a){var b=Jr().get("requests",!0)||{};delete b[a];Jr().set("requests",b,86400,!0)}
function Mr(a){var b=Jr().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(V())-d.requestTime<6E4)){var e=d.authState,f=Hr(Uq(!1));Cg(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(V())),Nr(a,d.method,e,{}));delete b[c]}}Jr().set("requests",b,86400,!0)}}
;function Or(a){this.ic=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.zb=function(){};
this.now=Date.now;this.Sb=!1;var b;this.Od=(b=a.Od)!=null?b:100;var c;this.Jd=(c=a.Jd)!=null?c:1;var d;this.Hd=(d=a.Hd)!=null?d:2592E6;var e;this.Gd=(e=a.Gd)!=null?e:12E4;var f;this.Id=(f=a.Id)!=null?f:5E3;var g;this.V=(g=a.V)!=null?g:void 0;this.oc=!!a.oc;var h;this.lc=(h=a.lc)!=null?h:.1;var k;this.Bc=(k=a.Bc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.zb&&(this.zb=a.zb);a.Sb&&(this.Sb=a.Sb);a.ic&&(this.ic=a.ic);this.W=a.W;this.Ca=a.Ca;this.ga=a.ga;this.fa=a.fa;this.sendFn=a.sendFn;
this.Yc=a.Yc;this.Vc=a.Vc;Pr(this)&&(!this.W||this.W("networkless_logging"))&&Qr(this)}
function Qr(a){Pr(a)&&!a.Sb&&(a.h=!0,a.oc&&Math.random()<=a.lc&&a.ga.de(a.V),Rr(a),a.fa.ta()&&a.ec(),a.fa.listen(a.Yc,a.ec.bind(a)),a.fa.listen(a.Vc,a.rd.bind(a)))}
p=Or.prototype;p.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if(Pr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ga.set(d,this.V).then(function(e){d.id=e;c.fa.ta()&&Sr(c,d)}).catch(function(e){Sr(c,d);
Tr(c,e)})}else this.sendFn(a,b)};
p.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if(Pr(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.W&&this.W("nwl_skip_retry")&&(e.skipRetry=c);if(this.fa.ta()||this.W&&this.W("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return B(function(k){if(k.h==1)return k.yield(d.ga.set(e,d.V).catch(function(l){Tr(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ga.set(e,this.V).catch(function(g){d.sendFn(a,b,e.skipRetry);
Tr(d,g)})}else this.sendFn(a,b,this.W&&this.W("nwl_skip_retry")&&c)};
p.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if(Pr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.ga.xb(d.id,c.V):e=!0;c.fa.mb&&c.W&&c.W("vss_network_hint")&&c.fa.mb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ga.set(d,this.V).then(function(g){d.id=g;e&&c.ga.xb(d.id,c.V)}).catch(function(g){Tr(c,g)})}else this.sendFn(a,b,void 0,!0)};
p.ec=function(){var a=this;if(!Pr(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return c.yield(a.ga.vd("NEW",a.V),2);if(c.h!=3)return b=c.i,b?c.yield(Sr(a,b),3):(a.rd(),c.return());a.i&&(a.i=0,a.ec());c.h=0})},this.Od))};
p.rd=function(){this.Ca.qa(this.i);this.i=0};
function Sr(a,b){var c;return B(function(d){switch(d.h){case 1:if(!Pr(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.B(2);break}return d.yield(a.ga.Ie(b.id,a.V),3);case 3:(c=d.i)||a.zb(Error("The request cannot be found in the database."));case 2:if(Ur(a,b,a.Hd)){d.B(4);break}a.zb(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.B(5);break}return d.yield(a.ga.xb(b.id,a.V),5);case 5:return d.return();case 4:b.skipRetry||(b=Vr(a,
b));if(!b){d.B(0);break}if(!b.skipRetry||b.id===void 0){d.B(8);break}return d.yield(a.ga.xb(b.id,a.V),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function Vr(a,b){if(!Pr(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return B(function(m){switch(m.h){case 1:g=Wr(f);(h=Xr(f))&&a.W&&a.W("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.W&&a.W("nwl_consider_error_code")&&g||a.W&&!a.W("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.Bc)){m.B(2);break}if(!a.fa.Fc){m.B(3);break}return m.yield(a.fa.Fc(),3);case 3:if(a.fa.ta()){m.B(2);break}c(e,f);if(!a.W||!a.W("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){m.B(6);
break}return m.yield(a.ga.Zc(b.id,a.V,!1),6);case 6:return m.return();case 2:if(a.W&&a.W("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.Bc)return m.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){m.B(8);break}return b.sendCount<a.Jd?m.yield(a.ga.Zc(b.id,a.V,!0,h?!1:void 0),12):m.yield(a.ga.xb(b.id,a.V),8);case 12:a.Ca.pa(function(){a.fa.ta()&&a.ec()},a.Id);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return B(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.B(2):h.yield(a.ga.xb(b.id,a.V),2);a.fa.mb&&a.W&&a.W("vss_network_hint")&&a.fa.mb(!0);d(e,f);h.h=0})};
return b}
function Ur(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Rr(a){if(!Pr(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ga.vd("QUEUED",a.V).then(function(b){b&&!Ur(a,b,a.Gd)?a.Ca.pa(function(){return B(function(c){if(c.h==1)return b.id===void 0?c.B(2):c.yield(a.ga.Zc(b.id,a.V),2);Rr(a);c.h=0})}):a.fa.ta()&&a.ec()})}
function Tr(a,b){a.Td&&!a.fa.ta()?a.Td(b):a.handleError(b)}
function Pr(a){return!!a.V||a.ic}
function Wr(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function Xr(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var Yr;
function Zr(){if(Yr)return Yr();var a={};Yr=Dq("LogsDatabaseV2",{Hb:(a.LogsRequestsStore={Ob:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&Jp(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),Qp(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Yr()}
;function $r(a){return cq(Zr(),a)}
function as(a,b){var c,d,e,f;return B(function(g){if(g.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield($r(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:R("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(Lp(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=V();bs(c);return g.return(f)})}
function cs(a,b){var c,d,e,f,g,h,k,l;return B(function(m){if(m.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield($r(b),2);if(m.h!=3)return d=m.i,e=R("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,V()],h=IDBKeyRange.bound(f,g),k="prev",T("use_fifo_for_networkless")&&(k="next"),l=void 0,m.yield(Ip(d,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(n){return Wp(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(r){r.getValue()&&(l=r.getValue(),a==="NEW"&&(l.status="QUEUED",r.update(l)))})}),3);
c.ticks.tc=V();bs(c);return m.return(l)})}
function ds(a,b){var c;return B(function(d){if(d.h==1)return d.yield($r(b),2);c=d.i;return d.return(Ip(c,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Ep(f.h.put(g,void 0)).then(function(){return g})})}))})}
function es(a,b,c,d){c=c===void 0?!0:c;var e;return B(function(f){if(f.h==1)return f.yield($r(b),2);e=f.i;return f.return(Ip(e,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),Ep(h.h.put(k,void 0)).then(function(){return k})):yp.resolve(void 0)})}))})}
function gs(a,b){var c;return B(function(d){if(d.h==1)return d.yield($r(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function hs(a){var b,c;return B(function(d){if(d.h==1)return d.yield($r(a),2);b=d.i;c=V()-2592E6;return d.yield(Ip(b,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){return Sp(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return Tp(f)})})}),0)})}
function is(){B(function(a){return a.yield(zq(),0)})}
function bs(a){T("nwl_csi_killswitch")||lr("networkless_performance",a,{sampleRate:1})}
;var js={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrCowatchUserStartOrJoinEvent:504,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,
mbsConnectionInitiated:138,mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,
kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
transactionFlowPaymentSubmitted:460,transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,
ypcPauseFlowSucceeded:190,ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,
ypcFamilyCreateFlowCancelled:259,ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,
accountRegistryChange:226,userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,
musicSideloadedPlaylistServiceCalled:246,embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,
yongleUsbSetup:271,touStrikeInterstitialEvent:272,liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,
notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,
tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,
iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,
mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,
mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,
clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,
mdeQosEvent:510,mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,mdeExporterEvent:497,genericClientExperimentEvent:423,homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,externalVideoShareToYoutubeAttempt:501,parentCodeEvent:502,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,
mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,
cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,producerProjectElementAdded:453,producerProjectElementRemoved:454,producerAppStateChange:509,producerProjectDiskInsufficientExportFailure:516,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,
miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486,crossDeviceNotificationTransfer:487,androidIntentEvent:488,unpluggedAmbientInterludesCounterfactualEvent:489,keyPlaysPlayback:490,
shortsCreationFallbackEvent:493,vssData:491,castMatch:494,miniAppPerformanceMetrics:495,userFeedbackEvent:496,kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500,watchEpPromoConflict:503,innertubeResponseCacheMetrics:505,miniAppAdEvent:506,dataPlanUpsellEvent:507,producerProjectRenamed:508,producerMediaSelectionEvent:511,embedsAutoplayStatusChanged:512,remoteConnectEvent:513,connectedSessionMisattributionEvent:514,producerProjectElementModified:515,
adsSeenClientLogging:517,producerEvent:518};var ks={},ls=Dq("ServiceWorkerLogsDatabase",{Hb:(ks.SWHealthLog={Ob:1},ks),shared:!0,upgrade:function(a,b){b(1)&&Qp(Jp(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function ms(a){return cq(ls(),a)}
function ns(a){var b,c;B(function(d){if(d.h==1)return d.yield(ms(a),2);b=d.i;c=V()-2592E6;return d.yield(Ip(b,["SWHealthLog"],{mode:"readwrite",ka:!0},function(e){return Sp(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return Tp(f)})})}),0)})}
function ps(a){var b;return B(function(c){if(c.h==1)return c.yield(ms(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var qs={},rs=0;function ss(a){var b=b===void 0?{}:b;var c=new Image,d=""+rs++;qs[d]=c;c.onload=c.onerror=function(){delete qs[d]};
b.hi&&(c.referrerPolicy="no-referrer");c.src=a}
;var ts;function us(){ts||(ts=new Uo("yt.offline"));return ts}
function vs(a){if(T("offline_error_handling")){var b=us().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);us().set("errors",b,2592E3,!0)}}
;function ws(){this.h=new Map;this.i=!1}
function xs(){if(!ws.instance){var a=F("yt.networkRequestMonitor.instance")||new ws;E("yt.networkRequestMonitor.instance",a);ws.instance=a}return ws.instance}
ws.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
ws.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
ws.prototype.removeParams=function(a){return a.split("?")[0]};
ws.prototype.removeParams=ws.prototype.removeParams;ws.prototype.isEndpointCFR=ws.prototype.isEndpointCFR;ws.prototype.requestComplete=ws.prototype.requestComplete;ws.getInstance=xs;function ys(){gi.call(this);var a=this;this.j=!1;this.h=Xj();this.h.listen("networkstatus-online",function(){if(a.j&&T("offline_error_handling")){var b=us().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new U(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Pm(d)}us().set("errors",{},2592E3,!0)}}})}
v(ys,gi);function zs(){if(!ys.instance){var a=F("yt.networkStatusManager.instance")||new ys;E("yt.networkStatusManager.instance",a);ys.instance=a}return ys.instance}
p=ys.prototype;p.ta=function(){return this.h.ta()};
p.mb=function(a){this.h.h=a};
p.xe=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
p.ne=function(){this.j=!0};
p.listen=function(a,b){return this.h.listen(a,b)};
p.Fc=function(a){a=Vj(this.h,a);a.then(function(b){T("use_cfr_monitor")&&xs().requestComplete("generate_204",b)});
return a};
ys.prototype.sendNetworkCheckRequest=ys.prototype.Fc;ys.prototype.listen=ys.prototype.listen;ys.prototype.enableErrorFlushing=ys.prototype.ne;ys.prototype.getWindowStatus=ys.prototype.xe;ys.prototype.networkStatusHint=ys.prototype.mb;ys.prototype.isNetworkAvailable=ys.prototype.ta;ys.getInstance=zs;function As(a){a=a===void 0?{}:a;gi.call(this);var b=this;this.h=this.u=0;this.j=zs();var c=F("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Bs(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Bs(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){hi(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){hi(b,"publicytnetworkstatus-offline")})))}
v(As,gi);As.prototype.ta=function(){var a=F("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
As.prototype.mb=function(a){var b=F("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
As.prototype.Fc=function(a){var b=this,c;return B(function(d){c=F("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return T("skip_network_check_if_cfr")&&xs().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.mb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.ta())})):c?d.return(c(a)):d.return(!0)})};
function Bs(a,b){a.rateLimit?a.h?(Yj.qa(a.u),a.u=Yj.pa(function(){a.o!==b&&(hi(a,b),a.o=b,a.h=V())},a.rateLimit-(V()-a.h))):(hi(a,b),a.o=b,a.h=V()):hi(a,b)}
;var Cs;function Ds(){var a=Or.call;Cs||(Cs=new As({Uh:!0,Kh:!0}));a.call(Or,this,{ga:{de:hs,xb:gs,vd:cs,Ie:ds,Zc:es,set:as},fa:Cs,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;b=new U(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code);Qm(b,void 0,void 0,void 0,!0)}else Pm(b)},
zb:Qm,sendFn:Es,now:V,Td:vs,Ca:To(),Yc:"publicytnetworkstatus-online",Vc:"publicytnetworkstatus-offline",oc:!0,lc:.1,Bc:kn("potential_esf_error_limit",10),W:T,Sb:!(lo()&&Fs())});this.j=new Aj;T("networkless_immediately_drop_all_requests")&&is();Aq("LogsDatabaseV2")}
v(Ds,Or);function Gs(){var a=F("yt.networklessRequestController.instance");a||(a=new Ds,E("yt.networklessRequestController.instance",a),T("networkless_logging")&&pq().then(function(b){a.V=b;Qr(a);a.j.resolve();a.oc&&Math.random()<=a.lc&&a.V&&ns(a.V);T("networkless_immediately_drop_sw_health_store")&&Hs(a)}));
return a}
Ds.prototype.writeThenSend=function(a,b){b||(b={});b=Is(a,b);lo()||(this.h=!1);Or.prototype.writeThenSend.call(this,a,b)};
Ds.prototype.sendThenWrite=function(a,b,c){b||(b={});b=Is(a,b);lo()||(this.h=!1);Or.prototype.sendThenWrite.call(this,a,b,c)};
Ds.prototype.sendAndWrite=function(a,b){b||(b={});b=Is(a,b);lo()||(this.h=!1);Or.prototype.sendAndWrite.call(this,a,b)};
Ds.prototype.awaitInitialization=function(){return this.j.promise};
function Hs(a){var b;B(function(c){if(!a.V)throw b=up("clearSWHealthLogsDb"),b;return c.return(ps(a.V).catch(function(d){a.handleError(d)}))})}
function Es(a,b,c,d){d=d===void 0?!1:d;b=T("web_fp_via_jspb")?Object.assign({},b):b;T("use_cfr_monitor")&&Js(a,b);if(T("use_request_time_ms_header"))b.headers&&an(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(V())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)pn(a,void 0,"POST",f,void 0);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)pn(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{c:{var k=new db({url:a});if(ab(k.h,"dsh")==="1")var l=null;else{var m=ab(k.h,"ae");if(m==="1"){var n=ab(k.h,"adurl");if(n)try{l={version:3,ke:decodeURIComponent(n),ae:bb(k.h,"act=1","ri=1",eb(k))};break c}catch(Z){}}l=m==="2"?{version:4,ke:bb(k.h,"dct=1","suid="+k.i,""),ae:bb(k.h,"act=1","ri=1","suid="+k.i)}:null}}if(l){var r=nc(a),t;if(!(t=!r||!r.endsWith("/aclk"))){var w=a.search(vc),x=uc(a,0,"ri",w);if(x<0)var z=null;else{var G=a.indexOf("&",
x);if(G<0||G>w)G=w;z=ic(a.slice(x+3,G!==-1?G:0))}t=z!=="1"}var H=!t;break b}}catch(Z){}H=!1}if(H){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var S=!0;break b}}catch(Z){}S=!1}c=S?!0:!1}else c=!1;c||ss(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),Dr(a,b.postBody,b,tn,d)):Dr(a,JSON.stringify(b.postParams),b,sn,d):tn(a,b)}
function Is(a,b){T("use_event_time_ms_header")&&an(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(V())));return b}
function Js(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){xs().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){xs().requestComplete(a,!0);d(e,f)}}
function Fs(){return mc(document.location.toString())!=="www.youtube-nocookie.com"}
;var Ks=!1,Ps=D.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Ks};E("ytNetworklessLoggingInitializationOptions",Ps);function Qs(){var a;B(function(b){if(b.h==1)return b.yield(pq(),2);a=b.i;if(!a||!lo()&&!T("nwl_init_require_datasync_id_killswitch")||!Fs())return b.B(0);Ks=!0;Ps.isNwlInitialized=Ks;return b.yield(Gs().awaitInitialization(),0)})}
;function Rs(a){var b=this;this.config_=null;a?this.config_=a:Rq()&&(this.config_=Sq());oo(function(){Mr(b)},5E3)}
Rs.prototype.isReady=function(){!this.config_&&Rq()&&(this.config_=Sq());return!!this.config_};
function Nr(a,b,c,d){function e(n){n=n===void 0?!1:n;var r;if(d.retry&&h!="www.youtube-nocookie.com"&&(n||T("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(r=Kr(b,c,l,k)),r)){var t=g.onSuccess,w=g.onFetchSuccess;g.onSuccess=function(G,H){Lr(r);t(G,H)};
c.onFetchSuccess=function(G,H){Lr(r);w(G,H)}}try{if(n&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Gs().writeThenSend(m,g):Gs().sendAndWrite(m,g);
else if(d.compress){var x=!d.networklessOptions.writeThenSend;if(g.postBody){var z=g.postBody;typeof z!=="string"&&(z=JSON.stringify(g.postBody));Dr(m,z,g,tn,x)}else Dr(m,JSON.stringify(g.postParams),g,sn,x)}else T("web_all_payloads_via_jspb")?tn(m,g):sn(m,g)}catch(G){if(G.name==="InvalidAccessError")r&&(Lr(r),r=0),Qm(Error("An extension is blocking network request."));else throw G;}r&&oo(function(){Mr(a)},5E3)}
!R("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&Qm(new U("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new U("innertube xhrclient not ready",b,c,d);Pm(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(n,r){if(d.onSuccess)d.onSuccess(r)},
onFetchSuccess:function(n){if(d.onSuccess)d.onSuccess(n)},
onError:function(n,r){if(d.onError)d.onError(r)},
onFetchError:function(n){if(d.onError)d.onError(n)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.De)&&(h=f);var k=a.config_.Ee||!1,l=Uq(k,h,d);Object.assign(g.headers,l);g.headers.Authorization&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m=Zm(""+h+("/youtubei/"+a.config_.innertubeApiVersion+"/"+b),{alt:"json"});(F("ytNetworklessLoggingInitializationOptions")?Ps.isNwlInitialized:Ks)?nq().then(function(n){e(n)}):e(!1)}
;var Ss=0,Ts=pd?"webkit":od?"moz":md?"ms":ld?"o":"";E("ytDomDomGetNextId",F("ytDomDomGetNextId")||function(){return++Ss});var Us={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Vs(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Us||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Ws(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Vs.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Vs.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Vs.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var yg=D.ytEventsEventsListeners||{};E("ytEventsEventsListeners",yg);var Xs=D.ytEventsEventsCounter||{count:0};E("ytEventsEventsCounter",Xs);
function Ys(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return xg(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Oa(e[4])&&Oa(d)&&Cg(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function Zs(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Ys(a,b,c,d);if(e)return e;e=++Xs.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Vs(h);if(!Mg(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Vs(h);
h.currentTarget=a;return c.call(a,h)};
g=Om(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),$s()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);yg[e]=[a,b,c,g,d];return e}
function at(a){a&&(typeof a=="string"&&(a=[a]),Rb(a,function(b){if(b in yg){var c=yg[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?$s()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete yg[b]}}))}
var $s=wi(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function bt(a){this.G=a;this.h=null;this.o=0;this.A=null;this.u=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.U=Zs(window,"mousemove",Ua(this.Y,this));a=Ua(this.P,this);typeof a==="function"&&(a=Om(a));this.Z=window.setInterval(a,25)}
$a(bt,I);bt.prototype.Y=function(a){a.h===void 0&&Ws(a);var b=a.h;a.i===void 0&&Ws(a);this.h=new tg(b,a.i)};
bt.prototype.P=function(){if(this.h){var a=V();if(this.o!=0){var b=this.A,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.i[this.j]=Math.abs((d-this.u)/this.u)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.G();this.u=d}this.o=a;this.A=this.h;this.j=(this.j+1)%4}};
bt.prototype.ba=function(){window.clearInterval(this.Z);at(this.U)};var ct={};
function dt(a){var b=a===void 0?{}:a;a=b.Ue===void 0?!1:b.Ue;b=b.oe===void 0?!0:b.oe;if(F("_lact",window)==null){var c=parseInt(R("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;E("_lact",c,window);E("_fact",c,window);c==-1&&et();Zs(document,"keydown",et);Zs(document,"keyup",et);Zs(document,"mousedown",et);Zs(document,"mouseup",et);a?Zs(window,"touchmove",function(){ft("touchmove",200)},{passive:!0}):(Zs(window,"resize",function(){ft("resize",200)}),b&&Zs(window,"scroll",function(){ft("scroll",200)}));
new bt(function(){ft("mouse",100)});
Zs(document,"touchstart",et,{passive:!0});Zs(document,"touchend",et,{passive:!0})}}
function ft(a,b){ct[a]||(ct[a]=!0,Yj.pa(function(){et();ct[a]=!1},b))}
function et(){F("_lact",window)==null&&dt();var a=Date.now();E("_lact",a,window);F("_fact",window)==-1&&E("_fact",a,window);(a=F("ytglobal.ytUtilActivityCallback_"))&&a()}
function gt(){var a=F("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var ht=D.ytPubsubPubsubInstance||new N,jt=D.ytPubsubPubsubSubscribedKeys||{},kt=D.ytPubsubPubsubTopicToKeys||{},lt=D.ytPubsubPubsubIsSynchronous||{};function mt(a,b){var c=nt();if(c&&b){var d=c.subscribe(a,function(){function e(){jt[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{lt[a]?e():gn(e,0)}catch(g){Pm(g)}},void 0);
jt[d]=!0;kt[a]||(kt[a]=[]);kt[a].push(d);return d}return 0}
function ot(a){var b=nt();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Rb(a,function(c){b.unsubscribeByKey(c);delete jt[c]}))}
function pt(a,b){var c=nt();c&&c.publish.apply(c,arguments)}
function qt(a){var b=nt();if(b)if(b.clear(a),a)rt(a);else for(var c in kt)rt(c)}
function nt(){return D.ytPubsubPubsubInstance}
function rt(a){kt[a]&&(a=kt[a],Rb(a,function(b){jt[b]&&delete jt[b]}),a.length=0)}
N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.fc;N.prototype.publish=N.prototype.sb;N.prototype.clear=N.prototype.clear;E("ytPubsubPubsubInstance",ht);E("ytPubsubPubsubTopicToKeys",kt);E("ytPubsubPubsubIsSynchronous",lt);E("ytPubsubPubsubSubscribedKeys",jt);var st=Symbol("injectionDeps");function tt(a){this.name=a}
tt.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function ut(a){this.key=a}
function vt(a){return new ut(a)}
function wt(){this.i=new Map;this.j=new Map;this.h=new Map}
function xt(a,b){a.i.set(b.pb,b);var c=a.j.get(b.pb);if(c)try{c.di(a.resolve(b.pb))}catch(d){c.bi(d)}}
wt.prototype.resolve=function(a){return a instanceof ut?zt(this,a.key,[],!0):zt(this,a,[])};
function zt(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.kd!==void 0)var e=d.kd;else if(d.Bf)e=d[st]?At(a,d[st],c):[],e=d.Bf.apply(d,A(e));else if(d.Hc){e=d.Hc;var f=e[st]?At(a,e[st],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(A(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.ki||a.h.set(b,e);return e}
function At(a,b,c){return b?b.map(function(d){return d instanceof ut?zt(a,d.key,c,!0):zt(a,d,c)}):[]}
;var Bt;function Ct(){Bt||(Bt=new wt);return Bt}
;var Dt=window;function Et(){var a,b;return"h5vcc"in Dt&&((a=Dt.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Dt.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Dt&&Dt.performance.mark&&Dt.performance.measure?2:0}
function Ft(a){var b=Et();switch(b){case 1:Dt.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Dt.performance.mark(a+"-start");break;case 0:break;default:Cb(b,"unknown trace type")}}
function Gt(a){var b=Et();switch(b){case 1:Dt.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Dt.performance.mark(c);Dt.performance.measure(a,b,c);break;case 0:break;default:Cb(b,"unknown trace type")}}
;var Ht=T("web_enable_lifecycle_monitoring")&&Et()!==0,It=T("web_enable_lifecycle_monitoring");function Jt(a){var b,c;(c=(b=window).onerror)==null||c.call(b,a.message,"",0,0,a)}
;function Kt(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?To():d;this.j=c;this.scheduler=d;this.i=new Aj;this.h=a;for(a={jb:0};a.jb<this.h.length;a={Ac:void 0,jb:a.jb},a.jb++)a.Ac=this.h[a.jb],c=function(e){return function(){e.Ac.Pc();b.h[e.jb].Cc=!0;b.h.every(function(f){return f.Cc===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.Ac),d=this.scheduler.Sa(c,d),this.h[a.jb]=Object.assign({},a.Ac,{Pc:c,
jobId:d})}
function Lt(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=y(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.Cc||(a.scheduler.qa(c.jobId),a.scheduler.Sa(c.Pc,10))}
Kt.prototype.cancel=function(){for(var a=y(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.Cc||this.scheduler.qa(b.jobId),b.Cc=!0;this.i.resolve()};
Kt.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function Mt(a){this.state=a;this.plugins=[];this.o=void 0;this.A={};Ht&&Ft(this.state)}
p=Mt.prototype;p.install=function(a){this.plugins.push(a);return this};
p.uninstall=function(){var a=this;C.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
p.transition=function(a,b){var c=this;Ht&&Gt(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Lt(this.j),this.j=void 0);Nt(this,a,b);this.state=a;Ht&&Ft(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Ot(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Ot(a,b){var c=b.filter(function(e){return Pt(a,e)===10}),d=b.filter(function(e){return Pt(a,e)!==10});
return a.A.ji?function(){var e=C.apply(0,arguments);return B(function(f){if(f.h==1)return f.yield(a.af.apply(a,[c].concat(A(e))),2);a.Ld.apply(a,[d].concat(A(e)));f.h=0})}:function(){var e=C.apply(0,arguments);
a.bf.apply(a,[c].concat(A(e)));a.Ld.apply(a,[d].concat(A(e)))}}
p.bf=function(a){for(var b=C.apply(1,arguments),c=To(),d=y(a),e=d.next(),f={};!e.done;f={Ub:void 0},e=d.next())f.Ub=e.value,c.Mb(function(g){return function(){Qt(g.Ub.name);Rt(function(){return g.Ub.callback.apply(g.Ub,A(b))});
St(g.Ub.name)}}(f))};
p.af=function(a){var b=C.apply(1,arguments),c,d,e,f,g;return B(function(h){h.h==1&&(c=To(),d=y(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.B(0);f.Ya=e.value;f.hc=void 0;g=function(k){return function(){Qt(k.Ya.name);var l=Rt(function(){return k.Ya.callback.apply(k.Ya,A(b))});
oe(l)?k.hc=T("web_lifecycle_error_handling_killswitch")?l.then(function(){St(k.Ya.name)}):l.then(function(){St(k.Ya.name)},function(m){Jt(m);
St(k.Ya.name)}):St(k.Ya.name)}}(f);
c.Mb(g);return f.hc?h.yield(f.hc,3):h.B(3)}f={Ya:void 0,hc:void 0};e=d.next();return h.B(2)})};
p.Ld=function(a){var b=C.apply(1,arguments),c=this,d=a.map(function(e){return{Pc:function(){Qt(e.name);Rt(function(){return e.callback.apply(e,A(b))});
St(e.name)},
priority:Pt(c,e)}});
d.length&&(this.j=new Kt(d))};
function Pt(a,b){var c,d;return(d=(c=a.o)!=null?c:b.priority)!=null?d:0}
function Qt(a){Ht&&a&&Ft(a)}
function St(a){Ht&&a&&Gt(a)}
function Nt(a,b,c){It&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
da.Object.defineProperties(Mt.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});
function Rt(a){if(T("web_lifecycle_error_handling_killswitch"))return a();try{return a()}catch(b){Jt(b)}}
;function Tt(a){Mt.call(this,a===void 0?"none":a);this.h=null;this.o=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.u},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var Ut;v(Tt,Mt);Tt.prototype.i=function(a,b){var c=this;this.h=oo(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
Tt.prototype.u=function(a,b){this.h&&(Yj.qa(this.h),this.h=null);a(b==null?void 0:b.event)};
function Vt(){Ut||(Ut=new Tt);return Ut}
;var Wt=[];E("yt.logging.transport.getScrapedGelPayloads",function(){return Wt});function Xt(){this.store={};this.h={}}
Xt.prototype.storePayload=function(a,b){a=Yt(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);T("more_accurate_gel_parser")&&(b=new CustomEvent("TRANSPORTING_NEW_EVENT"),window.dispatchEvent(b));return a};
Xt.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=Zt(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,A(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,A(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,A(this.smartExtractMatchingEntries(a))));return c};
Xt.prototype.extractMatchingEntries=function(a){a=Zt(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,A(this.store[a[c]])),delete this.store[a[c]]);return b};
Xt.prototype.getSequenceCount=function(a){a=Zt(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function Zt(a,b){var c=Yt(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&Yt(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if($t(b.auth,g[0])){var h=b.isJspb;$t(h===void 0?"undefined":h?"true":"false",g[1])&&$t(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),$t(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function $t(a,b){return a===void 0||a==="undefined"?!0:a===b}
Xt.prototype.getSequenceCount=Xt.prototype.getSequenceCount;Xt.prototype.extractMatchingEntries=Xt.prototype.extractMatchingEntries;Xt.prototype.smartExtractMatchingEntries=Xt.prototype.smartExtractMatchingEntries;Xt.prototype.storePayload=Xt.prototype.storePayload;function Yt(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function au(a,b){if(a)return a[b.name]}
;var bu=kn("initial_gel_batch_timeout",2E3),cu=kn("gel_queue_timeout_max_ms",6E4),du=kn("gel_min_batch_size",5),eu=void 0;function fu(){this.o=this.h=this.i=0;this.j=!1}
var gu=new fu,hu=new fu,iu=new fu,ju=new fu,ku,lu=!0,mu=D.ytLoggingTransportTokensToCttTargetIds_||{};E("ytLoggingTransportTokensToCttTargetIds_",mu);var nu={};function ou(){var a=F("yt.logging.ims");a||(a=new Xt,E("yt.logging.ims",a));return a}
function pu(a,b){if(a.endpoint==="log_event"){qu(a);var c=ru(a),d=su(a.payload)||"";a:{if(T("enable_web_tiered_gel")){var e=js[d||""];var f,g,h,k=Ct().resolve(vt(Mq))==null?void 0:(f=Nq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!T("web_payload_policy_disabled_killswitch"))return;k=tu(e.tier);if(k===400){uu(a,b);return}}nu[c]=
!0;c={cttAuthInfo:c,isJspb:!1,tier:k};ou().storePayload(c,a.payload);vu(b,c,d==="gelDebuggingEvent")}}
function vu(a,b,c){function d(){wu({writeThenSend:!0},void 0,e,b.tier)}
var e=!1;e=e===void 0?!1:e;c=c===void 0?!1:c;a&&(eu=new a);a=kn("tvhtml5_logging_max_batch_ads_fork")||kn("tvhtml5_logging_max_batch")||kn("web_logging_max_batch")||100;var f=V(),g=xu(e,b.tier),h=g.o;c&&(g.j=!0);c=0;b&&(c=ou().getSequenceCount(b));c>=1E3?d():c>=a?ku||(ku=yu(function(){d();ku=void 0},0)):f-h>=10&&(zu(e,b.tier),g.o=f)}
function uu(a,b){if(a.endpoint==="log_event"){T("more_accurate_gel_parser")&&ou().storePayload({isJspb:!1},a.payload);qu(a);var c=ru(a),d=new Map;d.set(c,[a.payload]);var e=su(a.payload)||"";b&&(eu=new b);return new xi(function(f,g){eu&&eu.isReady()?Au(d,eu,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function ru(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);mu[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function wu(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new xi(function(e,f){var g=xu(c,d),h=g.j;g.j=!1;Bu(g.i);Bu(g.h);g.h=0;eu&&eu.isReady()?d===void 0&&T("enable_web_tiered_gel")?Cu(e,f,a,b,c,300,h):Cu(e,f,a,b,c,d,h):(zu(c,d),e())})}
function Cu(a,b,c,d,e,f,g){var h=eu;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=T("enable_web_tiered_gel")?ou().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):ou().extractMatchingEntries(e),k.set(d,f);else for(d=y(Object.keys(nu)),l=d.next();!l.done;l=d.next())l=l.value,e=T("enable_web_tiered_gel")?ou().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):ou().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(T("web_fp_via_jspb_and_json")&&c.writeThenSend||!T("web_fp_via_jspb_and_json"))&&delete nu[l];Au(k,h,a,b,c,!1,g)}
function zu(a,b){function c(){wu({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=xu(a,b),e=d===ju||d===iu?5E3:cu;T("web_gel_timeout_cap")&&!d.h&&(e=yu(function(){c()},e),d.h=e);
Bu(d.i);e=R("LOGGING_BATCH_TIMEOUT",kn("web_gel_debounce_ms",1E4));T("shorten_initial_gel_batch_timeout")&&lu&&(e=bu);e=yu(function(){kn("gel_min_batch_size")>0?ou().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=du&&c():c()},e);
d.i=e}
function Au(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(V()),k=a.size,l=(g===void 0?0:g)&&T("vss_through_gel_video_stats")?"video_stats":"log_event";a=y(a);var m=a.next();for(g={};!m.done;g={Uc:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Xc:void 0,Wc:void 0},m=a.next()){var n=y(m.value);m=n.next().value;n=n.next().value;g.batchRequest=Eg({context:Tq(b.config_||Sq())});if(!Ma(n)&&!T("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=n;(n=mu[m])&&
Du(g.batchRequest,m,n);delete mu[m];g.dangerousLogToVisitorSession=m==="visitorOnlyApprovedKey";Eu(g.batchRequest,h,g.dangerousLogToVisitorSession);T("always_send_and_write")&&(e.writeThenSend=!1);g.Xc=function(r){T("start_client_gcf")&&Yj.pa(function(){return B(function(t){return t.yield(Fu(r),0)})});
k--;k||c()};
g.Uc=0;g.Wc=function(r){return function(){r.Uc++;if(e.bypassNetworkless&&r.Uc===1)try{Nr(b,l,r.batchRequest,Gu({writeThenSend:!0},r.dangerousLogToVisitorSession,r.Xc,r.Wc,f)),lu=!1}catch(t){Pm(t),d()}k--;k||c()}}(g);
try{Nr(b,l,g.batchRequest,Gu(e,g.dangerousLogToVisitorSession,g.Xc,g.Wc,f)),lu=!1}catch(r){Pm(r),d()}}}
function Gu(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,wh:!!e,headers:{},postBodyFormat:"",postBody:"",compress:T("compress_gel")||T("compress_gel_lr")};Hu()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));return a}
function Eu(a,b,c){Hu()||(a.requestTimeMs=String(b));T("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=R("EVENT_ID"))&&((c=R("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*65535/2)),c++,c>65535&&(c=1),Km("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Du(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function qu(a){var b=jn("il_payload_scraping");b=(b!==void 0?String(b):"")==="enable_il_payload_scraping";if(!F("yt.logging.transport.enableScrapingForTest"))if(b)Wt=[],E("yt.logging.transport.enableScrapingForTest",!0),E("yt.logging.transport.scrapedPayloadsForTesting",Wt),E("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),E("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
E("yt.logging.transport.scrapeClientEvent",!0);else return;b=F("yt.logging.transport.scrapedPayloadsForTesting");var c=F("yt.logging.transport.payloadToScrape"),d=F("yt.logging.transport.scrapeClientEvent");if(c&&c.length>=1)for(var e=0;e<c.length;e++)if(a&&a.payload[c[e]])if(d)b.push(a.payload);else{var f=void 0;b.push(((f=a)==null?void 0:f.payload)[c[e]])}E("yt.logging.transport.scrapedPayloadsForTesting",b)}
function Hu(){return T("use_request_time_ms_header")||T("lr_use_request_time_ms_header")}
function yu(a,b){return T("transport_use_scheduler")===!1?gn(a,b):T("logging_avoid_blocking_during_navigation")||T("lr_logging_avoid_blocking_during_navigation")?oo(function(){if(Vt().currentState==="none")a();else{var c={};Vt().install((c.none={callback:a},c))}},b):oo(a,b)}
function Bu(a){T("transport_use_scheduler")?Yj.qa(a):window.clearTimeout(a)}
function Fu(a){var b,c,d,e,f,g,h,k,l,m;return B(function(n){return n.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=au(d,km),g=(f=d)==null?void 0:f.hotHashData,h=au(d,jm),l=(k=d)==null?void 0:k.coldHashData,(m=Ct().resolve(vt(Mq)))?g?e?n.yield(Oq(m,g,e),2):n.yield(Oq(m,g),2):n.B(2):n.return()):l?h?n.yield(Pq(m,l,h),0):n.yield(Pq(m,l),0):n.B(0)})}
function xu(a,b){b=b===void 0?200:b;return a?b===300?ju:hu:b===300?iu:gu}
function su(a){a=Object.keys(a);a=y(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,js[b])return b}
function tu(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var Iu=D.ytLoggingGelSequenceIdObj_||{};E("ytLoggingGelSequenceIdObj_",Iu);
function Ju(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||V());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=gt();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!T("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,Iu[b]=b in Iu?Iu[b]+1:0,a.sequence={index:Iu[b],groupKey:b},d.endOfSequence&&delete Iu[d.sequenceGroup]);(d.sendIsolatedPayload?uu:pu)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function cp(a,b,c){c=c===void 0?{}:c;var d=Rs;R("ytLoggingEventsDefaultDisabled",!1)&&Rs===Rs&&(d=null);Ju(a,b,d,c)}
;var Ku=new Set,Lu=0,Mu=0,Nu=0,Ou=[],Pu=[],Qu=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function bp(a){Ru(a)}
function Su(a){Ru(a,"WARNING")}
function Tu(a){a instanceof Error?Ru(a):(a=Oa(a)?JSON.stringify(a):String(a),a=new U(a),a.name="RejectedPromiseError",Su(a))}
function Ru(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),T("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(Lu>=5))){d=[];e=y(Pu);for(f=e.next();!f.done;f=e.next()){f=f.value;try{f()&&d.push(f())}catch(z){}}d=[].concat(A(Ou),A(d));var k=dc(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var m=l.split("\n");m.shift();l=m.join("\n")}m=k.lineNumber||"Not available";k=k.fileName||"Not available";var n=0;if(a.hasOwnProperty("args")&&
a.args&&a.args.length)for(var r=0;r<a.args.length&&!(n=Ln(a.args[r],"params."+r,c,n),n>=500);r++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(r in t){if(t[r]){var w="params."+r,x=Nn(t[r]);c[w]=x;n+=w.length+x.length;if(n>500)break}}else c.params=Nn(t)}if(d.length)for(r=0;r<d.length&&!(n=Ln(d[r],"params.context."+r,c,n),n>=500);r++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);r={message:e,name:f,lineNumber:m,
fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(r.lineNumber=r.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=Hn();c=y(a.Za);for(d=c.next();!d.done;d=c.next())if(d=d.value,r.message&&r.message.match(d.Wh)){a=d.weight;break a}a=y(a.Ua);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(r)){a=c.weight;break a}a=1}r.sampleWeight=a;a=y(Cn);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.zc[r.name])for(e=y(c.zc[r.name]),d=e.next();!d.done;d=e.next())if(f=
d.value,d=r.message.match(f.regexp)){r.params["params.error.original"]=d[0];e=f.groups;f={};for(m=0;m<e.length;m++)f[e[m]]=d[m+1],r.params["params.error."+e[m]]=d[m+1];r.message=c.Tc(f);break}r.params||(r.params={});a=Hn();r.params["params.errorServiceSignature"]="msg="+a.Za.length+"&cb="+a.Ua.length;r.params["params.serviceWorker"]="false";D.document&&D.document.querySelectorAll&&(r.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));(new Hg(Ig,"sample")).constructor!==
Hg&&(r.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&window.yterr(r);if(r.sampleWeight!==0&&!Ku.has(r.message)){if(g&&T("web_enable_error_204"))Uu(b===void 0?"ERROR":b,r);else{b=b===void 0?"ERROR":b;b==="ERROR"?(In.sb("handleError",r),T("record_app_crashed_web")&&Nu===0&&r.sampleWeight===1&&(Nu++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},T("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:r.message}}}}),cp("appCrashed",
g)),Mu++):b==="WARNING"&&In.sb("handleWarning",r);if(T("kevlar_gel_error_routing")){g=b;h=h===void 0?{}:h;b:{a=y(Qu);for(c=a.next();!c.done;c=a.next())if(ip(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:r.stack};r.fileName&&(c.filename=r.fileName);a=r.lineNumber&&r.lineNumber.split?r.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=
Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:r.message,errorClassName:r.name,sampleWeight:r.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];R("FEXP_EXPERIMENTS")&&(h.experimentIds=R("FEXP_EXPERIMENTS"));d=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Lm("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=y(Object.keys(d)),f=e.next();!f.done;f=e.next())f=
f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=r.params)for(e=y(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=R("SERVER_NAME");e=R("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(cp("clientError",h),(g==="ERROR"||T("errors_flush_gel_always_killswitch"))&&wu(void 0,void 0,!1))}T("suppress_error_204_logging")||
Uu(b,r)}try{Ku.add(r.message)}catch(z){}Lu++}}}
function Uu(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:R("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=y(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=y(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];(c=R("LAVA_VERSION"))&&(a.postParams["lava.version"]=c);c=R("SERVER_NAME");b=R("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}tn(R("ECATCHER_REPORT_HOST","")+"/error_204",a)}
function Vu(a){var b=C.apply(1,arguments);a.args||(a.args=[]);Array.isArray(a.args)&&a.args.push.apply(a.args,A(b))}
;function Wu(){this.register=new Map}
function Xu(a){a=y(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.ai("ABORTED")}
Wu.prototype.clear=function(){Xu(this);this.register.clear()};
var Yu=new Wu;var Zu=Date.now().toString();
function $u(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(Zu)for(a=1,b=0;b<Zu.length;b++)d[a%16]^=d[(a-1)%16]/4^Zu.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var av,bv=D.ytLoggingDocDocumentNonce_;bv||(bv=$u(),E("ytLoggingDocDocumentNonce_",bv));av=bv;function cv(a){this.h=a}
p=cv.prototype;p.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
p.getAsJspb=function(){var a=new mm;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&yf(a,2,Pe(this.h.veType)),this.h.veCounter!==void 0&&yf(a,6,Pe(this.h.veCounter)),this.h.elementIndex!==void 0&&yf(a,3,Pe(this.h.elementIndex)),this.h.isCounterfactual&&yf(a,5,Le(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();If(a,mm,7,b)}this.h.youtubeData!==void 0&&If(a,lm,8,this.h.jspbYoutubeData);return a};
p.toString=function(){return JSON.stringify(this.getAsJson())};
p.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
p.getLoggingDirectives=function(){return this.h.loggingDirectives};function dv(a){return R("client-screen-nonce-store",{})[a===void 0?0:a]}
function ev(a,b){b=b===void 0?0:b;var c=R("client-screen-nonce-store");c||(c={},Km("client-screen-nonce-store",c));c[b]=a}
function fv(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function gv(a){return R(fv(a===void 0?0:a))}
E("yt_logging_screen.getRootVeType",gv);function hv(){var a=R("csn-to-ctt-auth-info");a||(a={},Km("csn-to-ctt-auth-info",a));return a}
function iv(){return Object.values(R("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function jv(a){a=dv(a===void 0?0:a);if(!a&&!R("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
E("yt_logging_screen.getCurrentCsn",jv);function kv(a,b,c){var d=hv();(c=jv(c))&&delete d[c];b&&(d[a]=b)}
function lv(a){return hv()[a]}
E("yt_logging_screen.getCttAuthInfo",lv);E("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==dv(c)||b!==R(fv(c)))if(kv(a,d,c),ev(a,c),Km(fv(c),b),b=function(){setTimeout(function(){a&&cp("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:av,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function mv(){var a=Dg(nv),b;return(new xi(function(c,d){a.onSuccess=function(e){fn(e)?c(new ov(e)):d(new pv("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new pv("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new pv("Request timed out","net.timeout",e))};
b=tn("//googleads.g.doubleclick.net/pagead/id",a)})).Gc(function(c){if(c instanceof Gi){var d;
(d=b)==null||d.abort()}return Ci(c)})}
function pv(a,b,c){fb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(pv,fb);function ov(a){this.xhr=a}
;function qv(){this.X=0;this.h=null}
qv.prototype.then=function(a,b,c){return this.X===1&&a?(a=a.call(c,this.h))&&typeof a.then==="function"?a:rv(a):this.X===2&&b?(a=b.call(c,this.h))&&typeof a.then==="function"?a:sv(a):this};
qv.prototype.getValue=function(){return this.h};
qv.prototype.isRejected=function(){return this.X==2};
qv.prototype.$goog_Thenable=!0;function sv(a){var b=new qv;a=a===void 0?null:a;b.X=2;b.h=a===void 0?null:a;return b}
function rv(a){var b=new qv;a=a===void 0?null:a;b.X=1;b.h=a===void 0?null:a;return b}
;function tv(a){var b=R("INNERTUBE_HOST_OVERRIDE");b&&(a=String(b)+String(oc(a)));return a}
function uv(a){var b={};T("json_condensed_response")&&(b.prettyPrint="false");return a=$m(a,b||{},!1)}
function vv(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:an(a)?"same-origin":"cors",credentials:an(a)?"same-origin":"include"};b={};for(var d=y(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function wv(){return lg()||(rd||sd)&&ip("applewebkit")&&!ip("version")&&(!ip("safari")||ip("gsa/"))||qd&&ip("version/")?!0:R("EOM_VISITOR_DATA")?!1:!0}
;function xv(a){var b=a.docid||a.video_id||a.videoId||a.id;if(b)return b;b=a.raw_player_response;b||(a=a.player_response)&&(b=JSON.parse(a));return b&&b.videoDetails&&b.videoDetails.videoId||null}
;function yv(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in qm)if(qm[d]==c.embeddedPlayerMode){b=qm[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function zv(a){fb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Av;this.isTimeout=a instanceof pv&&a.errorCode=="net.timeout";this.isCanceled=a instanceof Gi}
v(zv,fb);zv.prototype.name="BiscottiError";function Av(){fb.call(this,"Biscotti ID is missing from server")}
v(Av,fb);Av.prototype.name="BiscottiMissingError";var nv={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Bv=null;function Cv(){if(T("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!wv())return Error("User has not consented - not fetching biscotti id.");var a=R("PLAYER_VARS",{});if(Bg(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(yv(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Dm(){var a=Cv();if(a!==void 0)return Ci(a);Bv||(Bv=mv().then(Dv).Gc(function(b){return Ev(2,b)}));
return Bv}
function Dv(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Av;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Av;a=a.id;Em(a);Bv=rv(a);Fv(18E5,2);return a}
function Ev(a,b){b=new zv(b);Em("");Bv=sv(b);a>0&&Fv(12E4,a-1);throw b;}
function Fv(a,b){gn(function(){mv().then(Dv,function(c){return Ev(b,c)}).Gc(vi)},a)}
function Gv(){try{var a=F("yt.ads.biscotti.getId_");return a?a():Dm()}catch(b){return Ci(b)}}
;var Mb=oa(["data-"]);function Hv(a){a&&(a.dataset?a.dataset[Iv()]="true":Nb(a))}
function Jv(a){return a?a.dataset?a.dataset[Iv()]:a.getAttribute("data-loaded"):null}
var Kv={};function Iv(){return Kv.loaded||(Kv.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function Lv(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||Dg(b);this.assets=a.assets||{};this.attrs=a.attrs||Dg(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Lv.prototype.clone=function(){var a=new Lv,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];La(c)=="object"?a[b]=Dg(c):a[b]=c}return a};var Mv=["att/get"],Nv=["share/get_share_panel"],Ov=["share/get_web_player_share_panel"],Pv=["feedback"],Qv=["notification/modify_channel_preference"],Rv=["browse/edit_playlist"],Sv=["subscription/subscribe"],Tv=["subscription/unsubscribe"];var Uv=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};E("yt.msgs_",Uv);function Vv(a){Fm(Uv,arguments)}
;function Wv(a,b,c){Xv(a,b,c===void 0?null:c)}
function Yv(a){a=Zv(a);var b=document.getElementById(a);b&&(qt(a),b.parentNode.removeChild(b))}
function $v(a,b){a&&b&&(a=""+Pa(b),(a=aw[a])&&ot(a))}
function Xv(a,b,c){c=c===void 0?null:c;var d=Zv(a),e=document.getElementById(d),f=e&&Jv(e),g=e&&!f;f?b&&b():(b&&(f=mt(d,b),b=""+Pa(b),aw[b]=f),g||(e=bw(a,d,function(){Jv(e)||(Hv(e),pt(d),gn(function(){qt(d)},0))},c)))}
function bw(a,b,c,d){d=d===void 0?null:d;var e=Kg("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Kb(e,hm(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Zv(a){var b=document.createElement("a");Bb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+jc(a)}
var aw={};function cw(a){var b=dw(a),c=document.getElementById(b),d=c&&Jv(c);d||c&&!d||(c=ew(a,b,function(){if(!Jv(c)){Hv(c);pt(b);var e=Va(qt,b);gn(e,0)}}))}
function ew(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=hm(a);Pb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function dw(a){var b=Kg("A");Bb(b,new ub(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+jc(a)}
;function fw(a){var b=C.apply(1,arguments);if(!gw(a)||b.some(function(d){return!gw(d)}))throw Error("Only objects may be merged.");
b=y(b);for(var c=b.next();!c.done;c=b.next())hw(a,c.value)}
function hw(a,b){for(var c in b)if(gw(b[c])){if(c in a&&!gw(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});hw(a[c],b[c])}else if(iw(b[c])){if(c in a&&!iw(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);jw(a[c],b[c])}else a[c]=b[c];return a}
function jw(a,b){b=y(b);for(var c=b.next();!c.done;c=b.next())c=c.value,gw(c)?a.push(hw({},c)):iw(c)?a.push(jw([],c)):a.push(c);return a}
function gw(a){return typeof a==="object"&&!Array.isArray(a)}
function iw(a){return typeof a==="object"&&Array.isArray(a)}
;var kw="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function lw(a,b){var c=c===void 0?!0:c;var d=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=mc(window.location.href);e&&d.push(e);e=mc(a);if(Qb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),Bb(d,a),a=d.href)if(a=oc(a),a=pc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:jv()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&mw(a,b,f)}else mw(a,b)}
function mw(a,b,c){a=nw(a);b=b?sc(b):"";c=c||5;wv()&&Un(a,b,c)}
function nw(a){for(var b=y(kw),c=b.next();!c.done;c=b.next())a=xc(a,c.value);return"ST-"+jc(a).toString(36)}
;function ow(a){Zq.call(this,1,arguments);this.csn=a}
v(ow,Zq);var hr=new $q("screen-created",ow),pw=[],qw=0,rw=new Map,sw=new Map,tw=new Map;
function uw(a,b,c,d,e){e=e===void 0?!1:e;for(var f=vw({cttAuthInfo:lv(b)||void 0},b),g=y(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(zg(k)||!k.trackingParams&&!k.veType)&&Su(Error("Child VE logged with no data"));if(T("no_client_ve_attach_unless_shown")){var l=ww(h,b);if(k.veType&&!sw.has(l)&&!tw.has(l)&&!e){if(!T("il_attach_cache_limit")||rw.size<1E3){rw.set(l,[a,b,c,h]);return}T("il_attach_cache_limit")&&rw.size>1E3&&Su(new U("IL Attach cache exceeded limit"))}h=ww(c,b);rw.has(h)?
xw(c,b):tw.set(h,!0)}}d=d.filter(function(m){m.csn!==b?(m.csn=b,m=!0):m=!1;return m});
c={csn:b,parentVe:c.getAsJson(),childVes:Ub(d,function(m){return m.getAsJson()})};
b==="UNDEFINED_CSN"?yw("visualElementAttached",f,c):a?Ju("visualElementAttached",c,a,f):cp("visualElementAttached",c,f)}
function yw(a,b,c){pw.push({Te:a,payload:c,Rh:void 0,options:b});qw||(qw=ir())}
function jr(a){if(pw){for(var b=y(pw),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,cp(c.Te,c.payload,c.options));pw.length=0}qw=0}
function ww(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function xw(a,b){a=ww(a,b);rw.has(a)&&(b=rw.get(a)||[],uw(b[0],b[1],b[2],[b[3]],!0),rw.delete(a))}
function vw(a,b){T("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function zw(){try{return!!self.localStorage}catch(a){return!1}}
;function Aw(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Bw(a){if(zw()){var b=Object.keys(window.localStorage);b=y(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Aw(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Cw(){if(!zw())return!1;var a=mo(),b=Object.keys(window.localStorage);b=y(b);for(var c=b.next();!c.done;c=b.next())if(c=Aw(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Dw(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(R("INNERTUBE_CLIENT_NAME")==="WEB"||R("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Ew(){var a=a===void 0?!0:a;try{window.sessionStorage.removeItem("stickiness_reload");window.sessionStorage.removeItem("session_logininfo");Km("LOGIN_INFO","");a&&window.sessionStorage.setItem("from_switch_account","1");a=!0;a=a===void 0?!1:a;var b,c=Fw;c||(c=document.querySelector("#persist_identity"));if(b=c){var d=b.src?(new URL(b.src)).origin:"*";if(a){var e;(e=b.contentWindow)==null||e.postMessage({action:"clear"},d)}else if(!(Number(window.sessionStorage.getItem("stickiness_reload"))>=
2)){var f=window.sessionStorage.getItem("session_logininfo");if(f){var g;(g=b.contentWindow)==null||g.postMessage({loginInfo:f},d)}}}}catch(h){}}
function Gw(a){if(a)if(a.startsWith("https://accounts.google.com/AddSession"))Ew();else if(a.startsWith("https://accounts.google.com/ServiceLogin"))Ew();else{var b;if(b=a.startsWith("https://myaccount.google.com"))b=(a instanceof Dk?a.clone():new Dk(a)).h.endsWith("/youtubeoptions");b&&Ew()}if(R("LOGGED_IN",!0)&&Dw()){b=R("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=mc(window.location.href);c&&b.push(c);c=mc(a);Qb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=oc(a),(b=pc(b))?(b=nw(b),b=(b=Vn(b)||null)?Xm(b):
{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Dw()?(d||(d=R("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&lw(a,b)}}
var Fw=null;function Hw(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));b&&lw(a,b);if(c)return!1;Gw(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;b=tc(a,e);Gw(b);a=void 0;a=a===void 0?yb:a;a:if(f=b+f,a=a===void 0?yb:a,!(f instanceof ub)){for(b=0;b<a.length;++b)if(c=a[b],c instanceof wb&&c.Ge(f)){f=new ub(f);break a}f=void 0}g=g.location;f=Ab(f||vb);f!==void 0&&(g.href=f);return!0}
;function Iw(a){if(Bg(R("PLAYER_VARS",{}))!="1"){a&&Cm();try{Gv().then(function(){},function(){}),gn(Iw,18E5)}catch(b){Pm(b)}}}
;var Jw=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Kw(){var a=a===void 0?window.location.href:a;if(T("kevlar_disable_theme_param"))return null;var b=nc(a);if(T("enable_dark_theme_only_on_shorts")&&b!=null&&b.startsWith("/shorts/"))return"USER_INTERFACE_THEME_DARK";try{var c=Ym(a).theme;return Jw.get(c)||null}catch(d){}return null}
;function Lw(){this.h={};if(this.i=Xn()){var a=Vn("CONSISTENCY");a&&Mw(this,{encryptedTokenJarContents:a})}}
Lw.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Ga.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=y(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Mw(this,a)}};
function Mw(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&Un("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Nw=window.location.hostname.split(".").slice(-2).join(".");function Ow(){this.j=-1;var a=R("LOCATION_PLAYABILITY_TOKEN");R("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=Pw(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Qw;function Rw(){Qw=F("yt.clientLocationService.instance");Qw||(Qw=new Ow,E("yt.clientLocationService.instance",Qw));return Qw}
p=Ow.prototype;
p.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.o||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.o||
this.locationPlayabilityToken};
p.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,R("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=Pw(this))&&this.h.set("yt-location-playability-token",a,15552E3):Un("YT_CL",JSON.stringify({loctok:a}),15552E3,Nw,!0))};
function Pw(a){return a.h===void 0?new Uo("yt-client-location"):a.h}
p.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=Pw(this))&&this.h.remove("yt-location-playability-token"):Wn("YT_CL");this.o=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
p.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;R("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
p.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
p.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function Sw(a,b,c){b=b===void 0?!1:b;c=c===void 0?!1:c;var d=R("INNERTUBE_CONTEXT");if(!d)return Ru(Error("Error: No InnerTubeContext shell provided in ytconfig.")),{};d=Eg(d);T("web_no_tracking_params_in_shell_killswitch")||delete d.clickTracking;d.client||(d.client={});var e=d.client;e.clientName==="MWEB"&&e.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(e.clientFormFactor=R("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");e.screenWidthPoints=window.innerWidth;e.screenHeightPoints=window.innerHeight;
e.screenPixelDensity=Math.round(window.devicePixelRatio||1);e.screenDensityFloat=window.devicePixelRatio||1;e.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var f=f===void 0?!1:f;ao();var g="USER_INTERFACE_THEME_LIGHT";eo(165)?g="USER_INTERFACE_THEME_DARK":eo(174)?g="USER_INTERFACE_THEME_LIGHT":!T("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(g="USER_INTERFACE_THEME_DARK");
f=f?g:Kw()||g;e.userInterfaceTheme=f;if(!b){if(f=jo())e.connectionType=f;T("web_log_effective_connection_type")&&(f=ko())&&(d.client.effectiveConnectionType=f)}var h;if(T("web_log_memory_total_kbytes")&&((h=D.navigator)==null?0:h.deviceMemory)){var k;h=(k=D.navigator)==null?void 0:k.deviceMemory;d.client.memoryTotalKbytes=""+h*1E6}T("web_gcf_hashes_innertube")&&(f=Qq())&&(k=f.coldConfigData,h=f.coldHashData,f=f.hotHashData,d.client.configInfo=d.client.configInfo||{},k&&(d.client.configInfo.coldConfigData=
k),h&&(d.client.configInfo.coldHashData=h),f&&(d.client.configInfo.hotHashData=f));k=Ym(D.location.href);!T("web_populate_internal_geo_killswitch")&&k.internalcountrycode&&(e.internalGeo=k.internalcountrycode);e.clientName==="MWEB"||e.clientName==="WEB"?(e.mainAppWebInfo={graftUrl:D.location.href},T("kevlar_woffle")&&On.instance&&(k=On.instance,e.mainAppWebInfo.pwaInstallabilityStatus=!k.h&&k.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),e.mainAppWebInfo.webDisplayMode=
Pn(),e.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):e.clientName==="TVHTML5"&&(!T("web_lr_app_quality_killswitch")&&(k=R("LIVING_ROOM_APP_QUALITY"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{appQuality:k})),k=R("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{certificationScope:k}));if(!T("web_populate_time_zone_itc_killswitch")){a:{if(typeof Intl!=="undefined")try{var l=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break a}catch(Z){}l=
void 0}l&&(e.timeZone=l)}(l=R("EXPERIMENTS_TOKEN",""))?e.experimentsToken=l:delete e.experimentsToken;l=ln();Lw.instance||(Lw.instance=new Lw);d.request=Object.assign({},d.request,{internalExperimentFlags:l,consistencyTokenJars:wg(Lw.instance.h)});!T("web_prequest_context_killswitch")&&(l=R("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(d.request.externalPrequestContext=l);e=ao();l=eo(58);e=e.get("gsml","");d.user=Object.assign({},d.user);l&&(d.user.enableSafetyMode=l);e&&(d.user.lockedSafetyMode=!0);T("warm_op_csn_cleanup")?
c&&(b=jv())&&(d.clientScreenNonce=b):!b&&(b=jv())&&(d.clientScreenNonce=b);a&&(d.clickTracking={clickTrackingParams:a});if(a=F("yt.mdx.remote.remoteClient_"))d.remoteClient=a;Rw().setLocationOnInnerTubeContext(d);try{var m=bn(),n=m.bid;delete m.bid;d.adSignalsInfo={params:[],bid:n};for(var r=y(Object.entries(m)),t=r.next();!t.done;t=r.next()){var w=y(t.value),x=w.next().value,z=w.next().value;m=x;n=z;a=void 0;(a=d.adSignalsInfo.params)==null||a.push({key:m,value:""+n})}var G,H;if(((G=d.client)==null?
void 0:G.clientName)==="TVHTML5"||((H=d.client)==null?void 0:H.clientName)==="TVHTML5_UNPLUGGED"){var S=R("INNERTUBE_CONTEXT");S.adSignalsInfo&&(d.adSignalsInfo.advertisingId=S.adSignalsInfo.advertisingId,d.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",d.adSignalsInfo.limitAdTracking=S.adSignalsInfo.limitAdTracking)}}catch(Z){Ru(Z)}return d}
;function Tw(a){var b={"Content-Type":"application/json"};R("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=R("EOM_VISITOR_DATA"):R("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=R("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=R("LOGGED_IN",!1);R("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=R("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=R("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=R("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=R("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=R("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a),R("ENABLE_LAVA_HEADER_ON_IT_EXPANSION")&&(a=R("SERIALIZED_LAVA_DEVICE_CONTEXT"))&&(b["X-YouTube-Lava-Device-Context"]=a));return b}
;function Uw(){this.h={}}
p=Uw.prototype;p.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
p.get=function(a){if(this.contains(a))return this.h[a]};
p.set=function(a,b){this.h[a]=b};
p.Tb=function(){return Object.keys(this.h)};
p.remove=function(a){delete this.h[a]};function Vw(){this.mappings=new Uw}
Vw.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
Vw.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=Cb(b)}}return a};
new Vw;function Ww(a){return function(){return new a}}
;var Xw={},Yw=(Xw.WEB_UNPLUGGED="^unplugged/",Xw.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Xw.WEB_UNPLUGGED_OPS="^unplugged/",Xw.WEB_UNPLUGGED_PUBLIC="^unplugged/",Xw.WEB_CREATOR="^creator/",Xw.WEB_KIDS="^kids/",Xw.WEB_EXPERIMENTS="^experiments/",Xw.WEB_MUSIC="^music/",Xw.WEB_REMIX="^music/",Xw.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Xw.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Xw);
function Zw(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=Yw[b];if(c){c=new RegExp(c);for(var d=y(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(Yw).forEach(function(g){var h=y(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=y(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function $w(){}
$w.prototype.u=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?Tn:c;var d={context:Sw(a.clickTrackingParams,!1,this.o)};var e=this.i(a);if(e){this.h(d,e,b);var f;b="/youtubei/v1/"+Zw(this.j());(e=(f=au(a.commandMetadata,om))==null?void 0:f.apiUrl)&&(b=e);f=uv(tv(b));a=Object.assign({},{command:a},void 0);d={input:f,ab:vv(f),Ga:d,config:a};d.config.Pb?d.config.Pb.identity=c:d.config.Pb={identity:c};return d}c=new U("Error: Failed to create Request from Command.",a);Ru(c)};
da.Object.defineProperties($w.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function ax(){}
v(ax,$w);function bx(){}
v(bx,ax);bx.prototype.u=function(){return{input:"/getDatasyncIdsEndpoint",ab:vv("/getDatasyncIdsEndpoint","GET"),Ga:{}}};
bx.prototype.j=function(){return[]};
bx.prototype.i=function(){};
bx.prototype.h=function(){};var cx={},dx=(cx.GET_DATASYNC_IDS=Ww(bx),cx);function ex(a){var b;(b=F("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},E("ytcsi."+(a||"")+"data_",b));return b}
function fx(){var a=ex();a.info||(a.info={});return a.info}
function gx(a){a=ex(a);a.metadata||(a.metadata={});return a.metadata}
function hx(a){a=ex(a);a.tick||(a.tick={});return a.tick}
function ix(a){a=ex(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function jx(a){a=ix(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function kx(a){var b=ex(a).nonce;b||(b=$u(),ex(a).nonce=b);return b}
;function lx(){var a=F("ytcsi.debug");a||(a=[],E("ytcsi.debug",a),E("ytcsi.reference",{}));return a}
function mx(a){a=a||"";var b=F("ytcsi.reference");b||(lx(),b=F("ytcsi.reference"));if(b[a])return b[a];var c=lx(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var W={},nx=(W.auto_search="LATENCY_ACTION_AUTO_SEARCH",W.ad_to_ad="LATENCY_ACTION_AD_TO_AD",W.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",W.app_startup="LATENCY_ACTION_APP_STARTUP",W.browse="LATENCY_ACTION_BROWSE",W.cast_splash="LATENCY_ACTION_CAST_SPLASH",W.channel_activity="LATENCY_ACTION_KIDS_CHANNEL_ACTIVITY",W.channels="LATENCY_ACTION_CHANNELS",W.chips="LATENCY_ACTION_CHIPS",W.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",W.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",W.editor=
"LATENCY_ACTION_EDITOR",W.embed="LATENCY_ACTION_EMBED",W.embed_no_video="LATENCY_ACTION_EMBED_NO_VIDEO",W.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",W.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",W.explore="LATENCY_ACTION_EXPLORE",W.favorites="LATENCY_ACTION_FAVORITES",W.home="LATENCY_ACTION_HOME",W.inboarding="LATENCY_ACTION_INBOARDING",W.landing="LATENCY_ACTION_LANDING",W.library="LATENCY_ACTION_LIBRARY",W.live="LATENCY_ACTION_LIVE",
W.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",W.management="LATENCY_ACTION_MANAGEMENT",W.mini_app="LATENCY_ACTION_MINI_APP_PLAY",W.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",W.onboarding="LATENCY_ACTION_ONBOARDING",W.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",W.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",W.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",W.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",W.prebuffer=
"LATENCY_ACTION_PREBUFFER",W.prefetch="LATENCY_ACTION_PREFETCH",W.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",W.profile_switcher="LATENCY_ACTION_LOGIN",W.projects="LATENCY_ACTION_PROJECTS",W.reel_watch="LATENCY_ACTION_REEL_WATCH",W.results="LATENCY_ACTION_RESULTS",W.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",W.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",W.privacy_policy="LATENCY_ACTION_KIDS_PRIVACY_POLICY",W.review="LATENCY_ACTION_REVIEW",W.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",
W.search_ui="LATENCY_ACTION_SEARCH_UI",W.search_suggest="LATENCY_ACTION_SUGGEST",W.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",W.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",W.seek="LATENCY_ACTION_PLAYER_SEEK",W.settings="LATENCY_ACTION_SETTINGS",W.store="LATENCY_ACTION_STORE",W.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",W.tenx="LATENCY_ACTION_TENX",W.video_preview="LATENCY_ACTION_VIDEO_PREVIEW",W.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",W.watch="LATENCY_ACTION_WATCH",
W.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",W["watch,watch7"]="LATENCY_ACTION_WATCH",W["watch,watch7_html5"]="LATENCY_ACTION_WATCH",W["watch,watch7ad"]="LATENCY_ACTION_WATCH",W["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",W.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",W.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",W.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",W.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",W.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",
W.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",W.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",W.attestation_challenge_fetch="LATENCY_ACTION_ATTESTATION_CHALLENGE_FETCH",W);function ox(a,b){Zq.call(this,1,arguments);this.timer=b}
v(ox,Zq);var px=new $q("aft-recorded",ox);E("ytLoggingGelSequenceIdObj_",D.ytLoggingGelSequenceIdObj_||{});var qx=D.ytLoggingLatencyUsageStats_||{};E("ytLoggingLatencyUsageStats_",qx);function rx(){this.h=0}
function sx(){rx.instance||(rx.instance=new rx);return rx.instance}
rx.prototype.tick=function(a,b,c,d){tx(this,"tick_"+a+"_"+b)||cp("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
rx.prototype.info=function(a,b,c){var d=Object.keys(a).join("");tx(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,cp("latencyActionInfo",a,{cttAuthInfo:c}))};
rx.prototype.jspbInfo=function(){};
rx.prototype.span=function(a,b,c){var d=Object.keys(a).join("");tx(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,cp("latencyActionSpan",a,{cttAuthInfo:c}))};
function tx(a,b){qx[b]=qx[b]||{count:0};var c=qx[b];c.count++;c.time=V();a.h||(a.h=oo(function(){var d=V(),e;for(e in qx)qx[e]&&d-qx[e].time>6E4&&delete qx[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new U("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||Su(c)),!0):!1}
;var ux=window;function vx(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function wx(){var a;if(T("csi_use_performance_navigation_timing")||T("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=X==null?void 0:(a=X.getEntriesByType)==null?void 0:(b=a.call(X,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=xx(e.requestStart),e.responseEnd=xx(e.responseEnd),e.redirectStart=xx(e.redirectStart),e.redirectEnd=xx(e.redirectEnd),e.domainLookupEnd=xx(e.domainLookupEnd),e.connectStart=xx(e.connectStart),e.connectEnd=
xx(e.connectEnd),e.responseStart=xx(e.responseStart),e.secureConnectionStart=xx(e.secureConnectionStart),e.domainLookupStart=xx(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=X.timing}else a=T("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(X.timing)):X.timing;return a}
function xx(a){return Math.round(yx()+a)}
function yx(){return(T("csi_use_time_origin")||T("csi_use_time_origin_tvhtml5"))&&X.timeOrigin?Math.floor(X.timeOrigin):X.timing.navigationStart}
var X=ux.performance||ux.mozPerformance||ux.msPerformance||ux.webkitPerformance||new vx;var zx=!1,Ax=!1,Bx={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj",'script[name="embed_client"]':"ecj",'link[rel="stylesheet"][name="embed-ui"]':"ecc"};Ua(X.clearResourceTimings||X.webkitClearResourceTimings||X.mozClearResourceTimings||X.msClearResourceTimings||X.oClearResourceTimings||vi,X);function Cx(a,b){if(!T("web_csi_action_sampling_enabled")||!ex(b).actionDisabled){var c=mx(b||"");fw(c.info,a);a.loadType&&(c=a.loadType,gx(b).loadType=c);fw(jx(b),a);c=kx(b);b=ex(b).cttAuthInfo;sx().info(a,c,b)}}
function Dx(){var a,b,c,d;return((d=Ct().resolve(vt(Mq))==null?void 0:(a=Nq())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Ex(a,b,c){if(!T("web_csi_action_sampling_enabled")||!ex(c).actionDisabled){var d=kx(c),e;if(e=T("web_csi_debug_sample_enabled")&&d){(Ct().resolve(vt(Mq))==null?0:Nq())&&!Ax&&(Ax=!0,Ex("gcfl",V(),c));var f,g,h;e=(Ct().resolve(vt(Mq))==null?void 0:(f=Nq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Dx();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+d.charCodeAt(g),
g<d.length-1&&(f%=0x800000000000);e=f%1E5%e!==0;ex(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Cx(f,c));ex(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,X.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||T("web_csi_disable_alt_time_performance_mark"))X.mark(e);else{f=T("csi_use_performance_navigation_timing")||T("csi_use_performance_navigation_timing_tvhtml5")?f-X.timeOrigin:f-(X.timeOrigin||X.timing.navigationStart);try{X.mark(e,
{startTime:f})}catch(k){}}e=mx(c||"");e.tick[a]=b||V();if(e.callback&&e.callback[a])for(e=y(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=ix(c);e.gelTicks&&(e.gelTicks[a]=!0);f=hx(c);e=b||V();T("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=ex(c).cttAuthInfo;a==="_start"?(a=sx(),tx(a,"baseline_"+d)||cp("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):sx().tick(a,d,b,f);Fx(c);return e}}}
function Gx(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Ts+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Hx(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=y(Object.entries(R("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=y(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Ix(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);Fb(document)&&a.setAttribute("nonce",Fb(document));return c?(a=X.getEntriesByName(c))&&a[0]&&(a=a[0],c=yx(),Ex("rsf_"+b,c+Math.round(a.fetchStart)),Ex("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Jx(){var a=window.location.protocol,b=X.getEntriesByType("resource");b=Tb(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Vb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Ex("wffs",xx(b.startTime)),Ex("wffe",xx(b.responseEnd)))}
function Kx(a){var b=Lx("aft",a);if(b)return b;b=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Lx(b[d],a);if(e)return e}return NaN}
function Lx(a,b){if(a=hx(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Fx(a){var b=Lx("_start",a),c=Kx(a),d=!zx;b&&c&&d&&(er(px,new ox(Math.round(c-b),a)),zx=!0)}
function Mx(){if(X.getEntriesByType){var a=X.getEntriesByType("paint");if(a=Wb(a,function(c){return c.name==="first-paint"}))return xx(a.startTime)}var b;
T("csi_use_performance_navigation_timing")||T("csi_use_performance_navigation_timing_tvhtml5")?b=X.getEntriesByType("first-paint")[0].startTime:b=X.timing.Yh;return b?Math.max(0,b):0}
;function Nx(a,b){Om(function(){mx("").info.actionType=a;b&&Km("TIMING_AFT_KEYS",b);Km("TIMING_ACTION",a);var c=Hx();Object.keys(c).length>0&&Cx(c);c={isNavigation:!0,actionType:nx[R("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=R("PREVIOUS_ACTION");d&&(c.previousAction=nx[d]||"LATENCY_ACTION_UNKNOWN");if(d=R("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=R("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=jv())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Gx();if(d===1||d===-1)c.isVisible=!0;gx();fx();
c.loadType="cold";d=fx();var e=wx(),f=yx(),g=R("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!T("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Ex("srt",e.responseStart),d.prerender!==1&&Ex("_start",f,void 0));d=Mx();d>0&&Ex("fpt",d);d=wx();d.isPerformanceNavigationTiming&&Cx({performanceNavigationTiming:!0},void 0);Ex("nreqs",d.requestStart,void 0);Ex("nress",d.responseStart,void 0);Ex("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Ex("nrs",d.redirectStart,void 0),Ex("nre",
d.redirectEnd,void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Ex("ndnss",d.domainLookupStart,void 0),Ex("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Ex("ntcps",d.connectStart,void 0),Ex("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=yx()&&d.connectEnd-d.secureConnectionStart>0&&(Ex("nstcps",d.secureConnectionStart,void 0),Ex("ntcpe",d.connectEnd,void 0));X&&"getEntriesByType"in X&&Jx();d=[];if(document.querySelector&&X&&X.getEntriesByName)for(var h in Bx)Bx.hasOwnProperty(h)&&
(e=Bx[h],Ix(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=y(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Cx(c);c=ix();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=jx();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(gx().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=hx();e=ix();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Ex(k,Lx(k));else if(T("log_repeated_ytcsi_ticks"))for(f=
y(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Ex(k.slice(1),g);k={};d=!1;h=y(h);for(e=h.next();!e.done;e=h.next())d=e.value,fw(c,d),fw(k,d),d=!0;d&&Cx(k)}E("ytglobal.timingready_",!0);k=R("TIMING_ACTION");F("ytglobal.timingready_")&&k&&Ox()&&Kx()&&Fx()})()}
function Ox(a){return Om(function(){return Px("_start",a)})()}
function Qx(a,b,c){Om(Cx)(a,b,c===void 0?!1:c)}
function Rx(a,b,c){return Om(Ex)(a,b,c)}
function Px(a,b){return Om(function(){var c=hx(b);return a in c})()}
function Sx(a){if(!T("universal_csi_network_ticks"))return"";a=nc(a)||"";for(var b=Object.keys(Xq),c=0;c<b.length;c++){var d=b[c];if(a.includes(d))return d}return""}
function Tx(a){if(!T("universal_csi_network_ticks"))return function(){};
var b=Xq[a];return b?(Ux(b),function(){var c=T("universal_csi_network_ticks")?(c=Yq[a])?Ux(c):!1:!1;return c}):function(){}}
function Ux(a){return Om(function(){if(Px(a))return!1;Rx(a,void 0,void 0);return!0})()}
function Vx(a){Om(function(){if(!Ox("attestation_challenge_fetch")||Px(a,"attestation_challenge_fetch"))return!1;Rx(a,void 0,"attestation_challenge_fetch");return!0})()}
function Wx(){Om(function(){var a=kx();requestAnimationFrame(function(){setTimeout(function(){a===kx()&&Rx("ol",void 0,void 0)},0)})})()}
var Xx=window;Xx.ytcsi&&(Xx.ytcsi.infoGel=Qx,Xx.ytcsi.tick=Rx);var Yx="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD shorts_prefetch".split(" "),Zx=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function $x(a,b,c,d){this.u=a;this.fa=b;this.j=c;this.o=d;this.i=void 0;this.h=new Map;a.cc||(a.cc={});a.cc=Object.assign({},dx,a.cc)}
function ay(a,b,c,d){if($x.instance!==void 0){if(d=$x.instance,a=[a!==d.u,b!==d.fa,c!==d.j,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new U("InnerTubeTransportService is already initialized",a);
}else $x.instance=new $x(a,b,c,d)}
function by(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?Tn:c;var d=cy(a,b);return d?new xi(function(e,f){var g,h,k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d,2);case 2:g=n.i;h=g.u(b,void 0,c);if(!h){f(new U("Error: Failed to build request for command.",b));n.B(0);break}Gw(h.input);l=((k=h.ab)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.j.Nd){m=dy(h.config,l);n.B(4);break}return n.yield(ey(h.config,l),5);case 5:m=n.i;case 4:e(fy(a,h,m)),n.h=
0}})}):Ci(new U("Error: No request builder found for command.",b))}
function gy(a,b){function c(){}
var d="/youtubei/v1/"+Zw(Mv);var e=e===void 0?{Pb:{identity:Tn}}:e;var f=f===void 0?!0:f;c=Tx(Sx(d));b.context||(b.context=Sw(void 0,f));return new xi(function(g){var h,k,l,m,n;return B(function(r){if(r.h==1)return h=tv(d),k=an(h)?"same-origin":"cors",a.j.Nd?(l=dy(e,k),r.B(2)):r.yield(ey(e,k),3);r.h!=2&&(l=r.i);m=uv(tv(d));n={input:m,ab:vv(m),Ga:b,config:e};g(fy(a,n,l,c));r.h=0})})}
function hy(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.o){d=y(Yx);for(var e=d.next();!e.done;e=d.next())e=e.value,a.o[e]&&a.o[e].handleResponse(b,c)}}
function fy(a,b,c,d){d=d===void 0?function(){}:d;
var e,f,g,h,k,l,m,n,r,t,w,x,z,G,H,S,Z,mb,Sb,Wa,Db,Xa,Na,Ja,Ia,sh,Ls,Ms,Ns,Os;return B(function(ha){switch(ha.h){case 1:ha.B(2);break;case 3:if((e=ha.i)&&!e.isExpired())return ha.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Ga)==null?0:g.context)){ha.B(4);break}h=b.Ga.context;ha.B(5);break;case 5:k=y([]),l=k.next();case 8:if(l.done){ha.B(4);break}m=l.value;return ha.yield(m.Zh(h),9);case 9:l=k.next();ha.B(8);break;case 4:if((n=a.i)==null||!n.ii(b.input,b.Ga)){ha.B(12);break}return ha.yield(a.i.Th(b.input,
b.Ga),13);case 13:return r=ha.i,hy(a,r,b),ha.return(r);case 12:return(x=(w=b.config)==null?void 0:w.ci)&&a.h.has(x)?t=a.h.get(x):(z=JSON.stringify(b.Ga),S=(H=(G=b.ab)==null?void 0:G.headers)!=null?H:{},b.ab=Object.assign({},b.ab,{headers:Object.assign({},S,c)}),Z=Object.assign({},b.ab),b.ab.method==="POST"&&(Z=Object.assign({},Z,{body:z})),((mb=b.config)==null?0:mb.Ye)&&Rx(b.config.Ye),Sb=function(){return a.fa.fetch(b.input,Z,b.config)},t=Sb(),x&&a.h.set(x,t)),ha.yield(t,14);
case 14:if((Wa=ha.i)&&"error"in Wa&&((Db=Wa)==null?0:(Xa=Db.error)==null?0:Xa.details))for(Na=Wa.error.details,Ja=y(Na),Ia=Ja.next();!Ia.done;Ia=Ja.next())sh=Ia.value,(Ls=sh["@type"])&&Zx.indexOf(Ls)>-1&&(delete sh["@type"],Wa=sh);x&&a.h.has(x)&&a.h.delete(x);((Ms=b.config)==null?0:Ms.Ze)&&Rx(b.config.Ze);if(Wa||(Ns=a.i)==null||!Ns.yh(b.input,b.Ga)){ha.B(15);break}return ha.yield(a.i.Sh(b.input,b.Ga),16);case 16:Wa=ha.i;case 15:return hy(a,Wa,b),((Os=b.config)==null?0:Os.Ve)&&Rx(b.config.Ve),d(),
ha.return(Wa||void 0)}})}
function cy(a,b){a:{a=a.u;var c,d=(c=au(b,pm))==null?void 0:c.signal;if(d&&a.cc&&(c=a.cc[d])){var e=c();break a}var f;if((c=(f=au(b,nm))==null?void 0:f.request)&&a.he&&(f=a.he[c])){e=f();break a}for(e in b)if(a.Kc[e]&&(b=a.Kc[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function ey(a,b){var c,d,e,f;return B(function(g){if(g.h==1){e=(c=a)==null?void 0:(d=c.Pb)==null?void 0:d.sessionIndex;var h=g.yield;var k=Sn(0,{sessionIndex:e});if(!(k instanceof xi)){var l=new xi(vi);yi(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Tw(b),f)))})}
function dy(a,b){var c;a=a==null?void 0:(c=a.Pb)==null?void 0:c.sessionIndex;c=Sn(0,{sessionIndex:a});return Object.assign({},Tw(b),c)}
;var iy=new tt("INNERTUBE_TRANSPORT_TOKEN");function jy(){}
v(jy,ax);jy.prototype.j=function(){return Sv};
jy.prototype.i=function(a){return au(a,Bm)||void 0};
jy.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
da.Object.defineProperties(jy.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function ky(){}
v(ky,ax);ky.prototype.j=function(){return Tv};
ky.prototype.i=function(a){return au(a,Am)||void 0};
ky.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
da.Object.defineProperties(ky.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});var ly=new tt("SHARE_CLIENT_PARAMS_PROVIDER_TOKEN");function my(a){this.H=a}
v(my,ax);my.prototype.j=function(){return Nv};
my.prototype.i=function(a){return au(a,tm)||au(a,um)||au(a,sm)};
my.prototype.h=function(a,b){b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);if(b.clientParamIdentifier){var c;if((c=this.H)==null?0:c.h(b.clientParamIdentifier))a.clientParams=this.H.i(b.clientParamIdentifier)}};
my[st]=[ly];function ny(){}
v(ny,ax);ny.prototype.j=function(){return Pv};
ny.prototype.i=function(a){return au(a,rm)||void 0};
ny.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
da.Object.defineProperties(ny.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function oy(){}
v(oy,ax);oy.prototype.j=function(){return Qv};
oy.prototype.i=function(a){return au(a,ym)||void 0};
oy.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function py(){}
v(py,ax);py.prototype.j=function(){return Rv};
py.prototype.i=function(a){return au(a,xm)||void 0};
py.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function qy(){}
v(qy,ax);qy.prototype.j=function(){return Ov};
qy.prototype.i=function(a){return au(a,wm)};
qy.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var ry=new tt("FETCH_FN_TOKEN"),sy=new tt("PARSE_FN_TOKEN"),ty=new tt("WINDOW_REQUEST_TOKEN");function uy(a,b){var c=C.apply(2,arguments);a=a===void 0?0:a;U.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
v(uy,U);var vy=new tt("NETWORK_SLI_TOKEN");function wy(a,b,c,d){this.h=a;this.i=b;this.j=c;this.o=d}
wy.prototype.fetch=function(a,b,c){var d=this,e,f,g;return B(function(h){e=xy(d,a,b);g=(f=d.i)!=null?f:fetch;return h.return(g(e).then(function(k){return d.handleResponse(k,c)}).catch(function(k){Su(k);
if((c==null?0:c.re)&&k instanceof uy&&k.errorType===1)return Promise.reject(k)}))})};
function xy(a,b,c){if(a.h){var d=nc(xc(b,"key"))||"/UNKNOWN_PATH";a.h.start(d)}d=c;T("wug_networking_gzip_request")&&(d=Gr(c));var e;return new ((e=a.o)!=null?e:window.Request)(b,d)}
wy.prototype.handleResponse=function(a,b){var c,d=(c=this.j)!=null?c:JSON.parse;c=a.text().then(function(e){if((b==null?0:b.He)&&a.ok)return Qf(b.He,e);e=e.replace(")]}'","");if((b==null?0:b.re)&&e)try{var f=d(e)}catch(h){throw new uy(1,"JSON parsing failed after fetch");}var g;return(g=f)!=null?g:d(e)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Mh(),c=c.then(function(e){Su(new U("Error: API fetch failed",a.status,a.url,e));return Object.assign({},e,{errorMetadata:{status:a.status}})}));
return c};
wy[st]=[vt(vy),vt(ry),vt(sy),vt(ty)];var yy=new tt("NETWORK_MANAGER_TOKEN");var zy;function Ay(a){var b=new wj;if(a.interpreterJavascript){var c=fm(a.interpreterJavascript);c=Ib(c).toString();var d=new uj;Nf(d,6,c);If(b,uj,1,d,he)}else a.interpreterUrl&&(c=gm(a.interpreterUrl),c=ob(c).toString(),d=new vj,Nf(d,4,c),If(b,vj,2,d,he));a.interpreterHash&&Of(b,3,a.interpreterHash);a.program&&Of(b,4,a.program);a.globalName&&Of(b,5,a.globalName);a.clientExperimentsStateBlob&&Of(b,7,a.clientExperimentsStateBlob);return b}
function By(a){var b={};a=y(a.split("&"));for(var c=a.next();!c.done;c=a.next())c=c.value.split("="),c.length===2&&(b[c[0]]=c[1]);return b}
;function Dc(){if(T("bg_st_hr"))return"havuokmhhs-0";var a,b=((a=performance)==null?void 0:a.timeOrigin)||0;return"havuokmhhs-"+Math.floor(b)}
function Cy(a){this.h=a}
Cy.prototype.bindInnertubeChallengeFetcher=function(a){this.h.bicf(a)};
Cy.prototype.registerChallengeFetchedCallback=function(a){this.h.bcr(a)};
Cy.prototype.getLatestChallengeResponse=function(){return this.h.blc()};
function Dy(){return new Promise(function(a){var b=window.top;b.ntpevasrs!==void 0?a(new Cy(b.ntpevasrs)):(b.ntpqfbel===void 0&&(b.ntpqfbel=[]),b.ntpqfbel.push(function(c){a(new Cy(c))}))})}
;var Ey=[],Fy=!1;function Gy(){if(wv()){var a=R("PLAYER_VARS",{});if(Bg(a)!="1"&&!yv(a)){var b=function(){Fy=!0;"google_ad_status"in window?Km("DCLKSTAT",1):Km("DCLKSTAT",2)};
try{Wv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Ey.push(Yj.pa(function(){if(!(Fy||"google_ad_status"in window)){try{$v("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Fy=!0;Km("DCLKSTAT",3)}},5E3))}}}
function Hy(){var a=Number(R("DCLKSTAT",0));return isNaN(a)?0:a}
;function Y(a){this.h=a}
[new Y("b.f_"),new Y("j.s_"),new Y("r.s_"),new Y("e.h_"),new Y("i.s_"),new Y("s.t_"),new Y("p.h_"),new Y("s.i_"),new Y("f.i_"),new Y("a.b_"),new Y("a.o_"),new Y("g.o_"),new Y("p.i_"),new Y("p.m_"),new Y("n.k_"),new Y("i.f_"),new Y("a.s_"),new Y("m.c_"),new Y("n.h_"),new Y("o.p_"),new Y("m.p_"),new Y("o.a_"),new Y("d.p_")].reduce(function(a,b){a[b.h]=b;return a},{});function Iy(a,b,c){var d=this;this.network=a;this.options=b;this.o=c;this.h=null;if(b.ni){var e=new Aj;this.h=e.promise;D.ytAtRC&&Yj.Sa(function(){var f,g;return B(function(h){if(h.h==1){if(!D.ytAtRC)return h.return();f=Jy(null);return h.yield(d.ib(f),2)}g=h.i;D.ytAtRC&&D.ytAtRC(JSON.stringify(g));h.h=0})},2);
Dy().then(function(f){var g,h,k,l;return B(function(m){if(m.h==1)return f.bindInnertubeChallengeFetcher(function(n){return d.ib(Jy(n))}),m.yield(Cc(),2);
g=m.i;h=f.getLatestChallengeResponse();k=h.challenge;if(!k)throw Error("BGE_MACIL");l={challenge:k,gb:By(k),vm:g,bgChallenge:new wj};e.resolve(l);f.registerChallengeFetchedCallback(function(n){n=n.challenge;if(!n)throw Error("BGE_MACR");n={challenge:n,gb:By(n),vm:g,bgChallenge:new wj};d.h=Promise.resolve(n)});
m.h=0})})}else b.preload&&Ky(this,new Promise(function(f){oo(function(){f(Ly(d))},0)}))}
Iy.prototype.j=function(){var a=this;return B(function(b){return b.h==1?b.yield(Promise.race([a.h,null]),2):b.return(!!b.i)})};
Iy.prototype.i=function(a,b,c){var d=this,e,f,g;return B(function(h){d.h===null&&Ky(d,Ly(d));e=!1;f={};g=function(){var k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d.h,2);case 2:k=n.i;f.challenge=k.challenge;if(!k.vm){"c1a"in k.gb&&(f.error="ATTESTATION_ERROR_VM_NOT_INITIALIZED");n.B(3);break}l=Object.assign({},{c:k.challenge,e:a},b);va(n,4);e=!0;if(T("attbs")&&!T("attmusi")){m=k.vm.hd({wb:l});n.B(6);break}return n.yield(k.vm.snapshot({wb:l}),7);case 7:m=n.i;case 6:m?f.webResponse=
m:f.error="ATTESTATION_ERROR_VM_NO_RESPONSE";wa(n,3);break;case 4:xa(n),f.error="ATTESTATION_ERROR_VM_INTERNAL_ERROR";case 3:if(a==="ENGAGEMENT_TYPE_PLAYBACK"){var r=k.gb,t={};r.c6a&&(t.reportingStatus=String(Number(r.c)^Hy()));r.c6b&&(t.broadSpectrumDetectionResult=String(Number(r.c)^Number(R("CATSTAT",0))));f.adblockReporting=t}return n.return(f)}})};
return h.return(Promise.race([g(),My(c,function(){var k=Object.assign({},f);e&&(k.error="ATTESTATION_ERROR_VM_TIMEOUT");return k})]))})};
function Jy(a){var b={engagementType:"ENGAGEMENT_TYPE_UNBOUND"};a&&(b.interpreterHash=a);return b}
function Ly(a,b){b=b===void 0?0:b;var c,d,e,f,g,h,k,l,m,n,r,t;return B(function(w){switch(w.h){case 1:c=Jy(Fj().h);if(T("att_fet_ks"))return va(w,7),w.yield(a.ib(c),9);va(w,4);return w.yield(Ny(a,c),6);case 6:g=w.i;e=g.Qe;f=g.Re;d=g;wa(w,3);break;case 4:return xa(w),Su(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),Oy(a,864E5),w.return({challenge:"",gb:{},vm:void 0,bgChallenge:void 0});case 9:d=w.i;if(!d)throw Error("Fetching Attestation challenge returned falsy");
if(!d.challenge)throw Error("Missing Attestation challenge");e=d.challenge;f=By(e);if("c1a"in f&&(!d.bgChallenge||!d.bgChallenge.program))throw Error("Expected bg challenge but missing.");wa(w,3);break;case 7:h=xa(w);Su(h);b++;if(b>=5)return Su(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),Oy(a,864E5),w.return({challenge:"",gb:{},vm:void 0,bgChallenge:void 0});k=1E3*Math.pow(2,b-1)+Math.random()*1E3;return w.return(new Promise(function(x){oo(function(){x(Ly(a,
b))},k)}));
case 3:l=Number(f.t)||7200;Oy(a,l*1E3);m=void 0;if(!("c1a"in f&&d.bgChallenge)){w.B(10);break}n=Ay(d.bgChallenge);va(w,11);return w.yield(Gj(Fj(),n),13);case 13:wa(w,12);break;case 11:return r=xa(w),Su(r),w.return({challenge:e,gb:f,vm:m,bgChallenge:n});case 12:return va(w,14),m=new Cj({challenge:n,Bd:{Da:"aGIf"}}),w.yield(m.cd,16);case 16:wa(w,10);break;case 14:t=xa(w),Su(t),m=void 0;case 10:return w.return({challenge:e,gb:f,vm:m,bgChallenge:n})}})}
Iy.prototype.ib=function(a){var b=this,c;return B(function(d){c=b.o;if(!c||c.ta())return d.return(b.network.ib(a));Vx("att_pna");return d.return(new Promise(function(e){ci(c,"publicytnetworkstatus-online",function(){b.network.ib(a).then(e)})}))})};
function Py(a){if(!a)throw Error("Fetching Attestation challenge returned falsy");if(!a.challenge)throw Error("Missing Attestation challenge");var b=a.challenge,c=By(b);if("c1a"in c&&(!a.bgChallenge||!a.bgChallenge.program))throw Error("Expected bg challenge but missing.");return Object.assign({},a,{Qe:b,Re:c})}
function Ny(a,b){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:c=void 0,d=0,e={};case 2:if(!(d<5)){h.B(4);break}if(!(d>0)){h.B(5);break}e.pd=1E3*Math.pow(2,d-1)+Math.random()*1E3;return h.yield(new Promise(function(k){return function(l){oo(function(){l(void 0)},k.pd)}}(e)),5);
case 5:return va(h,7),h.yield(a.ib(b),9);case 9:return f=h.i,h.return(Py(f));case 7:c=g=xa(h),g instanceof Error&&Su(g);case 8:d++;e={pd:void 0};h.B(2);break;case 4:throw c;}})}
function Ky(a,b){a.h=b}
function Qy(a){var b,c,d;return B(function(e){if(e.h==1)return e.yield(Promise.race([a.h,null]),2);b=e.i;var f=Ly(a);a.h=f;(c=b)==null||(d=c.vm)==null||d.dispose();e.h=0})}
function Oy(a,b){function c(){var e;return B(function(f){e=d-Date.now();return e<1E3?f.yield(Qy(a),0):(oo(c,Math.min(e,6E4)),f.B(0))})}
var d=Date.now()+b;c()}
function My(a,b){return new Promise(function(c){oo(function(){c(b())},a)})}
;function Ry(a){this.h=a}
Ry.prototype.ib=function(a){Vx("att_fsr");return gy(this.h,a).then(function(b){Vx("att_frr");return b})};function Sy(){var a,b,c;return B(function(d){if(d.h==1)return a=Ct().resolve(iy),a?d.yield(by(a),2):(Su(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return Su(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Bh;return d.return(c)}Su(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function Ty(){}
v(Ty,ax);Ty.prototype.j=function(){return Pv};
Ty.prototype.i=function(a){return au(a,zm)};
Ty.prototype.h=function(a,b){b.undoToken&&(a.feedbackTokens=[b.undoToken]);b.isUndoTokenUnencrypted&&(a.isFeedbackTokenUnencrypted=b.isUndoTokenUnencrypted)};
da.Object.defineProperties(Ty.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Uy(){var a;return(a=R("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var Vy=D.caches,Wy;function Xy(a){var b=a.indexOf(":");return b===-1?{Ed:a}:{Ed:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Yy(){return B(function(a){if(Wy!==void 0)return a.return(Wy);Wy=new Promise(function(b){var c;return B(function(d){switch(d.h){case 1:return va(d,2),d.yield(Vy.open("test-only"),4);case 4:return d.yield(Vy.delete("test-only"),5);case 5:wa(d,3);break;case 2:if(c=xa(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Wy)})}
function Zy(a){var b,c,d,e,f,g,h;B(function(k){if(k.h==1)return k.yield(Yy(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(Vy.keys(),3)}c=k.i;d=y(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Xy(f),h=g.datasyncId,!h||a.includes(h)||b.push(Vy.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
function $y(){var a,b,c,d,e,f,g;return B(function(h){if(h.h==1)return h.yield(Yy(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=mo("cache contains other");return h.yield(Vy.keys(),3)}b=h.i;c=y(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Xy(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function az(){try{return!!self.sessionStorage}catch(a){return!1}}
;function bz(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function cz(a){if(az()){var b=Object.keys(window.sessionStorage);b=y(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=bz(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function dz(){if(!az())return!1;var a=mo(),b=Object.keys(window.sessionStorage);b=y(b);for(var c=b.next();!c.done;c=b.next())if(c=bz(c.value),c!==void 0&&c!==a)return!0;return!1}
;function ez(){Sy().then(function(a){a&&(rq(a),Zy(a),Bw(a),cz(a))})}
function fz(){var a=new As;Yj.pa(function(){var b,c,d,e,f;return B(function(g){switch(g.h){case 1:if(T("ytidb_clear_optimizations_killswitch")){g.B(2);break}b=mo("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];rq(h);Zy(h);Bw(h);cz(h);return g.return()}c=Cw();d=dz();return g.yield($y(),3);case 3:return e=g.i,g.yield(sq(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.ta()?ez():ci(a,"publicytnetworkstatus-online",ez),g.h=0}})})}
;var gz=["www.youtube-nocookie.com","www.youtubeeducation.com","youtube.googleapis.com"];function hz(){this.state=1;this.vm=null;this.h=void 0}
p=hz.prototype;p.initialize=function(a,b,c,d){this.h=d;if(a.program){var e;d=(e=a.interpreterUrl)!=null?e:null;if(a.interpreterSafeScript)e=fm(a.interpreterSafeScript);else{var f;e=(f=a.interpreterScript)!=null?f:null}a.interpreterSafeUrl&&(d=gm(a.interpreterSafeUrl).toString());iz(this,e,d,a.program,b,c)}else Su(Error("BL:CIP"))};
function iz(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,Wv(c,function(){window[g]?jz(a,d,g,e):(a.state=3,Yv(c),Su(new U("BL:ULB",""+c)))},f)):b?(f=Kg("SCRIPT"),b instanceof Gb?(f.textContent=Ib(b),Jb(f)):f.textContent=b,f.nonce=Fb(document),document.head.appendChild(f),document.head.removeChild(f),window[g]?jz(a,d,g,e):(a.state=4,Su(new U("BL:ULBJ")))):Su(new U("BL:ULV"))}
p.isLoading=function(){return this.state===2};
function jz(a,b,c,d){a.state=5;var e=!!a.h&&gz.includes(mc(a.h)||"");try{var f=new Cj({program:b,globalName:c,Bd:{disable:!T("att_web_record_metrics")||!T("att_skip_metrics_for_cookieless_domains_ks")&&e,Da:"aGIf"}});f.cd.then(function(){a.state=6;d&&d(b)});
a.bd(f)}catch(g){a.state=7,g instanceof Error&&Su(g)}}
p.invoke=function(a){a=a===void 0?{}:a;return this.ld()?this.Rd({wb:a}):null};
p.dispose=function(){this.bd(null);this.state=8};
p.ld=function(){return!!this.vm};
p.Rd=function(a){return this.vm.hd(a)};
p.bd=function(a){zc(this.vm);this.vm=a};function kz(){var a=F("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function lz(){hz.apply(this,arguments)}
v(lz,hz);lz.prototype.bd=function(a){var b;(b=kz())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.hd.bind(a)},E("yt.abuse.playerAttLoader",b),E("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(E("yt.abuse.playerAttLoader",null),E("yt.abuse.playerAttLoaderRun",null))};
lz.prototype.ld=function(){return!!kz()};
lz.prototype.Rd=function(a){return kz().bgvmc(a)};var mz=new tt("AUTH_SERVICE_TOKEN");function nz(a){Mt.call(this,a===void 0?"document_active":a);var b=this;this.o=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.G},{from:"document_active",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"flush_logs",action:this.H},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.H},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
v(nz,Mt);nz.prototype.G=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
nz.prototype.u=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
nz.prototype.H=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
nz.prototype.i=function(){this.h=new Map};function oz(a){Mt.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.H},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.u},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.H},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.H},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.u},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.u},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
T("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
v(oz,Mt);oz.prototype.i=function(a,b){a(b==null?void 0:b.event);T("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
oz.prototype.h=function(a,b){a(b==null?void 0:b.event);T("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
oz.prototype.u=function(a,b){a(b==null?void 0:b.event)};
oz.prototype.H=function(a,b){a(b==null?void 0:b.event)};function pz(){this.o=new nz;this.u=new oz}
pz.prototype.install=function(){var a=C.apply(0,arguments),b=this;a.forEach(function(c){b.o.install(c)});
a.forEach(function(c){b.u.install(c)})};function qz(){this.o=[];this.i=new Map;this.h=new Map;this.j=new Set}
qz.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=jv(c===void 0?0:c)){a=this.client;d=new cv({trackingParams:d});var e=void 0;if(T("no_client_ve_attach_unless_shown")){var f=ww(d,c);sw.set(f,!0);xw(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=vw({cttAuthInfo:lv(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?yw("visualElementGestured",f,d):a?Ju("visualElementGestured",d,a,f):cp("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
qz.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new cv({trackingParams:a}),b,c===void 0?0:c)};
qz.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.o.push([a,b]);else{var d=c;d=d===void 0?0:d;c=jv(d);a||(a=(a=gv(d===void 0?0:d))?new cv({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=vw({cttAuthInfo:lv(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?yw("visualElementStateChanged",d,b):a?Ju("visualElementStateChanged",b,a,d):cp("visualElementStateChanged",b,d))}};
function rz(a,b){if(b===void 0)for(var c=iv(),d=0;d<c.length;d++)c[d]!==void 0&&rz(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&uw(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function sz(){pz.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));T("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));T("web_log_cfg_cee_ks")||oo(tz)}
v(sz,pz);sz.prototype.j=function(){cp("finalPayload",{csn:jv()})};
sz.prototype.h=function(){Xu(Yu)};
sz.prototype.i=function(){var a=rz;qz.instance||(qz.instance=new qz);a(qz.instance)};
function tz(){var a=R("CLIENT_EXPERIMENT_EVENTS");if(a){var b=me();a=y(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&cp("genericClientExperimentEvent",{eventType:c});delete Jm.CLIENT_EXPERIMENT_EVENTS}}
;function uz(){}
function vz(){var a=F("ytglobal.storage_");a||(a=new uz,E("ytglobal.storage_",a));return a}
uz.prototype.estimate=function(){var a,b,c;return B(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return(wz()):d.return()})};
function wz(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
E("ytglobal.storageClass_",uz);function ap(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
ap.prototype.Ha=function(a){this.handleError(a)};
ap.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":T("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":T("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":xz(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function xz(a,b){vz().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:yz(c==null?void 0:c.usage),deviceStorageQuotaMbytes:yz(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function yz(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;var zz={Kc:{feedbackEndpoint:Ww(ny),modifyChannelNotificationPreferenceEndpoint:Ww(oy),playlistEditEndpoint:Ww(py),shareEntityEndpoint:Ww(my),subscribeEndpoint:Ww(jy),undoFeedbackEndpoint:Ww(Ty),unsubscribeEndpoint:Ww(ky),webPlayerShareEntityServiceEndpoint:Ww(qy)}};function Az(){var a=Ct();xt(a,{pb:yy,Hc:wy});xt(a,{pb:mz,Hc:Qn});var b=Rw(),c=a.resolve(mz),d=a.resolve(yy),e={};b&&(e.client_location=b);ay(zz,d,c,e);xt(a,{pb:iy,kd:$x.instance})}
;var Bz={},Cz=(Bz["api.invalidparam"]=2,Bz.auth=150,Bz["drm.auth"]=150,Bz["heartbeat.net"]=150,Bz["heartbeat.servererror"]=150,Bz["heartbeat.stop"]=150,Bz["html5.unsupportedads"]=5,Bz["fmt.noneavailable"]=5,Bz["fmt.decode"]=5,Bz["fmt.unplayable"]=5,Bz["html5.missingapi"]=5,Bz["html5.unsupportedlive"]=5,Bz["drm.unavailable"]=5,Bz["mrm.blocked"]=151,Bz["embedder.identity.denied"]=152,Bz);var Dz=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn playmuted muted_autoplay_duration_mode".split(" "));function Ez(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function Fz(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=y(Dz);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Gz(a,b,c,d){if(Oa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function Hz(a){I.call(this);var b=this;this.api=a;this.Y=this.u=!1;this.A=[];this.P={};this.j=[];this.i=[];this.Z=!1;this.sessionId=this.h=null;this.targetOrigin="*";this.U=T("web_player_split_event_bus_iframe");this.o=R("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.G=function(c){a:if(!(b.o!=="*"&&c.origin!==b.o||b.h&&c.source!==b.h||typeof c.data!=="string")){try{var d=JSON.parse(c.data)}catch(h){break a}if(d)switch(d.event){case "listening":var e=c.source;
c=c.origin;d=d.id;c!=="null"&&(b.o=b.targetOrigin=c);b.h=e;b.sessionId=d;if(b.u){b.Y=!0;b.u=!1;b.sendMessage("initialDelivery",Iz(b));b.sendMessage("onReady");e=y(b.A);for(d=e.next();!d.done;d=e.next())Jz(b,d.value);b.A=[]}break;case "command":if(e=d.func,d=d.args,e==="addEventListener"&&d)e=d[0],d=c.origin,e==="onReady"?b.api.logApiCall(e+" invocation",d):e==="onError"&&b.Z&&(b.api.logApiCall(e+" invocation",d,b.errorCode),b.errorCode=void 0),b.api.logApiCall(e+" registration",d),b.P[e]||e==="onReady"||
(c=Kz(b,e,d),b.i.push({eventType:e,listener:c,origin:d}),b.U?b.api.handleExternalCall("addEventListener",[e,c],d):b.api.addEventListener(e,c),b.P[e]=!0);else if(c=c.origin,b.api.isExternalMethodAvailable(e,c)){d=d||[];if(d.length>0&&Ez(e)){var f=d;if(Oa(f[0])&&!Array.isArray(f[0]))var g=f[0];else switch(g={},e){case "loadVideoById":case "cueVideoById":g=Fz(f[0],f[1]!==void 0?Number(f[1]):void 0,f[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":g=f[0];typeof g==="string"&&(g={mediaContentUrl:g,
startSeconds:f[1]!==void 0?Number(f[1]):void 0,suggestedQuality:f[2]});c:{if((f=g.mediaContentUrl)&&(f=/\/([ve]|embed)\/([^#?]+)/.exec(f))&&f[2]){f=f[2];break c}f=null}g.videoId=f;g=Fz(g);break;case "loadPlaylist":case "cuePlaylist":g=Gz(f[0],f[1],f[2],f[3])}d.length=1;d[0]=g}b.api.handleExternalCall(e,d,c);Ez(e)&&Lz(b,Iz(b))}}}};
Mz.addEventListener("message",this.G);if(a=R("WIDGET_ID"))this.sessionId=a;Nz(this,"onReady",function(){b.u=!0;var c=b.api.getVideoData();if(!c.isPlayable){b.Z=!0;c=c.errorCode;var d=d===void 0?5:d;b.errorCode=c?Cz[c]||d:d;b.sendMessage("onError",Number(b.errorCode))}});
Nz(this,"onVideoProgress",this.lf.bind(this));Nz(this,"onVolumeChange",this.mf.bind(this));Nz(this,"onApiChange",this.df.bind(this));Nz(this,"onPlaybackQualityChange",this.hf.bind(this));Nz(this,"onPlaybackRateChange",this.jf.bind(this));Nz(this,"onStateChange",this.kf.bind(this));Nz(this,"onWebglSettingsChanged",this.nf.bind(this));Nz(this,"onCaptionsTrackListChanged",this.ef.bind(this));Nz(this,"captionssettingschanged",this.ff.bind(this))}
v(Hz,I);function Lz(a,b){a.sendMessage("infoDelivery",b)}
p=Hz.prototype;p.sendMessage=function(a,b){a={event:a,info:b===void 0?null:b};this.Y?Jz(this,a):this.A.push(a)};
function Kz(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
function Nz(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function Iz(a){if(!a.api)return null;var b=a.api.getApiInterface();Xb(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substring(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
p.kf=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&!T("embeds_enable_vfsyb")&&(a.storyboardFormat=this.api.getStoryboardFormat());Lz(this,a)};
p.hf=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());Lz(this,a)};
p.jf=function(a){Lz(this,{playbackRate:a})};
p.df=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
p.mf=function(){Lz(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
p.lf=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Lz(this,a)};
p.nf=function(){Lz(this,{sphericalProperties:this.api.getSphericalProperties()})};
p.ef=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};Lz(this,a)}};
p.ff=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};Lz(this,a)}};
function Jz(a,b){if(a.h){b.channel="widget";a.sessionId&&(b.id=a.sessionId);try{var c=JSON.stringify(b);a.h.postMessage(c,a.targetOrigin)}catch(d){Su(d)}}}
p.ba=function(){I.prototype.ba.call(this);Mz.removeEventListener("message",this.G);for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.U?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};
var Mz=window;function Oz(a,b,c){I.call(this);var d=this;this.api=a;this.id=b;this.origin=c;this.h={};this.j=T("web_player_split_event_bus_iframe");this.i=function(e){a:if(e.origin===d.origin){var f=e.data;if(typeof f==="string"){try{f=JSON.parse(f)}catch(k){break a}if(f.command){var g=f.command;f=f.data;e=e.origin;if(!d.ea){var h=f||{};switch(g){case "addEventListener":typeof h.event==="string"&&d.addListener(h.event,e);break;case "removeEventListener":typeof h.event==="string"&&d.removeListener(h.event,e);break;
default:d.api.isReady()&&d.api.isExternalMethodAvailable(g,e||null)&&(f=Pz(g,f||{}),f=d.api.handleExternalCall(g,f,e||null),(f=Qz(g,f))&&Rz(d,g,f))}}}}}};
Sz.addEventListener("message",this.i);Rz(this,"RECEIVING")}
v(Oz,I);p=Oz.prototype;p.addListener=function(a,b){if(!(a in this.h)){var c=this.gf.bind(this,a);this.h[a]=c;this.addEventListener(a,c,b)}};
p.gf=function(a,b){this.ea||Rz(this,a,Tz(a,b))};
p.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
p.addEventListener=function(a,b,c){this.j?a==="onReady"?this.api.addEventListener(a,b):this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
p.removeEventListener=function(a,b,c){this.j?a==="onReady"?this.api.removeEventListener(a,b):this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function Pz(a,b){switch(a){case "loadVideoById":return[Fz(b)];case "cueVideoById":return[Fz(b)];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return[Gz(b)];case "cuePlaylist":return[Gz(b)];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];case "setShuffle":return[b.shufflePlaylist];
case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Qz(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function Tz(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
function Rz(a,b,c){a.ea||(b={id:a.id,command:b},c&&(b.data=c),Uz.postMessage(JSON.stringify(b),a.origin))}
p.ba=function(){Sz.removeEventListener("message",this.i);for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);I.prototype.ba.call(this)};
var Sz=window,Uz=window.parent;var Vz=new lz;function Wz(){return Vz.ld()}
function Xz(a){a=a===void 0?{}:a;return Vz.invoke(a)}
;function Yz(a,b,c,d,e){I.call(this);var f=this;this.A=b;this.webPlayerContextConfig=d;this.Lb=e;this.Qa=!1;this.api={};this.ma=this.u=null;this.U=new N;this.h={};this.Z=this.xa=this.elementId=this.Ra=this.config=null;this.Y=!1;this.j=this.G=null;this.Fa={};this.Ic=["onReady"];this.lastError=null;this.fb=NaN;this.P={};this.ha=0;this.i=this.o=a;Bc(this,this.U);Zz(this);c?this.ha=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&($z(this),aA(this))}
v(Yz,I);p=Yz.prototype;p.getId=function(){return this.A};
p.loadNewVideoConfig=function(a){if(!this.ea){this.ha&&(clearTimeout(this.ha),this.ha=0);var b=a||{};b instanceof Lv||(b=new Lv(b));this.config=b;this.setConfig(a);aA(this);this.isReady()&&bA(this)}};
function $z(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.A,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.A:a.config.attrs.id=a.A);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
p.setConfig=function(a){this.Ra=a;this.config=cA(a);$z(this);if(!this.xa){var b;this.xa=dA(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Sj(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Sj(Number(a)||a))};
function bA(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function eA(a){var b=!0,c=fA(a);c&&a.config&&(b=c.dataset.version===gA(a));return b&&!!F("yt.player.Application.create")}
function aA(a){if(!a.ea&&!a.Y){var b=eA(a);if(b&&(fA(a)?"html5":null)==="html5")a.Z="html5",a.isReady()||hA(a);else if(iA(a),a.Z="html5",b&&a.j&&a.o)a.o.appendChild(a.j),hA(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.G=function(){c=!0;var d=jA(a,"player_bootstrap_method")?F("yt.player.Application.createAlternate")||F("yt.player.Application.create"):F("yt.player.Application.create");var e=a.config?cA(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig,a.Lb);hA(a)};
a.Y=!0;b?a.G():(Wv(gA(a),a.G),(b=kA(a))&&cw(b||""),lA(a)&&!c&&E("yt.player.Application.create",null))}}}
function fA(a){var b=Jg(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function hA(a){if(!a.ea){var b=fA(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Y=!1;if(!jA(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}mA(a)}else a.fb=setTimeout(function(){hA(a)},50)}}
function mA(a){Zz(a);a.Qa=!0;var b=fA(a);if(b){a.u=nA(a,b,"addEventListener");a.ma=nA(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=nA(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.u&&a.u(g,a.h[g]);bA(a);a.xa&&a.xa(a.api);a.U.sb("onReady",a.api)}
function nA(a,b,c){var d=b[c];return function(){var e=C.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new U("PlayerProxy error in method call",{error:f,method:c,playerId:a.A}),e.level="WARNING",e;}}}
function Zz(a){a.Qa=!1;if(a.ma)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ma(b,a.h[b]);for(var c in a.P)a.P.hasOwnProperty(c)&&clearTimeout(Number(c));a.P={};a.u=null;a.ma=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ra};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
p.isReady=function(){return this.Qa};
p.addEventListener=function(a,b){var c=this,d=dA(this,b);d&&(Qb(this.Ic,a)>=0||this.h[a]||(b=oA(this,a),this.u&&this.u(a,b)),this.U.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
p.removeEventListener=function(a,b){this.ea||(b=dA(this,b))&&this.U.unsubscribe(a,b)};
function dA(a,b){var c=b;if(typeof b==="string"){if(a.Fa[b])return a.Fa[b];c=function(){var d=C.apply(0,arguments),e=F(b);if(e)try{e.apply(D,d)}catch(f){throw d=new U("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.Fa[b]=c}return c?c:null}
function oA(a,b){function c(d){function e(){if(!a.ea)try{a.U.sb(b,d!=null?d:void 0)}catch(h){var g=new U("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.A,data:d,originalStack:h.stack,componentStack:h.ge});g.level="WARNING";throw g;}}
if(jA(a,"web_player_publish_events_immediately"))e();else{var f=setTimeout(function(){e();var g=a.P,h=String(f);h in g&&delete g[h]},0);
Ag(a.P,String(f))}}
return a.h[b]=c}
p.getPlayerType=function(){return this.Z||(fA(this)?"html5":null)};
p.getLastError=function(){return this.lastError};
function iA(a){a.cancel();Zz(a);a.Z=null;a.config&&(a.config.loaded=!1);var b=fA(a);b&&(eA(a)||!lA(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
p.cancel=function(){this.G&&$v(gA(this),this.G);clearTimeout(this.fb);this.Y=!1};
p.ba=function(){iA(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new U("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.Fa=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Ra=this.config=this.api=null;delete this.o;delete this.i;I.prototype.ba.call(this)};
function lA(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function gA(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function kA(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function jA(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function cA(a){for(var b={},c=y(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?Dg(e):e}return b}
;var pA={},qA="player_uid_"+(Math.random()*1E9>>>0);function rA(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?Jg(c):c;var e=qA+"_"+Pa(c),f=pA[e];if(f&&d)return sA(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Yz(c,e,a,b,void 0);pA[e]=f;f.addOnDisposeCallback(function(){delete pA[f.getId()]});
return f.api}
function sA(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var tA=null,uA=null;
function vA(){Wx();var a=ao(),b=eo(119),c=window.devicePixelRatio>1;if(document.body&&gk(document.body,"exp-invert-logo"))if(c&&!gk(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!gk(d,"inverted-hdpi")){var e=ek(d);fk(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&gk(document.body,"inverted-hdpi")&&hk();if(b!=c){b="f"+(Math.floor(119/31)+1);d=fo(b)||0;d=c?d|67108864:d&-67108865;d===0?delete Yn[b]:(c=d.toString(16),Yn[b]=c.toString());
c=!0;T("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in Yn)Yn.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(Yn[f])));var f=d.join("&");Un(b,f,63072E3,a.i,c)}}
function wA(){xA()}
function yA(){Rx("ep_init_pr");xA()}
function xA(){var a=tA.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function zA(){tA&&tA.sendAbandonmentPing&&tA.sendAbandonmentPing();R("PL_ATT")&&Vz.dispose();for(var a=Yj,b=0,c=Ey.length;b<c;b++)a.qa(Ey[b]);Ey.length=0;Yv("//static.doubleclick.net/instream/ad_status.js");Fy=!1;Km("DCLKSTAT",0);Ac(uA);tA&&(tA.removeEventListener("onVideoDataChange",wA),tA.destroy())}
;Rx("ep_init_eps");E("yt.setConfig",Km);E("yt.config.set",Km);E("yt.setMsg",Vv);E("yt.msgs.set",Vv);E("yt.logging.errors.log",Ru);
E("writeEmbed",function(){Rx("ep_init_wes");var a=R("PLAYER_CONFIG");if(!a){var b=R("PLAYER_VARS");b&&(a={args:b})}Iw(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);c=Uy();if(!c.serializedForcedExperimentIds){var d=Ym(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=
d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)?Nx("watch",["pbs","pbu","pbp"]):a.args&&xv(a.args)?Nx("video_preview",["ol"]):Nx("embed_no_video",["ep_init_pr"]);tA=rA(a,c);tA.addEventListener("onVideoDataChange",wA);tA.addEventListener("onReady",yA);a=R("POST_MESSAGE_ID","player");R("ENABLE_JS_API")?uA=new Hz(tA):R("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(uA=new Oz(tA,a,b));Gy();T("ytidb_create_logger_embed_killswitch")||$o();a={};sz.h||(sz.h=new sz);sz.h.install((a.flush_logs=
{callback:function(){wu()}},a));
Qs();if(T("embeds_enable_separate_ITS")){Az();var f=function(){return $x.instance}}else f=function(){var g,h;
if(!zy){var k=Ct();xt(k,{pb:yy,Hc:wy});var l={Kc:{feedbackEndpoint:Ww(ny),modifyChannelNotificationPreferenceEndpoint:Ww(oy),playlistEditEndpoint:Ww(py),shareEntityEndpoint:Ww(my),subscribeEndpoint:Ww(jy),unsubscribeEndpoint:Ww(ky),webPlayerShareEntityServiceEndpoint:Ww(qy)}},m=Rw(),n={};m&&(n.client_location=m);g===void 0&&(g=Rn());h===void 0&&(h=k.resolve(yy));ay(l,h,g,n);xt(k,{pb:iy,kd:$x.instance});zy=k.resolve(iy)}return zy};
T("ytidb_clear_embedded_player")&&Yj.pa(function(){f();fz()});
T("enable_rta_manager")&&oo(function(){var g=new Ry(f());var h={preload:!T("enable_rta_npi")},k=!1;if(typeof h==="boolean")var l={preload:h};else typeof h==="undefined"?l={preload:!0}:(l=h,k=!!h.Ch);h=k?void 0:new As;Iy.instance=new Iy(g,l,h);g=Iy.instance;l=g.i.bind(g);E("yt.aba.att",l);g=g.j.bind(g);E("yt.aba.att2",g)});
Rx("ep_init_wee")});
E("yt.abuse.player.botguardInitialized",F("yt.abuse.player.botguardInitialized")||Wz);E("yt.abuse.player.invokeBotguard",F("yt.abuse.player.invokeBotguard")||Xz);E("yt.abuse.dclkstatus.checkDclkStatus",F("yt.abuse.dclkstatus.checkDclkStatus")||Hy);E("yt.player.exports.navigate",F("yt.player.exports.navigate")||Hw);E("yt.util.activity.init",F("yt.util.activity.init")||dt);E("yt.util.activity.getTimeSinceActive",F("yt.util.activity.getTimeSinceActive")||gt);
E("yt.util.activity.setTimestamp",F("yt.util.activity.setTimestamp")||et);window.addEventListener("load",Om(function(){vA()}));
window.addEventListener("pageshow",Om(function(a){a.persisted||vA()}));
window.addEventListener("pagehide",Om(function(a){T("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?zA():a.persisted||zA()}));
window.onerror=function(a,b,c,d,e){var f=d,g;b=b===void 0?"Unknown file":b;c=c===void 0?0:c;d=!1;var h=Lm("log_window_onerror_fraction");if(h&&Math.random()<h)d=!0;else{h=document.getElementsByTagName("script");for(var k=0,l=h.length;k<l;k++)if(h[k].src.indexOf("/debug-")>0){d=!0;break}}if(d){d=!1;e?d=!0:(typeof a==="string"?h=a:ErrorEvent&&a instanceof ErrorEvent?(d=!0,h=a.message,b=a.filename,c=a.lineno,f=a.colno):(h="Unknown error",b="Unknown file",c=0),e=new U(h),e.name="UnhandledWindowError",
e.message=h,e.fileName=b,e.lineNumber=c,isNaN(f)?delete e.columnNumber:e.columnNumber=f);if(!T("wiz_enable_component_stack_propagation_killswitch")){a=e;var m;if((m=g)==null||!m.componentStack)if(a=a.ge){g||(g={});m=g;for(b=[];b.length<20&&a;)b.push(a.name),a=a.parent;a=b.join(" > ");m.componentStack=a}}g&&Vu(e,g);d?Ru(e):Su(e)}};
Oi=Tu;window.addEventListener("unhandledrejection",function(a){Tu(a.reason)});
Rb(R("ERRORS")||[],function(a){Ru.apply(null,a)});
Km("ERRORS",[]);Rx("ep_init_epe");}).call(this);
