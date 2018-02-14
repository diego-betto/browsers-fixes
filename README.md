# browsers-fixes
A collection of browsers issues and fixes

### jQuery scrollTop always 0 in some browsers (IE, Edge, Safari)

```js
    var scrollTopBody = jQuery('body').scrollTop();
    var scrollTop = jQuery('html,body').scrollTop();

    if(scrollTopBody > 0) {
        scrollTop = scrollTopBody;
    }
```
