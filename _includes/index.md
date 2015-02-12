## Across the Great Wall

_穿越长城，走向世界_
_免费网络代理公益小组_

+ 免费代理帐号
+ 关于我们
+ 加入我们

## 免费代理帐号

免费，亦有成本。它不能像专业服务商一样提供快速支持服务，它也无法承诺提供的服务随时可用。它只是您的可选代理方案，使用权决定于您。

### SSH 

【公共帐号1】
~~~
用户名: public 
服务器地址: acrossthegreatwall.org 
服务器端口: 22（选填）
本地端口：7070（默认）
密码：acrossthegreatwall
~~~

【公共帐号2】
~~~
用户名：public 
服务器地址：204.12.192.18 
服务器端口：22（选填）
本地端口：7070（默认）
密码：acrossthegreatwall
~~~

使用方法简介：

+ Mac OS & Linux：打开终端，输入命令`ssh -N -D 7070 public@服务器地址` 
，(服务器地址可按照上面提供的服务器地址填写)，然后回车，在出现提示“public@acrossthegreatwall.org's password:”输入密码`accrossthegreatwall`(输入过程中,密码不会被显示出来)，这时已经建立好了连接，不要关闭终端。
+ Windows：可使用 MyEnTunnel 客户端连接设置。

同时，Linux系统可安装SSH客户端 gSTM，Mac OS系统安装iSSH。（感谢darkshell.me提供SSH使用教程）

注意，Firefox浏览器请安装 AutoProxy，可在AutoProxy设置端口(port) 
为其它端口，默认为7070。如果其他端口，Linux和Mac命令方式时，需替换命令中的 
7070。Google Chrome (Chromium)浏览器则需要配合扩展ProxySwitch。

### Shadowsocks

【公共帐号1】
~~~
服务器: 204.12.192.18 
远程端口:8388 
本地端口：1080 
密码：acrossthegreatwall 
加密方法：AES-256-CFB
~~~

或使用Shadowsocks应用扫描下面二维码，快速添加代理帐号信息：

![Shadowsocks](./images/S1.png)

【公共帐号2】
~~~
服务器: 104.236.191.62
远程端口:8388
本地端口：1080
密码：across
加密方法：AES-256-CFB
~~~

【update】2015.02.12更新密码

客户端下载：
+ 下载地址1：[Shadowsocks官网][5]，包括Windows、Mac OS X、Linux、Android和iOS、OpenWRT客户端。
+ 使用说明：可参考教程[GitHub][6]。

安装完毕，将上述帐号信息填入即可！

*提示：限于iOS的安全策略，iOS用户使用Shadowsocks时，需要时隔几分钟就切换到Shadowsocks一次，才能不断激活代理服务。*

## 站外资源推荐(Update：2014.12.07)

+ [51FQ][51FQ]：提供免费VPN服务，最新帐号情况请访问该站点获取。
+ 微信号pennyjob：大家可以订阅该微信号，然后发送“翻墙”，就会收到SSH、VPN、Shadowsocks等代理帐号。
+ [玩转SSH][8]：免费提供美国SSH帐号、Shadowsocks帐号，并提供交流QQ群。
+ [shadowsocks免费帐号][9]：在这里你可以获得更多shadowsocks免费代理帐号。

[51FQ]: http://51fq.info/?page_id=5
[3]: https://sourceforge.net/projects/shadowsocksgui/
[4]: https://github.com/shadowsocks/shadowsocks-iOS/wiki/Shadowsocks-for-OSX-帮助
[5]: http://shadowsocks.org/en/download/clients.html
[6]: https://github.com/clowwindy/shadowsocks/wiki/Shadowsocks-%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E
[8]: http://playssh.com
[9]: http://shadowsocks.cn/get.html

## 小组愿景

我们的目标着实简单——帮助人们获取优质互联网资源，提供免费网络代理服务。

我们能够创建并运营该小组得益于开源社区众力开发的优秀开源软件和技术。开源软件，作为互联网发展的基石和催化剂，以及开源社区所蕴藏的巨大智慧，令人赞叹。

## 加入我们

1. 邮件列表。发送邮件到 acrossthegreatwall+subscribe@googlegroups.com，主题与内容皆填写 subscribe 
即可。加入邮件列表，可以与大家讨论代理技术问题，并获得最新的翻墙帐号信息。

2. 帮助我们

	+ 服务器推广。我们的服务器位于[DigitalOcean][1]，通过该推荐的链接购买，您可以获得10美元奖金，我们也将得到奖励。
	+ 捐赠。可以捐赠到支付宝帐号 1132321739qq#gmail.com（用@代替#），每一分捐赠将用于抵消服务器费用，也都将公示（留言中请注明您愿意公示的姓名或昵称）。扫一扫，就捐助，爱捐多少就捐多少：
	![Alipay](./images/alipay.jpeg)
	+ 主机资源。如果您有闲置的海外主机资源，愿意提供公共代理帐号，请加入我们的邮件列表，发送即可，我们会将期更新到本页面。

------

Follow us on [GitHub][7]. Last Update time: 2014.12.07

[1]: https://www.digitalocean.com/?refcode=14d8e6d96950  
[7]: https://github.com/tuhaihe/acrossthegreatwall
