some utils.

## Installation

    npm i mix-util

## Usage

```js
// util工具集
var util = require('mix-util');

util.loadScript // 加载js
util.loadImage // 加载图片
util.nextFrame // requestAnimationFrame或者setTimeout fallback
util.cancelFrame // cancelRequestAnimationFrame或者clearTimeout fallback
util.setCssPrefix // 根据浏览器设置css前缀
util.styleVender // 根据浏览器获取css前缀
util.browser // 浏览器内核判断 ex: util.browser.versions.ios
util.isFunction
util.isString
util.isArray
util.getElement // 根据输入内容返回DOM元素，传入字符串就作为DOM的id，传入DOM元素返回本身
util.getOffset // 根据输入内容返回DOM元素，传入字符串就作为DOM的id，传入DOM元素相对给定相对元素或body左上角的偏移量
util.extend // 将源对象的所有属性拷贝到目标对象中
util.genNonceStr // 获取随机数
util.setCookie
util.getCookie
util.clearCookie
util.getUrlQuery // 读取url上带的参数
util.buildUrlQuery // 拼接url参数
```

## License
<a href="http://nate.mit-license.org">MIT</a>