(function(){'use strict';var r;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var da=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ea(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ea(this);function u(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&da(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;da(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&da(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
var ka=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},la=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=ka(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ma;
if(typeof Object.setPrototypeOf=="function")ma=Object.setPrototypeOf;else{var na;a:{var oa={a:!0},pa={};try{pa.__proto__=oa;na=pa.a;break a}catch(a){}na=!1}ma=na?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var qa=ma;
function w(a,b){a.prototype=ka(b.prototype);a.prototype.constructor=a;if(qa)qa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function z(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function A(a){if(!(a instanceof Array)){a=z(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ra(a){return sa(a,a)}
function sa(a,b){a.raw=b;Object.freeze&&(Object.freeze(a),Object.freeze(b));return a}
function ta(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ua=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ta(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||ua});
function va(){this.D=!1;this.u=null;this.i=void 0;this.h=1;this.o=this.M=0;this.P=this.j=null}
function wa(a){if(a.D)throw new TypeError("Generator is already running");a.D=!0}
va.prototype.G=function(a){this.i=a};
function xa(a,b){a.j={exception:b,xd:!0};a.h=a.M||a.o}
va.prototype.return=function(a){this.j={return:a};this.h=this.o};
va.prototype.yield=function(a,b){this.h=b;return{value:a}};
va.prototype.A=function(a){this.h=a};
function ya(a,b,c){a.M=b;c!=void 0&&(a.o=c)}
function za(a,b){a.h=b;a.M=0}
function Aa(a){a.M=0;var b=a.j.exception;a.j=null;return b}
function Ba(a){var b=a.P.splice(0)[0];(b=a.j=a.j||b)?b.xd?a.h=a.M||a.o:b.A!=void 0&&a.o<b.A?(a.h=b.A,a.j=null):a.h=a.o:a.h=0}
function Ca(a){this.h=new va;this.i=a}
function Da(a,b){wa(a.h);var c=a.h.u;if(c)return Ea(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Fa(a)}
function Ea(a,b,c,d){try{var e=b.call(a.h.u,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.D=!1,e;var f=e.value}catch(g){return a.h.u=null,xa(a.h,g),Fa(a)}a.h.u=null;d.call(a.h,f);return Fa(a)}
function Fa(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.D=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.D=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.xd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ga(a){this.next=function(b){wa(a.h);a.h.u?b=Ea(a,a.h.u.next,b,a.h.G):(a.h.G(b),b=Fa(a));return b};
this.throw=function(b){wa(a.h);a.h.u?b=Ea(a,a.h.u["throw"],b,a.h.G):(xa(a.h,b),b=Fa(a));return b};
this.return=function(b){return Da(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ha(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function B(a){return Ha(new Ga(new Ca(a)))}
function C(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("globalThis",function(a){return a||fa});
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return la});
u("Reflect.setPrototypeOf",function(a){return a?a:qa?function(b,c){try{return qa(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.X=0;this.ab=void 0;this.h=[];this.u=!1;var h=this.i();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.u()})}this.h.push(g)};
var e=fa.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.u=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.o(l)}}}this.h=null};
c.prototype.o=function(g){this.j(function(){throw g;})};
b.prototype.i=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.U),reject:g(this.j)}};
b.prototype.U=function(g){if(g===this)this.j(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.Z(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.P(g):this.o(g)}};
b.prototype.P=function(g){var h=void 0;try{h=g.then}catch(k){this.j(k);return}typeof h=="function"?this.ha(h,g):this.o(g)};
b.prototype.j=function(g){this.M(2,g)};
b.prototype.o=function(g){this.M(1,g)};
b.prototype.M=function(g,h){if(this.X!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.X);this.X=g;this.ab=h;this.X===2&&this.Y();this.D()};
b.prototype.Y=function(){var g=this;e(function(){if(g.G()){var h=fa.console;typeof h!=="undefined"&&h.error(g.ab)}},1)};
b.prototype.G=function(){if(this.u)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.ab;return k(g)};
b.prototype.D=function(){if(this.h!=null){for(var g=0;g<this.h.length;++g)f.i(this.h[g]);this.h=null}};
var f=new c;b.prototype.Z=function(g){var h=this.i();g.ic(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.i();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(p,t){return typeof p=="function"?function(v){try{l(p(v))}catch(x){m(x)}}:t}
var l,m,n=new b(function(p,t){l=p;m=t});
this.ic(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.ic=function(g,h){function k(){switch(l.X){case 1:g(l.ab);break;case 2:h(l.ab);break;default:throw Error("Unexpected state: "+l.X);}}
var l=this;this.h==null?f.i(k):this.h.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=z(g),m=l.next();!m.done;m=l.next())d(m.value).ic(h,k)})};
b.all=function(g){var h=z(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(v){return function(x){p[v]=x;t--;t==0&&l(p)}}
var p=[],t=0;do p.push(void 0),t++,d(k.value).ic(n(p.length-1),m),k=h.next();while(!k.done)})};
return b});
u("Object.setPrototypeOf",function(a){return a||qa});
u("Symbol.dispose",function(a){return a?a:Symbol("Symbol.dispose")});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=z(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!ta(k,g)){var l=new c;da(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(m.get(k)!=2||m.get(l)!=3)return!1;m.delete(k);m.set(l,4);return!m.has(k)&&m.get(l)==4}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ta(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&ta(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ta(k,g)&&ta(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ta(k,g)&&ta(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ha(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&ta(h[0],l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,entry:n}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=z(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(z([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||m.value[1]!="s")return!1;m=l.next();return m.done||m.value[0].x!=4||m.value[1]!="t"||!l.next().done?!1:!0}catch(n){return!1}}())return a;
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
u("Set",function(a){function b(c){this.h=new Map;if(c){c=z(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(z([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
function Ia(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.entries",function(a){return a?a:function(){return Ia(this,function(b,c){return[b,c]})}});
u("Array.prototype.keys",function(a){return a?a:function(){return Ia(this,function(b){return b})}});
function Ja(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
u("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ta(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return Ja(this,b,"includes").indexOf(b,c||0)!==-1}});
u("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ta(b,d)&&c.push([d,b[d]]);return c}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.MIN_SAFE_INTEGER",function(){return-9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
u("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
u("Math.clz32",function(a){return a?a:function(b){b=Number(b)>>>0;if(b===0)return 32;var c=0;(b&4294901760)===0&&(b<<=16,c+=16);(b&4278190080)===0&&(b<<=8,c+=8);(b&4026531840)===0&&(b<<=4,c+=4);(b&3221225472)===0&&(b<<=2,c+=2);(b&2147483648)===0&&c++;return c}});
u("Math.log10",function(a){return a?a:function(b){return Math.log(b)/Math.LN10}});
u("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
u("Array.prototype.values",function(a){return a?a:function(){return Ia(this,function(b,c){return c})}});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Ka=Ka||{},D=this||self;function E(a,b,c){a=a.split(".");c=c||D;for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function F(a,b){a=a.split(".");b=b||D;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function La(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Ma(a){var b=La(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Ra(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Sa(a){return Object.prototype.hasOwnProperty.call(a,Ta)&&a[Ta]||(a[Ta]=++Ua)}
var Ta="closure_uid_"+(Math.random()*1E9>>>0),Ua=0;function Va(a,b,c){return a.call.apply(a.bind,arguments)}
function Wa(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Xa=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Va:Wa;return Xa.apply(null,arguments)}
function Za(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function $a(){return Date.now()}
function ab(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
;function bb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,bb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
ab(bb,Error);bb.prototype.name="CustomError";var cb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};/*

 Copyright Google LLC
 SPDX-License-Identifier: Apache-2.0
*/
var db=globalThis.trustedTypes,eb;function fb(){var a=null;if(!db)return a;try{var b=function(c){return c};
a=db.createPolicy("goog#html",{createHTML:b,createScript:b,createScriptURL:b})}catch(c){}return a}
function gb(){eb===void 0&&(eb=fb());return eb}
;function hb(a){this.h=a}
hb.prototype.toString=function(){return this.h+""};
function ib(a){var b=gb();return new hb(b?b.createScriptURL(a):a)}
function jb(a){if(a instanceof hb)return a.h;throw Error("");}
;var kb=ra([""]),lb=sa(["\x00"],["\\0"]),mb=sa(["\n"],["\\n"]),nb=sa(["\x00"],["\\u0000"]);function ob(a){return a.toString().indexOf("`")===-1}
ob(function(a){return a(kb)})||ob(function(a){return a(lb)})||ob(function(a){return a(mb)})||ob(function(a){return a(nb)});function pb(a){this.h=a}
pb.prototype.toString=function(){return this.h};
var qb=new pb("about:invalid#zClosurez");function rb(a){this.Ge=a}
function sb(a){return new rb(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var tb=[sb("data"),sb("http"),sb("https"),sb("mailto"),sb("ftp"),new rb(function(a){return/^[^:]*([/?#]|$)/.test(a)})],ub=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function vb(a){if(a instanceof pb)if(a instanceof pb)a=a.h;else throw Error("");else a=ub.test(a)?a:void 0;return a}
;function wb(a,b){b=vb(b);b!==void 0&&(a.href=b)}
;function xb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;function yb(a){this.h=a}
yb.prototype.toString=function(){return this.h+""};function zb(a){a=a===void 0?document:a;var b,c;a=(c=(b=a).querySelector)==null?void 0:c.call(b,"script[nonce]");return a==null?"":a.nonce||a.getAttribute("nonce")||""}
;function Ab(a){this.h=a}
Ab.prototype.toString=function(){return this.h+""};
function Bb(a){var b=gb();return new Ab(b?b.createScript(a):a)}
function Cb(a){if(a instanceof Ab)return a.h;throw Error("");}
;function Db(a){var b=zb(a.ownerDocument);b&&a.setAttribute("nonce",b)}
function Eb(a,b){a.src=jb(b);Db(a)}
;function Fb(){this.h=Gb[0].toLowerCase()}
Fb.prototype.toString=function(){return this.h};function Hb(a){var b="true".toString(),c=[new Fb];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof Fb)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;var Ib="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Jb(a,b){if(b instanceof hb)a.href=jb(b).toString(),a.rel="stylesheet";else{if(Ib.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=vb(b);b!==void 0&&(a.href=b,a.rel="stylesheet")}}
;var Lb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Mb=Array.prototype.forEach?function(a,b){Array.prototype.forEach.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)e in d&&b.call(void 0,d[e],e,a)},Nb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Ob=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Pb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Mb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Qb(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Rb(a,b){b=Lb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Sb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ma(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Tb(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function Ub(a){var b=F("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||D.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Vb(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Wb[c])c=Wb[c];else{c=String(c);if(!Wb[c]){var f=/function\s+([^\(]+)/m.exec(c);Wb[c]=f?f[1]:"[Anonymous]"}c=Wb[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function Vb(a,b){b||(b={});b[Xb(a)]=!0;var c=a.stack||"",d=a.cause;d&&!b[Xb(d)]&&(c+="\nCaused by: ",d.stack&&d.stack.indexOf(d.toString())==0||(c+=typeof d==="string"?d:d.message+"\n"),c+=Vb(d,b));a=a.errors;if(Array.isArray(a)){d=1;var e;for(e=0;e<a.length&&!(d>4);e++)b[Xb(a[e])]||(c+="\nInner error "+d++ +": ",a[e].stack&&a[e].stack.indexOf(a[e].toString())==0||(c+=typeof a[e]==="string"?a[e]:a[e].message+"\n"),c+=Vb(a[e],b));e<a.length&&(c+="\n... "+(a.length-e)+" more inner errors")}return c}
function Xb(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var Wb={};function Yb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var Zb=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function $b(a){return a?decodeURI(a):a}
function ac(a,b){return b.match(Zb)[a]||null}
function bc(a){return $b(ac(3,a))}
function cc(a){var b=a.match(Zb);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function dc(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function ec(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)ec(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function fc(a){var b=[],c;for(c in a)ec(c,a[c],b);return b.join("&")}
function hc(a,b){b=fc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function ic(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var jc=/#|$/,kc=/[?&]($|#)/;function lc(a,b){for(var c=a.search(jc),d=0,e,f=[];(e=ic(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(kc,"$1")}
;var mc=(new Date("2024-01-01T00:00:00Z")).getTime();function nc(a){var b=C.apply(1,arguments).filter(function(d){return d}).join("&");
if(!b)return a;var c=a.match(/[?&]adurl=/);return c?a.slice(0,c.index+1)+b+"&"+a.slice(c.index+1):a+(a.indexOf("?")===-1?"?":"&")+b}
function oc(a){var b=a.url;a=a.Xh;this.j=b;this.D=a;a=/[?&]dsh=1(&|$)/.test(b);this.u=!a&&/[?&]ae=1(&|$)/.test(b);this.M=!a&&/[?&]ae=2(&|$)/.test(b);if((this.h=/[?&]adurl=([^&]*)/.exec(b))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}this.o=(new Date).getTime()-mc}
function pc(a){a=a.D;if(!a)return"";var b="";a.platform&&(b+="&uap="+encodeURIComponent(a.platform));a.platformVersion&&(b+="&uapv="+encodeURIComponent(a.platformVersion));a.uaFullVersion&&(b+="&uafv="+encodeURIComponent(a.uaFullVersion));a.architecture&&(b+="&uaa="+encodeURIComponent(a.architecture));a.model&&(b+="&uam="+encodeURIComponent(a.model));a.bitness&&(b+="&uab="+encodeURIComponent(a.bitness));a.fullVersionList&&(b+="&uafvl="+encodeURIComponent(a.fullVersionList.map(function(c){return encodeURIComponent(c.brand)+
";"+encodeURIComponent(c.version)}).join("|")));
typeof a.wow64!=="undefined"&&(b+="&uaw="+Number(a.wow64));return b.substring(1)}
;function qc(){try{var a,b;return!!((a=window)==null?0:(b=a.top)==null?0:b.location.href)&&!1}catch(c){return!0}}
;function rc(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function sc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ma(d)?sc.apply(null,d):rc(d)}}
;function H(){this.ea=this.ea;this.M=this.M}
H.prototype.ea=!1;H.prototype.dispose=function(){this.ea||(this.ea=!0,this.ba())};
H.prototype[Symbol.dispose]=function(){this.dispose()};
function tc(a,b){a.addOnDisposeCallback(Za(rc,b))}
H.prototype.addOnDisposeCallback=function(a,b){this.ea?b!==void 0?a.call(b):a():(this.M||(this.M=[]),b&&(a=a.bind(b)),this.M.push(a))};
H.prototype.ba=function(){if(this.M)for(;this.M.length;)this.M.shift()()};function uc(){var a=vc();a=a===void 0?"bevasrsg":a;return new Promise(function(b){var c=window===window.top?window:qc()?window:window.top,d=c[a],e;((e=d)==null?0:e.bevasrs)?b(new wc(d.bevasrs)):(d||(d={},d=(d.nqfbel=[],d),c[a]=d),d.nqfbel.push(function(f){b(new wc(f))}))})}
function wc(a){H.call(this);var b=this;this.vm=a;this.i="keydown keypress keyup input focusin focusout select copy cut paste change click dblclick auxclick pointerover pointerdown pointerup pointermove pointerout dragenter dragleave drag dragend mouseover mousedown mouseup mousemove mouseout touchstart touchend touchmove wheel".split(" ");this.h=void 0;this.Zc=this.vm.p;this.j=this.o.bind(this);this.addOnDisposeCallback(function(){return void xc(b)})}
w(wc,H);wc.prototype.snapshot=function(a){return this.vm.s(Object.assign({},a.wb&&{c:a.wb},a.cd&&{s:a.cd},a.dd!==void 0&&{p:a.dd}))};
wc.prototype.o=function(a){this.vm.e(a)};
function xc(a){a.h!==void 0&&(a.i.forEach(function(b){var c;(c=a.h)==null||c.removeEventListener(b,a.j)}),a.h=void 0)}
;function yc(a){var b=b===void 0?47:b;var c=[];zc(a,Ac,6).forEach(function(d){Bc(d,2)<=b&&c.push(Bc(d,1))});
return c}
function Cc(a){var b=b===void 0?47:b;var c=[];zc(a,Ac,6).forEach(function(d){Bc(d,2)>b&&c.push(Bc(d,1))});
return c}
;var Dc;function Ec(){H.apply(this,arguments);this.j=1;this[Dc]=this.dispose}
w(Ec,H);Ec.prototype.share=function(){if(this.ea)throw Error("E:AD");this.j++;return this};
Ec.prototype.dispose=function(){--this.j||H.prototype.dispose.call(this)};
Dc=Symbol.dispose;function Fc(a){return{fieldType:2,fieldName:a}}
function Gc(a){return{fieldType:3,fieldName:a}}
;function Hc(a){this.h=a;a.Hc("/client_streamz/bg/frs",Gc("mk"))}
Hc.prototype.record=function(a,b){this.h.record("/client_streamz/bg/frs",a,b)};
function Ic(a){this.h=a;a.Hc("/client_streamz/bg/wrl",Gc("mn"),Fc("ac"),Fc("sc"),Gc("rk"),Gc("mk"))}
Ic.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function Jc(a){this.h=a;a.Mb("/client_streamz/bg/ec",Gc("en"),Gc("mk"))}
Jc.prototype.kb=function(a,b){this.h.Jb("/client_streamz/bg/ec",a,b)};
function Kc(a){this.h=a;a.Hc("/client_streamz/bg/el",Gc("en"),Gc("rk"),Gc("mk"))}
Kc.prototype.record=function(a,b,c,d){this.h.record("/client_streamz/bg/el",a,b,c,d)};
function Lc(a){this.h=a;a.Mb("/client_streamz/bg/cec",Fc("ec"),Gc("rk"),Gc("mk"))}
Lc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/cec",a,b,c)};
function Mc(a){this.h=a;a.Mb("/client_streamz/bg/po/csc",Fc("cs"),Gc("rk"),Gc("mk"))}
Mc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/po/csc",a,b,c)};
function Nc(a){this.h=a;a.Mb("/client_streamz/bg/po/ctav",Gc("av"),Gc("rk"),Gc("mk"))}
Nc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/po/ctav",a,b,c)};
function Oc(a){this.h=a;a.Mb("/client_streamz/bg/po/cwsc",Gc("su"),Gc("rk"),Gc("mk"))}
Oc.prototype.kb=function(a,b,c){this.h.Jb("/client_streamz/bg/po/cwsc",a,b,c)};function Pc(a){D.setTimeout(function(){throw a;},0)}
;var Qc,Rc=F("CLOSURE_FLAGS"),Sc=Rc&&Rc[610401301];Qc=Sc!=null?Sc:!1;function Tc(){var a=D.navigator;return a&&(a=a.userAgent)?a:""}
var Uc,Vc=D.navigator;Uc=Vc?Vc.userAgentData||null:null;function Wc(a){if(!Qc||!Uc)return!1;for(var b=0;b<Uc.brands.length;b++){var c=Uc.brands[b].brand;if(c&&c.indexOf(a)!=-1)return!0}return!1}
function I(a){return Tc().indexOf(a)!=-1}
;function Xc(){return Qc?!!Uc&&Uc.brands.length>0:!1}
function Yc(){return Xc()?!1:I("Opera")}
function Zc(){return I("Firefox")||I("FxiOS")}
function $c(){return Xc()?Wc("Chromium"):(I("Chrome")||I("CriOS"))&&!(Xc()?0:I("Edge"))||I("Silk")}
;function ad(){return Qc?!!Uc&&!!Uc.platform:!1}
function bd(){return I("iPhone")&&!I("iPod")&&!I("iPad")}
;function cd(a){cd[" "](a);return a}
cd[" "]=function(){};var dd=Yc(),ed=Xc()?!1:I("Trident")||I("MSIE"),fd=I("Edge"),gd=I("Gecko")&&!(Tc().toLowerCase().indexOf("webkit")!=-1&&!I("Edge"))&&!(I("Trident")||I("MSIE"))&&!I("Edge"),hd=Tc().toLowerCase().indexOf("webkit")!=-1&&!I("Edge");hd&&I("Mobile");ad()||I("Macintosh");ad()||I("Windows");(ad()?Uc.platform==="Linux":I("Linux"))||ad()||I("CrOS");var id=ad()?Uc.platform==="Android":I("Android");bd();I("iPad");I("iPod");bd()||I("iPad")||I("iPod");Tc().toLowerCase().indexOf("kaios");Zc();var jd=bd()||I("iPod"),kd=I("iPad");!I("Android")||$c()||Zc()||Yc()||I("Silk");$c();var ld=I("Safari")&&!($c()||(Xc()?0:I("Coast"))||Yc()||(Xc()?0:I("Edge"))||(Xc()?Wc("Microsoft Edge"):I("Edg/"))||(Xc()?Wc("Opera"):I("OPR"))||Zc()||I("Silk")||I("Android"))&&!(bd()||I("iPad")||I("iPod"));var md={},nd=null;function od(a,b){Ma(a);b===void 0&&(b=0);pd();b=md[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function qd(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;rd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function rd(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),m=nd[l];if(m!=null)return m;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
pd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function pd(){if(!nd){nd={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));md[c]=d;for(var e=0;e<d.length;e++){var f=d[e];nd[f]===void 0&&(nd[f]=e)}}}}
;var sd=typeof Uint8Array!=="undefined",td=!ed&&typeof btoa==="function",ud=/[-_.]/g,vd={"-":"+",_:"/",".":"="};function wd(a){return vd[a]||""}
var xd={};function yd(a,b){zd(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
yd.prototype.sizeBytes=function(){zd(xd);var a=this.h;if(!(a==null||sd&&a!=null&&a instanceof Uint8Array))if(typeof a==="string")if(td){ud.test(a)&&(a=a.replace(ud,wd));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=qd(a);else La(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};
var Ad;function zd(a){if(a!==xd)throw Error("illegal external caller");}
;var Bd=void 0;function Cd(a){a=Error(a);Tb(a,"warning");return a}
;var Dd=typeof Symbol==="function"&&typeof Symbol()==="symbol";function Ed(a,b,c){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?(c===void 0?0:c)&&Symbol.for&&a?Symbol.for(a):a!=null?Symbol(a):Symbol():b}
var Fd=Ed("jas",void 0,!0),Gd=Ed(void 0,"1oa"),Hd=Ed(void 0,"0actk");Math.max.apply(Math,A(Object.values({mh:1,lh:2,kh:4,ph:8,oh:16,nh:32,Nf:64,rh:128,ih:256,hh:512,Tf:1024,qh:2048,Uf:4096,Of:8192,jh:16384})));var K=Dd?Fd:"Fe",Id={Fe:{value:0,configurable:!0,writable:!0,enumerable:!1}},Jd=Object.defineProperties;function Kd(a,b){Dd||K in a||Jd(a,Id);a[K]|=b}
function Ld(a,b){Dd||K in a||Jd(a,Id);a[K]=b}
;var Md={};function Nd(a){return a!==null&&typeof a==="object"&&!Array.isArray(a)&&a.constructor===Object}
var Od,Pd=[];Ld(Pd,55);Od=Object.freeze(Pd);function Qd(a){if(a&2)throw Error();}
var Rd=Object.freeze({});function Sd(){return typeof BigInt==="function"}
;function Td(a){a.Fh=!0;return a}
;var Ud=Td(function(a){return typeof a==="number"}),Vd=Td(function(a){return typeof a==="string"}),Wd=Td(function(a){return typeof a==="boolean"});
function Xd(){var a=Yd;return Td(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
var Zd=Td(function(a){return a!=null&&typeof a==="object"&&typeof a.then==="function"});var $d=typeof D.BigInt==="function"&&typeof D.BigInt(0)==="bigint";function ae(a){var b=a;if(Vd(b)){if(!/^\s*(?:-?[1-9]\d*|0)?\s*$/.test(b))throw Error(String(b));}else if(Ud(b)&&!Number.isSafeInteger(b))throw Error(String(b));return $d?BigInt(a):a=Wd(a)?a?"1":"0":Vd(a)?a.trim()||"0":String(a)}
var ge=Td(function(a){return $d?a>=be&&a<=ce:a[0]==="-"?de(a,ee):de(a,fe)}),ee=Number.MIN_SAFE_INTEGER.toString(),be=$d?BigInt(Number.MIN_SAFE_INTEGER):void 0,fe=Number.MAX_SAFE_INTEGER.toString(),ce=$d?BigInt(Number.MAX_SAFE_INTEGER):void 0;
function de(a,b){if(a.length>b.length)return!1;if(a.length<b.length||a===b)return!0;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(d>e)return!1;if(d<e)return!0}}
;var he=0,ie=0;function je(a){var b=a>>>0;he=b;ie=(a-b)/4294967296>>>0}
function ke(a){if(a<0){je(0-a);var b=z(le(he,ie));a=b.next().value;b=b.next().value;he=a>>>0;ie=b>>>0}else je(a)}
function me(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else Sd()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=a/1E7>>>0,a%=1E7),c>=1E7&&(b+=c/1E7>>>0,c%=1E7),c=b+ne(c)+ne(a));return c}
function ne(a){a=String(a);return"0000000".slice(a.length)+a}
function oe(){var a=he,b=ie;b&2147483648?Sd()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=z(le(a,b)),a=b.next().value,b=b.next().value,a="-"+me(a,b)):a=me(a,b);return a}
function le(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function pe(a){return Array.prototype.slice.call(a)}
;var qe=typeof BigInt==="function"?BigInt.asIntN:void 0,re=Number.isSafeInteger,se=Number.isFinite,te=Math.trunc;function ue(a){return a.displayName||a.name||"unknown type name"}
function ve(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+La(a)+": "+a);return a}
var we=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function xe(a){switch(typeof a){case "bigint":return!0;case "number":return se(a);case "string":return we.test(a);default:return!1}}
function ye(a){if(typeof a!=="number")throw Cd("int32");if(!se(a))throw Cd("int32");return a|0}
function ze(a){return a==null?a:ye(a)}
function Ae(a){if(a==null)return a;if(typeof a==="string"&&a)a=+a;else if(typeof a!=="number")return;return se(a)?a|0:void 0}
function Be(a){var b=0;b=b===void 0?0:b;if(!xe(a))throw Cd("int64");var c=typeof a;switch(b){case 2048:switch(c){case "string":return Ce(a);case "bigint":return String(qe(64,a));default:return De(a)}case 4096:switch(c){case "string":return b=te(Number(a)),re(b)?a=ae(b):(b=a.indexOf("."),b!==-1&&(a=a.substring(0,b)),a=Sd()?ae(qe(64,BigInt(a))):ae(Ee(a))),a;case "bigint":return ae(qe(64,a));default:return re(a)?ae(Fe(a)):ae(De(a))}case 0:switch(c){case "string":return Ce(a);case "bigint":return ae(qe(64,
a));default:return Fe(a)}default:return xb(b,"Unknown format requested type for int64")}}
function Ge(a){return a==null?a:Be(a)}
function He(a){var b=a.length;return a[0]==="-"?b<20?!0:b===20&&Number(a.substring(0,7))>-922337:b<19?!0:b===19&&Number(a.substring(0,6))<922337}
function Ee(a){a.indexOf(".");if(He(a))return a;if(a.length<16)ke(Number(a));else if(Sd())a=BigInt(a),he=Number(a&BigInt(4294967295))>>>0,ie=Number(a>>BigInt(32)&BigInt(4294967295));else{var b=+(a[0]==="-");ie=he=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),ie*=1E6,he=he*1E6+d,he>=4294967296&&(ie+=Math.trunc(he/4294967296),ie>>>=0,he>>>=0);b&&(b=z(le(he,ie)),a=b.next().value,b=b.next().value,he=a,ie=b)}return oe()}
function Fe(a){xe(a);a=te(a);if(!re(a)){ke(a);var b=he,c=ie;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);var d=c*4294967296+(b>>>0);b=Number.isSafeInteger(d)?d:me(b,c);a=typeof b==="number"?a?-b:b:a?"-"+b:b}return a}
function De(a){xe(a);a=te(a);if(re(a))a=String(a);else{var b=String(a);He(b)?a=b:(ke(a),a=oe())}return a}
function Ce(a){xe(a);var b=te(Number(a));if(re(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return Ee(a)}
function Ie(a){if(a==null)return a;if(typeof a==="bigint")return ge(a)?a=Number(a):(a=qe(64,a),a=ge(a)?Number(a):String(a)),a;if(xe(a))return typeof a==="number"?Fe(a):Ce(a)}
function Je(a){if(typeof a!=="string")throw Error();return a}
function Ke(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function Le(a){return a==null||typeof a==="string"?a:void 0}
function Me(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+ue(b)+" but got "+(a&&ue(a.constructor)));}
function Ne(a,b,c){if(a!=null&&typeof a==="object"&&a.Rc===Md)return a;if(Array.isArray(a)){var d=a[K]|0,e=d;e===0&&(e|=c&32);e|=c&2;e!==d&&Ld(a,e);return new b(a)}}
;function Oe(a){return a}
function Pe(a){return a}
function Qe(a,b,c,d){return Re(a,b,c,d,Se,Te)}
function Ue(a,b,c,d){return Re(a,b,c,d,Ve,We)}
function Re(a,b,c,d,e,f){if(!c.length&&!d)return 1;for(var g=0,h=0,k=0,l=0,m=0,n=c.length-1;n>=0;n--){var p=c[n];d&&n===c.length-1&&p===d||(l++,p!=null&&k++)}if(d)for(var t in d)n=+t,isNaN(n)||(m+=Xe(n),h++,n>g&&(g=n));l=e(l,k)+f(h,g,m);t=k;n=h;p=g;for(var v=m,x=c.length-1;x>=0;x--){var y=c[x];if(!(y==null||d&&x===c.length-1&&y===d)){y=x-b;var G=e(y,t)+f(n,p,v);G<l&&(a=1+y,l=G);n++;t--;v+=Xe(y);p=Math.max(p,y)}}b=e(0,0)+f(n,p,v);b<l&&(a=1,l=b);if(d){n=h;p=g;v=m;t=k;for(var J in d)d=+J,isNaN(d)||d>=
1024||(n--,t++,v-=J.length,g=e(d,t)+f(n,p,v),g<l&&(a=1+d,l=g))}return a}
function We(a,b,c){return c+a*3+(a>1?a-1:0)}
function Ve(a,b){return(a>1?a-1:0)+(a-b)*4}
function Te(a,b){return a==0?0:9*Math.max(1<<32-Math.clz32(a+a/2-1),4)<=b?a==0?0:a<4?100+(a-1)*16:a<6?148+(a-4)*16:a<12?244+(a-6)*16:a<22?436+(a-12)*19:a<44?820+(a-22)*17:52+32*a:40+4*b}
function Se(a){return 40+4*a}
function Xe(a){return a>=100?a>=1E4?Math.ceil(Math.log10(1+a)):a<1E3?3:4:a<10?1:2}
;function Ye(a,b,c,d,e){d=d?!!(b&32):void 0;var f=[],g=a.length,h=!1;if(b&64){if(b&256){g--;var k=a[g];var l=g;Nd(k)}else l=4294967295,k=void 0,g&&Nd(a[g-1]);if(!(e||b&512)){h=!0;var m;var n=((m=Ze)!=null?m:Pe)(k?l- -1:b>>15&1023||536870912,-1,a,k);l=n+-1}}else l=4294967295,b&1||(k=g&&a[g-1],Nd(k)?(g--,l=g,n=0):k=void 0);m=void 0;for(var p=0;p<g;p++){var t=a[p];if(t!=null&&(t=c(t,d))!=null)if(p>=l){var v=void 0;((v=m)!=null?v:m={})[p- -1]=t}else f[p]=t}if(k)for(var x in k)a=k[x],a!=null&&(a=c(a,d))!=
null&&(g=+x,g<n?f[g+-1]=a:(g=void 0,((g=m)!=null?g:m={})[x]=a));m&&(h?f.push(m):f[l]=m);e&&Ld(f,b&33522241|(m!=null?290:34));return f}
function $e(a){switch(typeof a){case "number":return Number.isFinite(a)?a:""+a;case "bigint":return ge(a)?Number(a):""+a;case "boolean":return a?1:0;case "object":if(Array.isArray(a)){var b=a[K]|0;return a.length===0&&b&1?void 0:Ye(a,b,$e,!1,!1)}if(a.Rc===Md)return af(a);if(a instanceof yd){b=a.h;if(b==null)a="";else if(typeof b==="string")a=b;else{if(td){for(var c="",d=0,e=b.length-10240;d<e;)c+=String.fromCharCode.apply(null,b.subarray(d,d+=10240));c+=String.fromCharCode.apply(null,d?b.subarray(d):
b);b=btoa(c)}else b=od(b);a=a.h=b}return a}return}return a}
var Ze;function bf(a,b){if(b){Ze=b===Pe||b!==Oe&&b!==Qe&&b!==Ue?Pe:b;try{return af(a)}finally{Ze=void 0}}return af(a)}
function af(a){a=a.F;return Ye(a,a[K]|0,$e,void 0,!1)}
;function L(a,b,c){if(a==null){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-33521665|(b&1023)<<15)}else{if(!Array.isArray(a))throw Error("narr");d=a[K]|0;8192&d||!(64&d)||2&d||cf();if(d&1024)throw Error("farr");if(d&64)return d&16384||Ld(a,d|16384),a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error("mid");a:{c=a;var e=c.length;if(e){var f=e-1,g=c[f];if(Nd(g)){d|=256;b=d&512?0:-1;f-=b;if(f>=1024)throw Error("pvtlmt");for(var h in g)e=+h,e<f&&(c[e+b]=g[h],delete g[h]);d=d&-33521665|(f&1023)<<15;break a}}if(b){h=
Math.max(b,e-(d&512?0:-1));if(h>1024)throw Error("spvt");d=d&-33521665|(h&1023)<<15}}}Ld(a,d|16384);return a}
function cf(){if(Hd!=null){var a;var b=(a=Bd)!=null?a:Bd={};a=b[Hd]||0;a>=5||(b[Hd]=a+1,b=Error(),Tb(b,"incident"),Pc(b))}}
;function df(a,b){if(typeof a!=="object")return a;if(Array.isArray(a)){var c=a[K]|0;if(a.length===0&&c&1)return;if(c&2)return a;var d;if(d=b)d=c===0||!!(c&32)&&!(c&64||!(c&16));return d?(Kd(a,34),c&4&&Object.freeze(a),a):Ye(a,c,df,b!==void 0,!0)}if(a.Rc===Md)return b=a.F,c=b[K]|0,c&2?a:Ye(b,c,df,!0,!0);if(a instanceof yd)return a}
function ef(a){var b=a.F;if(!((b[K]|0)&2))return a;a=new a.constructor(Ye(b,b[K]|0,df,!0,!0));b=a.F;b[K]&=-3;return a}
;function ff(a,b){Object.isExtensible(a);a=a.F;return gf(a,a[K]|0,b)}
function gf(a,b,c){if(c===-1)return null;var d=c+(b&512?0:-1),e=a.length-1;if(d>=e&&b&256)return a[e][c];if(d<=e)return a[d]}
function hf(a,b,c){var d=a.F,e=d[K]|0;Qd(e);jf(d,e,b,c);return a}
function jf(a,b,c,d){var e=b&512?0:-1,f=c+e,g=a.length-1;if(f>=g&&b&256)return a[g][c]=d,b;if(f<=g)return a[f]=d,b;d!==void 0&&(g=b>>15&1023||536870912,c>=g?d!=null&&(f={},a[g+e]=(f[c]=d,f),b|=256,Ld(a,b)):a[f]=d);return b}
function kf(a){return!!(2&a)&&!!(4&a)||!!(1024&a)}
function lf(a,b,c){var d=a.F,e=d[K]|0;Qd(e);if(b==null)return jf(d,e,3),a;if(!Array.isArray(b))throw Cd();var f=b[K]|0,g=f,h=kf(f),k=h||Object.isFrozen(b);h||(f=0);k||(b=pe(b),g=0,f=mf(f,e),f=nf(f,e,!0),k=!1);f|=21;h=4&f?2048&f?2048:4096&f?4096:0:void 0;h=h!=null?h:0;for(var l=0;l<b.length;l++){var m=b[l],n=c(m,h);Object.is(m,n)||(k&&(b=pe(b),g=0,f=mf(f,e),f=nf(f,e,!0),k=!1),b[l]=n)}f!==g&&(k&&(b=pe(b),f=mf(f,e),f=nf(f,e,!0)),Ld(b,f));jf(d,e,3,b);return a}
function of(a,b,c,d){a=a.F;var e=a[K]|0;Qd(e);if(d==null){var f=pf(a);if(qf(f,a,e,c)===b)f.set(c,0);else return}else{c.includes(b);f=pf(a);var g=qf(f,a,e,c);g!==b&&(g&&(e=jf(a,e,g)),f.set(c,b))}jf(a,e,b,d)}
function pf(a){if(Dd){var b;return(b=a[Gd])!=null?b:a[Gd]=new Map}if(Gd in a)return a[Gd];b=new Map;Object.defineProperty(a,Gd,{value:b});return b}
function qf(a,b,c,d){var e=a.get(d);if(e!=null)return e;for(var f=e=0;f<d.length;f++){var g=d[f];gf(b,c,g)!=null&&(e!==0&&(c=jf(b,c,e)),e=g)}a.set(d,e);return e}
function rf(a,b,c){a=a.F;var d=a[K]|0,e=gf(a,d,c);b=Ne(e,b,d);b!==e&&b!=null&&jf(a,d,c,b);return b}
function sf(a,b,c){b=rf(a,b,c);if(b==null)return b;a=a.F;var d=a[K]|0;if(!(d&2)){var e=ef(b);e!==b&&(b=e,jf(a,d,c,b))}return b}
function zc(a,b,c){var d=void 0===Rd?2:4;var e=a.F[K]|0,f=e,g=!(2&e);a=a.F;var h=!!(2&f);e=h?1:d;g&&(g=!h);d=gf(a,f,c);d=Array.isArray(d)?d:Od;var k=d[K]|0;h=!!(4&k);if(!h){var l=k;l===0&&(l=mf(l,f));k=d;l|=1;var m=f,n=!!(2&l);n&&(m|=2);for(var p=!n,t=!0,v=0,x=0;v<k.length;v++){var y=Ne(k[v],b,m);if(y instanceof b){if(!n){var G=!!((y.F[K]|0)&2);p&&(p=!G);t&&(t=G)}k[x++]=y}}x<v&&(k.length=x);l|=4;l=t?l|16:l&-17;l=p?l|8:l&-9;Ld(k,l);n&&Object.freeze(k);k=l}if(g&&!(8&k||!d.length&&(e===1||e===4&&32&
k))){kf(k)&&(d=pe(d),k=mf(k,f),f=jf(a,f,c,d));b=d;g=k;for(k=0;k<b.length;k++)l=b[k],m=ef(l),l!==m&&(b[k]=m);g|=8;g=b.length?g&-17:g|16;Ld(b,g);k=g}e===1||e===4&&32&k?kf(k)||(f=k,c=!!(32&k),k|=!d.length||16&k&&(!h||c)?2:1024,k!==f&&Ld(d,k),Object.freeze(d)):(e===2&&kf(k)&&(d=pe(d),k=mf(k,f),k=nf(k,f,!1),Ld(d,k),f=jf(a,f,c,d)),kf(k)||(c=k,k=nf(k,f,!1),k!==c&&Ld(d,k)));return d}
function tf(a,b,c,d){d!=null?Me(d,b):d=void 0;return hf(a,c,d)}
function uf(a,b,c,d){var e=a.F,f=e[K]|0;Qd(f);if(d==null)return jf(e,f,c),a;if(!Array.isArray(d))throw Cd();for(var g=d[K]|0,h=g,k=kf(g),l=k||Object.isFrozen(d),m=!0,n=!0,p=0;p<d.length;p++){var t=d[p];Me(t,b);k||(t=!!((t.F[K]|0)&2),m&&(m=!t),n&&(n=t))}k||(g=m?13:5,g=n?g|16:g&-17);l&&g===h||(d=pe(d),h=0,g=mf(g,f),g=nf(g,f,!0));g!==h&&Ld(d,g);jf(e,f,c,d);return a}
function mf(a,b){a=(2&b?a|2:a&-3)|32;return a&=-1025}
function nf(a,b,c){32&b&&c||(a&=-33);return a}
function vf(a){a=ff(a,1);var b=b===void 0?!1:b;var c=typeof a;b=a==null?a:c==="bigint"?String(qe(64,a)):xe(a)?c==="string"?Ce(a):b?De(a):Fe(a):void 0;return b}
function Bc(a,b,c){c=c===void 0?0:c;var d;return(d=Ae(ff(a,b)))!=null?d:c}
function wf(a,b){var c=c===void 0?"":c;var d;return(d=Le(ff(a,b)))!=null?d:c}
function xf(a){var b=b===void 0?0:b;a=ff(a,1);a=a==null?a:se(a)?a|0:void 0;return a!=null?a:b}
function yf(a,b,c){return hf(a,b,Ke(c))}
function zf(a,b,c){c=Ke(c);a=a.F;var d=a[K]|0;Qd(d);jf(a,d,b,c===""?void 0:c)}
function Af(a,b,c){if(c!=null){if(!se(c))throw Cd("enum");c|=0}return hf(a,b,c)}
;function M(a,b,c){this.F=L(a,b,c)}
r=M.prototype;r.toJSON=function(){return bf(this)};
r.serialize=function(a){return JSON.stringify(bf(this,a))};
function Bf(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");Kd(b,32);return new a(b)}
r.clone=function(){var a=this,b=a.F;a=new a.constructor(Ye(b,b[K]|0,df,!0,!0));b=a.F;b[K]&=-3;return a};
r.Rc=Md;r.toString=function(){return this.F.toString()};function Cf(){this.ctor=Df;this.isRepeated=0;this.h=sf;this.defaultValue=void 0}
Cf.prototype.register=function(){cd(this)};function Ef(a){return function(b){return Bf(a,b)}}
;function Ff(a){this.F=L(a)}
w(Ff,M);function Gf(a,b){return lf(a,b,ye)}
;function Hf(a){this.F=L(a)}
w(Hf,M);var If=[1,2,3];function Jf(a){this.F=L(a)}
w(Jf,M);var Kf=[1,2,3];function Lf(a){this.F=L(a)}
w(Lf,M);function Mf(a){this.F=L(a)}
w(Mf,M);function Nf(a){this.F=L(a)}
w(Nf,M);function Of(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function Pf(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var p=g,t=0;t<64;t+=4)p[t/4]=n[t]<<24|n[t+1]<<16|n[t+2]<<8|n[t+3];for(t=16;t<80;t++)n=p[t-3]^p[t-8]^p[t-14]^p[t-16],p[t]=(n<<1|n>>>31)&4294967295;n=e[0];var v=e[1],x=e[2],y=e[3],G=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var J=y^v&(x^y);var ba=1518500249}else J=v^x^y,ba=1859775393;else t<60?(J=v&x|y&(v|x),ba=2400959708):(J=v^x^y,ba=3395469782);J=((n<<5|n>>>27)&4294967295)+J+G+ba+p[t]&4294967295;G=y;y=x;x=(v<<30|v>>>2)&4294967295;v=n;n=J}e[0]=e[0]+n&4294967295;e[1]=e[1]+v&4294967295;
e[2]=e[2]+x&4294967295;e[3]=e[3]+y&4294967295;e[4]=e[4]+G&4294967295}
function c(n,p){if(typeof n==="string"){n=unescape(encodeURIComponent(n));for(var t=[],v=0,x=n.length;v<x;++v)t.push(n.charCodeAt(v));n=t}p||(p=n.length);t=0;if(l==0)for(;t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64;for(;t<p;)if(f[l++]=n[t++],m++,l==64)for(l=0,b(f);t+64<p;)b(n.slice(t,t+64)),t+=64,m+=64}
function d(){var n=[],p=m*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=p&255,p>>>=8;b(f);for(t=p=0;t<5;t++)for(var v=24;v>=0;v-=8)n[p++]=e[t]>>v&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,je:function(){for(var n=d(),p="",t=0;t<n.length;t++)p+="0123456789ABCDEF".charAt(Math.floor(n[t]/16))+"0123456789ABCDEF".charAt(n[t]%16);return p}}}
;function Qf(a,b,c){var d=String(D.location.href);return d&&a&&b?[b,Rf(Of(d),a,c||null)].join(" "):null}
function Rf(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Mb(d,function(h){e.push(h)}),Sf(e.join(" "));
var f=[],g=[];Mb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Mb(d,function(h){e.push(h)});
a=Sf(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function Sf(a){var b=Pf();b.update(a);return b.je().toLowerCase()}
;function Tf(a){this.h=a||{cookie:""}}
r=Tf.prototype;r.isEnabled=function(){if(!D.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Vb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
r.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.bf;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Vb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
r.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=cb(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
r.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Vb:0,path:b,domain:c});return d};
r.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=cb(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;a>=0;a--)this.remove(b[a])};
var Uf=new Tf(typeof document=="undefined"?null:document);function Vf(){var a=D.__SAPISID||D.__APISID||D.__3PSAPISID||D.__1PSAPISID||D.__OVERRIDE_SID;if(a)return!0;typeof document!=="undefined"&&(a=new Tf(document),a=a.get("SAPISID")||a.get("APISID")||a.get("__Secure-3PAPISID")||a.get("__Secure-1PAPISID"));return!!a}
function Wf(a,b,c,d){(a=D[a])||typeof document==="undefined"||(a=(new Tf(document)).get(b));return a?Qf(a,c,d):null}
function Xf(a){var b=Of(String(D.location.href)),c=[];if(Vf()){b=b.indexOf("https:")==0||b.indexOf("chrome-extension:")==0||b.indexOf("chrome-untrusted://new-tab-page")==0||b.indexOf("moz-extension:")==0;var d=b?D.__SAPISID:D.__APISID;d||typeof document==="undefined"||(d=new Tf(document),d=d.get(b?"SAPISID":"APISID")||d.get("__Secure-3PAPISID"));(d=d?Qf(d,b?"SAPISIDHASH":"APISIDHASH",a):null)&&c.push(d);b&&((b=Wf("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&c.push(b),(a=Wf("__3PSAPISID",
"__Secure-3PAPISID","SAPISID3PHASH",a))&&c.push(a))}return c.length==0?null:c.join(" ")}
;function Yf(){}
Yf.prototype.compress=function(a){var b,c,d,e;return B(function(f){switch(f.h){case 1:return b=new CompressionStream("gzip"),c=(new Response(b.readable)).arrayBuffer(),d=b.writable.getWriter(),f.yield(d.write((new TextEncoder).encode(a)),2);case 2:return f.yield(d.close(),3);case 3:return e=Uint8Array,f.yield(c,4);case 4:return f.return(new e(f.i))}})};
Yf.prototype.isSupported=function(a){return a<1024?!1:typeof CompressionStream!=="undefined"};function Zf(a){this.F=L(a)}
w(Zf,M);function $f(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return $a()};
this.i=this.h()}
$f.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
$f.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
$f.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
$f.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function ag(a){this.F=L(a)}
w(ag,M);function bg(a){this.F=L(a)}
w(bg,M);function cg(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
r=cg.prototype;r.clone=function(){return new cg(this.x,this.y)};
r.equals=function(a){return a instanceof cg&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
r.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
r.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
r.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
r.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function dg(a,b){this.width=a;this.height=b}
r=dg.prototype;r.clone=function(){return new dg(this.width,this.height)};
r.aspectRatio=function(){return this.width/this.height};
r.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
r.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
r.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
r.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function eg(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function fg(a){var b=gg,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function hg(a){for(var b in a)return!1;return!0}
function ig(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function jg(a){return a!==null&&"privembed"in a?a.privembed:!1}
function kg(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function lg(a){var b={},c;for(c in a)b[c]=a[c];return b}
function mg(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=mg(a[c]);return b}
var ng="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function og(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<ng.length;f++)c=ng[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function pg(a,b){this.h=a===qg&&b||""}
pg.prototype.toString=function(){return this.h};
var qg={};new pg(qg,"");"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function rg(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function sg(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function tg(a){a&&a.parentNode&&a.parentNode.removeChild(a)}
function ug(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function vg(a){this.F=L(a)}
w(vg,M);vg.prototype.oc=function(){return xf(this)};function wg(a){this.F=L(a)}
w(wg,M);function xg(a){this.F=L(a)}
w(xg,M);function yg(a,b){uf(a,wg,1,b)}
;function zg(a){this.F=L(a)}
w(zg,M);var Ag=["platform","platformVersion","architecture","model","uaFullVersion"],Bg=new xg,Cg=null;function Dg(a,b){b=b===void 0?Ag:b;if(!Cg){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));c=(a.brands||[]).map(function(e){var f=new wg;f=yf(f,1,e.brand);return yf(f,2,e.version)});
yg(hf(Bg,2,ve(a.mobile)),c);Cg=a.getHighEntropyValues(b)}var d=new Set(b);return Cg.then(function(e){var f=Bg.clone();d.has("platform")&&yf(f,3,e.platform);d.has("platformVersion")&&yf(f,4,e.platformVersion);d.has("architecture")&&yf(f,5,e.architecture);d.has("model")&&yf(f,6,e.model);d.has("uaFullVersion")&&yf(f,7,e.uaFullVersion);return f}).catch(function(){return Bg.clone()})}
;function Eg(a){this.F=L(a)}
w(Eg,M);function Fg(a){this.F=L(a,4)}
w(Fg,M);function Gg(a){this.F=L(a,36)}
w(Gg,M);function Hg(a){this.F=L(a,19)}
w(Hg,M);Hg.prototype.Yb=function(a){return Af(this,2,a)};function Ig(a,b){this.Wa=b=b===void 0?!1:b;this.j=this.locale=null;this.i=0;this.isFinal=!1;this.h=new Hg;Number.isInteger(a)&&this.h.Yb(a);b||(this.locale=document.documentElement.getAttribute("lang"));Jg(this,new Eg)}
Ig.prototype.Yb=function(a){this.h.Yb(a);return this};
function Jg(a,b){tf(a.h,Eg,1,b);xf(b)||Af(b,1,1);a.Wa||(b=Kg(a),wf(b,5)||yf(b,5,a.locale));a.j&&(b=Kg(a),sf(b,xg,9)||tf(b,xg,9,a.j))}
function Lg(a,b){a.i=b}
function Mg(a){var b=b===void 0?Ag:b;var c=a.Wa?void 0:window;c?Dg(c,b).then(function(d){a.j=d;d=Kg(a);tf(d,xg,9,a.j);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function Kg(a){a=sf(a.h,Eg,1);var b=sf(a,zg,11);b||(b=new zg,tf(a,zg,11,b));return b}
function Ng(a,b,c,d,e,f,g){c=c===void 0?0:c;d=d===void 0?0:d;e=e===void 0?null:e;f=f===void 0?0:f;g=g===void 0?0:g;if(rf(sf(a.h,Eg,1),zg,11)!==void 0){var h=Kg(a);var k=new vg;k=Af(k,1,a.i);k=hf(k,2,ve(a.isFinal));d=hf(k,3,ze(d>0?d:void 0));d=hf(d,4,ze(f>0?f:void 0));d=hf(d,5,ze(g>0?g:void 0));f=d.F;g=f[K]|0;d=g&2?d:new d.constructor(Ye(f,g,df,!0,!0));tf(h,vg,10,d)}a=a.h.clone();h=Date.now().toString();a=hf(a,4,Ge(h));b=b.slice();b=uf(a,Gg,3,b);e&&(a=new ag,e=hf(a,13,ze(e)),a=new bg,e=tf(a,ag,2,e),
a=new Fg,e=tf(a,bg,1,e),e=Af(e,2,9),tf(b,Fg,18,e));c&&hf(b,14,Ge(c));return b}
;var Og=function(){if(!D.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
D.addEventListener("test",c,b);D.removeEventListener("test",c,b)}catch(d){}return a}();function Pg(a){this.h=this.i=this.j=a}
Pg.prototype.reset=function(){this.h=this.i=this.j};
Pg.prototype.getValue=function(){return this.i};function Qg(a){this.F=L(a,8)}
w(Qg,M);var Rg=Ef(Qg);function Df(a){this.F=L(a)}
w(Df,M);var Sg=new Cf;function Tg(a){H.call(this);var b=this;this.componentId="";this.h=[];this.Qa="";this.pageId=null;this.eb=this.ma=-1;this.G=this.experimentIds=null;this.D=this.o=0;this.U=null;this.Z=this.ha=0;this.Kb=1;this.timeoutMillis=0;this.xa=!1;this.logSource=a.logSource;this.ib=a.ib||function(){};
this.j=new Ig(a.logSource,a.Wa);this.network=a.network||null;this.ob=a.ob||null;this.bufferSize=1E3;this.P=a.zf||null;this.sessionIndex=a.sessionIndex||null;this.Qb=a.Qb||!1;this.logger=null;this.withCredentials=!a.qd;this.Wa=a.Wa||!1;this.Y=!this.Wa&&!!window&&!!window.navigator&&window.navigator.sendBeacon!==void 0;this.Pa=typeof URLSearchParams!=="undefined"&&!!(new URL(Ug())).searchParams&&!!(new URL(Ug())).searchParams.set;var c=Af(new Eg,1,1);Jg(this.j,c);this.u=new Pg(1E4);a=Vg(this,a.ld);
this.i=new $f(this.u.getValue(),a);this.Fa=new $f(6E5,a);this.Qb||this.Fa.start();this.Wa||(document.addEventListener("visibilitychange",function(){if(document.visibilityState==="hidden"){Wg(b);var d;(d=b.U)==null||d.flush()}}),document.addEventListener("pagehide",function(){Wg(b);
var d;(d=b.U)==null||d.flush()}))}
w(Tg,H);function Vg(a,b){return a.Pa?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
Tg.prototype.ba=function(){Wg(this);this.i.stop();this.Fa.stop();H.prototype.ba.call(this)};
function Xg(a){a.P||(a.P=Ug());try{return(new URL(a.P)).toString()}catch(b){return(new URL(a.P,window.location.origin)).toString()}}
function Yg(a,b,c){a.U&&a.U.kb(b,c)}
Tg.prototype.log=function(a){Yg(this,2,1);if(this.Pa){a=a.clone();var b=this.Kb++;a=hf(a,21,Ge(b));this.componentId&&yf(a,26,this.componentId);b=a;if(vf(b)==null){var c=Date.now();c=Number.isFinite(c)?c.toString():"0";hf(b,1,Ge(c))}Ie(ff(b,15))==null&&hf(b,15,Ge((new Date).getTimezoneOffset()*60));this.experimentIds&&(c=this.experimentIds.clone(),tf(b,Zf,16,c));Yg(this,1,1);b=this.h.length-this.bufferSize+1;b>0&&(this.h.splice(0,b),this.o+=b,Yg(this,3,b));this.h.push(a);this.Qb||this.i.enabled||this.i.start()}};
Tg.prototype.flush=function(a,b){var c=this;if(this.h.length===0)a&&a();else if(this.xa&&this.Y)this.j.i=3,Zg(this);else{var d=Date.now();if(this.eb>d&&this.ma<d)b&&b("throttled");else{this.network&&(typeof this.network.oc==="function"?Lg(this.j,this.network.oc()):this.j.i=0);var e=this.h.length,f=Ng(this.j,this.h,this.o,this.D,this.ob,this.ha,this.Z),g=this.ib();if(g&&this.Qa===g)b&&b("stale-auth-token");else{this.h=[];this.i.enabled&&this.i.stop();this.o=0;d=f.serialize();var h;this.G&&this.G.isSupported(d.length)&&
(h=this.G.compress(d));var k=$g(this,d,g),l=function(p){c.u.reset();c.i.setInterval(c.u.getValue());if(p){var t=null;try{var v=JSON.stringify(JSON.parse(p.replace(")]}'\n","")));t=Rg(v)}catch(G){}if(t){p=Number;var x="-1";x=x===void 0?"0":x;var y;v=(y=vf(t))!=null?y:x;y=p(v);y>0&&(c.ma=Date.now(),c.eb=c.ma+y);t=Sg.ctor?Sg.h(t,Sg.ctor,175237375):Sg.h(t,175237375,null);if(t=t===null?void 0:t)t=Bc(t,1,-1),t!==-1&&(c.u=new Pg(t<1?1:t),c.i.setInterval(c.u.getValue()))}}a&&a();c.D=0},m=function(p,t){var v=
zc(f,Gg,3);
var x;var y=(x=Ie(ff(f,14)))!=null?x:void 0;x=c.u;x.h=Math.min(3E5,x.h*2);x.i=Math.min(3E5,x.h+Math.round(.1*(Math.random()-.5)*2*x.h));c.i.setInterval(c.u.getValue());p===401&&g&&(c.Qa=g);y&&(c.o+=y);t===void 0&&(t=c.isRetryable(p));t&&(c.h=v.concat(c.h),c.Qb||c.i.enabled||c.i.start());Yg(c,7,1);b&&b("net-send-failed",p);++c.D},n=function(){c.network&&c.network.send(k,l,m)};
h?h.then(function(p){Yg(c,5,e);k.Dc["Content-Encoding"]="gzip";k.Dc["Content-Type"]="application/binary";k.body=p;k.ce=2;n()},function(){Yg(c,6,e);
n()}):n()}}}};
function $g(a,b,c){c=c===void 0?a.ib():c;var d=d===void 0?a.withCredentials:d;var e={},f=new URL(Xg(a));c&&(e.Authorization=c);a.sessionIndex&&(e["X-Goog-AuthUser"]=a.sessionIndex,f.searchParams.set("authuser",a.sessionIndex));a.pageId&&(Object.defineProperty(e,"X-Goog-PageId",{value:a.pageId}),f.searchParams.set("pageId",a.pageId));return{url:f.toString(),body:b,ce:1,Dc:e,requestType:"POST",withCredentials:d,timeoutMillis:a.timeoutMillis}}
function Wg(a){a.j.isFinal=!0;a.flush();a.j.isFinal=!1}
function Zg(a){ah(a,function(b,c){b=new URL(b);b.searchParams.set("format","json");var d=!1;try{d=window.navigator.sendBeacon(b.toString(),c.serialize())}catch(e){}d||(a.Y=!1);return d})}
function ah(a,b){if(a.h.length!==0){var c=new URL(Xg(a));c.searchParams.delete("format");var d=a.ib();d&&c.searchParams.set("auth",d);c.searchParams.set("authuser",a.sessionIndex||"0");for(d=0;d<10&&a.h.length;++d){var e=a.h.slice(0,32),f=Ng(a.j,e,a.o,a.D,a.ob,a.ha,a.Z);if(!b(c.toString(),f)){++a.D;break}a.o=0;a.D=0;a.ha=0;a.Z=0;a.h=a.h.slice(e.length)}a.i.enabled&&a.i.stop()}}
Tg.prototype.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function Ug(){return"https://play.google.com/log?format=json&hasfast=true"}
;function bh(){this.Wd=typeof AbortController!=="undefined"}
bh.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,m,n,p,t;return B(function(v){switch(v.h){case 1:return f=(e=d.Wd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,ya(v,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.Dc)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),v.yield(fetch(a.url,g),5);case 5:h=v.i;if(h.status!==200){(k=c)==null||k(h.status);v.A(3);break}if((l=b)==null){v.A(7);break}return v.yield(h.text(),8);case 8:l(v.i);case 7:case 3:v.P=[v.j];v.M=0;v.o=0;clearTimeout(f);Ba(v);break;case 2:m=Aa(v);switch((n=m)==null?void 0:n.name){case "AbortError":(p=c)==null||p(408);break;default:(t=c)==null||t(400)}v.A(3)}})};
bh.prototype.oc=function(){return 4};function ch(a,b){H.call(this);this.logSource=a;this.sessionIndex=b;this.Ua="https://play.google.com/log?format=json&hasfast=true";this.i=null;this.o=!1;this.network=null;this.componentId="";this.h=this.ob=null;this.j=!1;this.pageId=null;this.bufferSize=void 0}
w(ch,H);function dh(a,b){a.i=b;return a}
function gh(a,b){a.network=b;return a}
function hh(a,b){a.h=b}
function ih(a){a.j=!0;return a}
ch.prototype.qd=function(){this.u=!0;return this};
function jh(a){a.network||(a.network=new bh);var b=new Tg({logSource:a.logSource,ib:a.ib?a.ib:Xf,sessionIndex:a.sessionIndex,zf:a.Ua,Wa:a.o,Qb:!1,qd:a.u,ld:a.ld,network:a.network});tc(a,b);if(a.i){var c=a.i,d=Kg(b.j);yf(d,7,c)}b.G=new Yf;a.componentId&&(b.componentId=a.componentId);a.ob&&(b.ob=a.ob);a.pageId&&(b.pageId=a.pageId);a.h&&((d=a.h)?(b.experimentIds||(b.experimentIds=new Zf),c=b.experimentIds,d=d.serialize(),yf(c,4,d)):b.experimentIds&&hf(b.experimentIds,4));a.j&&(b.xa=b.Y);Mg(b.j);a.bufferSize&&
(b.bufferSize=a.bufferSize);a.network.Yb&&a.network.Yb(a.logSource);a.network.nf&&a.network.nf(b);return b}
;function kh(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;H.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new ch(a,"0"),a.componentId=b,tc(this,a),c!==""&&(a.Ua=c),d&&(a.o=!0),e&&dh(a,e),g&&gh(a,g),b=jh(a));this.h=b}
w(kh,H);
kh.prototype.flush=function(a){var b=a||[];if(b.length){a=new Nf;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=new Mf;f=yf(f,1,e.i);var g=lh(e);f=lf(f,g,Je);g=[];var h=[];for(var k=z(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var m=e.o;for(var n=e.Kc(l)||[],p=[],t=0;t<n.length;t++){var v=n[t],x=v&&v.h;v=new Jf;switch(m){case 3:x=Number(x);Number.isFinite(x)&&of(v,1,Kf,Ge(x));break;case 2:x=Number(x);if(x!=null&&typeof x!=="number")throw Error("Value of float/double field must be a number, found "+typeof x+
": "+x);of(v,2,Kf,x)}p.push(v)}m=p;for(n=0;n<m.length;n++){p=m[n];t=new Lf;p=tf(t,Jf,2,p);t=l;v=[];x=mh(e);for(var y=0;y<x.length;y++){var G=x[y],J=t[y],ba=new Hf;switch(G){case 3:of(ba,1,If,Ke(String(J)));break;case 2:G=Number(J);Number.isFinite(G)&&of(ba,2,If,ze(G));break;case 1:of(ba,3,If,ve(J==="true"))}v.push(ba)}uf(p,Hf,1,v);g.push(p)}}uf(f,Lf,4,g);c.push(f);e.clear()}uf(a,Mf,1,c);b=this.h;if(a instanceof Gg)b.log(a);else try{var ca=new Gg,Na=a.serialize();var Kb=yf(ca,8,Na);b.log(Kb)}catch(ja){Yg(b,
4,1)}this.h.flush()}};function nh(a){this.h=a}
;function oh(a,b,c){this.i=a;this.o=b;this.fields=c||[];this.h=new Map}
function mh(a){return a.fields.map(function(b){return b.fieldType})}
function lh(a){return a.fields.map(function(b){return b.fieldName})}
r=oh.prototype;r.Xd=function(a){var b=C.apply(1,arguments),c=this.Kc(b);c?c.push(new nh(a)):this.Id(a,b)};
r.Id=function(a){var b=this.kd(C.apply(1,arguments));this.h.set(b,[new nh(a)])};
r.Kc=function(){var a=this.kd(C.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
r.we=function(){var a=this.Kc(C.apply(0,arguments));return a&&a.length?a[0]:void 0};
r.clear=function(){this.h.clear()};
r.kd=function(){var a=C.apply(0,arguments);return a?a.join(","):"key"};function ph(a,b){oh.call(this,a,3,b)}
w(ph,oh);ph.prototype.j=function(a){var b=C.apply(1,arguments),c=0,d=this.we(b);d&&(c=d.h);this.Id(c+a,b)};function qh(a,b){oh.call(this,a,2,b)}
w(qh,oh);qh.prototype.record=function(a){this.Xd(a,C.apply(1,arguments))};function rh(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
rh.prototype.stopPropagation=function(){this.j=!0};
rh.prototype.preventDefault=function(){this.defaultPrevented=!0};function sh(a,b){rh.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
ab(sh,rh);
sh.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;b=a.relatedTarget;b||(c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement));this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==
void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=a.pointerType;this.state=a.state;this.i=a;a.defaultPrevented&&sh.Aa.preventDefault.call(this)};
sh.prototype.stopPropagation=function(){sh.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
sh.prototype.preventDefault=function(){sh.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var th="closure_listenable_"+(Math.random()*1E6|0);var uh=0;function vh(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.qc=e;this.key=++uh;this.Xb=this.hc=!1}
function wh(a){a.Xb=!0;a.listener=null;a.proxy=null;a.src=null;a.qc=null}
;function xh(a){this.src=a;this.listeners={};this.h=0}
xh.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=yh(a,b,d,e);g>-1?(b=a[g],c||(b.hc=!1)):(b=new vh(b,this.src,f,!!d,e),b.hc=c,a.push(b));return b};
xh.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=yh(e,b,c,d);return b>-1?(wh(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function zh(a,b){var c=b.type;c in a.listeners&&Rb(a.listeners[c],b)&&(wh(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function yh(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Xb&&f.listener==b&&f.capture==!!c&&f.qc==d)return e}return-1}
;var Ah="closure_lm_"+(Math.random()*1E6|0),Bh={},Ch=0;function Dh(a,b,c,d,e){if(d&&d.once)Eh(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Dh(a,b[f],c,d,e);else c=Fh(c),a&&a[th]?a.listen(b,c,Ra(d)?!!d.capture:!!d,e):Gh(a,b,c,!1,d,e)}
function Gh(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ra(e)?!!e.capture:!!e,h=Hh(a);h||(a[Ah]=h=new xh(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ih();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Og||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Jh(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Ch++}}
function Ih(){function a(c){return b.call(a.src,a.listener,c)}
var b=Kh;return a}
function Eh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Eh(a,b[f],c,d,e);else c=Fh(c),a&&a[th]?Lh(a,b,c,Ra(d)?!!d.capture:!!d,e):Gh(a,b,c,!0,d,e)}
function Mh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Mh(a,b[f],c,d,e);else(d=Ra(d)?!!d.capture:!!d,c=Fh(c),a&&a[th])?a.i.remove(String(b),c,d,e):a&&(a=Hh(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=yh(b,c,d,e)),(c=a>-1?b[a]:null)&&Nh(c))}
function Nh(a){if(typeof a!=="number"&&a&&!a.Xb){var b=a.src;if(b&&b[th])zh(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Jh(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Ch--;(c=Hh(b))?(zh(c,a),c.h==0&&(c.src=null,b[Ah]=null)):wh(a)}}}
function Jh(a){return a in Bh?Bh[a]:Bh[a]="on"+a}
function Kh(a,b){if(a.Xb)a=!0;else{b=new sh(b,this);var c=a.listener,d=a.qc||a.src;a.hc&&Nh(a);a=c.call(d,b)}return a}
function Hh(a){a=a[Ah];return a instanceof xh?a:null}
var Oh="__closure_events_fn_"+(Math.random()*1E9>>>0);function Fh(a){if(typeof a==="function")return a;a[Oh]||(a[Oh]=function(b){return a.handleEvent(b)});
return a[Oh]}
;function Ph(){H.call(this);this.i=new xh(this);this.xa=this;this.Z=null}
ab(Ph,H);Ph.prototype[th]=!0;r=Ph.prototype;r.addEventListener=function(a,b,c,d){Dh(this,a,b,c,d)};
r.removeEventListener=function(a,b,c,d){Mh(this,a,b,c,d)};
function Qh(a,b){var c=a.Z;if(c){var d=[];for(var e=1;c;c=c.Z)d.push(c),++e}a=a.xa;c=b.type||b;typeof b==="string"?b=new rh(b,a):b instanceof rh?b.target=b.target||a:(e=b,b=new rh(c,a),og(b,e));e=!0;var f;if(d)for(f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=Rh(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Rh(g,c,!0,b)&&e,b.j||(e=Rh(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Rh(g,c,!1,b)&&e}
r.ba=function(){Ph.Aa.ba.call(this);this.removeAllListeners();this.Z=null};
r.listen=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function Lh(a,b,c,d,e){a.i.add(String(b),c,!0,d,e)}
r.removeAllListeners=function(a){if(this.i){var b=this.i;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,wh(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function Rh(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Xb&&g.capture==c){var h=g.listener,k=g.qc||g.src;g.hc&&zh(a.i,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;var Sh=typeof AsyncContext!=="undefined"&&typeof AsyncContext.Snapshot==="function"?function(a){return a&&AsyncContext.Snapshot.wrap(a)}:function(a){return a};function Th(a,b){this.j=a;this.o=b;this.i=0;this.h=null}
Th.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Uh(a,b){a.o(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function Vh(){this.i=this.h=null}
Vh.prototype.add=function(a,b){var c=Wh.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Vh.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Wh=new Th(function(){return new Xh},function(a){return a.reset()});
function Xh(){this.next=this.scope=this.h=null}
Xh.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Xh.prototype.reset=function(){this.next=this.scope=this.h=null};var Yh,Zh=!1,$h=new Vh;function ai(a,b){Yh||bi();Zh||(Yh(),Zh=!0);$h.add(a,b)}
function bi(){var a=Promise.resolve(void 0);Yh=function(){a.then(ci)}}
function ci(){for(var a;a=$h.remove();){try{a.h.call(a.scope)}catch(b){Pc(b)}Uh(Wh,a)}Zh=!1}
;function di(){}
function ei(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;function fi(a){this.X=0;this.ab=void 0;this.vb=this.Sa=this.parent_=null;this.pc=this.Jc=!1;if(a!=di)try{var b=this;a.call(void 0,function(c){gi(b,2,c)},function(c){gi(b,3,c)})}catch(c){gi(this,3,c)}}
function hi(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
hi.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var ii=new Th(function(){return new hi},function(a){a.reset()});
function ji(a,b,c){var d=ii.get();d.i=a;d.h=b;d.context=c;return d}
function ki(a){return new fi(function(b,c){c(a)})}
fi.prototype.then=function(a,b,c){return li(this,Sh(typeof a==="function"?a:null),Sh(typeof b==="function"?b:null),c)};
fi.prototype.$goog_Thenable=!0;function mi(a,b,c,d){ni(a,ji(b||di,c||null,d))}
r=fi.prototype;r.finally=function(a){var b=this;a=Sh(a);return new Promise(function(c,d){mi(b,function(e){a();c(e)},function(e){a();
d(e)})})};
r.Fc=function(a,b){return li(this,null,Sh(a),b)};
r.catch=fi.prototype.Fc;r.cancel=function(a){if(this.X==0){var b=new oi(a);ai(function(){pi(this,b)},this)}};
function pi(a,b){if(a.X==0)if(a.parent_){var c=a.parent_;if(c.Sa){for(var d=0,e=null,f=null,g=c.Sa;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.X==0&&d==1?pi(c,b):(f?(d=f,d.next==c.vb&&(c.vb=d),d.next=d.next.next):qi(c),ri(c,e,3,b)))}a.parent_=null}else gi(a,3,b)}
function ni(a,b){a.Sa||a.X!=2&&a.X!=3||si(a);a.vb?a.vb.next=b:a.Sa=b;a.vb=b}
function li(a,b,c,d){var e=ji(null,null,null);e.child=new fi(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof oi?g(h):f(k)}catch(l){g(l)}}:g});
e.child.parent_=a;ni(a,e);return e.child}
r.xf=function(a){this.X=0;gi(this,2,a)};
r.yf=function(a){this.X=0;gi(this,3,a)};
function gi(a,b,c){if(a.X==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.X=1;a:{var d=c,e=a.xf,f=a.yf;if(d instanceof fi){mi(d,e,f,a);var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ra(d))try{var k=d.then;if(typeof k==="function"){ti(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.ab=c,a.X=b,a.parent_=null,si(a),b!=3||c instanceof oi||ui(a,c))}}
function ti(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function si(a){a.Jc||(a.Jc=!0,ai(a.qe,a))}
function qi(a){var b=null;a.Sa&&(b=a.Sa,a.Sa=b.next,b.next=null);a.Sa||(a.vb=null);return b}
r.qe=function(){for(var a;a=qi(this);)ri(this,a,this.X,this.ab);this.Jc=!1};
function ri(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.pc;a=a.parent_)a.pc=!1;if(b.child)b.child.parent_=null,vi(b,c,d);else try{b.j?b.i.call(b.context):vi(b,c,d)}catch(e){wi.call(null,e)}Uh(ii,b)}
function vi(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function ui(a,b){a.pc=!0;ai(function(){a.pc&&wi.call(null,b)})}
var wi=Pc;function oi(a){bb.call(this,a)}
ab(oi,bb);oi.prototype.name="cancel";function xi(a,b){Ph.call(this);this.j=a||1;this.h=b||D;this.o=Xa(this.tf,this);this.u=$a()}
ab(xi,Ph);r=xi.prototype;r.enabled=!1;r.Ea=null;r.setInterval=function(a){this.j=a;this.Ea&&this.enabled?(this.stop(),this.start()):this.Ea&&this.stop()};
r.tf=function(){if(this.enabled){var a=$a()-this.u;a>0&&a<this.j*.8?this.Ea=this.h.setTimeout(this.o,this.j-a):(this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null),Qh(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
r.start=function(){this.enabled=!0;this.Ea||(this.Ea=this.h.setTimeout(this.o,this.j),this.u=$a())};
r.stop=function(){this.enabled=!1;this.Ea&&(this.h.clearTimeout(this.Ea),this.Ea=null)};
r.ba=function(){xi.Aa.ba.call(this);this.stop();delete this.h};function yi(a){H.call(this);this.G=a;this.j=0;this.o=100;this.u=!1;this.i=new Map;this.D=new Set;this.flushInterval=3E4;this.h=new xi(this.flushInterval);this.h.listen("tick",this.ac,!1,this);tc(this,this.h)}
w(yi,H);r=yi.prototype;r.sendIsolatedPayload=function(a){this.u=a;this.o=1};
function zi(a){a.h.enabled||a.h.start();a.j++;a.j>=a.o&&a.ac()}
r.ac=function(){var a=this.i.values();a=[].concat(A(a)).filter(function(b){return b.h.size});
a.length&&this.G.flush(a,this.u);Ai(a);this.j=0;this.h.enabled&&this.h.stop()};
r.Mb=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new ph(a,b))};
r.Hc=function(a){var b=C.apply(1,arguments);this.i.has(a)||this.i.set(a,new qh(a,b))};
function Bi(a,b){return a.D.has(b)?void 0:a.i.get(b)}
r.Jb=function(a){this.Vd(a,1,C.apply(1,arguments))};
r.Vd=function(a,b){var c=C.apply(2,arguments),d=Bi(this,a);d&&d instanceof ph&&(d.j(b,c),zi(this))};
r.record=function(a,b){var c=C.apply(2,arguments),d=Bi(this,a);d&&d instanceof qh&&(d.record(b,c),zi(this))};
function Ai(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Ci(){}
Ci.prototype.serialize=function(a){var b=[];Di(this,a,b);return b.join("")};
function Di(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Di(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),Ei(d,c),c.push(":"),Di(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Ei(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Fi={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Gi=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Ei(a,b){b.push('"',a.replace(Gi,function(c){var d=Fi[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Fi[c]=d);return d}),'"')}
;function Hi(){Ph.call(this);this.headers=new Map;this.h=!1;this.J=null;this.o=this.Y="";this.j=this.U=this.D=this.P=!1;this.G=0;this.u=null;this.ma="";this.ha=!1}
ab(Hi,Ph);var Ii=/^https?$/i,Ji=["POST","PUT"],Ki=[];function Li(a,b,c,d,e,f,g){var h=new Hi;Ki.push(h);b&&h.listen("complete",b);Lh(h,"ready",h.ee);f&&(h.G=Math.max(0,f));g&&(h.ha=g);h.send(a,c,d,e)}
r=Hi.prototype;r.ee=function(){this.dispose();Rb(Ki,this)};
r.send=function(a,b,c,d){if(this.J)throw Error("[goog.net.XhrIo] Object is active with another request="+this.Y+"; newUri="+a);b=b?b.toUpperCase():"GET";this.Y=a;this.o="";this.P=!1;this.h=!0;this.J=new XMLHttpRequest;this.J.onreadystatechange=Sh(Xa(this.Bd,this));try{this.getStatus(),this.U=!0,this.J.open(b,String(a),!0),this.U=!1}catch(g){this.getStatus();Mi(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,d[e]);else if(typeof d.keys===
"function"&&typeof d.get==="function"){e=z(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=D.FormData&&a instanceof D.FormData;!(Lb(Ji,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=z(c);for(d=b.next();!d.done;d=b.next())c=z(d.value),d=c.next().value,c=c.next().value,this.J.setRequestHeader(d,c);this.ma&&(this.J.responseType=this.ma);"withCredentials"in this.J&&this.J.withCredentials!==this.ha&&(this.J.withCredentials=this.ha);try{this.u&&(clearTimeout(this.u),this.u=null),this.G>0&&(this.getStatus(),this.u=setTimeout(this.wf.bind(this),this.G)),
this.getStatus(),this.D=!0,this.J.send(a),this.D=!1}catch(g){this.getStatus(),Mi(this,g)}};
r.wf=function(){typeof Ka!="undefined"&&this.J&&(this.o="Timed out after "+this.G+"ms, aborting",this.getStatus(),Qh(this,"timeout"),this.abort(8))};
function Mi(a,b){a.h=!1;a.J&&(a.j=!0,a.J.abort(),a.j=!1);a.o=b;Ni(a);Oi(a)}
function Ni(a){a.P||(a.P=!0,Qh(a,"complete"),Qh(a,"error"))}
r.abort=function(){this.J&&this.h&&(this.getStatus(),this.h=!1,this.j=!0,this.J.abort(),this.j=!1,Qh(this,"complete"),Qh(this,"abort"),Oi(this))};
r.ba=function(){this.J&&(this.h&&(this.h=!1,this.j=!0,this.J.abort(),this.j=!1),Oi(this,!0));Hi.Aa.ba.call(this)};
r.Bd=function(){this.ea||(this.U||this.D||this.j?Pi(this):this.Ne())};
r.Ne=function(){Pi(this)};
function Pi(a){if(a.h&&typeof Ka!="undefined")if(a.D&&(a.J?a.J.readyState:0)==4)setTimeout(a.Bd.bind(a),0);else if(Qh(a,"readystatechange"),a.isComplete()){a.getStatus();a.h=!1;try{if(Qi(a))Qh(a,"complete"),Qh(a,"success");else{try{var b=(a.J?a.J.readyState:0)>2?a.J.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Ni(a)}}finally{Oi(a)}}}
function Oi(a,b){if(a.J){a.u&&(clearTimeout(a.u),a.u=null);var c=a.J;a.J=null;b||Qh(a,"ready");try{c.onreadystatechange=null}catch(d){}}}
r.isActive=function(){return!!this.J};
r.isComplete=function(){return(this.J?this.J.readyState:0)==4};
function Qi(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=ac(1,String(a.Y)),!a&&D.self&&D.self.location&&(a=D.self.location.protocol.slice(0,-1)),b=!Ii.test(a?a.toLowerCase():"");c=b}return c}
r.getStatus=function(){try{return(this.J?this.J.readyState:0)>2?this.J.status:-1}catch(a){return-1}};
r.getLastError=function(){return typeof this.o==="string"?this.o:String(this.o)};function Ri(){}
Ri.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
Li(a.url,function(d){d=d.target;if(Qi(d)){try{var e=d.J?d.J.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Dc,a.timeoutMillis,a.withCredentials)};
Ri.prototype.oc=function(){return 1};function Si(a,b){this.logger=a;this.event=b;this.startTime=Ti()}
Si.prototype.done=function(){this.logger.Ub(this.event,Ti()-this.startTime)};
function Ui(){Ec.apply(this,arguments)}
w(Ui,Ec);function Vi(a,b){var c=Ti();b=b();a.Ub("n",Ti()-c);return b}
function Wi(){Ui.apply(this,arguments)}
w(Wi,Ui);r=Wi.prototype;r.Oc=function(){};
r.Cb=function(){};
r.Ub=function(){};
r.Ha=function(){};
r.Cc=function(){};
r.Nd=function(){};
function Xi(a){return{rf:new Hc(a),errorCount:new Lc(a),eventCount:new Jc(a),pe:new Kc(a),ai:new Ic(a),ci:new Mc(a),vh:new Nc(a),bi:new Oc(a)}}
function Yi(a,b,c,d){a=ih(gh(dh(new ch(1828,"0"),a),new Ri));b.length&&hh(a,Gf(new Ff,b));d!==void 0&&(a.Ua=d);var e=new kh(1828,"","",!1,"",jh(a));tc(e,a);var f=new yi({flush:function(g){try{e.flush(g)}catch(h){c(h)}}});
f.addOnDisposeCallback(function(){setTimeout(function(){try{f.ac()}finally{e.dispose()}})});
f.o=1E5;f.flushInterval=3E4;f.h.setInterval(3E4);return f}
function Zi(a,b){H.call(this);var c=this;this.callback=a;this.i=b;this.h=-b;this.addOnDisposeCallback(function(){return void clearTimeout(c.timer)})}
w(Zi,H);function $i(a){if(a.timer===void 0){var b=Math.max(0,a.h+a.i-Ti());a.timer=setTimeout(function(){try{a.callback()}finally{a.h=Ti(),a.timer=void 0}},b)}}
function aj(a,b,c){Ui.call(this);this.metrics=a;this.Da=b;this.qb=c}
w(aj,Ui);aj.prototype.Oc=function(a){this.metrics.rf.record(a,this.Da)};
aj.prototype.Cb=function(a){this.metrics.eventCount.kb(a,this.Da)};
aj.prototype.Ub=function(a,b){this.metrics.pe.record(b,a,this.qb,this.Da)};
aj.prototype.Ha=function(a){this.metrics.errorCount.kb(a,this.qb,this.Da)};
function bj(a,b){b=b===void 0?[]:b;var c={Da:a.Da||"_",qb:a.qb||"",nc:a.nc||[],vc:a.vc|0,Ua:a.Ua,wc:a.wc||function(){},
Ib:a.Ib||function(e,f){return Yi(e,f,c.wc,c.Ua)}};
b=c.Ib("47",c.nc.concat(b));aj.call(this,Xi(b),c.Da,c.qb);var d=this;this.options=c;this.service=b;this.i=!a.Ib;this.h=new Zi(function(){return void d.service.ac()},c.vc);
this.addOnDisposeCallback(function(){d.h.dispose();d.i&&d.service.dispose()})}
w(bj,aj);bj.prototype.Nd=function(a){var b=this;this.h.dispose();this.i&&this.service.dispose();this.service=this.options.Ib("47",this.options.nc.concat(a));this.h=new Zi(function(){return void b.service.ac()},this.options.vc);
this.metrics=Xi(this.service)};
bj.prototype.Cc=function(){$i(this.h)};
function Ti(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function cj(a){this.F=L(a)}
w(cj,M);function dj(a){this.F=L(a)}
w(dj,M);function ej(a){this.F=L(a,0,"bfkj")}
w(ej,M);var fj=function(a){return Td(function(b){return b instanceof a&&!((b.F[K]|0)&2)})}(ej);function Ac(a){this.F=L(a)}
w(Ac,M);function gj(a){this.F=L(a)}
w(gj,M);var hj=Ef(gj);function ij(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function jj(a,b,c){if(a.disable)return new Wi;b=b?yc(b):[];if(c)return c.Nd(b),c.share();a={Da:a.Da,qb:a.qb,nc:a.Bh,vc:a.Lh,Ua:a.Ua,wc:a.wc,Ib:a.Ib};c=b;c=c===void 0?[]:c;return new bj(a,c)}
function kj(a){function b(v,x,y,G){Promise.resolve().then(function(){k.done();h.Cc();h.dispose();g.resolve({Zd:v,qf:x,Re:y,xh:G})})}
function c(v,x,y,G){if(!d.logger.ea){var J="k";x?J="h":y&&(J="u");J!=="k"?G!==0&&(d.logger.Cb(J),d.logger.Ub(J,v)):d.i<=0?(d.logger.Cb(J),d.logger.Ub(J,v),d.i=Math.floor(Math.random()*200)):d.i--}}
H.call(this);var d=this;this.i=Math.floor(Math.random()*200);this.h=new gj;if("challenge"in a&&fj(a.challenge)){var e=wf(a.challenge,4);var f=wf(a.challenge,5);wf(a.challenge,7)&&(this.h=hj(wf(a.challenge,7)))}else e=a.program,f=a.globalName;this.addOnDisposeCallback(function(){var v,x,y;return B(function(G){if(G.h==1)return G.yield(d.j,2);v=G.i;x=v.qf;(y=x)==null||y();G.h=0})});
this.logger=jj(a.zd||{},this.h,a.yh);tc(this,this.logger);var g=new ij;this.j=g.promise;this.logger.Cb("t");var h=this.logger.share(),k=new Si(h,"t");if(!D[f])throw this.logger.Ha(25),Error("EGOU");if(!D[f].a)throw this.logger.Ha(26),Error("ELIU");try{var l=D[f].a;f=[];for(var m=[],n=yc(this.h),p=0;p<n.length;p++)f.push(n[p]),m.push(1);var t=Cc(this.h);for(n=0;n<t.length;n++)f.push(t[n]),m.push(2);this.u=z(l(e,b,!0,a.Zh,c,[f,m],wf(this.h,5))).next().value;this.Zc=g.promise.then(function(){})}catch(v){throw this.logger.Ha(28),
v;
}}
w(kj,H);kj.prototype.snapshot=function(a){if(this.ea)throw Error("Already disposed");this.logger.Cb("n");var b=this.logger.share();return this.j.then(function(c){var d=c.Zd;return new Promise(function(e){var f=new Si(b,"n");d(function(g){f.done();b.Oc(g.length);b.Cc();b.dispose();e(g)},[a.wb,
a.cd,a.Bf,a.dd])})})};
kj.prototype.ed=function(a){var b=this;if(this.ea)throw Error("Already disposed");this.logger.Cb("n");var c=Vi(this.logger,function(){return b.u([a.wb,a.cd,a.Bf,a.dd])});
this.logger.Oc(c.length);this.logger.Cc();return c};
kj.prototype.o=function(a){this.j.then(function(b){var c;(c=b.Re)==null||c(a)})};function lj(a){if(!a)return null;a=Le(ff(a,4));return a===null||a===void 0?null:ib(a)}
;function mj(){this.promises={};this.h=null}
function nj(){mj.instance||(mj.instance=new mj);return mj.instance}
function oj(a,b){return pj(a,sf(b,cj,1),sf(b,dj,2),wf(b,3))}
function pj(a,b,c,d){if(!b&&!c)return Promise.resolve();if(!d)return qj(b,c);var e;(e=a.promises)[d]||(e[d]=new Promise(function(f,g){qj(b,c).then(function(){a.h=d;f()},function(h){delete a.promises[d];
g(h)})}));
return a.promises[d]}
function qj(a,b){return b?rj(b):a?sj(a):Promise.resolve()}
function rj(a){return new Promise(function(b,c){var d=sg("SCRIPT"),e=lj(a);Eb(d,e);d.onload=function(){tg(d);b()};
d.onerror=function(){tg(d);c(Error("EWLS"))};
(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(d)})}
function sj(a){return new Promise(function(b){var c=sg("SCRIPT");if(a){var d=Le(ff(a,6));d=d===null||d===void 0?null:Bb(d)}else d=null;c.textContent=Cb(d);Db(c);(document.getElementsByTagName("HEAD")[0]||document.documentElement).appendChild(c);tg(c);b()})}
;var tj=window;function uj(a){var b=vj;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function wj(){var a=[];uj(function(b){a.push(b)});
return a}
var vj={Cf:"allow-forms",Df:"allow-modals",Ef:"allow-orientation-lock",Ff:"allow-pointer-lock",Gf:"allow-popups",Hf:"allow-popups-to-escape-sandbox",If:"allow-presentation",Jf:"allow-same-origin",Kf:"allow-scripts",Lf:"allow-top-navigation",Mf:"allow-top-navigation-by-user-activation"},xj=ei(function(){return wj()});
function yj(){var a=zj(),b={};Mb(xj(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function zj(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Aj(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Bj=(new Date).getTime();function Cj(a){Ph.call(this);var b=this;this.D=this.j=0;this.Ca=a!=null?a:{pa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.h=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.o=function(){return B(function(e){return e.yield(Dj(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.D||Ej(this)}
w(Cj,Ph);function Fj(){var a=Gj;Cj.instance||(Cj.instance=new Cj(a));return Cj.instance}
Cj.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Ca.qa(this.D);delete Cj.instance};
Cj.prototype.ta=function(){return this.h};
function Ej(a){a.D=a.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return a.h?((b=window.navigator)==null?0:b.onLine)?c.A(3):c.yield(Dj(a),3):c.yield(Dj(a),3);Ej(a);c.h=0})},3E4)}
function Dj(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f,g;return B(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.j=a.Ca.pa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.P=[h.j];h.M=0;h.o=0;a.u=void 0;a.j&&(a.Ca.qa(a.j),a.j=0);g!==a.h&&(a.h=g,a.h?Qh(a,"networkstatus-online"):Qh(a,"networkstatus-offline"));c(g);Ba(h);break;case 2:Aa(h),g=!1,h.A(3)}})})}
;function Hj(){this.data=[];this.h=-1}
Hj.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Hj.prototype.get=function(a){return!!this.data[a]};
function Ij(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function Jj(){this.blockSize=-1}
;function Kj(){this.blockSize=-1;this.blockSize=64;this.h=[];this.u=[];this.M=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.o=this.i=0;this.reset()}
ab(Kj,Jj);Kj.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.o=this.i=0};
function Lj(a,b,c){c||(c=0);var d=a.M;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(b=16;b<80;b++)c=d[b-3]^d[b-8]^d[b-14]^d[b-16],d[b]=(c<<1|c>>>31)&4294967295;b=a.h[0];c=a.h[1];e=a.h[2];for(var f=a.h[3],g=a.h[4],h,k,l=0;l<80;l++)l<40?l<20?(h=f^c&(e^f),k=1518500249):(h=c^e^f,k=1859775393):l<60?(h=c&e|f&(c|e),k=2400959708):(h=c^e^f,k=3395469782),
h=(b<<5|b>>>27)+h+g+k+d[l]&4294967295,g=f,f=e,e=(c<<30|c>>>2)&4294967295,c=b,b=h;a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+e&4294967295;a.h[3]=a.h[3]+f&4294967295;a.h[4]=a.h[4]+g&4294967295}
Kj.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.u,f=this.i;d<b;){if(f==0)for(;d<=c;)Lj(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Lj(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Lj(this,e);f=0;break}}this.i=f;this.o+=b}};
Kj.prototype.digest=function(){var a=[],b=this.o*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.u[c]=b&255,b/=256;Lj(this,this.u);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Mj(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Nj(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Oj(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Mj(a).match(/\S+/g)||[],b=Lb(a,b)>=0);return b}
function Pj(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Oj(a,"inverted-hdpi")&&Nj(a,Array.prototype.filter.call(a.classList?a.classList:Mj(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function Qj(){}
Qj.prototype.next=function(){return Rj};
var Rj={done:!0,value:void 0};Qj.prototype.tb=function(){return this};function Sj(a){if(a instanceof Tj||a instanceof Uj||a instanceof Vj)return a;if(typeof a.next=="function")return new Tj(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new Tj(function(){return a[Symbol.iterator]()});
if(typeof a.tb=="function")return new Tj(function(){return a.tb()});
throw Error("Not an iterator or iterable.");}
function Tj(a){this.h=a}
Tj.prototype.tb=function(){return new Uj(this.h())};
Tj.prototype[Symbol.iterator]=function(){return new Vj(this.h())};
Tj.prototype.i=function(){return new Vj(this.h())};
function Uj(a){this.h=a}
w(Uj,Qj);Uj.prototype.next=function(){return this.h.next()};
Uj.prototype[Symbol.iterator]=function(){return new Vj(this.h)};
Uj.prototype.i=function(){return new Vj(this.h)};
function Vj(a){Tj.call(this,function(){return a});
this.j=a}
w(Vj,Tj);Vj.prototype.next=function(){return this.j.next()};function N(a){H.call(this);this.u=1;this.j=[];this.o=0;this.h=[];this.i={};this.D=!!a}
ab(N,H);r=N.prototype;r.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.u;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.u=e+3;d.push(e);return e};
r.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.dc(a)}return!1};
r.dc=function(a){var b=this.h[a];if(b){var c=this.i[b];this.o!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Rb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
r.sb=function(a,b){var c=this.i[a];if(c){var d=Array(arguments.length-1),e=arguments.length,f;for(f=1;f<e;f++)d[f-1]=arguments[f];if(this.D)for(f=0;f<c.length;f++)e=c[f],Wj(this.h[e+1],this.h[e+2],d);else{this.o++;try{for(f=0,e=c.length;f<e&&!this.ea;f++){var g=c[f];this.h[g+1].apply(this.h[g+2],d)}}finally{if(this.o--,this.j.length>0&&this.o==0)for(;c=this.j.pop();)this.dc(c)}}return f!=0}return!1};
function Wj(a,b,c){ai(function(){a.apply(b,c)})}
r.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.dc,this),delete this.i[a])}else this.h.length=0,this.i={}};
r.ba=function(){N.Aa.ba.call(this);this.clear();this.j.length=0};function Xj(a){this.h=a}
Xj.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new Ci).serialize(b))};
Xj.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Xj.prototype.remove=function(a){this.h.remove(a)};function Yj(a){this.h=a}
ab(Yj,Xj);function Zj(a){this.data=a}
function ak(a){return a===void 0||a instanceof Zj?a:new Zj(a)}
Yj.prototype.set=function(a,b){Yj.Aa.set.call(this,a,ak(b))};
Yj.prototype.i=function(a){a=Yj.Aa.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Yj.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function bk(a){this.h=a}
ab(bk,Yj);bk.prototype.set=function(a,b,c){if(b=ak(b)){if(c){if(c<$a()){bk.prototype.remove.call(this,a);return}b.expiration=c}b.creation=$a()}bk.Aa.set.call(this,a,b)};
bk.prototype.i=function(a){var b=bk.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<$a()||c&&c>$a())bk.prototype.remove.call(this,a);else return b}};function ck(){}
;function dk(){}
ab(dk,ck);dk.prototype[Symbol.iterator]=function(){return Sj(this.tb(!0)).i()};
dk.prototype.clear=function(){var a=Array.from(this);a=z(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function ek(a){this.h=a;this.i=null}
ab(ek,dk);r=ek.prototype;r.isAvailable=function(){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;return this.i=b};
r.set=function(a,b){fk(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
r.get=function(a){fk(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
r.remove=function(a){fk(this);this.h.removeItem(a)};
r.tb=function(a){fk(this);var b=0,c=this.h,d=new Qj;d.next=function(){if(b>=c.length)return Rj;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
r.clear=function(){fk(this);this.h.clear()};
r.key=function(a){fk(this);return this.h.key(a)};
function fk(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");var b;((b=a.i)!=null?b:a.isAvailable())||Pc(Error("Storage mechanism: Storage unavailable"))}
;function gk(){var a=null;try{a=D.localStorage||null}catch(b){}ek.call(this,a)}
ab(gk,ek);function hk(a,b){this.i=a;this.h=b+"::"}
ab(hk,dk);hk.prototype.set=function(a,b){this.i.set(this.h+a,b)};
hk.prototype.get=function(a){return this.i.get(this.h+a)};
hk.prototype.remove=function(a){this.i.remove(this.h+a)};
hk.prototype.tb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Qj;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
return d};/*

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
var O={},ik=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";O.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
O.bd=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var jk={ub:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
sd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},kk={ub:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
sd:function(a){return[].concat.apply([],a)}};
O.pf=function(){ik?(O.rb=Uint8Array,O.Ja=Uint16Array,O.Ud=Int32Array,O.assign(O,jk)):(O.rb=Array,O.Ja=Array,O.Ud=Array,O.assign(O,kk))};
O.pf();var lk=!0;try{new Uint8Array(1)}catch(a){lk=!1}
function mk(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new O.rb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var nk={};nk=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var ok={},pk,qk=[],rk=0;rk<256;rk++){pk=rk;for(var sk=0;sk<8;sk++)pk=pk&1?3988292384^pk>>>1:pk>>>1;qk[rk]=pk}ok=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^qk[(a^b[d])&255];return a^-1};var tk={};tk={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function uk(a){for(var b=a.length;--b>=0;)a[b]=0}
var vk=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],wk=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],xk=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],yk=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],zk=Array(576);uk(zk);var Ak=Array(60);uk(Ak);var Bk=Array(512);uk(Bk);var Ck=Array(256);uk(Ck);var Dk=Array(29);uk(Dk);var Ek=Array(30);uk(Ek);function Fk(a,b,c,d,e){this.Kd=a;this.te=b;this.se=c;this.le=d;this.Le=e;this.vd=a&&a.length}
var Gk,Hk,Ik;function Jk(a,b){this.rd=a;this.Eb=0;this.bb=b}
function Kk(a,b){a.aa[a.pending++]=b&255;a.aa[a.pending++]=b>>>8&255}
function Lk(a,b,c){a.ia>16-c?(a.oa|=b<<a.ia&65535,Kk(a,a.oa),a.oa=b>>16-a.ia,a.ia+=c-16):(a.oa|=b<<a.ia&65535,a.ia+=c)}
function Mk(a,b,c){Lk(a,c[b*2],c[b*2+1])}
function Nk(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function Ok(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=Nk(d[e]++,e))}
function Pk(a){var b;for(b=0;b<286;b++)a.ra[b*2]=0;for(b=0;b<30;b++)a.gb[b*2]=0;for(b=0;b<19;b++)a.ja[b*2]=0;a.ra[512]=1;a.Oa=a.Hb=0;a.ya=a.matches=0}
function Qk(a){a.ia>8?Kk(a,a.oa):a.ia>0&&(a.aa[a.pending++]=a.oa);a.oa=0;a.ia=0}
function Rk(a,b,c){Qk(a);Kk(a,c);Kk(a,~c);O.ub(a.aa,a.window,b,c,a.pending);a.pending+=c}
function Sk(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Tk(a,b,c){for(var d=a.da[c],e=c<<1;e<=a.Na;){e<a.Na&&Sk(b,a.da[e+1],a.da[e],a.depth)&&e++;if(Sk(b,d,a.da[e],a.depth))break;a.da[c]=a.da[e];c=e;e<<=1}a.da[c]=d}
function Uk(a,b,c){var d=0;if(a.ya!==0){do{var e=a.aa[a.Pb+d*2]<<8|a.aa[a.Pb+d*2+1];var f=a.aa[a.Nc+d];d++;if(e===0)Mk(a,f,b);else{var g=Ck[f];Mk(a,g+256+1,b);var h=vk[g];h!==0&&(f-=Dk[g],Lk(a,f,h));e--;g=e<256?Bk[e]:Bk[256+(e>>>7)];Mk(a,g,c);h=wk[g];h!==0&&(e-=Ek[g],Lk(a,e,h))}}while(d<a.ya)}Mk(a,256,b)}
function Vk(a,b){var c=b.rd,d=b.bb.Kd,e=b.bb.vd,f=b.bb.le,g,h=-1;a.Na=0;a.zb=573;for(g=0;g<f;g++)c[g*2]!==0?(a.da[++a.Na]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.Na<2;){var k=a.da[++a.Na]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Oa--;e&&(a.Hb-=d[k*2+1])}b.Eb=h;for(g=a.Na>>1;g>=1;g--)Tk(a,c,g);k=f;do g=a.da[1],a.da[1]=a.da[a.Na--],Tk(a,c,1),d=a.da[1],a.da[--a.zb]=g,a.da[--a.zb]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.da[1]=k++,Tk(a,c,1);while(a.Na>=
2);a.da[--a.zb]=a.da[1];g=b.rd;k=b.Eb;d=b.bb.Kd;e=b.bb.vd;f=b.bb.te;var l=b.bb.se,m=b.bb.Le,n,p=0;for(n=0;n<=15;n++)a.Ka[n]=0;g[a.da[a.zb]*2+1]=0;for(b=a.zb+1;b<573;b++){var t=a.da[b];n=g[g[t*2+1]*2+1]+1;n>m&&(n=m,p++);g[t*2+1]=n;if(!(t>k)){a.Ka[n]++;var v=0;t>=l&&(v=f[t-l]);var x=g[t*2];a.Oa+=x*(n+v);e&&(a.Hb+=x*(d[t*2+1]+v))}}if(p!==0){do{for(n=m-1;a.Ka[n]===0;)n--;a.Ka[n]--;a.Ka[n+1]+=2;a.Ka[m]--;p-=2}while(p>0);for(n=m;n!==0;n--)for(t=a.Ka[n];t!==0;)d=a.da[--b],d>k||(g[d*2+1]!==n&&(a.Oa+=(n-g[d*
2+1])*g[d*2],g[d*2+1]=n),t--)}Ok(c,h,a.Ka)}
function Wk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ja[l*2]+=g:l!==0?(l!==e&&a.ja[l*2]++,a.ja[32]++):g<=10?a.ja[34]++:a.ja[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Xk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do Mk(a,l,a.ja);while(--g!==0)}else l!==0?(l!==e&&(Mk(a,l,a.ja),g--),Mk(a,16,a.ja),Lk(a,g-3,2)):g<=10?(Mk(a,17,a.ja),Lk(a,g-3,3)):(Mk(a,18,a.ja),Lk(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Yk(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.ra[c*2]!==0)return 0;if(a.ra[18]!==0||a.ra[20]!==0||a.ra[26]!==0)return 1;for(c=32;c<256;c++)if(a.ra[c*2]!==0)return 1;return 0}
var Zk=!1;function $k(a,b,c){a.aa[a.Pb+a.ya*2]=b>>>8&255;a.aa[a.Pb+a.ya*2+1]=b&255;a.aa[a.Nc+a.ya]=c&255;a.ya++;b===0?a.ra[c*2]++:(a.matches++,b--,a.ra[(Ck[c]+256+1)*2]++,a.gb[(b<256?Bk[b]:Bk[256+(b>>>7)])*2]++);return a.ya===a.Tb-1}
;function al(a,b){a.msg=tk[b];return b}
function bl(a){for(var b=a.length;--b>=0;)a[b]=0}
function cl(a){var b=a.state,c=b.pending;c>a.S&&(c=a.S);c!==0&&(O.ub(a.output,b.aa,b.Wb,c,a.Fb),a.Fb+=c,b.Wb+=c,a.gd+=c,a.S-=c,b.pending-=c,b.pending===0&&(b.Wb=0))}
function dl(a,b){var c=a.va>=0?a.va:-1,d=a.v-a.va,e=0;if(a.level>0){a.K.Ic===2&&(a.K.Ic=Yk(a));Vk(a,a.uc);Vk(a,a.kc);Wk(a,a.ra,a.uc.Eb);Wk(a,a.gb,a.kc.Eb);Vk(a,a.nd);for(e=18;e>=3&&a.ja[yk[e]*2+1]===0;e--);a.Oa+=3*(e+1)+5+5+4;var f=a.Oa+3+7>>>3;var g=a.Hb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)Lk(a,b?1:0,3),Rk(a,c,d);else if(a.strategy===4||g===f)Lk(a,2+(b?1:0),3),Uk(a,zk,Ak);else{Lk(a,4+(b?1:0),3);c=a.uc.Eb+1;d=a.kc.Eb+1;e+=1;Lk(a,c-257,5);Lk(a,d-1,5);Lk(a,e-4,4);for(f=0;f<e;f++)Lk(a,
a.ja[yk[f]*2+1],3);Xk(a,a.ra,c-1);Xk(a,a.gb,d-1);Uk(a,a.ra,a.gb)}Pk(a);b&&Qk(a);a.va=a.v;cl(a.K)}
function P(a,b){a.aa[a.pending++]=b}
function el(a,b){a.aa[a.pending++]=b>>>8&255;a.aa[a.pending++]=b&255}
function fl(a,b){var c=a.yd,d=a.v,e=a.wa,f=a.Ad,g=a.v>a.la-262?a.v-(a.la-262):0,h=a.window,k=a.cb,l=a.Ia,m=a.v+258,n=h[d+e-1],p=h[d+e];a.wa>=a.ud&&(c>>=2);f>a.B&&(f=a.B);do{var t=b;if(h[t+e]===p&&h[t+e-1]===n&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<m;);t=258-(m-d);d=m-258;if(t>e){a.Db=b;e=t;if(t>=f)break;n=h[d+e-1];p=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.B?e:a.B}
function gl(a){var b=a.la,c;do{var d=a.Sd-a.B-a.v;if(a.v>=b+(b-262)){O.ub(a.window,a.window,b,b,0);a.Db-=b;a.v-=b;a.va-=b;var e=c=a.sc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(a.K.na===0)break;e=a.K;c=a.window;f=a.v+a.B;var g=e.na;g>d&&(g=d);g===0?c=0:(e.na-=g,O.ub(c,e.input,e.nb,g,f),e.state.wrap===1?e.I=nk(e.I,c,g,f):e.state.wrap===2&&(e.I=ok(e.I,c,g,f)),e.nb+=g,e.pb+=g,c=g);a.B+=c;if(a.B+a.sa>=3)for(d=a.v-a.sa,a.R=a.window[d],
a.R=(a.R<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.R=(a.R<<a.Ma^a.window[d+3-1])&a.La,a.Ia[d&a.cb]=a.head[a.R],a.head[a.R]=d,d++,a.sa--,a.B+a.sa<3););}while(a.B<262&&a.K.na!==0)}
function hl(a,b){for(var c;;){if(a.B<262){gl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);c!==0&&a.v-c<=a.la-262&&(a.T=fl(a,c));if(a.T>=3)if(c=$k(a,a.v-a.Db,a.T-3),a.B-=a.T,a.T<=a.Pc&&a.B>=3){a.T--;do a.v++,a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v;while(--a.T!==0);a.v++}else a.v+=a.T,a.T=0,a.R=a.window[a.v],a.R=(a.R<<a.Ma^a.window[a.v+1])&a.La;else c=$k(a,0,
a.window[a.v]),a.B--,a.v++;if(c&&(dl(a,!1),a.K.S===0))return 1}a.sa=a.v<2?a.v:2;return b===4?(dl(a,!0),a.K.S===0?3:4):a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function il(a,b){for(var c,d;;){if(a.B<262){gl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,c=a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);a.wa=a.T;a.Dd=a.Db;a.T=2;c!==0&&a.wa<a.Pc&&a.v-c<=a.la-262&&(a.T=fl(a,c),a.T<=5&&(a.strategy===1||a.T===3&&a.v-a.Db>4096)&&(a.T=2));if(a.wa>=3&&a.T<=a.wa){d=a.v+a.B-3;c=$k(a,a.v-1-a.Dd,a.wa-3);a.B-=a.wa-1;a.wa-=2;do++a.v<=d&&(a.R=(a.R<<a.Ma^a.window[a.v+3-1])&a.La,a.Ia[a.v&a.cb]=a.head[a.R],a.head[a.R]=a.v);
while(--a.wa!==0);a.lb=0;a.T=2;a.v++;if(c&&(dl(a,!1),a.K.S===0))return 1}else if(a.lb){if((c=$k(a,0,a.window[a.v-1]))&&dl(a,!1),a.v++,a.B--,a.K.S===0)return 1}else a.lb=1,a.v++,a.B--}a.lb&&($k(a,0,a.window[a.v-1]),a.lb=0);a.sa=a.v<2?a.v:2;return b===4?(dl(a,!0),a.K.S===0?3:4):a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function jl(a,b){for(var c,d,e,f=a.window;;){if(a.B<=258){gl(a);if(a.B<=258&&b===0)return 1;if(a.B===0)break}a.T=0;if(a.B>=3&&a.v>0&&(d=a.v-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.v+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.T=258-(e-d);a.T>a.B&&(a.T=a.B)}a.T>=3?(c=$k(a,1,a.T-3),a.B-=a.T,a.v+=a.T,a.T=0):(c=$k(a,0,a.window[a.v]),a.B--,a.v++);if(c&&(dl(a,!1),a.K.S===0))return 1}a.sa=0;return b===4?(dl(a,!0),a.K.S===0?3:4):
a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function kl(a,b){for(var c;;){if(a.B===0&&(gl(a),a.B===0)){if(b===0)return 1;break}a.T=0;c=$k(a,0,a.window[a.v]);a.B--;a.v++;if(c&&(dl(a,!1),a.K.S===0))return 1}a.sa=0;return b===4?(dl(a,!0),a.K.S===0?3:4):a.ya&&(dl(a,!1),a.K.S===0)?1:2}
function ll(a,b,c,d,e){this.ye=a;this.Ke=b;this.Me=c;this.Je=d;this.ue=e}
var ml;ml=[new ll(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(a.B<=1){gl(a);if(a.B===0&&b===0)return 1;if(a.B===0)break}a.v+=a.B;a.B=0;var d=a.va+c;if(a.v===0||a.v>=d)if(a.B=a.v-d,a.v=d,dl(a,!1),a.K.S===0)return 1;if(a.v-a.va>=a.la-262&&(dl(a,!1),a.K.S===0))return 1}a.sa=0;if(b===4)return dl(a,!0),a.K.S===0?3:4;a.v>a.va&&dl(a,!1);return 1}),
new ll(4,4,8,4,hl),new ll(4,5,16,8,hl),new ll(4,6,32,32,hl),new ll(4,4,16,16,il),new ll(8,16,32,32,il),new ll(8,16,128,128,il),new ll(8,32,128,256,il),new ll(32,128,258,1024,il),new ll(32,258,258,4096,il)];
function nl(){this.K=null;this.status=0;this.aa=null;this.wrap=this.pending=this.Wb=this.za=0;this.H=null;this.Ba=0;this.method=8;this.Bb=-1;this.cb=this.jd=this.la=0;this.window=null;this.Sd=0;this.head=this.Ia=null;this.Ad=this.ud=this.strategy=this.level=this.Pc=this.yd=this.wa=this.B=this.Db=this.v=this.lb=this.Dd=this.T=this.va=this.Ma=this.La=this.Lc=this.sc=this.R=0;this.ra=new O.Ja(1146);this.gb=new O.Ja(122);this.ja=new O.Ja(78);bl(this.ra);bl(this.gb);bl(this.ja);this.nd=this.kc=this.uc=
null;this.Ka=new O.Ja(16);this.da=new O.Ja(573);bl(this.da);this.zb=this.Na=0;this.depth=new O.Ja(573);bl(this.depth);this.ia=this.oa=this.sa=this.matches=this.Hb=this.Oa=this.Pb=this.ya=this.Tb=this.Nc=0}
function ol(a,b){if(!a||!a.state||b>5||b<0)return a?al(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.na!==0||c.status===666&&b!==4)return al(a,a.S===0?-5:-2);c.K=a;var d=c.Bb;c.Bb=b;if(c.status===42)if(c.wrap===2)a.I=0,P(c,31),P(c,139),P(c,8),c.H?(P(c,(c.H.text?1:0)+(c.H.Va?2:0)+(c.H.extra?4:0)+(c.H.name?8:0)+(c.H.comment?16:0)),P(c,c.H.time&255),P(c,c.H.time>>8&255),P(c,c.H.time>>16&255),P(c,c.H.time>>24&255),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,c.H.os&255),c.H.extra&&c.H.extra.length&&
(P(c,c.H.extra.length&255),P(c,c.H.extra.length>>8&255)),c.H.Va&&(a.I=ok(a.I,c.aa,c.pending,0)),c.Ba=0,c.status=69):(P(c,0),P(c,0),P(c,0),P(c,0),P(c,0),P(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),P(c,3),c.status=113);else{var e=8+(c.jd-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.v!==0&&(e|=32);c.status=113;el(c,e+(31-e%31));c.v!==0&&(el(c,a.I>>>16),el(c,a.I&65535));a.I=1}if(c.status===69)if(c.H.extra){for(e=c.pending;c.Ba<(c.H.extra.length&65535)&&(c.pending!==c.za||
(c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e)),cl(a),e=c.pending,c.pending!==c.za));)P(c,c.H.extra[c.Ba]&255),c.Ba++;c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e));c.Ba===c.H.extra.length&&(c.Ba=0,c.status=73)}else c.status=73;if(c.status===73)if(c.H.name){e=c.pending;do{if(c.pending===c.za&&(c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e)),cl(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ba<c.H.name.length?c.H.name.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.H.Va&&c.pending>
e&&(a.I=ok(a.I,c.aa,c.pending-e,e));f===0&&(c.Ba=0,c.status=91)}else c.status=91;if(c.status===91)if(c.H.comment){e=c.pending;do{if(c.pending===c.za&&(c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e)),cl(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ba<c.H.comment.length?c.H.comment.charCodeAt(c.Ba++)&255:0;P(c,f)}while(f!==0);c.H.Va&&c.pending>e&&(a.I=ok(a.I,c.aa,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.H.Va?(c.pending+2>c.za&&cl(a),c.pending+2<=c.za&&(P(c,
a.I&255),P(c,a.I>>8&255),a.I=0,c.status=113)):c.status=113);if(c.pending!==0){if(cl(a),a.S===0)return c.Bb=-1,0}else if(a.na===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return al(a,-5);if(c.status===666&&a.na!==0)return al(a,-5);if(a.na!==0||c.B!==0||b!==0&&c.status!==666){d=c.strategy===2?kl(c,b):c.strategy===3?jl(c,b):ml[c.level].ue(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.S===0&&(c.Bb=-1),0;if(d===2&&(b===1?(Lk(c,2,3),Mk(c,256,zk),c.ia===16?(Kk(c,c.oa),c.oa=0,c.ia=0):c.ia>=
8&&(c.aa[c.pending++]=c.oa&255,c.oa>>=8,c.ia-=8)):b!==5&&(Lk(c,0,3),Rk(c,0,0),b===3&&(bl(c.head),c.B===0&&(c.v=0,c.va=0,c.sa=0))),cl(a),a.S===0))return c.Bb=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(P(c,a.I&255),P(c,a.I>>8&255),P(c,a.I>>16&255),P(c,a.I>>24&255),P(c,a.pb&255),P(c,a.pb>>8&255),P(c,a.pb>>16&255),P(c,a.pb>>24&255)):(el(c,a.I>>>16),el(c,a.I&65535));cl(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var pl={};pl=function(){this.input=null;this.pb=this.na=this.nb=0;this.output=null;this.gd=this.S=this.Fb=0;this.msg="";this.state=null;this.Ic=2;this.I=0};var ql=Object.prototype.toString;
function rl(a){if(!(this instanceof rl))return new rl(a);a=this.options=O.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.K=new pl;this.K.S=0;var b=this.K;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=al(b,-2);else{e===8&&(e=9);var k=new nl;b.state=k;k.K=b;k.wrap=h;k.H=null;k.jd=e;k.la=1<<k.jd;k.cb=k.la-1;k.Lc=f+7;k.sc=1<<k.Lc;k.La=k.sc-1;k.Ma=~~((k.Lc+3-1)/3);k.window=new O.rb(k.la*2);k.head=new O.Ja(k.sc);k.Ia=new O.Ja(k.la);k.Tb=1<<f+6;k.za=k.Tb*4;k.aa=new O.rb(k.za);k.Pb=1*k.Tb;k.Nc=3*k.Tb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.pb=b.gd=0;b.Ic=2;c=b.state;c.pending=0;c.Wb=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.I=c.wrap===2?
0:1;c.Bb=0;if(!Zk){d=Array(16);for(f=g=0;f<28;f++)for(Dk[f]=g,e=0;e<1<<vk[f];e++)Ck[g++]=f;Ck[g-1]=f;for(f=g=0;f<16;f++)for(Ek[f]=g,e=0;e<1<<wk[f];e++)Bk[g++]=f;for(g>>=7;f<30;f++)for(Ek[f]=g<<7,e=0;e<1<<wk[f]-7;e++)Bk[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)zk[e*2+1]=8,e++,d[8]++;for(;e<=255;)zk[e*2+1]=9,e++,d[9]++;for(;e<=279;)zk[e*2+1]=7,e++,d[7]++;for(;e<=287;)zk[e*2+1]=8,e++,d[8]++;Ok(zk,287,d);for(e=0;e<30;e++)Ak[e*2+1]=5,Ak[e*2]=Nk(e,5);Gk=new Fk(zk,vk,257,286,15);Hk=new Fk(Ak,
wk,0,30,15);Ik=new Fk([],xk,0,19,7);Zk=!0}c.uc=new Jk(c.ra,Gk);c.kc=new Jk(c.gb,Hk);c.nd=new Jk(c.ja,Ik);c.oa=0;c.ia=0;Pk(c);c=0}else c=al(b,-2);c===0&&(b=b.state,b.Sd=2*b.la,bl(b.head),b.Pc=ml[b.level].Ke,b.ud=ml[b.level].ye,b.Ad=ml[b.level].Me,b.yd=ml[b.level].Je,b.v=0,b.va=0,b.B=0,b.sa=0,b.T=b.wa=2,b.lb=0,b.R=0);b=c}}else b=-2;if(b!==0)throw Error(tk[b]);a.header&&(b=this.K)&&b.state&&b.state.wrap===2&&(b.state.H=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=mk(a.dictionary):
ql.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.K;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.B)b=-2;else{b===1&&(a.I=nk(a.I,f,g,0));l.wrap=0;g>=l.la&&(b===0&&(bl(l.head),l.v=0,l.va=0,l.sa=0),c=new O.rb(l.la),O.ub(c,f,g-l.la,l.la,0),f=c,g=l.la);c=a.na;d=a.nb;e=a.input;a.na=g;a.nb=0;a.input=f;for(gl(l);l.B>=3;){f=l.v;g=l.B-2;do l.R=(l.R<<l.Ma^l.window[f+3-1])&l.La,l.Ia[f&l.cb]=l.head[l.R],l.head[l.R]=f,f++;while(--g);
l.v=f;l.B=2;gl(l)}l.v+=l.B;l.va=l.v;l.sa=l.B;l.B=0;l.T=l.wa=2;l.lb=0;a.nb=d;a.input=e;a.na=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(tk[b]);this.sh=!0}}
rl.prototype.push=function(a,b){var c=this.K,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=mk(a):ql.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.nb=0;c.na=c.input.length;do{c.S===0&&(c.output=new O.rb(d),c.Fb=0,c.S=d);a=ol(c,e);if(a!==1&&a!==0)return sl(this,a),this.ended=!0,!1;if(c.S===0||c.na===0&&(e===4||e===2))if(this.options.to==="string"){var f=O.bd(c.output,c.Fb);b=f;f=f.length;if(f<65537&&(b.subarray&&lk||!b.subarray))b=
String.fromCharCode.apply(null,O.bd(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=O.bd(c.output,c.Fb),this.chunks.push(b)}while((c.na>0||c.S===0)&&a!==1);if(e===4)return(c=this.K)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=al(c,-2):(c.state=null,a=d===113?al(c,-3):0)):a=-2,sl(this,a),this.ended=!0,a===0;e===2&&(sl(this,0),c.S=0);return!0};
function sl(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):O.sd(a.chunks));a.chunks=[];a.err=b;a.msg=a.K.msg}
function tl(a,b){b=b||{};b.gzip=!0;b=new rl(b);b.push(a,!0);if(b.err)throw b.msg||tk[b.err];return b.result}
;function ul(a){return a?(a=a.privateDoNotAccessOrElseSafeScriptWrappedValue)?Bb(a):null:null}
function vl(a){return a?(a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue)?ib(a):null:null}
;function wl(a){return ib(a===null?"null":a===void 0?"undefined":a)}
;function xl(a){this.name=a}
;var yl=new xl("rawColdConfigGroup");var zl=new xl("rawHotConfigGroup");function Al(a){this.F=L(a)}
w(Al,M);function Bl(a){this.F=L(a)}
w(Bl,M);Bl.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new yd(a,xd):Ad||(Ad=new yd(null,xd));else if(a.constructor!==yd)if(sd&&a!=null&&a instanceof Uint8Array)a instanceof Uint8Array||Array.isArray(a),a=a.length?new yd(new Uint8Array(a),xd):Ad||(Ad=new yd(null,xd));else throw Error();return hf(this,1,a)};var Cl=new xl("continuationCommand");var Dl=new xl("webCommandMetadata");var El=new xl("signalServiceEndpoint");var Fl={Sf:"EMBEDDED_PLAYER_MODE_UNKNOWN",Pf:"EMBEDDED_PLAYER_MODE_DEFAULT",Rf:"EMBEDDED_PLAYER_MODE_PFP",Qf:"EMBEDDED_PLAYER_MODE_PFL"};var Gl=new xl("feedbackEndpoint");var Yd={Vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",Gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",Ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",Ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",Xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",Mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
Zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",Yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",Jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",Pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",eh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",dh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",bh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",Qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
Lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",fh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",Og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",gh:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",Cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",Bg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",Eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
ah:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",Fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",Dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
Ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED",zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_LACT_THRESHOLD_EXCEEDED",qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MATCHED_ON_REMOTE_CONNECTION",sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHABLE_ON_REMOTE_CONNECTION",rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MISATTRIBUTED_ON_REMOTE_CONNECTION",vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_TV_IS_SIGNED_IN_ON_REMOTE_CONNECTION",Sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_COLD_ON_REMOTE_CONNECTION",
Tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_NON_COLD_ON_REMOTE_CONNECTION",yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ON_REMOTE_CONNECTION",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_VALID",ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_INVALID",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_UNDEFINED",Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_DEFINED",xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_LACT_THRESHOLD_EXCEEDED",
Kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROUND_TRIP_HANDLING_ON_REMOTE_CONNECTION",ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_BEFORE_APP_RELOAD",tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHED_ON_REMOTE_CONNECTION_AFTER_APP_RELOAD",jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_INELIGIBLE",Rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TVHTML5_MID_ROLL_THRESHOLD_REACHED",ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_PENDING",
mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_ACTIVATED",kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_M2_ELIGIBLE",Hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_LANDSCAPE",Ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATE_DEVICE_TO_PORTRAIT",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMBEDS_FACEOFF_UI_EVENT",og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EXP_COBALT_HTTP3_CONFIG_RECEIVED",gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ELIGIBLE_TO_SUPPRESS_TRANSPORT_CONTROLS_BUTTONS",
Wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_USER_HAS_THEATER_MODE_COOKIE_ENABLED",fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DOCUMENT_PICTURE_IN_PICTURE_SUPPORTED"};var Hl=new xl("shareEndpoint"),Il=new xl("shareEntityEndpoint"),Jl=new xl("shareEntityServiceEndpoint"),Kl=new xl("webPlayerShareEntityServiceEndpoint");var Ll=new xl("playlistEditEndpoint");var Ml=new xl("modifyChannelNotificationPreferenceEndpoint");var Nl=new xl("unsubscribeEndpoint");var Ol=new xl("subscribeEndpoint");function Pl(){var a=Ql;F("yt.ads.biscotti.getId_")||E("yt.ads.biscotti.getId_",a)}
function Rl(a){E("yt.ads.biscotti.lastId_",a)}
;function Sl(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var Tl=D.window,Ul,Vl,Wl=(Tl==null?void 0:(Ul=Tl.yt)==null?void 0:Ul.config_)||(Tl==null?void 0:(Vl=Tl.ytcfg)==null?void 0:Vl.data_)||{};E("yt.config_",Wl);function Xl(){Sl(Wl,arguments)}
function R(a,b){return a in Wl?Wl[a]:b}
function Yl(a){var b=Wl.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var Zl=[];function $l(a){Zl.forEach(function(b){return b(a)})}
function am(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){bm(b)}}:a}
function bm(a){var b=F("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Xl("ERRORS",b));$l(a)}
function cm(a,b,c,d,e){var f=F("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=R("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Xl("ERRORS",f))}
;var dm=/^[\w.]*$/,em={q:!0,search_query:!0};function fm(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=gm(f[0]||""),h=gm(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Sb(k,h):c[g]=[k,h]}else c[g]=h}catch(p){var l=p,m=f[0],n=String(fm);l.args=[{key:m,value:f[1],query:a,method:hm===n?"unchanged":n}];em.hasOwnProperty(m)||cm(l)}}return c}
var hm=String(fm);function im(a){var b=[];eg(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Mb(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function jm(a){a.charAt(0)==="?"&&(a=a.substring(1));return fm(a,"&")}
function km(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),jm(a.length>1?a[1]:a[0])):{}}
function lm(a,b){return mm(a,b||{},!0)}
function mm(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=jm(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return hc(a,e)+d}
function nm(a){if(!b)var b=window.location.href;var c=ac(1,a),d=bc(a);c&&d?(a=a.match(Zb),b=b.match(Zb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?bc(b)===d&&(Number(ac(4,b))||null)===(Number(ac(4,a))||null):!0;return a}
function gm(a){return a&&a.match(dm)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function om(a){var b=pm;a=a===void 0?F("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Bj;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Oa){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?tj:g;try{var h=g.history.length}catch(Oa){h=0}e.u_his=h;var k;e.u_h=(k=tj.screen)==null?void 0:k.height;var l;e.u_w=(l=tj.screen)==null?void 0:l.width;var m;e.u_ah=(m=tj.screen)==null?void 0:m.availHeight;var n;e.u_aw=
(n=tj.screen)==null?void 0:n.availWidth;var p;e.u_cd=(p=tj.screen)==null?void 0:p.colorDepth}catch(Oa){}h=b.h;try{var t=h.screenX;var v=h.screenY}catch(Oa){}try{var x=h.outerWidth;var y=h.outerHeight}catch(Oa){}try{var G=h.innerWidth;var J=h.innerHeight}catch(Oa){}try{var ba=h.screenLeft;var ca=h.screenTop}catch(Oa){}try{G=h.innerWidth,J=h.innerHeight}catch(Oa){}try{var Na=h.screen.availWidth;var Kb=h.screen.availTop}catch(Oa){}t=[ba,ca,t,v,Na,Kb,x,y,G,J];try{var ja=(b.h.top||window).document,Ya=
ja.compatMode=="CSS1Compat"?ja.documentElement:ja.body;var Pa=(new dg(Ya.clientWidth,Ya.clientHeight)).round()}catch(Oa){Pa=new dg(-12245933,-12245933)}ja=Pa;Pa={};var Qa=Qa===void 0?D:Qa;Ya=new Hj;"SVGElement"in Qa&&"createElementNS"in Qa.document&&Ya.set(0);v=yj();v["allow-top-navigation-by-user-activation"]&&Ya.set(1);v["allow-popups-to-escape-sandbox"]&&Ya.set(2);Qa.crypto&&Qa.crypto.subtle&&Ya.set(3);"TextDecoder"in Qa&&"TextEncoder"in Qa&&Ya.set(4);Qa=Ij(Ya);Pa.bc=Qa;Pa.bih=ja.height;Pa.biw=
ja.width;Pa.brdim=t.join();b=b.i;b=(Pa.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,Pa.wgl=!!tj.WebGLRenderingContext,Pa);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var pm=new function(){var a=window.document;this.h=window;this.i=a};
E("yt.ads_.signals_.getAdSignalsString",function(a){return im(om(a))});$a();navigator.userAgent.indexOf(" (CrKey ");var qm="XMLHttpRequest"in D?function(){return new XMLHttpRequest}:null;
function rm(){if(!qm)return null;var a=qm();return"open"in a?a:null}
function sm(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function tm(a,b){typeof a==="function"&&(a=am(a));return window.setTimeout(a,b)}
;var um="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(A(um),["client_dev_set_cookie"]);function S(a){a=wm(a);return typeof a==="string"&&a==="false"?!1:!!a}
function T(a,b){a=wm(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function wm(a){return R("EXPERIMENT_FLAGS",{})[a]}
function xm(){for(var a=[],b=R("EXPERIMENTS_FORCED_FLAGS",{}),c=z(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=R("EXPERIMENT_FLAGS",{});d=z(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var ym={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},zm="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(A(um)),Am=!1;function Bm(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&am(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=rm();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;S("debug_forward_web_query_parameters")&&(a=Cm(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=Dm(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"===m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(n){cm(n)}}l.send(d);return l}
function Dm(a,b){b=b===void 0?{}:b;var c=nm(a),d=R("INNERTUBE_CLIENT_NAME"),e=S("web_ajax_ignore_global_headers_if_set"),f;for(f in ym){var g=R(ym[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=R("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||(bc(a)?!1:!0))){k=a;var l;if(l=S("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=bc(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=$b(ac(5,k))||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!bc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!bc(a)){try{var m=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(n){}m&&
(b["X-YouTube-Time-Zone"]=m)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&bc(a)||(b["X-YouTube-Ad-Signals"]=im(om()));return b}
function Em(a,b){b.method="POST";b.postParams||(b.postParams={});return Fm(a,b)}
function Fm(a,b){var c=b.format||"JSON";a=Gm(a,b);var d=Hm(a,b),e=!1,f=Im(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=sm(k),m=null,n=400<=k.status&&k.status<500,p=500<=k.status&&k.status<600;if(l||n||p)m=Jm(a,c,k,b.convertToSafeHtml);l&&(l=Km(c,k,m));m=m||{};n=b.context||D;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=tm(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||D,f))},d)}return f}
function Gm(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=lm(a,b);return a}
function Hm(a,b){var c=R("XSRF_FIELD_NAME"),d=R("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||bc(a)&&!b.withCredentials&&bc(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(S("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=jm(e),og(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):fc(e));f=e||f&&!hg(f);!Am&&f&&b.method!=="POST"&&(Am=!0,bm(Error("AJAX request with postData should use POST")));return e}
function Jm(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,cm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Lm(a):null)e={},Mb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Mm(g)})}d&&Nm(e);
return e}
function Nm(a){if(Ra(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b];var e=gb();d=new yb(e?e.createHTML(d):d);a[c]=d}else Nm(a[b])}}
function Km(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function Lm(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function Mm(a){var b="";Mb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Cm(a){var b=window.location.search,c=bc(a);S("debug_handle_relative_url_for_query_forward_killswitch")||!c&&nm(a)&&(c=document.location.hostname);var d=$b(ac(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=jm(b),f={};Mb(zm,function(g){e[g]&&(f[g]=e[g])});
return mm(a,f||{},!1)}
var Im=Bm;var Om=[{Qc:function(a){return"Cannot read property '"+a.key+"'"},
xc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Qc:function(a){return"Cannot call '"+a.key+"'"},
xc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Qc:function(a){return a.key+" is not defined"},
xc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Qm={Ya:[],Ta:[{callback:Pm,weight:500}]};function Pm(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Rm(){this.Ta=[];this.Ya=[]}
var Sm;function Tm(){if(!Sm){var a=Sm=new Rm;a.Ya.length=0;a.Ta.length=0;Qm.Ya&&a.Ya.push.apply(a.Ya,Qm.Ya);Qm.Ta&&a.Ta.push.apply(a.Ta,Qm.Ta)}return Sm}
;var Um=new N;function Vm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Wm(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=Wm(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=Wm(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function Wm(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function Xm(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Ym(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=Vm(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?Ym(f+".ve",g,h,k):0;d+=f;d+=Ym(e,a[e],b,c);if(d>500)break}}else c[b]=Zm(a),d+=c[b].length;else c[b]=Zm(a),d+=c[b].length;return d}
function Ym(a,b,c,d){c+="."+a;a=Zm(b);d[c]=a;return c.length+a.length}
function Zm(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function $m(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function an(){if(!D.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return D.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":D.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":D.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":D.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function bn(){this.Ld=!0}
function cn(){bn.instance||(bn.instance=new bn);return bn.instance}
function dn(a,b){a={};var c=[];"USER_SESSION_ID"in Wl&&c.push({key:"u",value:R("USER_SESSION_ID")});if(c=Xf(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(R("SESSION_INDEX",0)),c=isNaN(c)?0:c),S("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Wl||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in Wl&&(a["X-Goog-PageId"]=R("DELEGATED_SESSION_ID"));return a}
;var en={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function fn(a,b,c,d,e){Uf.set(""+a,b,{Vb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function gn(a){return Uf.get(""+a,void 0)}
function hn(a,b,c){Uf.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function jn(){if(S("embeds_web_enable_cookie_detection_fix")){if(!D.navigator.cookieEnabled)return!1}else if(!Uf.isEnabled())return!1;if(Uf.h.cookie)return!0;S("embeds_web_enable_cookie_detection_fix")?Uf.set("TESTCOOKIESENABLED","1",{Vb:60,bf:"none",secure:!0}):Uf.set("TESTCOOKIESENABLED","1",{Vb:60});if(Uf.get("TESTCOOKIESENABLED")!=="1")return!1;Uf.remove("TESTCOOKIESENABLED");return!0}
;var kn=F("ytglobal.prefsUserPrefsPrefs_")||{};E("ytglobal.prefsUserPrefsPrefs_",kn);function ln(){this.h=R("ALT_PREF_COOKIE_NAME","PREF");this.i=R("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=gn(this.h);a&&this.parse(a)}
var mn;function nn(){mn||(mn=new ln);return mn}
r=ln.prototype;r.get=function(a,b){on(a);pn(a);a=kn[a]!==void 0?kn[a].toString():null;return a!=null?a:b?b:""};
r.set=function(a,b){on(a);pn(a);if(b==null)throw Error("ExpectedNotNull");kn[a]=b.toString()};
function qn(a){return!!((rn("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
r.remove=function(a){on(a);pn(a);delete kn[a]};
r.clear=function(){for(var a in kn)delete kn[a]};
function pn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function on(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function rn(a){a=kn[a]!==void 0?kn[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
r.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(kn[d]=c.toString())}};var sn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},tn={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function un(){var a=D.navigator;return a?a.connection:void 0}
function vn(){var a=un();if(a){var b=sn[a.type||"unknown"]||"CONN_UNKNOWN";a=sn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function wn(){var a=un();if(a!=null&&a.effectiveType)return tn.hasOwnProperty(a.effectiveType)?tn[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function U(a){var b=C.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(A(b));Object.setPrototypeOf(this,this.constructor.prototype)}
w(U,Error);function xn(){try{return yn(),!0}catch(a){return!1}}
function yn(a){if(R("DATASYNC_ID")!==void 0)return R("DATASYNC_ID");throw new U("Datasync ID not set",a===void 0?"unknown":a);}
;function zn(){}
function An(a,b){return Gj.Ra(a,0,b)}
zn.prototype.pa=function(a,b){return this.Ra(a,1,b)};
zn.prototype.Lb=function(a){var b=F("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var Bn=T("web_emulated_idle_callback_delay",300),Cn=1E3/60-3,Dn=[8,5,4,3,2,1,0];
function En(a){a=a===void 0?{}:a;H.call(this);this.i=[];this.j={};this.Z=this.h=0;this.Y=this.u=!1;this.P=[];this.U=this.ha=!1;for(var b=z(Dn),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.o=0;this.Gc=a.timeout||1;this.G=Cn;this.D=0;this.xa=this.Oe.bind(this);this.Kb=this.uf.bind(this);this.Pa=this.Yd.bind(this);this.Qa=this.ze.bind(this);this.eb=this.Ve.bind(this);this.Fa=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!S("disable_scheduler_requestIdleCallback");(this.ma=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.xa)}
w(En,H);r=En.prototype;r.Lb=function(a){var b=$a();Fn(this,a);a=$a()-b;this.u||(this.G-=a)};
r.Ra=function(a,b,c){++this.Z;if(b===10)return this.Lb(a),this.Z;var d=this.Z;this.j[d]=a;this.u&&!c?this.P.push({id:d,priority:b}):(this.i[b].push(d),this.Y||this.u||(this.h!==0&&Gn(this)!==this.D&&this.stop(),this.start()));return d};
r.qa=function(a){delete this.j[a]};
function Hn(a){a.P.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
r.isHidden=function(){return!!document.hidden||!1};
function In(a){return!a.isHidden()&&a.ma}
function Gn(a){if(a.i[8].length){if(a.U)return 4;if(In(a))return 3}for(var b=5;b>=a.o;b--)if(a.i[b].length>0)return b>0?In(a)?3:2:1;return 0}
r.Ha=function(a){var b=F("yt.logging.errors.log");b&&b(a)};
function Fn(a,b){try{b()}catch(c){a.Ha(c)}}
function Jn(a){for(var b=z(Dn),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
r.ze=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ha=!0;Kn(this,b);this.ha=!1};
r.uf=function(){Kn(this)};
r.Yd=function(){Ln(this)};
r.Ve=function(a){this.U=!0;var b=Gn(this);b===4&&b!==this.D&&(this.stop(),this.start());Kn(this,void 0,a);this.U=!1};
r.Oe=function(){this.isHidden()||Ln(this);this.h&&(this.stop(),this.start())};
function Ln(a){a.stop();a.u=!0;for(var b=$a(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&Fn(a,e)}Mn(a);a.u=!1;Jn(a)&&a.start();b=$a()-b;a.G-=b}
function Mn(a){for(var b=0,c=a.P.length;b<c;b++){var d=a.P[b];a.i[d.priority].push(d.id)}a.P.length=0}
function Kn(a,b,c){a.U&&a.D===4&&a.h||a.stop();a.u=!0;b=$a()+(b||a.G);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ha(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&Fn(a,f);d=a.ha?0:1;d=a.o>d?a.o:d;if(!($a()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&Fn(a,c)}while(c&&$a()<b)}a.u=!1;Mn(a);a.G=Cn;Jn(a)&&a.start()}
r.start=function(){this.Y=!1;if(this.h===0)switch(this.D=Gn(this),this.D){case 1:var a=this.Qa;this.h=this.Fa?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,Bn);break;case 2:this.h=window.setTimeout(this.Kb,this.Gc);break;case 3:this.h=window.requestAnimationFrame(this.eb);break;case 4:this.h=window.setTimeout(this.Pa,0)}};
r.pause=function(){this.stop();this.Y=!0};
r.stop=function(){if(this.h){switch(this.D){case 1:var a=this.h;this.Fa?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
r.ba=function(){Hn(this);this.stop();this.ma&&document.removeEventListener("visibilitychange",this.xa);H.prototype.ba.call(this)};var Nn=F("yt.scheduler.instance.timerIdMap_")||{},On=T("kevlar_tuner_scheduler_soft_state_timer_ms",800),Pn=0,Qn=0;function Rn(){var a=F("ytglobal.schedulerInstanceInstance_");if(!a||a.ea)a=new En(R("scheduler")||{}),E("ytglobal.schedulerInstanceInstance_",a);return a}
function Sn(){Tn();var a=F("ytglobal.schedulerInstanceInstance_");a&&(rc(a),E("ytglobal.schedulerInstanceInstance_",null))}
function Tn(){Hn(Rn());for(var a in Nn)Nn.hasOwnProperty(a)&&delete Nn[Number(a)]}
function Un(a,b,c){if(!c)return c=c===void 0,-Rn().Ra(a,b,c);var d=window.setTimeout(function(){var e=Rn().Ra(a,b);Nn[d]=e},c);
return d}
function Vn(a){Rn().Lb(a)}
function Wn(a){var b=Rn();if(a<0)b.qa(-a);else{var c=Nn[a];c?(b.qa(c),delete Nn[a]):window.clearTimeout(a)}}
function Xn(){Yn()}
function Yn(){window.clearTimeout(Pn);Rn().start()}
function Zn(){Rn().pause();window.clearTimeout(Pn);Pn=window.setTimeout(Xn,On)}
function $n(){window.clearTimeout(Qn);Qn=window.setTimeout(function(){ao(0)},On)}
function ao(a){$n();var b=Rn();b.o=a;b.start()}
function bo(a){$n();var b=Rn();b.o>a&&(b.o=a,b.start())}
function co(){window.clearTimeout(Qn);var a=Rn();a.o=0;a.start()}
;function eo(){zn.apply(this,arguments)}
w(eo,zn);function fo(){eo.instance||(eo.instance=new eo);return eo.instance}
eo.prototype.Ra=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=F("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):tm(a,c||0)};
eo.prototype.qa=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=F("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
eo.prototype.start=function(){var a=F("yt.scheduler.instance.start");a&&a()};
eo.prototype.pause=function(){var a=F("yt.scheduler.instance.pause");a&&a()};
var Gj=fo();
S("web_scheduler_auto_init")&&!F("yt.scheduler.initialized")&&(E("yt.scheduler.instance.dispose",Sn),E("yt.scheduler.instance.addJob",Un),E("yt.scheduler.instance.addImmediateJob",Vn),E("yt.scheduler.instance.cancelJob",Wn),E("yt.scheduler.instance.cancelAllJobs",Tn),E("yt.scheduler.instance.start",Yn),E("yt.scheduler.instance.pause",Zn),E("yt.scheduler.instance.setPriorityThreshold",ao),E("yt.scheduler.instance.enablePriorityThreshold",bo),E("yt.scheduler.instance.clearPriorityThreshold",co),E("yt.scheduler.initialized",
!0));function go(a){var b=new gk;this.h=(a=b.isAvailable()?a?new hk(b,a):b:null)?new bk(a):null;this.i=document.domain||window.location.hostname}
go.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new Ci).serialize(b))}catch(f){return}else e=escape(b);fn(a,e,c,this.i)};
go.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=gn(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
go.prototype.remove=function(a){this.h&&this.h.remove(a);hn(a,"/",this.i)};var ho=function(){var a;return function(){a||(a=new go("ytidb"));return a}}();
function io(){var a;return(a=ho())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var jo=[],ko,lo=!1;function mo(){var a={};for(ko=new no(a.handleError===void 0?oo:a.handleError,a.logEvent===void 0?po:a.logEvent);jo.length>0;)switch(a=jo.shift(),a.type){case "ERROR":ko.Ha(a.payload);break;case "EVENT":ko.logEvent(a.eventType,a.payload)}}
function qo(a){lo||(ko?ko.Ha(a):(jo.push({type:"ERROR",payload:a}),jo.length>10&&jo.shift()))}
function ro(a,b){lo||(ko?ko.logEvent(a,b):(jo.push({type:"EVENT",eventType:a,payload:b}),jo.length>10&&jo.shift()))}
;function so(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function to(a){return a.substr(0,a.indexOf(":"))||a}
;var uo=jd||kd;function vo(a){var b=Tc();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var wo={},xo=(wo.AUTH_INVALID="No user identifier specified.",wo.EXPLICIT_ABORT="Transaction was explicitly aborted.",wo.IDB_NOT_SUPPORTED="IndexedDB is not supported.",wo.MISSING_INDEX="Index not created.",wo.MISSING_OBJECT_STORES="Object stores not created.",wo.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",wo.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",wo.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
wo.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",wo.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",wo.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",wo.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",wo),yo={},zo=(yo.AUTH_INVALID="ERROR",yo.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",yo.EXPLICIT_ABORT="IGNORED",yo.IDB_NOT_SUPPORTED="ERROR",yo.MISSING_INDEX=
"WARNING",yo.MISSING_OBJECT_STORES="ERROR",yo.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",yo.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",yo.QUOTA_EXCEEDED="WARNING",yo.QUOTA_MAYBE_EXCEEDED="WARNING",yo.UNKNOWN_ABORT="WARNING",yo.INCOMPATIBLE_DB_VERSION="WARNING",yo),Ao={},Bo=(Ao.AUTH_INVALID=!1,Ao.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Ao.EXPLICIT_ABORT=!1,Ao.IDB_NOT_SUPPORTED=!1,Ao.MISSING_INDEX=!1,Ao.MISSING_OBJECT_STORES=!1,Ao.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Ao.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Ao.QUOTA_EXCEEDED=!1,Ao.QUOTA_MAYBE_EXCEEDED=!0,Ao.UNKNOWN_ABORT=!0,Ao.INCOMPATIBLE_DB_VERSION=!1,Ao);function Co(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?xo[a]:c;d=d===void 0?zo[a]:d;e=e===void 0?Bo[a]:e;U.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Co.prototype)}
w(Co,U);function Do(a,b){Co.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},xo.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Do.prototype)}
w(Do,Co);function Eo(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Eo.prototype)}
w(Eo,Error);var Fo=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Go(a,b,c,d){b=to(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Co)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new Co("QUOTA_EXCEEDED",a);if(ld&&e.name==="UnknownError")return new Co("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Eo)return new Co("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&Fo.some(function(f){return e.message.includes(f)}))return new Co("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new Co("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Cd:e.name})];e.level="WARNING";return e}
function Ho(a,b,c){var d=io();return new Co("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function Io(a){if(!a)throw Error();throw a;}
function Jo(a){return a}
function Ko(a){this.h=a}
function Lo(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=z(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=z(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Lo.all=function(a){return new Lo(new Ko(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={Ab:0};f.Ab<a.length;f={Ab:f.Ab},++f.Ab)Lo.resolve(a[f.Ab]).then(function(g){return function(h){d[g.Ab]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
Lo.resolve=function(a){return new Lo(new Ko(function(b,c){a instanceof Lo?a.then(b,c):b(a)}))};
Lo.reject=function(a){return new Lo(new Ko(function(b,c){c(a)}))};
Lo.prototype.then=function(a,b){var c=this,d=a!=null?a:Jo,e=b!=null?b:Io;return new Lo(new Ko(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){Mo(c,c,d,f,g)}),c.i.push(function(){No(c,c,e,f,g)})):c.state.status==="FULFILLED"?Mo(c,c,d,f,g):c.state.status==="REJECTED"&&No(c,c,e,f,g)}))};
Lo.prototype.catch=function(a){return this.then(void 0,a)};
function Mo(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Lo?Oo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function No(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Lo?Oo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Oo(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Lo?Oo(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Po(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Qo(a){return new Promise(function(b,c){Po(a,b,c)})}
function Ro(a){return new Lo(new Ko(function(b,c){Po(a,b,c)}))}
;function So(a,b){return new Lo(new Ko(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var To=window,V=To.ytcsi&&To.ytcsi.now?To.ytcsi.now:To.performance&&To.performance.timing&&To.performance.now&&To.performance.timing.navigationStart?function(){return To.performance.timing.navigationStart+To.performance.now()}:function(){return(new Date).getTime()};function Uo(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(V());this.i=!1}
r=Uo.prototype;r.add=function(a,b,c){return Vo(this,[a],{mode:"readwrite",ka:!0},function(d){return d.objectStore(a).add(b,c)})};
r.clear=function(a){return Vo(this,[a],{mode:"readwrite",ka:!0},function(b){return b.objectStore(a).clear()})};
r.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
r.count=function(a,b){return Vo(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).count(b)})};
function Wo(a,b,c){a=a.h.createObjectStore(b,c);return new Xo(a)}
r.delete=function(a,b){return Vo(this,[a],{mode:"readwrite",ka:!0},function(c){return c.objectStore(a).delete(b)})};
r.get=function(a,b){return Vo(this,[a],{mode:"readonly",ka:!0},function(c){return c.objectStore(a).get(b)})};
function Yo(a,b,c){return Vo(a,[b],{mode:"readwrite",ka:!0},function(d){d=d.objectStore(b);return Ro(d.h.put(c,void 0))})}
r.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Vo(a,b,c,d){var e,f,g,h,k,l,m,n,p,t,v,x;return B(function(y){switch(y.h){case 1:var G={mode:"readonly",ka:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?G.mode=c:Object.assign(G,c);e=G;a.transactionCount++;f=e.ka?3:1;g=0;case 2:if(h){y.A(4);break}g++;k=Math.round(V());ya(y,5);l=a.h.transaction(b,e.mode);G=y.yield;var J=new Zo(l);J=$o(J,d);return G.call(y,J,7);case 7:return m=y.i,n=Math.round(V()),ap(a,k,n,g,void 0,b.join(),e),y.return(m);case 5:p=Aa(y);t=Math.round(V());v=Go(p,
a.h.name,b.join(),a.h.version);if((x=v instanceof Co&&!v.h)||g>=f)ap(a,k,t,g,v,b.join(),e),h=v;y.A(2);break;case 4:return y.return(Promise.reject(h))}})}
function ap(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Co&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&ro("QUOTA_EXCEEDED",{dbName:to(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Co&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=2147483648&&(c=0),ro("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),bp(a,!1,d,f,b,g.tag),qo(e)):bp(a,!0,d,f,b,g.tag)}
function bp(a,b,c,d,e,f){ro("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
r.getName=function(){return this.h.name};
function Xo(a){this.h=a}
r=Xo.prototype;r.add=function(a,b){return Ro(this.h.add(a,b))};
r.autoIncrement=function(){return this.h.autoIncrement};
r.clear=function(){return Ro(this.h.clear()).then(function(){})};
function cp(a,b,c){a.h.createIndex(b,c,{unique:!1})}
r.count=function(a){return Ro(this.h.count(a))};
function dp(a,b){return ep(a,{query:b},function(c){return c.delete().then(function(){return fp(c)})}).then(function(){})}
r.delete=function(a){return a instanceof IDBKeyRange?dp(this,a):Ro(this.h.delete(a))};
r.get=function(a){return Ro(this.h.get(a))};
r.index=function(a){try{return new gp(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new Eo(a,this.h.name);throw b;}};
r.getName=function(){return this.h.name};
r.keyPath=function(){return this.h.keyPath};
function ep(a,b,c){a=a.h.openCursor(b.query,b.direction);return hp(a).then(function(d){return So(d,c)})}
function Zo(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Co;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function $o(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return z(d).next().value})}
Zo.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Co("EXPLICIT_ABORT");};
Zo.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new Xo(a),this.i.set(a,b));return b};
function gp(a){this.h=a}
r=gp.prototype;r.count=function(a){return Ro(this.h.count(a))};
r.delete=function(a){return ip(this,{query:a},function(b){return b.delete().then(function(){return fp(b)})})};
r.get=function(a){return Ro(this.h.get(a))};
r.keyPath=function(){return this.h.keyPath};
r.unique=function(){return this.h.unique};
function ip(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return hp(a).then(function(d){return So(d,c)})}
function jp(a,b){this.request=a;this.cursor=b}
function hp(a){return Ro(a).then(function(b){return b?new jp(a,b):null})}
function fp(a){a.cursor.continue(void 0);return hp(a.request)}
jp.prototype.delete=function(){return Ro(this.cursor.delete()).then(function(){})};
jp.prototype.getValue=function(){return this.cursor.value};
jp.prototype.update=function(a){return Ro(this.cursor.update(a))};function kp(a,b,c){return new Promise(function(d,e){function f(){p||(p=new Uo(g.result,{closed:n}));return p}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.be,k=c.blocking,l=c.sf,m=c.upgrade,n=c.closed,p;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&ro("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:to(a)});var v=f(),x=new Zo(g.transaction);
m&&m(v,function(y){return t.oldVersion<y&&t.newVersion>=y},x);
x.done.catch(function(y){e(y)})}catch(y){e(y)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){ro("IDB_UNEXPECTEDLY_CLOSED",{dbName:to(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function lp(a,b,c){c=c===void 0?{}:c;return kp(a,b,c)}
function mp(a,b){b=b===void 0?{}:b;var c,d,e,f;return B(function(g){if(g.h==1)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.be)&&c.addEventListener("blocked",function(){e()}),g.yield(Qo(c),4);
if(g.h!=2)return za(g,0);f=Aa(g);throw Go(f,a,"",-1);})}
;function np(a,b){this.name=a;this.options=b;this.j=!0;this.u=this.o=0}
np.prototype.i=function(a,b,c){c=c===void 0?{}:c;return lp(a,b,c)};
np.prototype.delete=function(a){a=a===void 0?{}:a;return mp(this.name,a)};
function op(a,b){return new Co("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function pp(a,b){if(!b)throw Ho("openWithToken",to(a.name));return a.open()}
np.prototype.open=function(){function a(){var f,g,h,k,l,m,n,p,t,v;return B(function(x){switch(x.h){case 1:return g=(f=Error().stack)!=null?f:"",ya(x,2),x.yield(c.i(c.name,c.options.version,e),4);case 4:for(var y=h=x.i,G=c.options,J=[],ba=z(Object.keys(G.Gb)),ca=ba.next();!ca.done;ca=ba.next()){ca=ca.value;var Na=G.Gb[ca],Kb=Na.We===void 0?Number.MAX_VALUE:Na.We;!(y.h.version>=Na.Nb)||y.h.version>=Kb||y.h.objectStoreNames.contains(ca)||J.push(ca)}k=J;if(k.length===0){x.A(5);break}l=Object.keys(c.options.Gb);
m=h.objectStoreNames();if(c.u<T("ytidb_reopen_db_retries",0))return c.u++,h.close(),qo(new Co("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());if(!(c.o<T("ytidb_remake_db_retries",1))){x.A(6);break}c.o++;return x.yield(c.delete(),7);case 7:return qo(new Co("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());case 6:throw new Do(m,l);case 5:return x.return(h);case 2:n=Aa(x);
if(n instanceof DOMException?n.name!=="VersionError":"DOMError"in self&&n instanceof DOMError?n.name!=="VersionError":!(n instanceof Object&&"message"in n)||n.message!=="An attempt was made to open a database using a lower version than the existing version."){x.A(8);break}return x.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:p=x.i;t=p.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw p.close(),c.j=!1,op(c,t);return x.return(p);case 8:throw b(),n instanceof
Error&&!S("ytidb_async_stack_killswitch")&&(n.stack=n.stack+"\n"+g.substring(g.indexOf("\n")+1)),Go(n,c.name,"",(v=c.options.version)!=null?v:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw op(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,sf:b,upgrade:this.options.upgrade};return this.h=d=a()};var qp=new np("YtIdbMeta",{Gb:{databases:{Nb:1}},upgrade:function(a,b){b(1)&&Wo(a,"databases",{keyPath:"actualName"})}});
function rp(a,b){var c;return B(function(d){if(d.h==1)return d.yield(pp(qp,b),2);c=d.i;return d.return(Vo(c,["databases"],{ka:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Ro(f.h.put(a,void 0)).then(function(){})})}))})}
function sp(a,b){var c;return B(function(d){if(d.h==1)return a?d.yield(pp(qp,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function tp(a,b){var c,d;return B(function(e){return e.h==1?(c=[],e.yield(pp(qp,b),2)):e.h!=3?(d=e.i,e.yield(Vo(d,["databases"],{ka:!0,mode:"readonly"},function(f){c.length=0;return ep(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return fp(g)})}),3)):e.return(c)})}
function up(a){return tp(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function vp(a,b,c){return tp(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function wp(a){var b,c;return B(function(d){if(d.h==1)return b=yn("YtIdbMeta hasAnyMeta other"),d.yield(tp(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var xp,yp=new function(){}(new function(){});
function zp(){var a,b,c,d;return B(function(e){switch(e.h){case 1:a=io();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=uo)f=/WebKit\/([0-9]+)/.exec(Tc()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(Tc()),f=!(f&&parseInt(f[1],10)>=602));if(f||fd)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(rp(d,yp),4);case 4:return e.yield(sp("yt-idb-test-do-not-use",yp),5);case 5:return e.return(!0);case 2:return Aa(e),e.return(!1)}})}
function Ap(){if(xp!==void 0)return xp;lo=!0;return xp=zp().then(function(a){lo=!1;var b;if((b=ho())!=null&&b.h){var c;b={hasSucceededOnce:((c=io())==null?void 0:c.hasSucceededOnce)||a};var d;(d=ho())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Bp(){return F("ytglobal.idbToken_")||void 0}
function Cp(){var a=Bp();return a?Promise.resolve(a):Ap().then(function(b){(b=b?yp:void 0)&&E("ytglobal.idbToken_",b);return b})}
;var Dp=0;function Ep(a,b){Dp||(Dp=Gj.pa(function(){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:return h.yield(Cp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;ya(h,3);return h.yield(vp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return h.yield(mp(f.actualName),7);case 7:return h.yield(sp(f.actualName,c),6);case 6:za(h,4);break;case 3:g=Aa(h),qo(g),d=!1;case 4:Gj.qa(Dp),Dp=0,d&&Ep(a,b),h.h=0}})}))}
function Fp(){var a;return B(function(b){return b.h==1?b.yield(Cp(),2):(a=b.i)?b.return(wp(a)):b.return(!1)})}
new ij;function Gp(a){if(!xn())throw a=new Co("AUTH_INVALID",{dbName:a}),qo(a),a;var b=yn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Hp(a,b,c,d){var e,f,g,h,k,l;return B(function(m){switch(m.h){case 1:return f=(e=Error().stack)!=null?e:"",m.yield(Cp(),2);case 2:g=m.i;if(!g)throw h=Ho("openDbImpl",a,b),S("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),qo(h),h;so(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Gp(a);ya(m,3);return m.yield(rp(k,g),5);case 5:return m.yield(lp(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=Aa(m),ya(m,7),m.yield(sp(k.actualName,
g),9);case 9:za(m,8);break;case 7:Aa(m);case 8:throw l;}})}
function Ip(a,b,c){c=c===void 0?{}:c;return Hp(a,b,!1,c)}
function Jp(a,b,c){c=c===void 0?{}:c;return Hp(a,b,!0,c)}
function Kp(a,b){b=b===void 0?{}:b;var c,d;return B(function(e){if(e.h==1)return e.yield(Cp(),2);if(e.h!=3){c=e.i;if(!c)return e.return();so(a);d=Gp(a);return e.yield(mp(d.actualName,b),3)}return e.yield(sp(d.actualName,c),0)})}
function Lp(a,b,c){a=a.map(function(d){return B(function(e){return e.h==1?e.yield(mp(d.actualName,b),2):e.yield(sp(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Mp(){var a=a===void 0?{}:a;var b,c;return B(function(d){if(d.h==1)return d.yield(Cp(),2);if(d.h!=3){b=d.i;if(!b)return d.return();so("LogsDatabaseV2");return d.yield(up(b),3)}c=d.i;return d.yield(Lp(c,a,b),0)})}
function Np(a,b){b=b===void 0?{}:b;var c;return B(function(d){if(d.h==1)return d.yield(Cp(),2);if(d.h!=3){c=d.i;if(!c)return d.return();so(a);return d.yield(mp(a,b),3)}return d.yield(sp(a,c),0)})}
;function Op(a,b){np.call(this,a,b);this.options=b;so(a)}
w(Op,np);function Pp(a,b){var c;return function(){c||(c=new Op(a,b));return c}}
Op.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?Jp:Ip)(a,b,Object.assign({},c))};
Op.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?Np:Kp)(this.name,a)};
function Qp(a,b){return Pp(a,b)}
;var Rp={},Sp=Qp("ytGcfConfig",{Gb:(Rp.coldConfigStore={Nb:1},Rp.hotConfigStore={Nb:1},Rp),shared:!1,upgrade:function(a,b){b(1)&&(cp(Wo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),cp(Wo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Tp(a){return pp(Sp(),a)}
function Up(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:V()},g.yield(Tp(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(Yo(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Vp(a,b,c,d){var e,f,g;return B(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:V()},h.yield(Tp(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(Yo(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Wp(a){var b,c;return B(function(d){return d.h==1?d.yield(Tp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Vo(b,["coldConfigStore"],{mode:"readwrite",ka:!0},function(e){return ip(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Xp(a){var b,c;return B(function(d){return d.h==1?d.yield(Tp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Vo(b,["hotConfigStore"],{mode:"readwrite",ka:!0},function(e){return ip(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Yp(){H.call(this);this.i=[];this.h=[];var a=F("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(A(a)),this.h=a):(this.h=[],E("yt.gcf.config.hotUpdateCallbacks",this.h))}
w(Yp,H);Yp.prototype.ba=function(){for(var a=z(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;H.prototype.ba.call(this)};function Zp(){this.h=0;this.i=new Yp}
function $p(){var a;return(a=F("yt.gcf.config.hotConfigGroup"))!=null?a:R("RAW_HOT_CONFIG_GROUP")}
function aq(a,b,c){var d,e,f;return B(function(g){switch(g.h){case 1:if(!S("start_client_gcf")){g.A(0);break}c&&(a.j=c,E("yt.gcf.config.hotConfigGroup",a.j||null));a.o(b);d=Bp();if(!d){g.A(3);break}if(c){g.A(4);break}return g.yield(Xp(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(Up(c,b,d),3);case 3:if(c)for(var h=c,k=z(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function bq(a,b,c){var d,e,f,g;return B(function(h){if(h.h==1){if(!S("start_client_gcf"))return h.A(0);a.coldHashData=b;E("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Bp())?c?h.A(4):h.yield(Wp(d),5):h.A(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.A(0);g=c.configData;return h.yield(Vp(c,b,g,d),0)})}
function cq(){if(!Zp.instance){var a=new Zp;Zp.instance=a}a=Zp.instance;var b=V()-a.h;if(!(a.h!==0&&b<T("send_config_hash_timer"))){b=F("yt.gcf.config.coldConfigData");var c=F("yt.gcf.config.hotHashData"),d=F("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=V());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
Zp.prototype.o=function(a){this.hotHashData=a;E("yt.gcf.config.hotHashData",this.hotHashData||null)};function dq(){return"INNERTUBE_API_KEY"in Wl&&"INNERTUBE_API_VERSION"in Wl}
function eq(){return{innertubeApiKey:R("INNERTUBE_API_KEY"),innertubeApiVersion:R("INNERTUBE_API_VERSION"),Ae:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),wd:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Dh:R("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION"),Ce:R("INNERTUBE_CONTEXT_HL"),Be:R("INNERTUBE_CONTEXT_GL"),De:R("INNERTUBE_HOST_OVERRIDE")||"",Ee:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Eh:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA")}}
function fq(a){var b={client:{hl:a.Ce,gl:a.Be,clientName:a.wd,clientVersion:a.innertubeContextClientVersion,configInfo:a.Ae}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=D.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=xm();c.length>0&&(b.request={internalExperimentFlags:c});c=a.wd;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=an()}(d=F("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(S("web_log_memory_total_kbytes")&&((e=D.navigator)==null?0:e.deviceMemory)){var f;e=(f=D.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=vn())&&b&&(b.client.connectionType=a);S("web_log_effective_connection_type")&&
(a=wn())&&b&&(b.client.effectiveConnectionType=a);S("start_client_gcf")&&(e=cq())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));R("DELEGATED_SESSION_ID")&&!S("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});!S("fill_delegate_context_in_gel_killswitch")&&(a=R("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=R("INNERTUBE_CONTEXT");var g;if(S("enable_persistent_device_token")&&(a==null?0:(g=a.client)==null?0:g.rolloutToken)){var h;b.client.rolloutToken=a==null?void 0:(h=a.client)==null?void 0:h.rolloutToken}g=Object;h=g.assign;a=b.client;f={};e=z(Object.entries(jm(R("DEVICE",""))));for(d=e.next();!d.done;d=e.next())c=z(d.value),d=c.next().value,c=c.next().value,d==="cbrand"?f.deviceMake=c:d==="cmodel"?f.deviceModel=c:d==="cbr"?f.browserName=
c:d==="cbrver"?f.browserVersion=c:d==="cos"?f.osName=c:d==="cosver"?f.osVersion=c:d==="cplatform"&&(f.platform=c);b.client=h.call(g,a,f);return b}
function gq(a,b,c){c=c===void 0?{}:c;var d={};R("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":R("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||R("AUTHORIZATION");b||(a?b="Bearer "+F("gapi.auth.getToken")().th:(a=dn(cn()),S("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var hq=typeof TextEncoder!=="undefined"?new TextEncoder:null,iq=hq?function(a){return hq.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};var jq={next:"wn_s",browse:"br_s",search:"sr_s",reel:"r_wrs",player:"ps_s"},kq={next:"wn_r",browse:"br_r",search:"sr_r",reel:"r_wrr",player:"ps_r"};function lq(a,b){this.version=a;this.args=b}
lq.prototype.serialize=function(){return{version:this.version,args:this.args}};function mq(a,b){this.topic=a;this.h=b}
mq.prototype.toString=function(){return this.topic};var nq=F("ytPubsub2Pubsub2Instance")||new N;N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.dc;N.prototype.publish=N.prototype.sb;N.prototype.clear=N.prototype.clear;E("ytPubsub2Pubsub2Instance",nq);var oq=F("ytPubsub2Pubsub2SubscribedKeys")||{};E("ytPubsub2Pubsub2SubscribedKeys",oq);var pq=F("ytPubsub2Pubsub2TopicToKeys")||{};E("ytPubsub2Pubsub2TopicToKeys",pq);var qq=F("ytPubsub2Pubsub2IsAsync")||{};E("ytPubsub2Pubsub2IsAsync",qq);
E("ytPubsub2Pubsub2SkipSubKey",null);function rq(a,b){var c=sq();c&&c.publish.call(c,a.toString(),a,b)}
function tq(a){var b=uq,c=sq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=F("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(oq[d])try{if(f&&b instanceof mq&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Qd){var l=new h;h.Qd=l.version}var m=h.Qd}catch(y){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{m=Reflect;var n=m.construct;
var p=k.args,t=p.length;if(t>0){var v=Array(t);for(k=0;k<t;k++)v[k]=p[k];var x=v}else x=[];f=n.call(m,h,x)}catch(y){throw y.message="yt.pubsub2.Data.deserialize(): "+y.message,y;}}catch(y){throw y.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+y.message,y;}a.call(window,f)}catch(y){bm(y)}},qq[b.toString()]?F("yt.scheduler.instance")?Gj.pa(g):tm(g,0):g())});
oq[d]=!0;pq[b.toString()]||(pq[b.toString()]=[]);pq[b.toString()].push(d);return d}
function vq(){var a=wq,b=tq(function(c){a.apply(void 0,arguments);xq(b)});
return b}
function xq(a){var b=sq();b&&(typeof a==="number"&&(a=[a]),Mb(a,function(c){b.unsubscribeByKey(c);delete oq[c]}))}
function sq(){return F("ytPubsub2Pubsub2Instance")}
;function yq(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&rq("meta_logging_csi_event",{timerName:a,Wh:b})}
;var zq=void 0,Aq=void 0;function Bq(){Aq||(Aq=vl(R("WORKER_SERIALIZATION_URL")));return Aq||void 0}
function Cq(){var a=Bq();zq||a===void 0||(zq=new Worker(jb(a),void 0));return zq}
;var Dq=T("max_body_size_to_compress",5E5),Eq=T("min_body_size_to_compress",500),Fq=!0,Gq=0,Hq=0,Iq=T("compression_performance_threshold_lr",250),Jq=T("slow_compressions_before_abandon_count",4),Kq=!1,Lq=new Map,Mq=1,Nq=!0;function Oq(){if(typeof Worker==="function"&&Bq()&&!Kq){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=Lq.get(c.key);d&&(Pq(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Lq.delete(c.key))}},b=Cq();
b&&(b.addEventListener("message",a),b.onerror=function(){Lq.clear()},Kq=!0)}}
function Qq(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:V(),ticks:{},infos:{}};if(Fq)try{var g=Rq(b);if(g!=null&&(g>Dq||g<Eq))d(a,c);else{if(S("gzip_gel_with_worker")&&(S("initial_gzip_use_main_thread")&&!Nq||!S("initial_gzip_use_main_thread"))){Kq||Oq();var h=Cq();if(h&&!e){Lq.set(Mq,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:Mq});Mq++;return}}var k=tl(iq(b));Pq(k,f,a,c,d)}}catch(l){cm(l),d(a,c)}else d(a,c)}
function Pq(a,b,c,d,e){Nq=!1;var f=V();b.ticks.gelc=f;Hq++;S("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Iq&&(Gq++,S("abandon_compression_after_N_slow_zips")?Hq===T("compression_disable_point")&&Gq>Jq&&(Fq=!1):Fq=!1);Sq(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Tq(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=V(),e={startTime:d,ticks:{},infos:{}},f=b?F("yt.logging.gzipForFetch",!1):!0;if(Fq&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=Rq(g);if(h!=null&&(h>Dq||h<Eq))return a;c=b?{level:1}:void 0;f=tl(iq(g),c);var k=V();e.ticks.gelc=k;if(b){Hq++;if((S("disable_compression_due_to_performance_degredation")||S("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Iq)if(Gq++,S("abandon_compression_after_N_slow_zips")||S("abandon_compression_after_N_slow_zips_lr")){b=Gq/Hq;var l=Jq/T("compression_disable_point");Hq>0&&Hq%T("compression_disable_point")===0&&b>=l&&(Fq=!1)}else Fq=!1;Sq(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(m){return cm(m),a}}else return a}
function Rq(a){try{return(new Blob(a.split(""))).size}catch(b){return cm(b),null}}
function Sq(a){S("gel_compression_csi_killswitch")||!S("log_gel_compression_latency")&&!S("log_gel_compression_latency_lr")||yq("gel_compression",a,{sampleRate:.1})}
;function Uq(a){a=Object.assign({},a);delete a.Authorization;var b=Xf();if(b){var c=new Kj;c.update(R("INNERTUBE_API_KEY"));c.update(b);a.hash=od(c.digest(),3)}return a}
;var Vq;function Wq(){Vq||(Vq=new go("yt.innertube"));return Vq}
function Xq(a,b,c,d){if(d)return null;d=Wq().get("nextId",!0)||1;var e=Wq().get("requests",!0)||{};e[d]={method:a,request:b,authState:Uq(c),requestTime:Math.round(V())};Wq().set("nextId",d+1,86400,!0);Wq().set("requests",e,86400,!0);return d}
function Yq(a){var b=Wq().get("requests",!0)||{};delete b[a];Wq().set("requests",b,86400,!0)}
function Zq(a){var b=Wq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(V())-d.requestTime<6E4)){var e=d.authState,f=Uq(gq(!1));kg(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(V())),$q(a,d.method,e,{}));delete b[c]}}Wq().set("requests",b,86400,!0)}}
;function ar(a){this.fc=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.yb=function(){};
this.now=Date.now;this.Rb=!1;var b;this.Md=(b=a.Md)!=null?b:100;var c;this.Hd=(c=a.Hd)!=null?c:1;var d;this.Fd=(d=a.Fd)!=null?d:2592E6;var e;this.Ed=(e=a.Ed)!=null?e:12E4;var f;this.Gd=(f=a.Gd)!=null?f:5E3;var g;this.V=(g=a.V)!=null?g:void 0;this.lc=!!a.lc;var h;this.jc=(h=a.jc)!=null?h:.1;var k;this.zc=(k=a.zc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.yb&&(this.yb=a.yb);a.Rb&&(this.Rb=a.Rb);a.fc&&(this.fc=a.fc);this.W=a.W;this.Ca=a.Ca;this.ga=a.ga;this.fa=a.fa;this.sendFn=a.sendFn;
this.Wc=a.Wc;this.Tc=a.Tc;br(this)&&(!this.W||this.W("networkless_logging"))&&cr(this)}
function cr(a){br(a)&&!a.Rb&&(a.h=!0,a.lc&&Math.random()<=a.jc&&a.ga.de(a.V),dr(a),a.fa.ta()&&a.cc(),a.fa.listen(a.Wc,a.cc.bind(a)),a.fa.listen(a.Tc,a.od.bind(a)))}
r=ar.prototype;r.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if(br(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ga.set(d,this.V).then(function(e){d.id=e;c.fa.ta()&&er(c,d)}).catch(function(e){er(c,d);
fr(c,e)})}else this.sendFn(a,b)};
r.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if(br(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.W&&this.W("nwl_skip_retry")&&(e.skipRetry=c);if(this.fa.ta()||this.W&&this.W("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return B(function(k){if(k.h==1)return k.yield(d.ga.set(e,d.V).catch(function(l){fr(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ga.set(e,this.V).catch(function(g){d.sendFn(a,b,e.skipRetry);
fr(d,g)})}else this.sendFn(a,b,this.W&&this.W("nwl_skip_retry")&&c)};
r.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if(br(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.ga.xb(d.id,c.V):e=!0;c.fa.mb&&c.W&&c.W("vss_network_hint")&&c.fa.mb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ga.set(d,this.V).then(function(g){d.id=g;e&&c.ga.xb(d.id,c.V)}).catch(function(g){fr(c,g)})}else this.sendFn(a,b,void 0,!0)};
r.cc=function(){var a=this;if(!br(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ca.pa(function(){var b;return B(function(c){if(c.h==1)return c.yield(a.ga.td("NEW",a.V),2);if(c.h!=3)return b=c.i,b?c.yield(er(a,b),3):(a.od(),c.return());a.i&&(a.i=0,a.cc());c.h=0})},this.Md))};
r.od=function(){this.Ca.qa(this.i);this.i=0};
function er(a,b){var c;return B(function(d){switch(d.h){case 1:if(!br(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.A(2);break}return d.yield(a.ga.Ie(b.id,a.V),3);case 3:(c=d.i)||a.yb(Error("The request cannot be found in the database."));case 2:if(gr(a,b,a.Fd)){d.A(4);break}a.yb(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.A(5);break}return d.yield(a.ga.xb(b.id,a.V),5);case 5:return d.return();case 4:b.skipRetry||(b=hr(a,
b));if(!b){d.A(0);break}if(!b.skipRetry||b.id===void 0){d.A(8);break}return d.yield(a.ga.xb(b.id,a.V),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function hr(a,b){if(!br(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return B(function(m){switch(m.h){case 1:g=ir(f);(h=jr(f))&&a.W&&a.W("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.W&&a.W("nwl_consider_error_code")&&g||a.W&&!a.W("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.zc)){m.A(2);break}if(!a.fa.Ec){m.A(3);break}return m.yield(a.fa.Ec(),3);case 3:if(a.fa.ta()){m.A(2);break}c(e,f);if(!a.W||!a.W("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){m.A(6);
break}return m.yield(a.ga.Xc(b.id,a.V,!1),6);case 6:return m.return();case 2:if(a.W&&a.W("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.zc)return m.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){m.A(8);break}return b.sendCount<a.Hd?m.yield(a.ga.Xc(b.id,a.V,!0,h?!1:void 0),12):m.yield(a.ga.xb(b.id,a.V),8);case 12:a.Ca.pa(function(){a.fa.ta()&&a.cc()},a.Gd);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return B(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.A(2):h.yield(a.ga.xb(b.id,a.V),2);a.fa.mb&&a.W&&a.W("vss_network_hint")&&a.fa.mb(!0);d(e,f);h.h=0})};
return b}
function gr(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function dr(a){if(!br(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ga.td("QUEUED",a.V).then(function(b){b&&!gr(a,b,a.Ed)?a.Ca.pa(function(){return B(function(c){if(c.h==1)return b.id===void 0?c.A(2):c.yield(a.ga.Xc(b.id,a.V),2);dr(a);c.h=0})}):a.fa.ta()&&a.cc()})}
function fr(a,b){a.Td&&!a.fa.ta()?a.Td(b):a.handleError(b)}
function br(a){return!!a.V||a.fc}
function ir(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function jr(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var kr;
function lr(){if(kr)return kr();var a={};kr=Qp("LogsDatabaseV2",{Gb:(a.LogsRequestsStore={Nb:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&Wo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),cp(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return kr()}
;function mr(a){return pp(lr(),a)}
function nr(a,b){var c,d,e,f;return B(function(g){if(g.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(mr(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:R("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(Yo(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=V();or(c);return g.return(f)})}
function pr(a,b){var c,d,e,f,g,h,k,l;return B(function(m){if(m.h==1)return c={startTime:V(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield(mr(b),2);if(m.h!=3)return d=m.i,e=R("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,V()],h=IDBKeyRange.bound(f,g),k="prev",S("use_fifo_for_networkless")&&(k="next"),l=void 0,m.yield(Vo(d,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(n){return ip(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(p){p.getValue()&&(l=p.getValue(),a==="NEW"&&(l.status="QUEUED",p.update(l)))})}),3);
c.ticks.tc=V();or(c);return m.return(l)})}
function qr(a,b){var c;return B(function(d){if(d.h==1)return d.yield(mr(b),2);c=d.i;return d.return(Vo(c,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Ro(f.h.put(g,void 0)).then(function(){return g})})}))})}
function rr(a,b,c,d){c=c===void 0?!0:c;var e;return B(function(f){if(f.h==1)return f.yield(mr(b),2);e=f.i;return f.return(Vo(e,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),Ro(h.h.put(k,void 0)).then(function(){return k})):Lo.resolve(void 0)})}))})}
function sr(a,b){var c;return B(function(d){if(d.h==1)return d.yield(mr(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function tr(a){var b,c;return B(function(d){if(d.h==1)return d.yield(mr(a),2);b=d.i;c=V()-2592E6;return d.yield(Vo(b,["LogsRequestsStore"],{mode:"readwrite",ka:!0},function(e){return ep(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return fp(f)})})}),0)})}
function ur(){B(function(a){return a.yield(Mp(),0)})}
function or(a){S("nwl_csi_killswitch")||yq("networkless_performance",a,{sampleRate:1})}
;var vr={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
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
shortsCreationFallbackEvent:493,vssData:491,castMatch:494,miniAppPerformanceMetrics:495,userFeedbackEvent:496,kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500,watchEpPromoConflict:503,innertubeResponseCacheMetrics:505,miniAppAdEvent:506,dataPlanUpsellEvent:507,producerProjectRenamed:508,producerMediaSelectionEvent:511,embedsAutoplayStatusChanged:512,remoteConnectEvent:513,connectedSessionMisattributionEvent:514,producerProjectElementModified:515};var wr={},xr=Qp("ServiceWorkerLogsDatabase",{Gb:(wr.SWHealthLog={Nb:1},wr),shared:!0,upgrade:function(a,b){b(1)&&cp(Wo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function yr(a){return pp(xr(),a)}
function zr(a){var b,c;B(function(d){if(d.h==1)return d.yield(yr(a),2);b=d.i;c=V()-2592E6;return d.yield(Vo(b,["SWHealthLog"],{mode:"readwrite",ka:!0},function(e){return ep(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return fp(f)})})}),0)})}
function Ar(a){var b;return B(function(c){if(c.h==1)return c.yield(yr(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Br={},Cr=0;function Dr(a){var b=b===void 0?{}:b;var c=new Image,d=""+Cr++;Br[d]=c;c.onload=c.onerror=function(){delete Br[d]};
b.Sh&&(c.referrerPolicy="no-referrer");c.src=a}
;var Er;function Fr(){Er||(Er=new go("yt.offline"));return Er}
function Gr(a){if(S("offline_error_handling")){var b=Fr().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Fr().set("errors",b,2592E3,!0)}}
;function Hr(){this.h=new Map;this.i=!1}
function Ir(){if(!Hr.instance){var a=F("yt.networkRequestMonitor.instance")||new Hr;E("yt.networkRequestMonitor.instance",a);Hr.instance=a}return Hr.instance}
Hr.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Hr.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
Hr.prototype.removeParams=function(a){return a.split("?")[0]};
Hr.prototype.removeParams=Hr.prototype.removeParams;Hr.prototype.isEndpointCFR=Hr.prototype.isEndpointCFR;Hr.prototype.requestComplete=Hr.prototype.requestComplete;Hr.getInstance=Ir;function Jr(){Ph.call(this);var a=this;this.j=!1;this.h=Fj();this.h.listen("networkstatus-online",function(){if(a.j&&S("offline_error_handling")){var b=Fr().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new U(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;bm(d)}Fr().set("errors",{},2592E3,!0)}}})}
w(Jr,Ph);function Kr(){if(!Jr.instance){var a=F("yt.networkStatusManager.instance")||new Jr;E("yt.networkStatusManager.instance",a);Jr.instance=a}return Jr.instance}
r=Jr.prototype;r.ta=function(){return this.h.ta()};
r.mb=function(a){this.h.h=a};
r.xe=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
r.ne=function(){this.j=!0};
r.listen=function(a,b){return this.h.listen(a,b)};
r.Ec=function(a){a=Dj(this.h,a);a.then(function(b){S("use_cfr_monitor")&&Ir().requestComplete("generate_204",b)});
return a};
Jr.prototype.sendNetworkCheckRequest=Jr.prototype.Ec;Jr.prototype.listen=Jr.prototype.listen;Jr.prototype.enableErrorFlushing=Jr.prototype.ne;Jr.prototype.getWindowStatus=Jr.prototype.xe;Jr.prototype.networkStatusHint=Jr.prototype.mb;Jr.prototype.isNetworkAvailable=Jr.prototype.ta;Jr.getInstance=Kr;function Lr(a){a=a===void 0?{}:a;Ph.call(this);var b=this;this.h=this.u=0;this.j=Kr();var c=F("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Mr(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Mr(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Qh(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Qh(b,"publicytnetworkstatus-offline")})))}
w(Lr,Ph);Lr.prototype.ta=function(){var a=F("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Lr.prototype.mb=function(a){var b=F("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Lr.prototype.Ec=function(a){var b=this,c;return B(function(d){c=F("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return S("skip_network_check_if_cfr")&&Ir().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.mb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.ta())})):c?d.return(c(a)):d.return(!0)})};
function Mr(a,b){a.rateLimit?a.h?(Gj.qa(a.u),a.u=Gj.pa(function(){a.o!==b&&(Qh(a,b),a.o=b,a.h=V())},a.rateLimit-(V()-a.h))):(Qh(a,b),a.o=b,a.h=V()):Qh(a,b)}
;var Nr;function Or(){var a=ar.call;Nr||(Nr=new Lr({Jh:!0,Ah:!0}));a.call(ar,this,{ga:{de:tr,xb:sr,td:pr,Ie:qr,Xc:rr,set:nr},fa:Nr,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;cm(new U(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code),void 0,void 0,void 0,!0)}else bm(b)},
yb:cm,sendFn:Pr,now:V,Td:Gr,Ca:fo(),Wc:"publicytnetworkstatus-online",Tc:"publicytnetworkstatus-offline",lc:!0,jc:.1,zc:T("potential_esf_error_limit",10),W:S,Rb:!(xn()&&Qr())});this.j=new ij;S("networkless_immediately_drop_all_requests")&&ur();Np("LogsDatabaseV2")}
w(Or,ar);function Rr(){var a=F("yt.networklessRequestController.instance");a||(a=new Or,E("yt.networklessRequestController.instance",a),S("networkless_logging")&&Cp().then(function(b){a.V=b;cr(a);a.j.resolve();a.lc&&Math.random()<=a.jc&&a.V&&zr(a.V);S("networkless_immediately_drop_sw_health_store")&&Sr(a)}));
return a}
Or.prototype.writeThenSend=function(a,b){b||(b={});b=Tr(a,b);xn()||(this.h=!1);ar.prototype.writeThenSend.call(this,a,b)};
Or.prototype.sendThenWrite=function(a,b,c){b||(b={});b=Tr(a,b);xn()||(this.h=!1);ar.prototype.sendThenWrite.call(this,a,b,c)};
Or.prototype.sendAndWrite=function(a,b){b||(b={});b=Tr(a,b);xn()||(this.h=!1);ar.prototype.sendAndWrite.call(this,a,b)};
Or.prototype.awaitInitialization=function(){return this.j.promise};
function Sr(a){var b;B(function(c){if(!a.V)throw b=Ho("clearSWHealthLogsDb"),b;return c.return(Ar(a.V).catch(function(d){a.handleError(d)}))})}
function Pr(a,b,c,d){d=d===void 0?!1:d;b=S("web_fp_via_jspb")?Object.assign({},b):b;S("use_cfr_monitor")&&Ur(a,b);if(S("use_request_time_ms_header"))b.headers&&nm(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(V())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)Bm(a,void 0,"POST",f,void 0);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)Bm(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new oc({url:a});if(k.u?typeof k.i!=="string"||k.i.length===0?0:{version:3,ke:k.i,ae:nc(k.j,"act=1","ri=1",pc(k))}:k.M&&{version:4,ke:nc(k.j,"dct=1","suid="+k.o,""),ae:nc(k.j,"act=1","ri=1","suid="+k.o)}){var l=$b(ac(5,a)),m;if(!(m=!l||!l.endsWith("/aclk"))){var n=a.search(jc),p=ic(a,0,"ri",n);if(p<0)var t=null;else{var v=a.indexOf("&",p);if(v<0||v>n)v=n;t=decodeURIComponent(a.slice(p+3,v!==-1?v:0).replace(/\+/g," "))}m=t!=="1"}var x=
!m;break b}}catch(G){}x=!1}if(x){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var y=!0;break b}}catch(G){}y=!1}c=y?!0:!1}else c=!1;c||Dr(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),Qq(a,b.postBody,b,Fm,d)):Qq(a,JSON.stringify(b.postParams),b,Em,d):Fm(a,b)}
function Tr(a,b){S("use_event_time_ms_header")&&nm(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(V())));return b}
function Ur(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Ir().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Ir().requestComplete(a,!0);d(e,f)}}
function Qr(){return bc(document.location.toString())!=="www.youtube-nocookie.com"}
;var Vr=!1,Wr=D.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Vr};E("ytNetworklessLoggingInitializationOptions",Wr);function Xr(){var a;B(function(b){if(b.h==1)return b.yield(Cp(),2);a=b.i;if(!a||!xn()&&!S("nwl_init_require_datasync_id_killswitch")||!Qr())return b.A(0);Vr=!0;Wr.isNwlInitialized=Vr;return b.yield(Rr().awaitInitialization(),0)})}
;function Yr(a){var b=this;this.config_=null;a?this.config_=a:dq()&&(this.config_=eq());An(function(){Zq(b)},5E3)}
Yr.prototype.isReady=function(){!this.config_&&dq()&&(this.config_=eq());return!!this.config_};
function $q(a,b,c,d){function e(n){n=n===void 0?!1:n;var p;if(d.retry&&h!="www.youtube-nocookie.com"&&(n||S("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(p=Xq(b,c,l,k)),p)){var t=g.onSuccess,v=g.onFetchSuccess;g.onSuccess=function(G,J){Yq(p);t(G,J)};
c.onFetchSuccess=function(G,J){Yq(p);v(G,J)}}try{if(n&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Rr().writeThenSend(m,g):Rr().sendAndWrite(m,g);
else if(d.compress){var x=!d.networklessOptions.writeThenSend;if(g.postBody){var y=g.postBody;typeof y!=="string"&&(y=JSON.stringify(g.postBody));Qq(m,y,g,Fm,x)}else Qq(m,JSON.stringify(g.postParams),g,Em,x)}else S("web_all_payloads_via_jspb")?Fm(m,g):Em(m,g)}catch(G){if(G.name==="InvalidAccessError")p&&(Yq(p),p=0),cm(Error("An extension is blocking network request."));else throw G;}p&&An(function(){Zq(a)},5E3)}
!R("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&cm(new U("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new U("innertube xhrclient not ready",b,c,d);bm(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(n,p){if(d.onSuccess)d.onSuccess(p)},
onFetchSuccess:function(n){if(d.onSuccess)d.onSuccess(n)},
onError:function(n,p){if(d.onError)d.onError(p)},
onFetchError:function(n){if(d.onError)d.onError(n)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.De)&&(h=f);var k=a.config_.Ee||!1,l=gq(k,h,d);Object.assign(g.headers,l);g.headers.Authorization&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m=lm(""+h+("/youtubei/"+a.config_.innertubeApiVersion+"/"+b),{alt:"json"});(F("ytNetworklessLoggingInitializationOptions")?Wr.isNwlInitialized:Vr)?Ap().then(function(n){e(n)}):e(!1)}
;var Zr=0,$r=hd?"webkit":gd?"moz":ed?"ms":dd?"o":"";E("ytDomDomGetNextId",F("ytDomDomGetNextId")||function(){return++Zr});var as={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function bs(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in as||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function cs(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
bs.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
bs.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
bs.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var gg=D.ytEventsEventsListeners||{};E("ytEventsEventsListeners",gg);var ds=D.ytEventsEventsCounter||{count:0};E("ytEventsEventsCounter",ds);
function es(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return fg(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Ra(e[4])&&Ra(d)&&kg(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function gs(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=es(a,b,c,d);if(e)return e;e=++ds.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new bs(h);if(!ug(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new bs(h);
h.currentTarget=a;return c.call(a,h)};
g=am(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),ls()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);gg[e]=[a,b,c,g,d];return e}
function ms(a){a&&(typeof a=="string"&&(a=[a]),Mb(a,function(b){if(b in gg){var c=gg[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?ls()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete gg[b]}}))}
var ls=ei(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function ns(a){this.G=a;this.h=null;this.o=0;this.D=null;this.u=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.U=gs(window,"mousemove",Xa(this.Y,this));a=Xa(this.P,this);typeof a==="function"&&(a=am(a));this.Z=window.setInterval(a,25)}
ab(ns,H);ns.prototype.Y=function(a){a.h===void 0&&cs(a);var b=a.h;a.i===void 0&&cs(a);this.h=new cg(b,a.i)};
ns.prototype.P=function(){if(this.h){var a=V();if(this.o!=0){var b=this.D,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.i[this.j]=Math.abs((d-this.u)/this.u)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.G();this.u=d}this.o=a;this.D=this.h;this.j=(this.j+1)%4}};
ns.prototype.ba=function(){window.clearInterval(this.Z);ms(this.U)};var ps={};
function qs(a){var b=a===void 0?{}:a;a=b.Te===void 0?!1:b.Te;b=b.oe===void 0?!0:b.oe;if(F("_lact",window)==null){var c=parseInt(R("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;E("_lact",c,window);E("_fact",c,window);c==-1&&rs();gs(document,"keydown",rs);gs(document,"keyup",rs);gs(document,"mousedown",rs);gs(document,"mouseup",rs);a?gs(window,"touchmove",function(){ss("touchmove",200)},{passive:!0}):(gs(window,"resize",function(){ss("resize",200)}),b&&gs(window,"scroll",function(){ss("scroll",200)}));
new ns(function(){ss("mouse",100)});
gs(document,"touchstart",rs,{passive:!0});gs(document,"touchend",rs,{passive:!0})}}
function ss(a,b){ps[a]||(ps[a]=!0,Gj.pa(function(){rs();ps[a]=!1},b))}
function rs(){F("_lact",window)==null&&qs();var a=Date.now();E("_lact",a,window);F("_fact",window)==-1&&E("_fact",a,window);(a=F("ytglobal.ytUtilActivityCallback_"))&&a()}
function ts(){var a=F("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var us=D.ytPubsubPubsubInstance||new N,vs=D.ytPubsubPubsubSubscribedKeys||{},ws=D.ytPubsubPubsubTopicToKeys||{},xs=D.ytPubsubPubsubIsSynchronous||{};function ys(a,b){var c=zs();if(c&&b){var d=c.subscribe(a,function(){function e(){vs[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{xs[a]?e():tm(e,0)}catch(g){bm(g)}},void 0);
vs[d]=!0;ws[a]||(ws[a]=[]);ws[a].push(d);return d}return 0}
function As(a){var b=zs();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Mb(a,function(c){b.unsubscribeByKey(c);delete vs[c]}))}
function Bs(a,b){var c=zs();c&&c.publish.apply(c,arguments)}
function Cs(a){var b=zs();if(b)if(b.clear(a),a)Ds(a);else for(var c in ws)Ds(c)}
function zs(){return D.ytPubsubPubsubInstance}
function Ds(a){ws[a]&&(a=ws[a],Mb(a,function(b){vs[b]&&delete vs[b]}),a.length=0)}
N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.dc;N.prototype.publish=N.prototype.sb;N.prototype.clear=N.prototype.clear;E("ytPubsubPubsubInstance",us);E("ytPubsubPubsubTopicToKeys",ws);E("ytPubsubPubsubIsSynchronous",xs);E("ytPubsubPubsubSubscribedKeys",vs);var Es=Symbol("injectionDeps");function Fs(a){this.name=a}
Fs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Gs(a){this.key=a}
function Hs(){this.i=new Map;this.j=new Map;this.h=new Map}
function Is(a,b){a.i.set(b.Bc,b);var c=a.j.get(b.Bc);if(c)try{c.Rh(a.resolve(b.Bc))}catch(d){c.Ph(d)}}
Hs.prototype.resolve=function(a){return a instanceof Gs?Js(this,a.key,[],!0):Js(this,a,[])};
function Js(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.Pd!==void 0)var e=d.Pd;else if(d.Af)e=d[Es]?Ks(a,d[Es],c):[],e=d.Af.apply(d,A(e));else if(d.Od){e=d.Od;var f=e[Es]?Ks(a,e[Es],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(A(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Vh||a.h.set(b,e);return e}
function Ks(a,b,c){return b?b.map(function(d){return d instanceof Gs?Js(a,d.key,c,!0):Js(a,d,c)}):[]}
;var Ls;function Ms(){Ls||(Ls=new Hs);return Ls}
;var Ns=window;function Os(){var a,b;return"h5vcc"in Ns&&((a=Ns.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Ns.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Ns&&Ns.performance.mark&&Ns.performance.measure?2:0}
function Ps(a){var b=Os();switch(b){case 1:Ns.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Ns.performance.mark(a+"-start");break;case 0:break;default:xb(b,"unknown trace type")}}
function Qs(a){var b=Os();switch(b){case 1:Ns.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Ns.performance.mark(c);Ns.performance.measure(a,b,c);break;case 0:break;default:xb(b,"unknown trace type")}}
;var Rs=S("web_enable_lifecycle_monitoring")&&Os()!==0,Ss=S("web_enable_lifecycle_monitoring");function Ts(a){var b,c;(c=(b=window).onerror)==null||c.call(b,a.message,"",0,0,a)}
;function Us(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?fo():d;this.j=c;this.scheduler=d;this.i=new ij;this.h=a;for(a={jb:0};a.jb<this.h.length;a={yc:void 0,jb:a.jb},a.jb++)a.yc=this.h[a.jb],c=function(e){return function(){e.yc.Mc();b.h[e.jb].Ac=!0;b.h.every(function(f){return f.Ac===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.yc),d=this.scheduler.Ra(c,d),this.h[a.jb]=Object.assign({},a.yc,{Mc:c,
jobId:d})}
function Vs(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=z(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.Ac||(a.scheduler.qa(c.jobId),a.scheduler.Ra(c.Mc,10))}
Us.prototype.cancel=function(){for(var a=z(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.Ac||this.scheduler.qa(b.jobId),b.Ac=!0;this.i.resolve()};
Us.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function Ws(a){this.state=a;this.plugins=[];this.o=void 0;this.D={};Rs&&Ps(this.state)}
r=Ws.prototype;r.install=function(a){this.plugins.push(a);return this};
r.uninstall=function(){var a=this;C.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
r.transition=function(a,b){var c=this;Rs&&Qs(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Vs(this.j),this.j=void 0);Xs(this,a,b);this.state=a;Rs&&Ps(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Ys(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Ys(a,b){var c=b.filter(function(e){return Zs(a,e)===10}),d=b.filter(function(e){return Zs(a,e)!==10});
return a.D.Uh?function(){var e=C.apply(0,arguments);return B(function(f){if(f.h==1)return f.yield(a.Ze.apply(a,[c].concat(A(e))),2);a.Jd.apply(a,[d].concat(A(e)));f.h=0})}:function(){var e=C.apply(0,arguments);
a.af.apply(a,[c].concat(A(e)));a.Jd.apply(a,[d].concat(A(e)))}}
r.af=function(a){for(var b=C.apply(1,arguments),c=fo(),d=z(a),e=d.next(),f={};!e.done;f={Sb:void 0},e=d.next())f.Sb=e.value,c.Lb(function(g){return function(){$s(g.Sb.name);at(function(){return g.Sb.callback.apply(g.Sb,A(b))});
bt(g.Sb.name)}}(f))};
r.Ze=function(a){var b=C.apply(1,arguments),c,d,e,f,g;return B(function(h){h.h==1&&(c=fo(),d=z(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.A(0);f.Xa=e.value;f.ec=void 0;g=function(k){return function(){$s(k.Xa.name);var l=at(function(){return k.Xa.callback.apply(k.Xa,A(b))});
Zd(l)?k.ec=S("web_lifecycle_error_handling_killswitch")?l.then(function(){bt(k.Xa.name)}):l.then(function(){bt(k.Xa.name)},function(m){Ts(m);
bt(k.Xa.name)}):bt(k.Xa.name)}}(f);
c.Lb(g);return f.ec?h.yield(f.ec,3):h.A(3)}f={Xa:void 0,ec:void 0};e=d.next();return h.A(2)})};
r.Jd=function(a){var b=C.apply(1,arguments),c=this,d=a.map(function(e){return{Mc:function(){$s(e.name);at(function(){return e.callback.apply(e,A(b))});
bt(e.name)},
priority:Zs(c,e)}});
d.length&&(this.j=new Us(d))};
function Zs(a,b){var c,d;return(d=(c=a.o)!=null?c:b.priority)!=null?d:0}
function $s(a){Rs&&a&&Ps(a)}
function bt(a){Rs&&a&&Qs(a)}
function Xs(a,b,c){Ss&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
fa.Object.defineProperties(Ws.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});
function at(a){if(S("web_lifecycle_error_handling_killswitch"))return a();try{return a()}catch(b){Ts(b)}}
;function ct(a){Ws.call(this,a===void 0?"none":a);this.h=null;this.o=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.u},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var dt;w(ct,Ws);ct.prototype.i=function(a,b){var c=this;this.h=An(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
ct.prototype.u=function(a,b){this.h&&(Gj.qa(this.h),this.h=null);a(b==null?void 0:b.event)};
function et(){dt||(dt=new ct);return dt}
;var ft=[];E("yt.logging.transport.getScrapedGelPayloads",function(){return ft});function gt(){this.store={};this.h={}}
gt.prototype.storePayload=function(a,b){a=ht(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);S("more_accurate_gel_parser")&&(b=new CustomEvent("TRANSPORTING_NEW_EVENT"),window.dispatchEvent(b));return a};
gt.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=jt(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,A(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,A(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,A(this.smartExtractMatchingEntries(a))));return c};
gt.prototype.extractMatchingEntries=function(a){a=jt(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,A(this.store[a[c]])),delete this.store[a[c]]);return b};
gt.prototype.getSequenceCount=function(a){a=jt(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function jt(a,b){var c=ht(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&ht(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(kt(b.auth,g[0])){var h=b.isJspb;kt(h===void 0?"undefined":h?"true":"false",g[1])&&kt(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),kt(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function kt(a,b){return a===void 0||a==="undefined"?!0:a===b}
gt.prototype.getSequenceCount=gt.prototype.getSequenceCount;gt.prototype.extractMatchingEntries=gt.prototype.extractMatchingEntries;gt.prototype.smartExtractMatchingEntries=gt.prototype.smartExtractMatchingEntries;gt.prototype.storePayload=gt.prototype.storePayload;function ht(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function lt(a,b){if(a)return a[b.name]}
;var mt=T("initial_gel_batch_timeout",2E3),nt=T("gel_queue_timeout_max_ms",6E4),ot=T("gel_min_batch_size",5),pt=void 0;function qt(){this.o=this.h=this.i=0;this.j=!1}
var rt=new qt,st=new qt,tt=new qt,ut=new qt,vt,wt=!0,xt=D.ytLoggingTransportTokensToCttTargetIds_||{};E("ytLoggingTransportTokensToCttTargetIds_",xt);var zt={};function At(){var a=F("yt.logging.ims");a||(a=new gt,E("yt.logging.ims",a));return a}
function Bt(a,b){if(a.endpoint==="log_event"){Ct();var c=Dt(a),d=Et(a.payload)||"";a:{if(S("enable_web_tiered_gel")){var e=vr[d||""];var f,g,h,k=Ms().resolve(new Gs(Zp))==null?void 0:(f=$p())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!S("web_payload_policy_disabled_killswitch"))return;k=Ft(e.tier);if(k===400){Gt(a,b);return}}zt[c]=
!0;c={cttAuthInfo:c,isJspb:!1,tier:k};At().storePayload(c,a.payload);Ht(b,c,d==="gelDebuggingEvent")}}
function Ht(a,b,c){function d(){It({writeThenSend:!0},void 0,e,b.tier)}
var e=!1;e=e===void 0?!1:e;c=c===void 0?!1:c;a&&(pt=new a);a=T("tvhtml5_logging_max_batch_ads_fork")||T("tvhtml5_logging_max_batch")||T("web_logging_max_batch")||100;var f=V(),g=Jt(e,b.tier),h=g.o;c&&(g.j=!0);c=0;b&&(c=At().getSequenceCount(b));c>=1E3?d():c>=a?vt||(vt=Kt(function(){d();vt=void 0},0)):f-h>=10&&(Lt(e,b.tier),g.o=f)}
function Gt(a,b){if(a.endpoint==="log_event"){S("more_accurate_gel_parser")&&At().storePayload({isJspb:!1},a.payload);Ct();var c=Dt(a),d=new Map;d.set(c,[a.payload]);var e=Et(a.payload)||"";b&&(pt=new b);return new fi(function(f,g){pt&&pt.isReady()?Mt(d,pt,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function Dt(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);xt[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function It(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new fi(function(e,f){var g=Jt(c,d),h=g.j;g.j=!1;Nt(g.i);Nt(g.h);g.h=0;pt&&pt.isReady()?d===void 0&&S("enable_web_tiered_gel")?Ot(e,f,a,b,c,300,h):Ot(e,f,a,b,c,d,h):(Lt(c,d),e())})}
function Ot(a,b,c,d,e,f,g){var h=pt;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=S("enable_web_tiered_gel")?At().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):At().extractMatchingEntries(e),k.set(d,f);else for(d=z(Object.keys(zt)),l=d.next();!l.done;l=d.next())l=l.value,e=S("enable_web_tiered_gel")?At().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):At().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(S("web_fp_via_jspb_and_json")&&c.writeThenSend||!S("web_fp_via_jspb_and_json"))&&delete zt[l];Mt(k,h,a,b,c,!1,g)}
function Lt(a,b){function c(){It({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=Jt(a,b),e=d===ut||d===tt?5E3:nt;S("web_gel_timeout_cap")&&!d.h&&(e=Kt(function(){c()},e),d.h=e);
Nt(d.i);e=R("LOGGING_BATCH_TIMEOUT",T("web_gel_debounce_ms",1E4));S("shorten_initial_gel_batch_timeout")&&wt&&(e=mt);e=Kt(function(){T("gel_min_batch_size")>0?At().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=ot&&c():c()},e);
d.i=e}
function Mt(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(V()),k=a.size,l=(g===void 0?0:g)&&S("vss_through_gel_video_stats")?"video_stats":"log_event";a=z(a);var m=a.next();for(g={};!m.done;g={Sc:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Vc:void 0,Uc:void 0},m=a.next()){var n=z(m.value);m=n.next().value;n=n.next().value;g.batchRequest=mg({context:fq(b.config_||eq())});if(!Ma(n)&&!S("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=n;(n=xt[m])&&
Pt(g.batchRequest,m,n);delete xt[m];g.dangerousLogToVisitorSession=m==="visitorOnlyApprovedKey";Qt(g.batchRequest,h,g.dangerousLogToVisitorSession);S("always_send_and_write")&&(e.writeThenSend=!1);g.Vc=function(p){S("start_client_gcf")&&Gj.pa(function(){return B(function(t){return t.yield(Rt(p),0)})});
k--;k||c()};
g.Sc=0;g.Uc=function(p){return function(){p.Sc++;if(e.bypassNetworkless&&p.Sc===1)try{$q(b,l,p.batchRequest,St({writeThenSend:!0},p.dangerousLogToVisitorSession,p.Vc,p.Uc,f)),wt=!1}catch(t){bm(t),d()}k--;k||c()}}(g);
try{$q(b,l,g.batchRequest,St(e,g.dangerousLogToVisitorSession,g.Vc,g.Uc,f)),wt=!1}catch(p){bm(p),d()}}}
function St(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,uh:!!e,headers:{},postBodyFormat:"",postBody:"",compress:S("compress_gel")||S("compress_gel_lr")};Tt()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(V())));return a}
function Qt(a,b,c){Tt()||(a.requestTimeMs=String(b));S("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=R("EVENT_ID"))&&((c=R("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*65535/2)),c++,c>65535&&(c=1),Xl("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Pt(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Ct(){var a;(a=F("yt.logging.transport.enableScrapingForTest"))||(a=wm("il_payload_scraping"),a=(a!==void 0?String(a):"")!=="enable_il_payload_scraping");a||(ft=[],E("yt.logging.transport.enableScrapingForTest",!0),E("yt.logging.transport.scrapedPayloadsForTesting",ft),E("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),E("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
E("yt.logging.transport.scrapeClientEvent",!0))}
function Tt(){return S("use_request_time_ms_header")||S("lr_use_request_time_ms_header")}
function Kt(a,b){return S("transport_use_scheduler")===!1?tm(a,b):S("logging_avoid_blocking_during_navigation")||S("lr_logging_avoid_blocking_during_navigation")?An(function(){if(et().currentState==="none")a();else{var c={};et().install((c.none={callback:a},c))}},b):An(a,b)}
function Nt(a){S("transport_use_scheduler")?Gj.qa(a):window.clearTimeout(a)}
function Rt(a){var b,c,d,e,f,g,h,k,l,m;return B(function(n){return n.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=lt(d,zl),g=(f=d)==null?void 0:f.hotHashData,h=lt(d,yl),l=(k=d)==null?void 0:k.coldHashData,(m=Ms().resolve(new Gs(Zp)))?g?e?n.yield(aq(m,g,e),2):n.yield(aq(m,g),2):n.A(2):n.return()):l?h?n.yield(bq(m,l,h),0):n.yield(bq(m,l),0):n.A(0)})}
function Jt(a,b){b=b===void 0?200:b;return a?b===300?ut:st:b===300?tt:rt}
function Et(a){a=Object.keys(a);a=z(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,vr[b])return b}
function Ft(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var Ut=D.ytLoggingGelSequenceIdObj_||{};E("ytLoggingGelSequenceIdObj_",Ut);
function Vt(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||V());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=ts();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!S("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,Ut[b]=b in Ut?Ut[b]+1:0,a.sequence={index:Ut[b],groupKey:b},d.endOfSequence&&delete Ut[d.sequenceGroup]);(d.sendIsolatedPayload?Gt:Bt)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function po(a,b,c){c=c===void 0?{}:c;var d=Yr;R("ytLoggingEventsDefaultDisabled",!1)&&Yr===Yr&&(d=null);Vt(a,b,d,c)}
;function Wt(a){return a.slice(0,void 0).map(function(b){return b.name}).join(" > ")}
;var Xt=new Set,Yt=0,Zt=0,$t=0,au=[],bu=[],cu=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function oo(a){du(a)}
function W(a){du(a,"WARNING")}
function eu(a){a instanceof Error?du(a):(a=Ra(a)?JSON.stringify(a):String(a),a=new U(a),a.name="RejectedPromiseError",W(a))}
function du(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),S("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(Yt>=5))){d=[];e=z(bu);for(f=e.next();!f.done;f=e.next()){f=f.value;try{f()&&d.push(f())}catch(y){}}d=[].concat(A(au),A(d));var k=Ub(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var m=l.split("\n");m.shift();l=m.join("\n")}m=k.lineNumber||"Not available";k=k.fileName||"Not available";var n=0;if(a.hasOwnProperty("args")&&
a.args&&a.args.length)for(var p=0;p<a.args.length&&!(n=Xm(a.args[p],"params."+p,c,n),n>=500);p++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(p in t){if(t[p]){var v="params."+p,x=Zm(t[p]);c[v]=x;n+=v.length+x.length;if(n>500)break}}else c.params=Zm(t)}if(d.length)for(p=0;p<d.length&&!(n=Xm(d[p],"params.context."+p,c,n),n>=500);p++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);p={message:e,name:f,lineNumber:m,
fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(p.lineNumber=p.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=Tm();c=z(a.Ya);for(d=c.next();!d.done;d=c.next())if(d=d.value,p.message&&p.message.match(d.Kh)){a=d.weight;break a}a=z(a.Ta);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(p)){a=c.weight;break a}a=1}p.sampleWeight=a;a=z(Om);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.xc[p.name])for(e=z(c.xc[p.name]),d=e.next();!d.done;d=e.next())if(f=
d.value,d=p.message.match(f.regexp)){p.params["params.error.original"]=d[0];e=f.groups;f={};for(m=0;m<e.length;m++)f[e[m]]=d[m+1],p.params["params.error."+e[m]]=d[m+1];p.message=c.Qc(f);break}p.params||(p.params={});a=Tm();p.params["params.errorServiceSignature"]="msg="+a.Ya.length+"&cb="+a.Ta.length;p.params["params.serviceWorker"]="false";D.document&&D.document.querySelectorAll&&(p.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));(new pg(qg,"sample")).constructor!==
pg&&(p.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&window.yterr(p);if(p.sampleWeight!==0&&!Xt.has(p.message)){if(g&&S("web_enable_error_204"))fu(b===void 0?"ERROR":b,p);else{b=b===void 0?"ERROR":b;b==="ERROR"?(Um.sb("handleError",p),S("record_app_crashed_web")&&$t===0&&p.sampleWeight===1&&($t++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},S("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:p.message}}}}),po("appCrashed",
g)),Zt++):b==="WARNING"&&Um.sb("handleWarning",p);if(S("kevlar_gel_error_routing")){g=b;h=h===void 0?{}:h;b:{a=z(cu);for(c=a.next();!c.done;c=a.next())if(vo(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:p.stack};p.fileName&&(c.filename=p.fileName);a=p.lineNumber&&p.lineNumber.split?p.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=
Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:p.message,errorClassName:p.name,sampleWeight:p.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];R("FEXP_EXPERIMENTS")&&(h.experimentIds=R("FEXP_EXPERIMENTS"));d=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Yl("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=z(Object.keys(d)),f=e.next();!f.done;f=e.next())f=
f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=p.params)for(e=z(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=R("SERVER_NAME");e=R("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(po("clientError",h),(g==="ERROR"||S("errors_flush_gel_always_killswitch"))&&It(void 0,void 0,!1))}S("suppress_error_204_logging")||
fu(b,p)}try{Xt.add(p.message)}catch(y){}Yt++}}}
function fu(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:R("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=z(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=z(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];(c=R("LAVA_VERSION"))&&(a.postParams["lava.version"]=c);c=R("SERVER_NAME");b=R("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Fm(R("ECATCHER_REPORT_HOST","")+"/error_204",a)}
function gu(a){var b=C.apply(1,arguments);a.args||(a.args=[]);Array.isArray(a.args)&&a.args.push.apply(a.args,A(b))}
;function hu(){this.register=new Map}
function iu(a){a=z(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Oh("ABORTED")}
hu.prototype.clear=function(){iu(this);this.register.clear()};
var ju=new hu;var ku=Date.now().toString();
function lu(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(ku)for(a=1,b=0;b<ku.length;b++)d[a%16]^=d[(a-1)%16]/4^ku.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var mu,nu=D.ytLoggingDocDocumentNonce_;nu||(nu=lu(),E("ytLoggingDocDocumentNonce_",nu));mu=nu;function ou(a){this.h=a}
r=ou.prototype;r.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
r.getAsJspb=function(){var a=new Bl;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&hf(a,2,ze(this.h.veType)),this.h.veCounter!==void 0&&hf(a,6,ze(this.h.veCounter)),this.h.elementIndex!==void 0&&hf(a,3,ze(this.h.elementIndex)),this.h.isCounterfactual&&hf(a,5,ve(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();tf(a,Bl,7,b)}this.h.youtubeData!==void 0&&tf(a,Al,8,this.h.jspbYoutubeData);return a};
r.toString=function(){return JSON.stringify(this.getAsJson())};
r.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
r.getLoggingDirectives=function(){return this.h.loggingDirectives};function pu(a){return R("client-screen-nonce-store",{})[a===void 0?0:a]}
function qu(a,b){b=b===void 0?0:b;var c=R("client-screen-nonce-store");c||(c={},Xl("client-screen-nonce-store",c));c[b]=a}
function ru(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function su(a){return R(ru(a===void 0?0:a))}
E("yt_logging_screen.getRootVeType",su);function tu(){var a=R("csn-to-ctt-auth-info");a||(a={},Xl("csn-to-ctt-auth-info",a));return a}
function uu(){return Object.values(R("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function vu(a){a=pu(a===void 0?0:a);if(!a&&!R("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
E("yt_logging_screen.getCurrentCsn",vu);function wu(a,b,c){var d=tu();(c=vu(c))&&delete d[c];b&&(d[a]=b)}
function xu(a){return tu()[a]}
E("yt_logging_screen.getCttAuthInfo",xu);E("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==pu(c)||b!==R(ru(c)))if(wu(a,d,c),qu(a,c),Xl(ru(c),b),b=function(){setTimeout(function(){a&&po("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:mu,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function yu(){var a=lg(zu),b;return(new fi(function(c,d){a.onSuccess=function(e){sm(e)?c(new Au(e)):d(new Bu("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Bu("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Bu("Request timed out","net.timeout",e))};
b=Fm("//googleads.g.doubleclick.net/pagead/id",a)})).Fc(function(c){if(c instanceof oi){var d;
(d=b)==null||d.abort()}return ki(c)})}
function Bu(a,b,c){bb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
w(Bu,bb);function Au(a){this.xhr=a}
;function Cu(){this.X=0;this.h=null}
Cu.prototype.then=function(a,b,c){return this.X===1&&a?(a=a.call(c,this.h))&&typeof a.then==="function"?a:Du(a):this.X===2&&b?(a=b.call(c,this.h))&&typeof a.then==="function"?a:Eu(a):this};
Cu.prototype.getValue=function(){return this.h};
Cu.prototype.isRejected=function(){return this.X==2};
Cu.prototype.$goog_Thenable=!0;function Eu(a){var b=new Cu;a=a===void 0?null:a;b.X=2;b.h=a===void 0?null:a;return b}
function Du(a){var b=new Cu;a=a===void 0?null:a;b.X=1;b.h=a===void 0?null:a;return b}
;function Fu(a){var b=R("INNERTUBE_HOST_OVERRIDE");b&&(a=String(b)+String(cc(a)));return a}
function Gu(a){var b={};S("json_condensed_response")&&(b.prettyPrint="false");return a=mm(a,b||{},!1)}
function Hu(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:nm(a)?"same-origin":"cors",credentials:nm(a)?"same-origin":"include"};b={};for(var d=z(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function Iu(){return Vf()||(jd||kd)&&vo("applewebkit")&&!vo("version")&&(!vo("safari")||vo("gsa/"))||id&&vo("version/")?!0:R("EOM_VISITOR_DATA")?!1:!0}
;function Ju(a){var b=a.docid||a.video_id||a.videoId||a.id;if(b)return b;b=a.raw_player_response;b||(a=a.player_response)&&(b=JSON.parse(a));return b&&b.videoDetails&&b.videoDetails.videoId||null}
;function Ku(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Fl)if(Fl[d]==c.embeddedPlayerMode){b=Fl[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function Lu(a){bb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Mu;this.isTimeout=a instanceof Bu&&a.errorCode=="net.timeout";this.isCanceled=a instanceof oi}
w(Lu,bb);Lu.prototype.name="BiscottiError";function Mu(){bb.call(this,"Biscotti ID is missing from server")}
w(Mu,bb);Mu.prototype.name="BiscottiMissingError";var zu={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Nu=null;function Ou(){if(S("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Iu())return Error("User has not consented - not fetching biscotti id.");var a=R("PLAYER_VARS",{});if(jg(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(Ku(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Ql(){var a=Ou();if(a!==void 0)return ki(a);Nu||(Nu=yu().then(Pu).Fc(function(b){return Qu(2,b)}));
return Nu}
function Pu(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Mu;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Mu;a=a.id;Rl(a);Nu=Du(a);Ru(18E5,2);return a}
function Qu(a,b){b=new Lu(b);Rl("");Nu=Eu(b);a>0&&Ru(12E4,a-1);throw b;}
function Ru(a,b){tm(function(){yu().then(Pu,function(c){return Qu(b,c)}).Fc(di)},a)}
function Su(){try{var a=F("yt.ads.biscotti.getId_");return a?a():Ql()}catch(b){return ki(b)}}
;var Gb=ra(["data-"]);function Tu(a){a&&(a.dataset?a.dataset[Uu()]="true":Hb(a))}
function Vu(a){return a?a.dataset?a.dataset[Uu()]:a.getAttribute("data-loaded"):null}
var Wu={};function Uu(){return Wu.loaded||(Wu.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function Xu(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||lg(b);this.assets=a.assets||{};this.attrs=a.attrs||lg(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Xu.prototype.clone=function(){var a=new Xu,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];La(c)=="object"?a[b]=lg(c):a[b]=c}return a};var Yu=["att/get"],Zu=["share/get_share_panel"],$u=["share/get_web_player_share_panel"],av=["feedback"],bv=["notification/modify_channel_preference"],cv=["browse/edit_playlist"],dv=["subscription/subscribe"],ev=["subscription/unsubscribe"];var fv=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};E("yt.msgs_",fv);function gv(a){Sl(fv,arguments)}
;function hv(a,b,c){iv(a,b,c===void 0?null:c)}
function jv(a){a=kv(a);var b=document.getElementById(a);b&&(Cs(a),b.parentNode.removeChild(b))}
function lv(a,b){a&&b&&(a=""+Sa(b),(a=mv[a])&&As(a))}
function iv(a,b,c){c=c===void 0?null:c;var d=kv(a),e=document.getElementById(d),f=e&&Vu(e),g=e&&!f;f?b&&b():(b&&(f=ys(d,b),b=""+Sa(b),mv[b]=f),g||(e=nv(a,d,function(){Vu(e)||(Tu(e),Bs(d),tm(function(){Cs(d)},0))},c)))}
function nv(a,b,c,d){d=d===void 0?null:d;var e=sg("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Eb(e,wl(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function kv(a){var b=document.createElement("a");wb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Yb(a)}
var mv={};function ov(a){var b=pv(a),c=document.getElementById(b),d=c&&Vu(c);d||c&&!d||(c=qv(a,b,function(){if(!Vu(c)){Tu(c);Bs(b);var e=Za(Cs,b);tm(e,0)}}))}
function qv(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=wl(a);Jb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function pv(a){var b=sg("A");wb(b,new pb(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Yb(a)}
;function rv(a){var b=C.apply(1,arguments);if(!sv(a)||b.some(function(d){return!sv(d)}))throw Error("Only objects may be merged.");
b=z(b);for(var c=b.next();!c.done;c=b.next())tv(a,c.value)}
function tv(a,b){for(var c in b)if(sv(b[c])){if(c in a&&!sv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});tv(a[c],b[c])}else if(uv(b[c])){if(c in a&&!uv(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);vv(a[c],b[c])}else a[c]=b[c];return a}
function vv(a,b){b=z(b);for(var c=b.next();!c.done;c=b.next())c=c.value,sv(c)?a.push(tv({},c)):uv(c)?a.push(vv([],c)):a.push(c);return a}
function sv(a){return typeof a==="object"&&!Array.isArray(a)}
function uv(a){return typeof a==="object"&&Array.isArray(a)}
;var wv="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function xv(a,b){var c=c===void 0?!0:c;var d=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=bc(window.location.href);e&&d.push(e);e=bc(a);if(Lb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),wb(d,a),a=d.href)if(a=cc(a),a=dc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:vu()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&yv(a,b,f)}else yv(a,b)}
function yv(a,b,c){a=zv(a);b=b?fc(b):"";c=c||5;Iu()&&fn(a,b,c)}
function zv(a){for(var b=z(wv),c=b.next();!c.done;c=b.next())a=lc(a,c.value);return"ST-"+Yb(a).toString(36)}
;function Av(a){lq.call(this,1,arguments);this.csn=a}
w(Av,lq);var uq=new mq("screen-created",Av),Bv=[],Cv=0,Dv=new Map,Ev=new Map,Fv=new Map;
function Gv(a,b,c,d,e){e=e===void 0?!1:e;for(var f=Hv({cttAuthInfo:xu(b)||void 0},b),g=z(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(hg(k)||!k.trackingParams&&!k.veType)&&W(Error("Child VE logged with no data"));if(S("no_client_ve_attach_unless_shown")){var l=Iv(h,b);if(k.veType&&!Ev.has(l)&&!Fv.has(l)&&!e){if(!S("il_attach_cache_limit")||Dv.size<1E3){Dv.set(l,[a,b,c,h]);return}S("il_attach_cache_limit")&&Dv.size>1E3&&W(new U("IL Attach cache exceeded limit"))}h=Iv(c,b);Dv.has(h)?
Jv(c,b):Fv.set(h,!0)}}d=d.filter(function(m){m.csn!==b?(m.csn=b,m=!0):m=!1;return m});
c={csn:b,parentVe:c.getAsJson(),childVes:Ob(d,function(m){return m.getAsJson()})};
b==="UNDEFINED_CSN"?Kv("visualElementAttached",f,c):a?Vt("visualElementAttached",c,a,f):po("visualElementAttached",c,f)}
function Kv(a,b,c){Bv.push({Se:a,payload:c,Gh:void 0,options:b});Cv||(Cv=vq())}
function wq(a){if(Bv){for(var b=z(Bv),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,po(c.Se,c.payload,c.options));Bv.length=0}Cv=0}
function Iv(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Jv(a,b){a=Iv(a,b);Dv.has(a)&&(b=Dv.get(a)||[],Gv(b[0],b[1],b[2],[b[3]],!0),Dv.delete(a))}
function Hv(a,b){S("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Lv(){try{return!!self.localStorage}catch(a){return!1}}
;function Mv(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Nv(a){if(Lv()){var b=Object.keys(window.localStorage);b=z(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Mv(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Ov(){if(!Lv())return!1;var a=yn(),b=Object.keys(window.localStorage);b=z(b);for(var c=b.next();!c.done;c=b.next())if(c=Mv(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Pv(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(R("INNERTUBE_CLIENT_NAME")==="WEB"||R("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Qv(a){if(R("LOGGED_IN",!0)&&Pv()){var b=R("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=bc(window.location.href);c&&b.push(c);c=bc(a);Lb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=cc(a),(b=dc(b))?(b=zv(b),b=(b=gn(b)||null)?jm(b):{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Pv()?(d||(d=R("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&xv(a,b)}}
;function Rv(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));b&&xv(a,b);if(c)return!1;Qv(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;b=hc(a,e);Qv(b);a=void 0;a=a===void 0?tb:a;a:if(f=b+f,a=a===void 0?tb:a,!(f instanceof pb)){for(b=0;b<a.length;++b)if(c=a[b],c instanceof rb&&c.Ge(f)){f=new pb(f);break a}f=void 0}g=g.location;f=vb(f||qb);f!==void 0&&(g.href=f);return!0}
;function Sv(a){if(jg(R("PLAYER_VARS",{}))!="1"){a&&Pl();try{Su().then(function(){},function(){}),tm(Sv,18E5)}catch(b){bm(b)}}}
;var Tv=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Uv(){var a=a===void 0?window.location.href:a;if(S("kevlar_disable_theme_param"))return null;var b=$b(ac(5,a));if(S("enable_dark_theme_only_on_shorts")&&b!=null&&b.startsWith("/shorts/"))return"USER_INTERFACE_THEME_DARK";try{var c=km(a).theme;return Tv.get(c)||null}catch(d){}return null}
;function Vv(){this.h={};if(this.i=jn()){var a=gn("CONSISTENCY");a&&Wv(this,{encryptedTokenJarContents:a})}}
Vv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Ga.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=z(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Wv(this,a)}};
function Wv(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&fn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Xv=window.location.hostname.split(".").slice(-2).join(".");function Yv(){this.j=-1;var a=R("LOCATION_PLAYABILITY_TOKEN");R("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=Zv(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var $v;function aw(){$v=F("yt.clientLocationService.instance");$v||($v=new Yv,E("yt.clientLocationService.instance",$v));return $v}
r=Yv.prototype;
r.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.o||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.o||
this.locationPlayabilityToken};
r.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,R("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=Zv(this))&&this.h.set("yt-location-playability-token",a,15552E3):fn("YT_CL",JSON.stringify({loctok:a}),15552E3,Xv,!0))};
function Zv(a){return a.h===void 0?new go("yt-client-location"):a.h}
r.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=Zv(this))&&this.h.remove("yt-location-playability-token"):hn("YT_CL");this.o=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
r.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;R("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
r.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
r.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function bw(a,b,c){b=b===void 0?!1:b;c=c===void 0?!1:c;var d=R("INNERTUBE_CONTEXT");if(!d)return du(Error("Error: No InnerTubeContext shell provided in ytconfig.")),{};d=mg(d);S("web_no_tracking_params_in_shell_killswitch")||delete d.clickTracking;d.client||(d.client={});var e=d.client;e.clientName==="MWEB"&&e.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(e.clientFormFactor=R("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");e.screenWidthPoints=window.innerWidth;e.screenHeightPoints=window.innerHeight;
e.screenPixelDensity=Math.round(window.devicePixelRatio||1);e.screenDensityFloat=window.devicePixelRatio||1;e.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var f=f===void 0?!1:f;nn();var g="USER_INTERFACE_THEME_LIGHT";qn(165)?g="USER_INTERFACE_THEME_DARK":qn(174)?g="USER_INTERFACE_THEME_LIGHT":!S("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(g="USER_INTERFACE_THEME_DARK");
f=f?g:Uv()||g;e.userInterfaceTheme=f;if(!b){if(f=vn())e.connectionType=f;S("web_log_effective_connection_type")&&(f=wn())&&(d.client.effectiveConnectionType=f)}var h;if(S("web_log_memory_total_kbytes")&&((h=D.navigator)==null?0:h.deviceMemory)){var k;h=(k=D.navigator)==null?void 0:k.deviceMemory;d.client.memoryTotalKbytes=""+h*1E6}S("web_gcf_hashes_innertube")&&(f=cq())&&(k=f.coldConfigData,h=f.coldHashData,f=f.hotHashData,d.client.configInfo=d.client.configInfo||{},k&&(d.client.configInfo.coldConfigData=
k),h&&(d.client.configInfo.coldHashData=h),f&&(d.client.configInfo.hotHashData=f));k=km(D.location.href);!S("web_populate_internal_geo_killswitch")&&k.internalcountrycode&&(e.internalGeo=k.internalcountrycode);e.clientName==="MWEB"||e.clientName==="WEB"?(e.mainAppWebInfo={graftUrl:D.location.href},S("kevlar_woffle")&&$m.instance&&(k=$m.instance,e.mainAppWebInfo.pwaInstallabilityStatus=!k.h&&k.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),e.mainAppWebInfo.webDisplayMode=
an(),e.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):e.clientName==="TVHTML5"&&(!S("web_lr_app_quality_killswitch")&&(k=R("LIVING_ROOM_APP_QUALITY"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{appQuality:k})),k=R("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(e.tvAppInfo=Object.assign(e.tvAppInfo||{},{certificationScope:k}));if(!S("web_populate_time_zone_itc_killswitch")){a:{if(typeof Intl!=="undefined")try{var l=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break a}catch(Na){}l=
void 0}l&&(e.timeZone=l)}(l=R("EXPERIMENTS_TOKEN",""))?e.experimentsToken=l:delete e.experimentsToken;l=xm();Vv.instance||(Vv.instance=new Vv);e=Vv.instance.h;k=[];h=0;for(var m in e)k[h++]=e[m];d.request=Object.assign({},d.request,{internalExperimentFlags:l,consistencyTokenJars:k});!S("web_prequest_context_killswitch")&&(m=R("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(d.request.externalPrequestContext=m);l=nn();m=qn(58);l=l.get("gsml","");d.user=Object.assign({},d.user);m&&(d.user.enableSafetyMode=
m);l&&(d.user.lockedSafetyMode=!0);S("warm_op_csn_cleanup")?c&&(b=vu())&&(d.clientScreenNonce=b):!b&&(b=vu())&&(d.clientScreenNonce=b);a&&(d.clickTracking={clickTrackingParams:a});if(a=F("yt.mdx.remote.remoteClient_"))d.remoteClient=a;aw().setLocationOnInnerTubeContext(d);try{var n=om(),p=n.bid;delete n.bid;d.adSignalsInfo={params:[],bid:p};for(var t=z(Object.entries(n)),v=t.next();!v.done;v=t.next()){var x=z(v.value),y=x.next().value,G=x.next().value;n=y;p=G;a=void 0;(a=d.adSignalsInfo.params)==
null||a.push({key:n,value:""+p})}var J,ba;if(((J=d.client)==null?void 0:J.clientName)==="TVHTML5"||((ba=d.client)==null?void 0:ba.clientName)==="TVHTML5_UNPLUGGED"){var ca=R("INNERTUBE_CONTEXT");ca.adSignalsInfo&&(d.adSignalsInfo.advertisingId=ca.adSignalsInfo.advertisingId,d.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",d.adSignalsInfo.limitAdTracking=ca.adSignalsInfo.limitAdTracking)}}catch(Na){du(Na)}return d}
;function cw(a){var b={"Content-Type":"application/json"};R("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=R("EOM_VISITOR_DATA"):R("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=R("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=R("LOGGED_IN",!1);R("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=R("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=R("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=R("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=R("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=R("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a),R("ENABLE_LAVA_HEADER_ON_IT_EXPANSION")&&(a=R("SERIALIZED_LAVA_DEVICE_CONTEXT"))&&(b["X-YouTube-Lava-Device-Context"]=a));return b}
;function dw(){this.h={}}
dw.prototype.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
dw.prototype.get=function(a){if(this.contains(a))return this.h[a]};
dw.prototype.set=function(a,b){this.h[a]=b};
dw.prototype.remove=function(a){delete this.h[a]};function ew(){this.mappings=new dw}
ew.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
ew.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=xb(b)}}return a};
new ew;function fw(a){return function(){return new a}}
;var gw={},hw=(gw.WEB_UNPLUGGED="^unplugged/",gw.WEB_UNPLUGGED_ONBOARDING="^unplugged/",gw.WEB_UNPLUGGED_OPS="^unplugged/",gw.WEB_UNPLUGGED_PUBLIC="^unplugged/",gw.WEB_CREATOR="^creator/",gw.WEB_KIDS="^kids/",gw.WEB_EXPERIMENTS="^experiments/",gw.WEB_MUSIC="^music/",gw.WEB_REMIX="^music/",gw.WEB_MUSIC_EMBEDDED_PLAYER="^music/",gw.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",gw);
function iw(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=hw[b];if(c){c=new RegExp(c);for(var d=z(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(hw).forEach(function(g){var h=z(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=z(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function jw(){}
jw.prototype.u=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?en:c;var d={context:bw(a.clickTrackingParams,!1,this.o)};var e=this.i(a);if(e){this.h(d,e,b);var f;b="/youtubei/v1/"+iw(this.j());(e=(f=lt(a.commandMetadata,Dl))==null?void 0:f.apiUrl)&&(b=e);f=Gu(Fu(b));a=Object.assign({},{command:a},void 0);d={input:f,Za:Hu(f),Ga:d,config:a};d.config.Ob?d.config.Ob.identity=c:d.config.Ob={identity:c};return d}du(new U("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(jw.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function kw(){}
w(kw,jw);function lw(){}
w(lw,kw);lw.prototype.u=function(){return{input:"/getDatasyncIdsEndpoint",Za:Hu("/getDatasyncIdsEndpoint","GET"),Ga:{}}};
lw.prototype.j=function(){return[]};
lw.prototype.i=function(){};
lw.prototype.h=function(){};var mw={},nw=(mw.GET_DATASYNC_IDS=fw(lw),mw);function ow(a){var b;(b=F("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},E("ytcsi."+(a||"")+"data_",b));return b}
function pw(){var a=ow();a.info||(a.info={});return a.info}
function qw(a){a=ow(a);a.metadata||(a.metadata={});return a.metadata}
function rw(a){a=ow(a);a.tick||(a.tick={});return a.tick}
function sw(a){a=ow(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function tw(a){a=sw(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function uw(a){var b=ow(a).nonce;b||(b=lu(),ow(a).nonce=b);return b}
;function vw(){var a=F("ytcsi.debug");a||(a=[],E("ytcsi.debug",a),E("ytcsi.reference",{}));return a}
function ww(a){a=a||"";var b=F("ytcsi.reference");b||(vw(),b=F("ytcsi.reference"));if(b[a])return b[a];var c=vw(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var X={},xw=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X.app_startup="LATENCY_ACTION_APP_STARTUP",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channel_activity="LATENCY_ACTION_KIDS_CHANNEL_ACTIVITY",X.channels="LATENCY_ACTION_CHANNELS",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.editor=
"LATENCY_ACTION_EDITOR",X.embed="LATENCY_ACTION_EMBED",X.embed_no_video="LATENCY_ACTION_EMBED_NO_VIDEO",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.favorites="LATENCY_ACTION_FAVORITES",X.home="LATENCY_ACTION_HOME",X.inboarding="LATENCY_ACTION_INBOARDING",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",
X.management="LATENCY_ACTION_MANAGEMENT",X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",
X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.projects="LATENCY_ACTION_PROJECTS",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.privacy_policy="LATENCY_ACTION_KIDS_PRIVACY_POLICY",X.review="LATENCY_ACTION_REVIEW",X.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",X.search_ui="LATENCY_ACTION_SEARCH_UI",
X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",X.tenx="LATENCY_ACTION_TENX",X.video_preview="LATENCY_ACTION_VIDEO_PREVIEW",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",
X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",
X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",X.attestation_challenge_fetch="LATENCY_ACTION_ATTESTATION_CHALLENGE_FETCH",X);function yw(a,b){lq.call(this,1,arguments);this.timer=b}
w(yw,lq);var zw=new mq("aft-recorded",yw);E("ytLoggingGelSequenceIdObj_",D.ytLoggingGelSequenceIdObj_||{});var Aw=D.ytLoggingLatencyUsageStats_||{};E("ytLoggingLatencyUsageStats_",Aw);function Bw(){this.h=0}
function Cw(){Bw.instance||(Bw.instance=new Bw);return Bw.instance}
Bw.prototype.tick=function(a,b,c,d){Dw(this,"tick_"+a+"_"+b)||po("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
Bw.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Dw(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,po("latencyActionInfo",a,{cttAuthInfo:c}))};
Bw.prototype.jspbInfo=function(){};
Bw.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Dw(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,po("latencyActionSpan",a,{cttAuthInfo:c}))};
function Dw(a,b){Aw[b]=Aw[b]||{count:0};var c=Aw[b];c.count++;c.time=V();a.h||(a.h=An(function(){var d=V(),e;for(e in Aw)Aw[e]&&d-Aw[e].time>6E4&&delete Aw[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new U("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||W(c)),!0):!1}
;var Ew=window;function Fw(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Gw(){var a;if(S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=Y==null?void 0:(a=Y.getEntriesByType)==null?void 0:(b=a.call(Y,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=Hw(e.requestStart),e.responseEnd=Hw(e.responseEnd),e.redirectStart=Hw(e.redirectStart),e.redirectEnd=Hw(e.redirectEnd),e.domainLookupEnd=Hw(e.domainLookupEnd),e.connectStart=Hw(e.connectStart),e.connectEnd=
Hw(e.connectEnd),e.responseStart=Hw(e.responseStart),e.secureConnectionStart=Hw(e.secureConnectionStart),e.domainLookupStart=Hw(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=S("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(Y.timing)):Y.timing;return a}
function Hw(a){return Math.round(Iw()+a)}
function Iw(){return(S("csi_use_time_origin")||S("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=Ew.performance||Ew.mozPerformance||Ew.msPerformance||Ew.webkitPerformance||new Fw;var Jw=!1,Kw=!1,Lw={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj",'script[name="embed_client"]':"ecj",'link[rel="stylesheet"][name="embed-ui"]':"ecc"};Xa(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||di,Y);function Mw(a,b){if(!S("web_csi_action_sampling_enabled")||!ow(b).actionDisabled){var c=ww(b||"");rv(c.info,a);a.loadType&&(c=a.loadType,qw(b).loadType=c);rv(tw(b),a);c=uw(b);b=ow(b).cttAuthInfo;Cw().info(a,c,b)}}
function Nw(){var a,b,c,d;return((d=Ms().resolve(new Gs(Zp))==null?void 0:(a=$p())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Z(a,b,c){if(!S("web_csi_action_sampling_enabled")||!ow(c).actionDisabled){var d=uw(c),e;if(e=S("web_csi_debug_sample_enabled")&&d){(Ms().resolve(new Gs(Zp))==null?0:$p())&&!Kw&&(Kw=!0,Z("gcfl",V(),c));var f,g,h;e=(Ms().resolve(new Gs(Zp))==null?void 0:(f=$p())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Nw();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+d.charCodeAt(g),
g<d.length-1&&(f%=0x800000000000);e=f%1E5%e!==0;ow(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Mw(f,c));ow(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,Y.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||S("web_csi_disable_alt_time_performance_mark"))Y.mark(e);else{f=S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")?f-Y.timeOrigin:f-(Y.timeOrigin||Y.timing.navigationStart);try{Y.mark(e,
{startTime:f})}catch(k){}}e=ww(c||"");e.tick[a]=b||V();if(e.callback&&e.callback[a])for(e=z(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=sw(c);e.gelTicks&&(e.gelTicks[a]=!0);f=rw(c);e=b||V();S("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=ow(c).cttAuthInfo;a==="_start"?(a=Cw(),Dw(a,"baseline_"+d)||po("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):Cw().tick(a,d,b,f);Ow(c);return e}}}
function Pw(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=$r+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Qw(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=z(Object.entries(R("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=z(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Rw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);zb(document)&&a.setAttribute("nonce",zb(document));return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Iw(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Sw(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=Nb(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Pb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Z("wffs",Hw(b.startTime)),Z("wffe",Hw(b.responseEnd)))}
function Tw(a){var b=Uw("aft",a);if(b)return b;b=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Uw(b[d],a);if(e)return e}return NaN}
function Uw(a,b){if(a=rw(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Ow(a){var b=Uw("_start",a),c=Tw(a),d=S("enable_cow_info_csi")||!Jw;b&&c&&d&&(rq(zw,new yw(Math.round(c-b),a)),Jw=!0)}
function Vw(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=Qb(a,function(c){return c.name==="first-paint"}))return Hw(a.startTime)}var b;
S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")?b=Y.getEntriesByType("first-paint")[0].startTime:b=Y.timing.Mh;return b?Math.max(0,b):0}
;function Ww(a,b){am(function(){ww("").info.actionType=a;b&&Xl("TIMING_AFT_KEYS",b);Xl("TIMING_ACTION",a);var c=Qw();Object.keys(c).length>0&&Mw(c);c={isNavigation:!0,actionType:xw[R("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=R("PREVIOUS_ACTION");d&&(c.previousAction=xw[d]||"LATENCY_ACTION_UNKNOWN");if(d=R("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=R("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=vu())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Pw();if(d===1||d===-1)c.isVisible=!0;qw();pw();
c.loadType="cold";d=pw();var e=Gw(),f=Iw(),g=R("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!S("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Z("srt",e.responseStart),d.prerender!==1&&Z("_start",f,void 0));d=Vw();d>0&&Z("fpt",d);d=Gw();d.isPerformanceNavigationTiming&&Mw({performanceNavigationTiming:!0},void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,
void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Iw()&&d.connectEnd-d.secureConnectionStart>0&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Sw();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Lw)Lw.hasOwnProperty(h)&&(e=Lw[h],
Rw(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=z(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Mw(c);c=sw();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=tw();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(qw().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=rw();e=sw();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Z(k,Uw(k));else if(S("log_repeated_ytcsi_ticks"))for(f=
z(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Z(k.slice(1),g);k={};d=!1;h=z(h);for(e=h.next();!e.done;e=h.next())d=e.value,rv(c,d),rv(k,d),d=!0;d&&Mw(k)}E("ytglobal.timingready_",!0);k=R("TIMING_ACTION");F("ytglobal.timingready_")&&k&&Xw()&&Tw()&&Ow()})()}
function Xw(a){return am(function(){return Yw("_start",a)})()}
function Zw(a,b,c){am(Mw)(a,b,c===void 0?!1:c)}
function $w(a,b,c){return am(Z)(a,b,c)}
function Yw(a,b){return am(function(){var c=rw(b);return a in c})()}
function ax(a){if(!S("universal_csi_network_ticks"))return"";a=$b(ac(5,a))||"";for(var b=Object.keys(jq),c=0;c<b.length;c++){var d=b[c];if(a.includes(d))return d}return""}
function bx(a){if(!S("universal_csi_network_ticks"))return function(){};
var b=jq[a];return b?(cx(b),function(){var c=S("universal_csi_network_ticks")?(c=kq[a])?cx(c):!1:!1;return c}):function(){}}
function cx(a){return am(function(){if(Yw(a))return!1;$w(a,void 0,void 0);return!0})()}
function dx(a){am(function(){if(!Xw("attestation_challenge_fetch")||Yw(a,"attestation_challenge_fetch"))return!1;$w(a,void 0,"attestation_challenge_fetch");return!0})()}
function ex(){am(function(){var a=uw();requestAnimationFrame(function(){setTimeout(function(){a===uw()&&$w("ol",void 0,void 0)},0)})})()}
var fx=window;fx.ytcsi&&(fx.ytcsi.infoGel=Zw,fx.ytcsi.tick=$w);function gx(a,b){var c=C.apply(2,arguments);a=a===void 0?0:a;U.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
w(gx,U);var hx="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD shorts_prefetch".split(" "),ix=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function jx(a,b,c,d){this.u=a;this.fa=b;this.j=c;this.o=d;this.i=void 0;this.h=new Map;a.Zb||(a.Zb={});a.Zb=Object.assign({},nw,a.Zb)}
function kx(a,b,c,d){if(jx.instance!==void 0){if(d=jx.instance,a=[a!==d.u,b!==d.fa,c!==d.j,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new U("InnerTubeTransportService is already initialized",a);
}else jx.instance=new jx(a,b,c,d)}
function lx(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?en:c;var d=mx(a,b);return d?new fi(function(e,f){var g,h,k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d,2);case 2:g=n.i;h=g.u(b,void 0,c);if(!h){f(new U("Error: Failed to build request for command.",b));n.A(0);break}Qv(h.input);l=((k=h.Za)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.j.Ld){m=nx(h.config,l);n.A(4);break}return n.yield(ox(h.config,l),5);case 5:m=n.i;case 4:e(px(a,h,m)),n.h=
0}})}):ki(new U("Error: No request builder found for command.",b))}
function qx(a,b){function c(){}
var d="/youtubei/v1/"+iw(Yu);var e=e===void 0?{Ob:{identity:en}}:e;var f=f===void 0?!0:f;c=bx(ax(d));b.context||(b.context=bw(void 0,f));return new fi(function(g){var h,k,l,m,n;return B(function(p){if(p.h==1)return h=Fu(d),k=nm(h)?"same-origin":"cors",a.j.Ld?(l=nx(e,k),p.A(2)):p.yield(ox(e,k),3);p.h!=2&&(l=p.i);m=Gu(Fu(d));n={input:m,Za:Hu(m),Ga:b,config:e};g(px(a,n,l,c));p.h=0})})}
function rx(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.o){d=z(hx);for(var e=d.next();!e.done;e=d.next())e=e.value,a.o[e]&&a.o[e].handleResponse(b,c)}}
function px(a,b,c,d){d=d===void 0?function(){}:d;
var e,f,g,h,k,l,m,n,p,t,v,x,y,G,J,ba,ca,Na,Kb,ja,Ya,Pa,Qa,Oa,eh,fh,hs,is,js,ks;return B(function(ia){switch(ia.h){case 1:ia.A(2);break;case 3:if((e=ia.i)&&!e.isExpired())return ia.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Ga)==null?0:g.context)){ia.A(4);break}h=b.Ga.context;ia.A(5);break;case 5:k=z([]),l=k.next();case 8:if(l.done){ia.A(4);break}m=l.value;return ia.yield(m.Nh(h),9);case 9:l=k.next();ia.A(8);break;case 4:if((n=a.i)==null||!n.Th(b.input,b.Ga)){ia.A(12);break}return ia.yield(a.i.Ih(b.input,
b.Ga),13);case 13:return p=ia.i,rx(a,p,b),ia.return(p);case 12:return(x=(v=b.config)==null?void 0:v.Qh)&&a.h.has(x)?t=a.h.get(x):(y=JSON.stringify(b.Ga),ba=(J=(G=b.Za)==null?void 0:G.headers)!=null?J:{},b.Za=Object.assign({},b.Za,{headers:Object.assign({},ba,c)}),ca=Object.assign({},b.Za),b.Za.method==="POST"&&(ca=Object.assign({},ca,{body:y})),((Na=b.config)==null?0:Na.Xe)&&$w(b.config.Xe),Kb=function(){return a.fa.fetch(b.input,ca,b.config)},t=Kb(),x&&a.h.set(x,t)),ia.yield(t,14);
case 14:if((ja=ia.i)&&"error"in ja&&((Ya=ja)==null?0:(Pa=Ya.error)==null?0:Pa.details))for(Qa=ja.error.details,Oa=z(Qa),eh=Oa.next();!eh.done;eh=Oa.next())fh=eh.value,(hs=fh["@type"])&&ix.indexOf(hs)>-1&&(delete fh["@type"],ja=fh);x&&a.h.has(x)&&a.h.delete(x);((is=b.config)==null?0:is.Ye)&&$w(b.config.Ye);if(ja||(js=a.i)==null||!js.wh(b.input,b.Ga)){ia.A(15);break}return ia.yield(a.i.Hh(b.input,b.Ga),16);case 16:ja=ia.i;case 15:return rx(a,ja,b),((ks=b.config)==null?0:ks.Ue)&&$w(b.config.Ue),d(),
ia.return(ja||void 0)}})}
function mx(a,b){a:{a=a.u;var c,d=(c=lt(b,El))==null?void 0:c.signal;if(d&&a.Zb&&(c=a.Zb[d])){var e=c();break a}var f;if((c=(f=lt(b,Cl))==null?void 0:f.request)&&a.he&&(f=a.he[c])){e=f();break a}for(e in b)if(a.pd[e]&&(b=a.pd[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function ox(a,b){var c,d,e,f;return B(function(g){if(g.h==1){e=(c=a)==null?void 0:(d=c.Ob)==null?void 0:d.sessionIndex;var h=g.yield;var k=dn(0,{sessionIndex:e});if(!(k instanceof fi)){var l=new fi(di);gi(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},cw(b),f)))})}
function nx(a,b){var c;a=a==null?void 0:(c=a.Ob)==null?void 0:c.sessionIndex;c=dn(0,{sessionIndex:a});return Object.assign({},cw(b),c)}
;var sx=new Fs("INNERTUBE_TRANSPORT_TOKEN");function tx(){}
w(tx,kw);tx.prototype.j=function(){return dv};
tx.prototype.i=function(a){return lt(a,Ol)||void 0};
tx.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(tx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function ux(){}
w(ux,kw);ux.prototype.j=function(){return ev};
ux.prototype.i=function(a){return lt(a,Nl)||void 0};
ux.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(ux.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});var vx=new Fs("SHARE_CLIENT_PARAMS_PROVIDER_TOKEN");function wx(a){this.M=a}
w(wx,kw);wx.prototype.j=function(){return Zu};
wx.prototype.i=function(a){return lt(a,Il)||lt(a,Jl)||lt(a,Hl)};
wx.prototype.h=function(a,b){b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);if(b.clientParamIdentifier){var c;if((c=this.M)==null?0:c.h(b.clientParamIdentifier))a.clientParams=this.M.i(b.clientParamIdentifier)}};
wx[Es]=[vx];function xx(){}
w(xx,kw);xx.prototype.j=function(){return av};
xx.prototype.i=function(a){return lt(a,Gl)||void 0};
xx.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(xx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function yx(){}
w(yx,kw);yx.prototype.j=function(){return bv};
yx.prototype.i=function(a){return lt(a,Ml)||void 0};
yx.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function zx(){}
w(zx,kw);zx.prototype.j=function(){return cv};
zx.prototype.i=function(a){return lt(a,Ll)||void 0};
zx.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Ax(){}
w(Ax,kw);Ax.prototype.j=function(){return $u};
Ax.prototype.i=function(a){return lt(a,Kl)};
Ax.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Bx=new Fs("FETCH_FN_TOKEN"),Cx=new Fs("PARSE_FN_TOKEN");var Dx=new Fs("NETWORK_SLI_TOKEN");function Ex(a,b,c){this.h=a;this.i=b;this.j=c}
Ex.prototype.fetch=function(a,b,c){var d=this,e,f,g;return B(function(h){e=Fx(d,a,b);g=(f=d.i)!=null?f:fetch;return h.return(g(e).then(function(k){return d.handleResponse(k,c)}).catch(function(k){W(k);
if((c==null?0:c.re)&&k instanceof gx&&k.errorType===1)return Promise.reject(k)}))})};
function Fx(a,b,c){if(a.h){var d=$b(ac(5,lc(b,"key")))||"/UNKNOWN_PATH";a.h.start(d)}a=c;S("wug_networking_gzip_request")&&(a=Tq(c));return new window.Request(b,a)}
Ex.prototype.handleResponse=function(a,b){var c,d=(c=this.j)!=null?c:JSON.parse;c=a.text().then(function(e){if((b==null?0:b.He)&&a.ok)return Bf(b.He,e);e=e.replace(")]}'","");if((b==null?0:b.re)&&e)try{var f=d(e)}catch(h){throw new gx(1,"JSON parsing failed after fetch");}var g;return(g=f)!=null?g:d(e)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Ch(),c=c.then(function(e){W(new U("Error: API fetch failed",a.status,a.url,e));return Object.assign({},e,{errorMetadata:{status:a.status}})}));
return c};
Ex[Es]=[new Gs(Dx),new Gs(Bx),new Gs(Cx)];var Gx=new Fs("NETWORK_MANAGER_TOKEN");var Hx;function Ix(){var a,b;if(!Hx){var c=Ms();Is(c,{Bc:Gx,Od:Ex});var d={pd:{feedbackEndpoint:fw(xx),modifyChannelNotificationPreferenceEndpoint:fw(yx),playlistEditEndpoint:fw(zx),shareEntityEndpoint:fw(wx),subscribeEndpoint:fw(tx),unsubscribeEndpoint:fw(ux),webPlayerShareEntityServiceEndpoint:fw(Ax)}},e=aw(),f={};e&&(f.client_location=e);a===void 0&&(a=cn());b===void 0&&(b=c.resolve(Gx));kx(d,b,a,f);Is(c,{Bc:sx,Pd:jx.instance});Hx=c.resolve(sx)}return Hx}
;function Jx(a){var b=new ej;if(a.interpreterJavascript){var c=ul(a.interpreterJavascript);c=Cb(c).toString();var d=new cj;yf(d,6,c);tf(b,cj,1,d)}else a.interpreterUrl&&(c=vl(a.interpreterUrl),c=jb(c).toString(),d=new dj,yf(d,4,c),tf(b,dj,2,d));a.interpreterHash&&zf(b,3,a.interpreterHash);a.program&&zf(b,4,a.program);a.globalName&&zf(b,5,a.globalName);a.clientExperimentsStateBlob&&zf(b,7,a.clientExperimentsStateBlob);return b}
function Kx(a){var b={};a=z(a.split("&"));for(var c=a.next();!c.done;c=a.next())c=c.value.split("="),c.length===2&&(b[c[0]]=c[1]);return b}
;function vc(){if(S("bg_st_hr"))return"havuokmhhs-0";var a,b=((a=performance)==null?void 0:a.timeOrigin)||0;return"havuokmhhs-"+Math.floor(b)}
function Lx(a){this.h=a}
Lx.prototype.bindInnertubeChallengeFetcher=function(a){this.h.bicf(a)};
Lx.prototype.registerChallengeFetchedCallback=function(a){this.h.bcr(a)};
Lx.prototype.getLatestChallengeResponse=function(){return this.h.blc()};
function Mx(){return new Promise(function(a){var b=window.top;b.ntpevasrs!==void 0?a(new Lx(b.ntpevasrs)):(b.ntpqfbel===void 0&&(b.ntpqfbel=[]),b.ntpqfbel.push(function(c){a(new Lx(c))}))})}
;var Nx=[],Ox=!1;function Px(){if(!S("disable_biscotti_fetch_for_ad_blocker_detection")&&!S("disable_biscotti_fetch_entirely_for_all_web_clients")&&Iu()){var a=R("PLAYER_VARS",{});if(jg(a)!="1"&&!Ku(a)){var b=function(){Ox=!0;"google_ad_status"in window?Xl("DCLKSTAT",1):Xl("DCLKSTAT",2)};
try{hv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Nx.push(Gj.pa(function(){if(!(Ox||"google_ad_status"in window)){try{lv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Ox=!0;Xl("DCLKSTAT",3)}},5E3))}}}
function Qx(){var a=Number(R("DCLKSTAT",0));return isNaN(a)?0:a}
;function Rx(a){this.h=a}
[new Rx("b.f_"),new Rx("j.s_"),new Rx("r.s_"),new Rx("e.h_"),new Rx("i.s_"),new Rx("s.t_"),new Rx("p.h_"),new Rx("s.i_"),new Rx("f.i_"),new Rx("a.b_"),new Rx("a.o_"),new Rx("g.o_"),new Rx("p.i_"),new Rx("p.m_"),new Rx("n.k_"),new Rx("i.f_"),new Rx("a.s_"),new Rx("m.c_"),new Rx("n.h_"),new Rx("o.p_")].reduce(function(a,b){a[b.h]=b;return a},{});function Sx(a,b,c){var d=this;this.network=a;this.options=b;this.o=c;this.h=null;if(b.Yh){var e=new ij;this.h=e.promise;D.ytAtRC&&Gj.Ra(function(){var f,g;return B(function(h){if(h.h==1){if(!D.ytAtRC)return h.return();f=Tx(null);return h.yield(d.hb(f),2)}g=h.i;D.ytAtRC&&D.ytAtRC(JSON.stringify(g));h.h=0})},2);
Mx().then(function(f){var g,h,k,l;return B(function(m){if(m.h==1)return f.bindInnertubeChallengeFetcher(function(n){return d.hb(Tx(n))}),m.yield(uc(),2);
g=m.i;h=f.getLatestChallengeResponse();k=h.challenge;if(!k)throw Error("BGE_MACIL");l={challenge:k,fb:Kx(k),vm:g,bgChallenge:new ej};e.resolve(l);f.registerChallengeFetchedCallback(function(n){n=n.challenge;if(!n)throw Error("BGE_MACR");n={challenge:n,fb:Kx(n),vm:g,bgChallenge:new ej};d.h=Promise.resolve(n)});
m.h=0})})}else b.preload&&Ux(this,new Promise(function(f){An(function(){f(Vx(d))},0)}))}
Sx.prototype.j=function(){var a=this;return B(function(b){return b.h==1?b.yield(Promise.race([a.h,null]),2):b.return(!!b.i)})};
Sx.prototype.i=function(a,b,c){var d=this,e,f,g;return B(function(h){d.h===null&&Ux(d,Vx(d));e=!1;f={};g=function(){var k,l,m;return B(function(n){switch(n.h){case 1:return n.yield(d.h,2);case 2:k=n.i;f.challenge=k.challenge;if(!k.vm){"c1a"in k.fb&&(f.error="ATTESTATION_ERROR_VM_NOT_INITIALIZED");n.A(3);break}l=Object.assign({},{c:k.challenge,e:a},b);ya(n,4);e=!0;if(S("attbs")&&!S("attmusi")){m=k.vm.ed({wb:l});n.A(6);break}return n.yield(k.vm.snapshot({wb:l}),7);case 7:m=n.i;case 6:m?f.webResponse=
m:f.error="ATTESTATION_ERROR_VM_NO_RESPONSE";za(n,3);break;case 4:Aa(n),f.error="ATTESTATION_ERROR_VM_INTERNAL_ERROR";case 3:if(a==="ENGAGEMENT_TYPE_PLAYBACK"){var p=k.fb,t={};p.c6a&&(t.reportingStatus=String(Number(p.c)^Qx()));p.c6b&&(t.broadSpectrumDetectionResult=String(Number(p.c)^Number(R("CATSTAT",0))));f.adblockReporting=t}return n.return(f)}})};
return h.return(Promise.race([g(),Wx(c,function(){var k=Object.assign({},f);e&&(k.error="ATTESTATION_ERROR_VM_TIMEOUT");return k})]))})};
function Tx(a){var b={engagementType:"ENGAGEMENT_TYPE_UNBOUND"};a&&(b.interpreterHash=a);return b}
function Vx(a,b){b=b===void 0?0:b;var c,d,e,f,g,h,k,l,m,n,p,t;return B(function(v){switch(v.h){case 1:c=Tx(nj().h);if(S("att_fet_ks"))return ya(v,7),v.yield(a.hb(c),9);ya(v,4);return v.yield(Xx(a,c),6);case 6:g=v.i;e=g.Pe;f=g.Qe;d=g;za(v,3);break;case 4:return Aa(v),W(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),Yx(a,864E5),v.return({challenge:"",fb:{},vm:void 0,bgChallenge:void 0});case 9:d=v.i;if(!d)throw Error("Fetching Attestation challenge returned falsy");
if(!d.challenge)throw Error("Missing Attestation challenge");e=d.challenge;f=Kx(e);if("c1a"in f&&(!d.bgChallenge||!d.bgChallenge.program))throw Error("Expected bg challenge but missing.");za(v,3);break;case 7:h=Aa(v);W(h);b++;if(b>=5)return W(Error("Failed to fetch attestation challenge after "+(b+" attempts; not retrying for 24h."))),Yx(a,864E5),v.return({challenge:"",fb:{},vm:void 0,bgChallenge:void 0});k=1E3*Math.pow(2,b-1)+Math.random()*1E3;return v.return(new Promise(function(x){An(function(){x(Vx(a,
b))},k)}));
case 3:l=Number(f.t)||7200;Yx(a,l*1E3);m=void 0;if(!("c1a"in f&&d.bgChallenge)){v.A(10);break}n=Jx(d.bgChallenge);ya(v,11);return v.yield(oj(nj(),n),13);case 13:za(v,12);break;case 11:return p=Aa(v),W(p),v.return({challenge:e,fb:f,vm:m,bgChallenge:n});case 12:return ya(v,14),m=new kj({challenge:n,zd:{Da:"aGIf"}}),v.yield(m.Zc,16);case 16:za(v,10);break;case 14:t=Aa(v),W(t),m=void 0;case 10:return v.return({challenge:e,fb:f,vm:m,bgChallenge:n})}})}
Sx.prototype.hb=function(a){var b=this,c;return B(function(d){c=b.o;if(!c||c.ta())return d.return(b.network.hb(a));dx("att_pna");return d.return(new Promise(function(e){Lh(c,"publicytnetworkstatus-online",function(){b.network.hb(a).then(e)})}))})};
function Zx(a){if(!a)throw Error("Fetching Attestation challenge returned falsy");if(!a.challenge)throw Error("Missing Attestation challenge");var b=a.challenge,c=Kx(b);if("c1a"in c&&(!a.bgChallenge||!a.bgChallenge.program))throw Error("Expected bg challenge but missing.");return Object.assign({},a,{Pe:b,Qe:c})}
function Xx(a,b){var c,d,e,f,g;return B(function(h){switch(h.h){case 1:c=void 0,d=0,e={};case 2:if(!(d<5)){h.A(4);break}if(!(d>0)){h.A(5);break}e.md=1E3*Math.pow(2,d-1)+Math.random()*1E3;return h.yield(new Promise(function(k){return function(l){An(function(){l(void 0)},k.md)}}(e)),5);
case 5:return ya(h,7),h.yield(a.hb(b),9);case 9:return f=h.i,h.return(Zx(f));case 7:c=g=Aa(h),g instanceof Error&&W(g);case 8:d++;e={md:void 0};h.A(2);break;case 4:throw c;}})}
function Ux(a,b){a.h=b}
function $x(a){var b,c,d;return B(function(e){if(e.h==1)return e.yield(Promise.race([a.h,null]),2);b=e.i;var f=Vx(a);a.h=f;(c=b)==null||(d=c.vm)==null||d.dispose();e.h=0})}
function Yx(a,b){function c(){var e;return B(function(f){e=d-Date.now();return e<1E3?f.yield($x(a),0):(An(c,Math.min(e,6E4)),f.A(0))})}
var d=Date.now()+b;c()}
function Wx(a,b){return new Promise(function(c){An(function(){c(b())},a)})}
;function ay(){this.h=Ix()}
ay.prototype.hb=function(a){dx("att_fsr");return qx(this.h,a).then(function(b){dx("att_frr");return b})};function by(){var a,b,c;return B(function(d){if(d.h==1)return a=Ms().resolve(sx),a?d.yield(lx(a),2):(W(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return W(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.zh;return d.return(c)}W(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function cy(){var a;return(a=R("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var dy=D.caches,ey;function fy(a){var b=a.indexOf(":");return b===-1?{Cd:a}:{Cd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function gy(){return B(function(a){if(ey!==void 0)return a.return(ey);ey=new Promise(function(b){var c;return B(function(d){switch(d.h){case 1:return ya(d,2),d.yield(dy.open("test-only"),4);case 4:return d.yield(dy.delete("test-only"),5);case 5:za(d,3);break;case 2:if(c=Aa(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(ey)})}
function hy(a){var b,c,d,e,f,g,h;B(function(k){if(k.h==1)return k.yield(gy(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(dy.keys(),3)}c=k.i;d=z(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=fy(f),h=g.datasyncId,!h||a.includes(h)||b.push(dy.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
function iy(){var a,b,c,d,e,f,g;return B(function(h){if(h.h==1)return h.yield(gy(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=yn("cache contains other");return h.yield(dy.keys(),3)}b=h.i;c=z(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=fy(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function jy(){try{return!!self.sessionStorage}catch(a){return!1}}
;function ky(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function ly(a){if(jy()){var b=Object.keys(window.sessionStorage);b=z(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=ky(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function my(){if(!jy())return!1;var a=yn(),b=Object.keys(window.sessionStorage);b=z(b);for(var c=b.next();!c.done;c=b.next())if(c=ky(c.value),c!==void 0&&c!==a)return!0;return!1}
;function ny(){by().then(function(a){a&&(Ep(a),hy(a),Nv(a),ly(a))})}
function oy(){var a=new Lr;Gj.pa(function(){var b,c,d,e,f;return B(function(g){switch(g.h){case 1:if(S("ytidb_clear_optimizations_killswitch")){g.A(2);break}b=yn("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];Ep(h);hy(h);Nv(h);ly(h);return g.return()}c=Ov();d=my();return g.yield(iy(),3);case 3:return e=g.i,g.yield(Fp(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.ta()?ny():Lh(a,"publicytnetworkstatus-online",ny),g.h=0}})})}
;var py=["www.youtube-nocookie.com","www.youtubeeducation.com","youtube.googleapis.com"];function qy(){this.state=1;this.vm=null;this.h=void 0}
r=qy.prototype;r.initialize=function(a,b,c,d){this.h=d;if(a.program){var e;d=(e=a.interpreterUrl)!=null?e:null;if(a.interpreterSafeScript)e=ul(a.interpreterSafeScript);else{var f;e=(f=a.interpreterScript)!=null?f:null}a.interpreterSafeUrl&&(d=vl(a.interpreterSafeUrl).toString());ry(this,e,d,a.program,b,c)}else W(Error("Cannot initialize botguard without program"))};
function ry(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,hv(c,function(){window[g]?sy(a,d,g,e):(a.state=3,jv(c),W(new U("Unable to load Botguard","from "+c)))},f)):b?(f=sg("SCRIPT"),b instanceof Ab?(f.textContent=Cb(b),Db(f)):f.textContent=b,f.nonce=zb(document),document.head.appendChild(f),document.head.removeChild(f),window[g]?sy(a,d,g,e):(a.state=4,W(new U("Unable to load Botguard from JS")))):W(new U("Unable to load VM; no url or JS provided"))}
r.isLoading=function(){return this.state===2};
function sy(a,b,c,d){a.state=5;var e=!!a.h&&py.includes(bc(a.h)||"");try{var f=new kj({program:b,globalName:c,zd:{disable:!S("att_web_record_metrics")||!S("att_skip_metrics_for_cookieless_domains_ks")&&e,Da:"aGIf"}});f.Zc.then(function(){a.state=6;d&&d(b)});
a.Yc(f)}catch(g){a.state=7,g instanceof Error&&W(g)}}
r.invoke=function(a){a=a===void 0?{}:a;return this.hd()?this.Rd({wb:a}):null};
r.dispose=function(){this.Yc(null);this.state=8};
r.hd=function(){return!!this.vm};
r.Rd=function(a){return this.vm.ed(a)};
r.Yc=function(a){rc(this.vm);this.vm=a};function ty(){var a=F("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function uy(){qy.apply(this,arguments)}
w(uy,qy);uy.prototype.Yc=function(a){var b;(b=ty())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.ed.bind(a)},E("yt.abuse.playerAttLoader",b),E("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(E("yt.abuse.playerAttLoader",null),E("yt.abuse.playerAttLoaderRun",null))};
uy.prototype.hd=function(){return!!ty()};
uy.prototype.Rd=function(a){return ty().bgvmc(a)};function vy(a){Ws.call(this,a===void 0?"document_active":a);var b=this;this.o=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.G},{from:"document_active",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"document_disposed",action:this.u},{from:"document_disposed_preventable",to:"flush_logs",action:this.M},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.M},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
w(vy,Ws);vy.prototype.G=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
vy.prototype.u=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
vy.prototype.M=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
vy.prototype.i=function(){this.h=new Map};function wy(a){Ws.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.M},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.u},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.M},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.M},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.u},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.u},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
S("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
w(wy,Ws);wy.prototype.i=function(a,b){a(b==null?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
wy.prototype.h=function(a,b){a(b==null?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
wy.prototype.u=function(a,b){a(b==null?void 0:b.event)};
wy.prototype.M=function(a,b){a(b==null?void 0:b.event)};function xy(){this.o=new vy;this.u=new wy}
xy.prototype.install=function(){var a=C.apply(0,arguments),b=this;a.forEach(function(c){b.o.install(c)});
a.forEach(function(c){b.u.install(c)})};function yy(){this.o=[];this.i=new Map;this.h=new Map;this.j=new Set}
yy.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=vu(c===void 0?0:c)){a=this.client;d=new ou({trackingParams:d});var e=void 0;if(S("no_client_ve_attach_unless_shown")){var f=Iv(d,c);Ev.set(f,!0);Jv(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Hv({cttAuthInfo:xu(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?Kv("visualElementGestured",f,d):a?Vt("visualElementGestured",d,a,f):po("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
yy.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new ou({trackingParams:a}),b,c===void 0?0:c)};
yy.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.o.push([a,b]);else{var d=c;d=d===void 0?0:d;c=vu(d);a||(a=(a=su(d===void 0?0:d))?new ou({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Hv({cttAuthInfo:xu(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?Kv("visualElementStateChanged",d,b):a?Vt("visualElementStateChanged",b,a,d):po("visualElementStateChanged",b,d))}};
function zy(a,b){if(b===void 0)for(var c=uu(),d=0;d<c.length;d++)c[d]!==void 0&&zy(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&Gv(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function Ay(){xy.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));S("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));S("web_log_cfg_cee_ks")||An(By)}
w(Ay,xy);Ay.prototype.j=function(){po("finalPayload",{csn:vu()})};
Ay.prototype.h=function(){iu(ju)};
Ay.prototype.i=function(){var a=zy;yy.instance||(yy.instance=new yy);a(yy.instance)};
function By(){var a=R("CLIENT_EXPERIMENT_EVENTS");if(a){var b=Xd();a=z(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&po("genericClientExperimentEvent",{eventType:c});delete Wl.CLIENT_EXPERIMENT_EVENTS}}
;function Cy(){}
function Dy(){var a=F("ytglobal.storage_");a||(a=new Cy,E("ytglobal.storage_",a));return a}
Cy.prototype.estimate=function(){var a,b,c;return B(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return(Ey()):d.return()})};
function Ey(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
E("ytglobal.storageClass_",Cy);function no(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
no.prototype.Ha=function(a){this.handleError(a)};
no.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":S("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":S("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Fy(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function Fy(a,b){Dy().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:Gy(c==null?void 0:c.usage),deviceStorageQuotaMbytes:Gy(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Gy(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;var Hy={},Iy=(Hy["api.invalidparam"]=2,Hy.auth=150,Hy["drm.auth"]=150,Hy["heartbeat.net"]=150,Hy["heartbeat.servererror"]=150,Hy["heartbeat.stop"]=150,Hy["html5.unsupportedads"]=5,Hy["fmt.noneavailable"]=5,Hy["fmt.decode"]=5,Hy["fmt.unplayable"]=5,Hy["html5.missingapi"]=5,Hy["html5.unsupportedlive"]=5,Hy["drm.unavailable"]=5,Hy["mrm.blocked"]=151,Hy["embedder.identity.denied"]=152,Hy);var Jy=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn playmuted muted_autoplay_duration_mode".split(" "));function Ky(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function Ly(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=z(Jy);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function My(a,b,c,d){if(Ra(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function Ny(a){H.call(this);var b=this;this.api=a;this.Y=this.u=!1;this.D=[];this.P={};this.j=[];this.i=[];this.Z=!1;this.sessionId=this.h=null;this.targetOrigin="*";this.U=S("web_player_split_event_bus_iframe");this.o=R("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.G=function(c){a:if(!(b.o!=="*"&&c.origin!==b.o||b.h&&c.source!==b.h||typeof c.data!=="string")){try{var d=JSON.parse(c.data)}catch(h){break a}if(d)switch(d.event){case "listening":var e=c.source;
c=c.origin;d=d.id;c!=="null"&&(b.o=b.targetOrigin=c);b.h=e;b.sessionId=d;if(b.u){b.Y=!0;b.u=!1;b.sendMessage("initialDelivery",Oy(b));b.sendMessage("onReady");e=z(b.D);for(d=e.next();!d.done;d=e.next())Py(b,d.value);b.D=[]}break;case "command":if(e=d.func,d=d.args,e==="addEventListener"&&d)e=d[0],d=c.origin,e==="onReady"?b.api.logApiCall(e+" invocation",d):e==="onError"&&b.Z&&(b.api.logApiCall(e+" invocation",d,b.errorCode),b.errorCode=void 0),b.api.logApiCall(e+" registration",d),b.P[e]||e==="onReady"||
(c=Qy(b,e,d),b.i.push({eventType:e,listener:c,origin:d}),b.U?b.api.handleExternalCall("addEventListener",[e,c],d):b.api.addEventListener(e,c),b.P[e]=!0);else if(c=c.origin,b.api.isExternalMethodAvailable(e,c)){d=d||[];if(d.length>0&&Ky(e)){var f=d;if(Ra(f[0])&&!Array.isArray(f[0]))var g=f[0];else switch(g={},e){case "loadVideoById":case "cueVideoById":g=Ly(f[0],f[1]!==void 0?Number(f[1]):void 0,f[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":g=f[0];typeof g==="string"&&(g={mediaContentUrl:g,
startSeconds:f[1]!==void 0?Number(f[1]):void 0,suggestedQuality:f[2]});c:{if((f=g.mediaContentUrl)&&(f=/\/([ve]|embed)\/([^#?]+)/.exec(f))&&f[2]){f=f[2];break c}f=null}g.videoId=f;g=Ly(g);break;case "loadPlaylist":case "cuePlaylist":g=My(f[0],f[1],f[2],f[3])}d.length=1;d[0]=g}b.api.handleExternalCall(e,d,c);Ky(e)&&Ry(b,Oy(b))}}}};
Sy.addEventListener("message",this.G);if(a=R("WIDGET_ID"))this.sessionId=a;Ty(this,"onReady",function(){b.u=!0;var c=b.api.getVideoData();if(!c.isPlayable){b.Z=!0;c=c.errorCode;var d=d===void 0?5:d;b.errorCode=c?Iy[c]||d:d;b.sendMessage("onError",Number(b.errorCode))}});
Ty(this,"onVideoProgress",this.kf.bind(this));Ty(this,"onVolumeChange",this.lf.bind(this));Ty(this,"onApiChange",this.cf.bind(this));Ty(this,"onPlaybackQualityChange",this.gf.bind(this));Ty(this,"onPlaybackRateChange",this.hf.bind(this));Ty(this,"onStateChange",this.jf.bind(this));Ty(this,"onWebglSettingsChanged",this.mf.bind(this));Ty(this,"onCaptionsTrackListChanged",this.df.bind(this));Ty(this,"captionssettingschanged",this.ef.bind(this))}
w(Ny,H);function Ry(a,b){a.sendMessage("infoDelivery",b)}
r=Ny.prototype;r.sendMessage=function(a,b){a={event:a,info:b===void 0?null:b};this.Y?Py(this,a):this.D.push(a)};
function Qy(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
function Ty(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function Oy(a){if(!a.api)return null;var b=a.api.getApiInterface();Rb(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substring(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
r.jf=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&!S("embeds_enable_vfsyb")&&(a.storyboardFormat=this.api.getStoryboardFormat());Ry(this,a)};
r.gf=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());Ry(this,a)};
r.hf=function(a){Ry(this,{playbackRate:a})};
r.cf=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
r.lf=function(){Ry(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
r.kf=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Ry(this,a)};
r.mf=function(){Ry(this,{sphericalProperties:this.api.getSphericalProperties()})};
r.df=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};Ry(this,a)}};
r.ef=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};Ry(this,a)}};
function Py(a,b){if(a.h){b.channel="widget";a.sessionId&&(b.id=a.sessionId);try{var c=JSON.stringify(b);a.h.postMessage(c,a.targetOrigin)}catch(d){W(d)}}}
r.ba=function(){H.prototype.ba.call(this);Sy.removeEventListener("message",this.G);for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.U?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};
var Sy=window;function Uy(a,b,c){H.call(this);var d=this;this.api=a;this.id=b;this.origin=c;this.h={};this.j=S("web_player_split_event_bus_iframe");this.i=function(e){a:if(e.origin===d.origin){var f=e.data;if(typeof f==="string"){try{f=JSON.parse(f)}catch(k){break a}if(f.command){var g=f.command;f=f.data;e=e.origin;if(!d.ea){var h=f||{};switch(g){case "addEventListener":typeof h.event==="string"&&d.addListener(h.event,e);break;case "removeEventListener":typeof h.event==="string"&&d.removeListener(h.event,e);break;
default:d.api.isReady()&&d.api.isExternalMethodAvailable(g,e||null)&&(f=Vy(g,f||{}),f=d.api.handleExternalCall(g,f,e||null),(f=Wy(g,f))&&Xy(d,g,f))}}}}}};
Yy.addEventListener("message",this.i);Xy(this,"RECEIVING")}
w(Uy,H);r=Uy.prototype;r.addListener=function(a,b){if(!(a in this.h)){var c=this.ff.bind(this,a);this.h[a]=c;this.addEventListener(a,c,b)}};
r.ff=function(a,b){this.ea||Xy(this,a,Zy(a,b))};
r.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
r.addEventListener=function(a,b,c){this.j?a==="onReady"?this.api.addEventListener(a,b):this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
r.removeEventListener=function(a,b,c){this.j?a==="onReady"?this.api.removeEventListener(a,b):this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function Vy(a,b){switch(a){case "loadVideoById":return[Ly(b)];case "cueVideoById":return[Ly(b)];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return[My(b)];case "cuePlaylist":return[My(b)];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];case "setShuffle":return[b.shufflePlaylist];
case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Wy(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function Zy(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
function Xy(a,b,c){a.ea||(b={id:a.id,command:b},c&&(b.data=c),$y.postMessage(JSON.stringify(b),a.origin))}
r.ba=function(){Yy.removeEventListener("message",this.i);for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);H.prototype.ba.call(this)};
var Yy=window,$y=window.parent;var az=new uy;function bz(){return az.hd()}
function cz(a){a=a===void 0?{}:a;return az.invoke(a)}
;function dz(a,b,c,d,e){H.call(this);var f=this;this.D=b;this.webPlayerContextConfig=d;this.Kb=e;this.Pa=!1;this.api={};this.ma=this.u=null;this.U=new N;this.h={};this.Z=this.xa=this.elementId=this.Qa=this.config=null;this.Y=!1;this.j=this.G=null;this.Fa={};this.Gc=["onReady"];this.lastError=null;this.eb=NaN;this.P={};this.ha=0;this.i=this.o=a;tc(this,this.U);ez(this);c?this.ha=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(fz(this),gz(this))}
w(dz,H);r=dz.prototype;r.getId=function(){return this.D};
r.loadNewVideoConfig=function(a){if(!this.ea){this.ha&&(clearTimeout(this.ha),this.ha=0);var b=a||{};b instanceof Xu||(b=new Xu(b));this.config=b;this.setConfig(a);gz(this);this.isReady()&&hz(this)}};
function fz(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.D,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.D:a.config.attrs.id=a.D);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
r.setConfig=function(a){this.Qa=a;this.config=iz(a);fz(this);if(!this.xa){var b;this.xa=jz(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Aj(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Aj(Number(a)||a))};
function hz(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function kz(a){var b=!0,c=lz(a);c&&a.config&&(b=c.dataset.version===mz(a));return b&&!!F("yt.player.Application.create")}
function gz(a){if(!a.ea&&!a.Y){var b=kz(a);if(b&&(lz(a)?"html5":null)==="html5")a.Z="html5",a.isReady()||nz(a);else if(oz(a),a.Z="html5",b&&a.j&&a.o)a.o.appendChild(a.j),nz(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.G=function(){c=!0;var d=pz(a,"player_bootstrap_method")?F("yt.player.Application.createAlternate")||F("yt.player.Application.create"):F("yt.player.Application.create");var e=a.config?iz(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig,a.Kb);nz(a)};
a.Y=!0;b?a.G():(hv(mz(a),a.G),(b=qz(a))&&ov(b||""),rz(a)&&!c&&E("yt.player.Application.create",null))}}}
function lz(a){var b=rg(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function nz(a){if(!a.ea){var b=lz(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Y=!1;if(!pz(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}sz(a)}else a.eb=setTimeout(function(){nz(a)},50)}}
function sz(a){ez(a);a.Pa=!0;var b=lz(a);if(b){a.u=tz(a,b,"addEventListener");a.ma=tz(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=tz(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.u&&a.u(g,a.h[g]);hz(a);a.xa&&a.xa(a.api);a.U.sb("onReady",a.api)}
function tz(a,b,c){var d=b[c];return function(){var e=C.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new U("PlayerProxy error in method call",{error:f,method:c,playerId:a.D}),e.level="WARNING",e;}}}
function ez(a){a.Pa=!1;if(a.ma)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ma(b,a.h[b]);for(var c in a.P)a.P.hasOwnProperty(c)&&clearTimeout(Number(c));a.P={};a.u=null;a.ma=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Qa};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
r.isReady=function(){return this.Pa};
r.addEventListener=function(a,b){var c=this,d=jz(this,b);d&&(Lb(this.Gc,a)>=0||this.h[a]||(b=uz(this,a),this.u&&this.u(a,b)),this.U.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
r.removeEventListener=function(a,b){this.ea||(b=jz(this,b))&&this.U.unsubscribe(a,b)};
function jz(a,b){var c=b;if(typeof b==="string"){if(a.Fa[b])return a.Fa[b];c=function(){var d=C.apply(0,arguments),e=F(b);if(e)try{e.apply(D,d)}catch(f){throw d=new U("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.Fa[b]=c}return c?c:null}
function uz(a,b){function c(d){function e(){if(!a.ea)try{a.U.sb(b,d!=null?d:void 0)}catch(h){var g=new U("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.D,data:d,originalStack:h.stack,componentStack:h.ge});g.level="WARNING";throw g;}}
if(pz(a,"web_player_publish_events_immediately"))e();else{var f=setTimeout(function(){e();var g=a.P,h=String(f);h in g&&delete g[h]},0);
ig(a.P,String(f))}}
return a.h[b]=c}
r.getPlayerType=function(){return this.Z||(lz(this)?"html5":null)};
r.getLastError=function(){return this.lastError};
function oz(a){a.cancel();ez(a);a.Z=null;a.config&&(a.config.loaded=!1);var b=lz(a);b&&(kz(a)||!rz(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
r.cancel=function(){this.G&&lv(mz(this),this.G);clearTimeout(this.eb);this.Y=!1};
r.ba=function(){oz(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new U("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.Fa=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Qa=this.config=this.api=null;delete this.o;delete this.i;H.prototype.ba.call(this)};
function rz(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function mz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function qz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function pz(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function iz(a){for(var b={},c=z(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?lg(e):e}return b}
;var vz={},wz="player_uid_"+(Math.random()*1E9>>>0);function xz(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?rg(c):c;var e=wz+"_"+Sa(c),f=vz[e];if(f&&d)return yz(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new dz(c,e,a,b,void 0);vz[e]=f;f.addOnDisposeCallback(function(){delete vz[f.getId()]});
return f.api}
function yz(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var zz=null,Az=null;
function Bz(){ex();var a=nn(),b=qn(119),c=window.devicePixelRatio>1;if(document.body&&Oj(document.body,"exp-invert-logo"))if(c&&!Oj(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Oj(d,"inverted-hdpi")){var e=Mj(d);Nj(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Oj(document.body,"inverted-hdpi")&&Pj();if(b!=c){b="f"+(Math.floor(119/31)+1);d=rn(b)||0;d=c?d|67108864:d&-67108865;d===0?delete kn[b]:(c=d.toString(16),kn[b]=c.toString());
c=!0;S("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in kn)kn.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(kn[f])));var f=d.join("&");fn(b,f,63072E3,a.i,c)}}
function Cz(){Dz()}
function Ez(){$w("ep_init_pr");Dz()}
function Dz(){var a=zz.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function Fz(){zz&&zz.sendAbandonmentPing&&zz.sendAbandonmentPing();R("PL_ATT")&&az.dispose();for(var a=Gj,b=0,c=Nx.length;b<c;b++)a.qa(Nx[b]);Nx.length=0;jv("//static.doubleclick.net/instream/ad_status.js");Ox=!1;Xl("DCLKSTAT",0);sc(Az);zz&&(zz.removeEventListener("onVideoDataChange",Cz),zz.destroy())}
;$w("ep_init_eps");E("yt.setConfig",Xl);E("yt.config.set",Xl);E("yt.setMsg",gv);E("yt.msgs.set",gv);E("yt.logging.errors.log",du);
E("writeEmbed",function(){$w("ep_init_wes");var a=R("PLAYER_CONFIG");if(!a){var b=R("PLAYER_VARS");b&&(a={args:b})}Sv(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);S("embeds_enable_new_csi")||Ww("embed",["ol"]);c=cy();if(!c.serializedForcedExperimentIds){var d=km(window.location.href);d.forced_experiments&&
(c.serializedForcedExperimentIds=d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)?Ww("watch",["pbs","pbu","pbp"]):S("embeds_enable_new_csi")&&(a.args&&Ju(a.args)?Ww("video_preview",["ol"]):Ww("embed_no_video",["ep_init_pr"]));zz=xz(a,c);zz.addEventListener("onVideoDataChange",Cz);zz.addEventListener("onReady",Ez);a=R("POST_MESSAGE_ID","player");R("ENABLE_JS_API")?Az=new Ny(zz):R("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(Az=new Uy(zz,a,b));Px();S("ytidb_create_logger_embed_killswitch")||
mo();a={};Ay.h||(Ay.h=new Ay);Ay.h.install((a.flush_logs={callback:function(){It()}},a));
Xr();S("ytidb_clear_embedded_player")&&Gj.pa(function(){Ix();oy()});
S("enable_rta_manager")&&An(function(){var f=new ay;var g={preload:!S("enable_rta_npi")},h;typeof g==="boolean"?h={preload:g}:typeof g==="undefined"?h={preload:!0}:h=g;g=new Lr;Sx.instance=new Sx(f,h,g);f=Sx.instance;h=f.i.bind(f);E("yt.aba.att",h);f=f.j.bind(f);E("yt.aba.att2",f)});
$w("ep_init_wee")});
E("yt.abuse.player.botguardInitialized",F("yt.abuse.player.botguardInitialized")||bz);E("yt.abuse.player.invokeBotguard",F("yt.abuse.player.invokeBotguard")||cz);E("yt.abuse.dclkstatus.checkDclkStatus",F("yt.abuse.dclkstatus.checkDclkStatus")||Qx);E("yt.player.exports.navigate",F("yt.player.exports.navigate")||Rv);E("yt.util.activity.init",F("yt.util.activity.init")||qs);E("yt.util.activity.getTimeSinceActive",F("yt.util.activity.getTimeSinceActive")||ts);
E("yt.util.activity.setTimestamp",F("yt.util.activity.setTimestamp")||rs);window.addEventListener("load",am(function(){Bz()}));
window.addEventListener("pageshow",am(function(a){a.persisted||Bz()}));
window.addEventListener("pagehide",am(function(a){S("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Fz():a.persisted||Fz()}));
window.onerror=function(a,b,c,d,e){var f;b=b===void 0?"Unknown file":b;c=c===void 0?0:c;var g=!1,h=Yl("log_window_onerror_fraction");if(h&&Math.random()<h)g=!0;else{h=document.getElementsByTagName("script");for(var k=0,l=h.length;k<l;k++)if(h[k].src.indexOf("/debug-")>0){g=!0;break}}if(g){g=!1;e?g=!0:(typeof a==="string"?h=a:ErrorEvent&&a instanceof ErrorEvent?(g=!0,h=a.message,b=a.filename,c=a.lineno,d=a.colno):(h="Unknown error",b="Unknown file",c=0),e=new U(h),e.name="UnhandledWindowError",e.message=
h,e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d);if(!S("wiz_enable_component_stack_propagation_killswitch")){a=e;var m;if((m=f)==null||!m.componentStack)if(m=a.ge)f||(f={}),f.componentStack=Wt(m)}f&&gu(e,f);g?du(e):W(e)}};
wi=eu;window.addEventListener("unhandledrejection",function(a){eu(a.reason)});
Mb(R("ERRORS")||[],function(a){du.apply(null,a)});
Xl("ERRORS",[]);$w("ep_init_epe");}).call(this);
