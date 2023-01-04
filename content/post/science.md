---
title: "科学上网纪实"
description: 必备技能
date: 2023-01-04T17:37:13+08:00
image: 
math: 
license: 
categories:
  - study
hidden: false
comments: true
draft: false
---

# 科学上网，科技强国

参考贴：https://writee.org/alcoholicalchemist/oxkya7im4b

如果有任何问题，参考上面的帖子，因为我是根据上面进行操作的，整个步骤也基本上是上面的，然后用我的语言写下来而已。

购买vps（Virtual Private Server），虚拟专用服务器技术，购买的时候要选国外的。

我购买使用的网站：Justhosts

https://my.justhost.ru/rdns

一些难处：俄语

人生在世就是要多学几门语言……

注1：后来又在hostwinds买了一个vps，就是贵一点，但更稳（买第二个的原因是justhosts俄罗斯那个登不上去了，然后过了几天又可以登了）

总之，步骤如下

**1. 购买**

从justhosts，啊，各尽其能吧，总之买一个vps就是了，有个justhosts的经验贴我放这里

https://www.daniao.org/8657.html?replytocom=7343

一些需要注意的地方：邮箱登录，会向邮箱发登录密码，之后的订单也是发到邮箱，包括root和密码也是处理完成后发送到邮箱，所以用安全点的，可以接收到邮件的邮箱。我直接用了163，因为懒得登gmail，还要先翻出去一下。

拿到ip后去ping一下，看看行不行，总之一个ping网站先放这里，全是勾就对了

https://www.vps234.com/ipchecker/

**2. 需下载的软件**

xshell，可以官网下免费版，提供邮箱就可以，下载链接会发邮箱

https://www.xshell.com/zh/（官网）

v2rayNC，我是从热心网友的网盘链接下的了。

**3. 设置**

现在是有了ip，有了软件

打开xshell，弹出的东西选新建，ip填上去，确认然后连接，就好了

然后下载v2ray，在框里输入

```
source <(curl -sL https://multi.netlify.app/v2ray.sh) --zh
```

等待

最后安装完会给出一个绿色的vmess的链接，很长

复制它

打开v2rayNC，任务栏有一个蓝图标

右键，从剪贴板导入批量url

好了之后再右键，服务器里会有vps，然后在http代理中开全局代理，图标会变红，就是成功连接了