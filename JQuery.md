# JQuery

- `Fast`, `easy` and `feature rich` client side JavaScript library.
- `JavaScript` is a language while `JQuery` is a built in `Library`.
- `JQuery` simplifies javascript, animations, ajax and DOM.
- Cross platform and supports different types of `Browsers`.
- `jQuery` only works for `HTML` document and not for `XML` document.

![jQuery](Image/jQuery.png)

![jQuery](Image/Event.png)

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

- Used to `get` or `set` style properties or values for selected elements, tags or class.

### What is a CDN

- Content delivery network or Content distribution network.
- It provides files from servers at high bandwidth that leads to faster loading time.
- There are several companies that provide free public CDN's. (`Google`, `Microsoft` and `Yahoo`)
- `Microsoft` loads jQuery from `AJAX` CDN.
- `Google` loads jQuery from Google libraries `API`.
- e.g. We use JavaScript, CSS, Bootstrap and JQuery libraries CDN links instead of downloading the zip files.

```javascript
\\ CDN : jQuery library link which we copy directly from it's official website

<script src="https://code.jquery.com/jquery-3.1.0.min.js"></script>
```

### animate() method

- Apply custom `animation effect` to elements.
