一键脚本
---

一键脚本搭建 + 设置开启自启动

## 支持系统
CentOS 6+

Debian 7+

Ubuntu 12+

## 使用教程
1. 安装git
```shell
yum install git
```

2. git clone
```shell
git clone -b master https://github.com/flyzy2005/ss-fly
```

中间换成自己fork的地址，原始地址已经被移除了

3. 密码+端口设置
```shell
ss-fly/ss-fly.sh -i password 1024
```

## 其它操作
```shell
修改配置文件：vim /etc/shadowsocks.json
停止服务：ssserver -c /etc/shadowsocks.json -d stop
启动服务：ssserver -c /etc/shadowsocks.json -d start
重启服务：ssserver -c /etc/shadowsocks.json -d restart
卸载:ss-fly/ss-fly.sh -uninstall
```

## 
1.
```shell
git clone -b master https://github.com/flyzy2005/ss-fly
```
2.
```shell
ss-fly/ss-fly.sh -ssr
```

```
启动：/etc/init.d/shadowsocks start
停止：/etc/init.d/shadowsocks stop
重启：/etc/init.d/shadowsocks restart
状态：/etc/init.d/shadowsocks status
 
配置文件路径：/etc/shadowsocks.json
日志文件路径：/var/log/shadowsocks.log
代码安装目录：/usr/local/shadowsocks
卸载: ./shadowsocksR.sh uninstall
```

## 
*b*b*r*
```shell
ss-fly/ss-fly.sh -bbr
```

## 推荐的VPS
[Vultr](https://www.vultr.com/products/cloud-compute/)
