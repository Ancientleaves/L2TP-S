# L2TP-server-dev
L2TP一键安装脚本:
支持的系统：CentOS 6+ / Debian 7+ / Ubuntu 12+  

```
wget --no-check-certificate https://raw.githubusercontent.com/Ancientleaves/L2TP-S/master/install.sh
```
```
chmod a+x install.sh
```
```
./install.sh
```
# 编辑配置文件
```
vim /etc/ipsec.conf
```
把yes改为no
```
sha2-truncbug= no
```
# 重启
```
servicr ipsec restart
```
