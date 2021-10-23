# AJAX

Asynchronous JavaScript and XML

- `AJAX` is used to `load` data from `server` and `display` it on `webpage` without reloading the whole page.
- `AJAX` is used for sending data to server in the background.

### AJAX Methods

Methods | Description
:--- | :---
`ajax()` | Perform `HTTP` request.
`load()` | Loads data from `server` and append to existing data.
`get()` | `Request` data from `server` using an `AJAX HTTP GET` request.
`post()` | `Requests` data from `server` using an `AJAX HTTP POST` reqest.

```javascript
$(selector).load(URL, data, callback);

URL : Location of page you want to load.
data : Information to be sent along with request | Data to be passed to server.
callback : The function to be executed after request is successful.
```

### AJAX with local events 

Events | Description
:--- | :---
`success` | Fired when data is successfully received from server.
`error` | Fired when there is any error while receiving data from the server

### AJAX with global events

Events | Description
:--- | :---
ajaxStart | Fired when a request is initiated.
ajaxSend | Fired when a request is yet to be sent.
ajaxSuccess | Fired when data is successfully received from server.
ajaxError | Error while sending request to server or receiving a data from server.
ajaxComplete | Fired when a request is successfully completed. 

### How to pass data to server using AJAX ?

Every `AJAX` call has a parameter `data` which can be used to pass data to server.

```javascript
$(selector).load(URL, data, callback);
```
