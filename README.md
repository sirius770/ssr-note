# ssr-note

#### 谷歌云 虚拟机选择Debian GNU/Linux
#### //SSR四合一键安装脚本

#下载脚本
```
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
```
#文件授权
```
chmod +x shadowsocks-all.sh
```
#启动脚本：
```
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```

#### 卸载命令
```
./shadowsocks-all.sh uninstall
```

#### 常用命令
```
启动脚本
启动脚本后面的参数含义，从左至右依次为：启动，停止，重启，查看状态。

Shadowsocks-Python 版：
/etc/init.d/shadowsocks-python start | stop | restart | status

ShadowsocksR 版：
/etc/init.d/shadowsocks-r start | stop | restart | status

Shadowsocks-Go 版：
/etc/init.d/shadowsocks-go start | stop | restart | status

Shadowsocks-libev 版：
/etc/init.d/shadowsocks-libev start | stop | restart | status

各版本默认配置文件
Shadowsocks-Python 版：
/etc/shadowsocks-python/config.json

ShadowsocksR 版：
/etc/shadowsocks-r/config.json

Shadowsocks-Go 版：
/etc/shadowsocks-go/config.json

Shadowsocks-libev 版：
/etc/shadowsocks-libev/config.json

```
