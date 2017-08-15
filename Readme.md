# 跨域方案

### 步骤

* npm install
* npm run dev
* 配置hosts(需打开默认)

```
127.0.0.1 x.stuq.com
127.0.0.1 y.stuq.com
```

* 例子是下面这几个

    1. http://y.stuq.com:7001/public/1.html
    2. http://y.stuq.com:7001/public/2.html
    3. http://y.stuq.com:7001/public/3.html
    4. http://y.stuq.com:7001/public/4.html
    5. http://y.stuq.com:7001/public/5.html

### 参考

* [Koa](https://github.com/koajs/koa)
* [egg](https://eggjs.org/)
* [浏览器同源政策及其规避方法](http://www.ruanyifeng.com/blog/2016/04/same-origin-policy.html)
* [XMLHTTPRequest](https://developer.mozilla.org/zh-CN/docs/Web/API/XMLHttpRequest)
* [window.postMessage](https://developer.mozilla.org/zh-CN/docs/Web/API/Window/postMessage)

# notes

1. html跨域 y跨域x
2. can i use 查询兼容性
视频看到1:26:59 
iframe跨域3 4 复习看
