# mailu是一套完全开源免费的邮箱系统。

# 教程
[点击进去](https://jose.scjtqs.com/docker/2020-05-02-1646/docker%e7%89%88%e7%9a%84-%e5%bc%80%e6%ba%90%e9%82%ae%e5%b1%80%e7%b3%bb%e7%bb%9f-%e5%85%a8%e5%a5%97%e6%95%99%e7%a8%8b-mailu.html)

## 简易使用步骤：

> `git clone https://github.com/scjtqs/docker-mail.git docker-mail`

> `cd docker-mail`

> 修改mailu.env 文件,使其匹配你自己的域名

> 修改cetbot-dns-dnspod-credentials.ini 加入你的dnspod.cn的注册邮箱、appid、token。


> `docker-compose up -d`

## 域名访问的一些说明

> /webmail 一个web的邮箱客户端

> /admin 管理后台，可以在mailu.env里面设置是否开启

> /webdav/ 一个webdav服务，后面的斜杠记得加上

