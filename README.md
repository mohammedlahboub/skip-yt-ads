# Bookmarklet Code

```js
javascript: void 0;
  (function () {  
    document.querySelectorAll('video')[0].currentTime = document.querySelectorAll('video')[0].duration;
    document.querySelectorAll('button.ytp-ad-skip-button-modern').length > 0 ? document.querySelectorAll('button.ytp-ad-skip-button-modern')[0].click() : null
  })()

```
