# “The Past, Present, and Future of Local Storage for Web Applications”
**INTRODUCING HTML5 STORAGE**
is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons.

it’s a way for web pages to store named key/value pairs locally, within the client web browser. 

you can use Modernizr to detect support for HTML5 Storage.

`if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}`

**USING HTML5 STORAGE**
You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string.

Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets. For example, this snippet of code:

var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);

There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};

there is a property to get the total number of values in the storage area, and to iterate through all of the keys by index (to get the name of each key).

interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};

**TRACKING CHANGES TO THE HTML5 STORAGE AREA**
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};

**LIMITATIONS IN CURRENT BROWSERS**
1. “5 megabytes” is how much storage space each origin gets by default.
2. “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes.
