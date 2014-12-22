zepto
=====

zepto源码，修正部分手机上swipe事件无效的bug

引入zepto源码的时候，发现在许多android手机上swipe事件根本不能使用，通过在touchmove事件中
加入return false来阻止文档默认事件，虽然可以使用touch事件，但是浏览器默认的事件没了，比如uc
浏览器的默认事件会返回前面或者后面的一个页面。

此解决方法可以修正以上两个问题。

同时引入修改后的event.js和touch.js
