# Bookmarklet Code

```js

javascript: void 0;
  (function () {  
    if(document.querySelectorAll('.ytp-ad-preview-container').length > 0){
      document.querySelectorAll('video')[0].currentTime = document.querySelectorAll('video')[0].duration;
      document.querySelectorAll('button.ytp-ad-skip-button-modern').length > 0 ? document.querySelectorAll('button.ytp-ad-skip-button-modern')[0].click() : null
    }
  })()

```
