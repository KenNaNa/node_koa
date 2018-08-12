# 事件简介
```
　　http://nodejs.org/api/events.html

　　http://www.infoq.com/cn/articles/tyq-nodejs-event

events是node.js 最重要的模块，events模块只提供了一个对象events.EventEmitter，EventEmitter 的核心是事件发射与事件监听器。

Node.js中大部分的模块，都继承自Event模块。

与DOM树上事件不同，不存在事件冒泡、逐层捕获等行为。

EventEmitter 支持若干个事件监听器。当事件发射时，注册到这个事件的事件监听器被依次调用，事件参数作为回调函数参数传递。 　
```

# 如何访问：
```
require('events');

```
