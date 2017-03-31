# IOSSecurity
iOS安全，App加固保护原理
我们直接进图主题，就不说什么背景。

`我们可以从以下几个方面来保护我们的APP:`

### `字符串混淆`
* 对应用程序中使用到的字符串进行加密，保证源码被逆向后不能看出字符串的直观含义。

### `类名、方法名混肴`
* 对应用程序的方法名和方法体进行混淆，保证源码被逆向后很难明白它的真正功能。

### `程序结构混肴`
* 对应用程序逻辑结构进行打乱混排，保证源码可读性降到最低。

### `反调试、反注入等一些主动保护策略`
* 这是一些主动保护策略，增大破解者调试、分析APP的门槛。


###

