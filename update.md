## 去广告
### 啥也不是？
#### 版本更新日志
### [源地址：如果有帮助，请您支持我一下😘！](https://lingeringsound.github.io/10007)

- **说明**
 > 模块下载后有`README.md`文件，请自行阅读。
- ***模块原理说明***
 > hosts拦截域名，host相当于一个本地的dns，理论上并不会影响网速，甚至还能加快(屏蔽了不需要的ip)节省流量，缺点就是不支持屏蔽二级域名和支持通配符。
 >> chattr +i 命令能够锁定文件不被删除/修改，能够有效屏蔽毒瘤的sdk写入上传信息。
 >>> iptables具体去百度一下，用法很多，目前我用来屏蔽某些网站的次级域名，补充一些host的不足。
 >>>> pm(cmd package)，安卓上通用的禁用应用组件方式，屏蔽不必要的流氓行为。
- ***模块结构说明***
 > `mod` 脚本执行文件夹，每个脚本有不同的功能，脚本里有注释，不想执行该脚本，可以改后缀名为`bak`
 >> `配置.conf`(配置.prop) 在刷入前可以用 **[mt文件管理器](https://binmt.lanzoui.com/b01bivkzc)** 修改来自定义模块的一些功能。

- v164
> #### 解除小米ROM包下载限速，重定向至`123.6.13.6`和`23.202.34.138`。
> #### 添加酷友的两个规则 不确定后续是否会误杀
> #### @coolapk [营销号666](http://www.coolapk.com/u/554004)
````
127.0.0.1 dsp-x.jd.com
127.0.0.1 dsp-x.jd.com.gslb.qianxun.com
````
> #### @coolapk [GreatYYH](http://www.coolapk.com/u/3241828)
```
127.0.0.1 api-cn.store.heytapmobi.com
```
- v170
> #### 添加拦截蓝奏云剪切板写入，来自酷友
> #### @coolapk[Aloazny](http://www.coolapk.com/u/27964501)
```
127.0.0.1 kl.67it.com
```
