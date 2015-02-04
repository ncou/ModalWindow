# What is it?

ModalWindow is a JavaScript open-source library that provides an interface of working with modal-windows (written by Dmitriy Buyanov). It uses pure JavaScript, so it doesn't depends on other libraries.

# A simple using example

```js
new ModalWindow('A window').show()
```

# How to customize a window?

You can use following ModalWindow's methods:
* getWindowLayoutElement()
* getOverlayElement()
* getModalWindowElement()
* getModalContentElement()

```js
var modal = new ModalWindow('A window.');

modal.getModalContentElement().style.fontSize = '25px';

modal.show();
```

# Where can I see examples?

[Here](http://razip.github.io/ModalWindow/).