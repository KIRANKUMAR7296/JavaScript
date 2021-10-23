# JQuery

- `Fast` and `feature rich` client side JavaScript library.
- `JavaScript` is a language while `JQuery` is a built in `Library`.
- Cross platform and supports different types of `Browsers`.
- Makes websites more `interactive` and `attractive`.
- `jQuery` only works for `HTML` document.

It does't work for `XML` document.

### What is $() in JQuery ?

- `$()` is an alias of jquery `function`
- Used to wrap any object into jquery object which helps to call various methods.

```javascript
$(document).ready(function(){   // Starting point
$("p").css("color","pink");
});
```

### Effects methods used in JQuery

1. `show()` : Display selected elements.
2. `hide()` : Hide selected elements.
3. `toggle()` : Toggle between two methods.
4. `fadein()` : Fades in selected elements.
5. `fadeout()` : Fades out the selected elements.
6. `fadeToggle()` : Toggle between `fadein()` and `fadeout()` methods.
7. `delay()` : Delay the executions of functions in the queue.

### html() method

- Change the entire content of the selected elements.
- It replaces the selected element contents with new contents.

### css() method

- Used to `get` or `set` style properties or values for selected elements.

### What is a CDN

- Content delivery network or Content distribution network.
- Large distributed system.
- It provides files from servers at high bandwidth that leads to faster loading time.
- There are several companies that provide free public CDN's. (`Google`, `Microsoft` and `Yahoo`)
- Reduces the load from the Server (Saves Bandwidth)
- `Microsoft` loads jQuery from `AJAX` CDN.
- `Google` loads jQuery from Google libraries `API`.

### animate() method

- Apply custom `animation effect` to elements.
