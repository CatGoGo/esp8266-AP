# esp8266路由刷机指南

这是esp8266模块：
![](./1.png)

这是ttl刷机连接图：
![](./2.png)

之后使用esp8266的刷机工具，把AP固件刷进去。
![](./3.png)

然后手机连接到MyAP热点，输入192.168.4.1，就可以愉快地设置了。
![](./4.png)

# 驱蚊器硬改连路由器

但是使用的时候，总不能就这样插着吧。所以，需要一个壳子。

现在，我找到一个驱蚊器。
![](./5.png)

把它拆开，里面就可以赛进入esp8266了。

现在使用一个220v转5v的降压模块，再使用一个5v转3.3v的降压模块，得到3.3v的电源。

然后，把它们焊接起来。

先不扣上壳子，直插220v试一下，手机是可以上网的。现在扣上盖子。

最终效果：
![](./6.png)
