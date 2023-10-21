
# 版本区别
文件夹为独立版本与根目录版本毫无关联，仅备份留存
- crack      破解版
- initial    官方原版
- local      本地版
------
镜像仓库地址：[https://hub.docker.com/r/gettionhub/baota-docker](https://hub.docker.com/r/gettionhub/baota-docker)

代码仓库地址：[https://github.com/gettionhub/baota](https://github.com/gettionhub/baota)

------

# 宝塔面板7.7安装脚本&优化补丁

### 宝塔面板7.7优化版安装脚本

1. 优化：去除无用接口、减少无用代码执行、减少对于宝塔云端请求、去除面板广告等，保持面板干净清爽。

2. 修复：兼容新版本面板运行环境、修复面板XSS高危漏洞。


* Github链接（若无法访问请重试或使用加速器）
```bash
wget -O install.sh https://raw.githubusercontent.com/GettionHub/baota/main/install_6.0_mod.sh && bash install.sh
```
- 通用jsdelivr加速链接：
```bash
wget -O install.sh https://cdn.jsdelivr.net/gh/GettionHub/baota/install_6.0_mod.sh && bash install.sh
```
- 国内jsdelivr加速链接：
```bash
wget -O install.sh https://gcore.jsdelivr.net/gh/GettionHub/baota/install_6.0_mod.sh && bash install.sh
```

### 宝塔面板7.7优化补丁

1. 去除宝塔面板强制绑定账号
2. 去除各种删除操作时的计算题与延时等待
3. 去除创建网站自动创建的垃圾文件（index.html、404.html、.htaccess）
4. 关闭未绑定域名提示页面，防止有人访问未绑定域名直接看出来是用的宝塔面板
5. 关闭活动推荐与在线客服，去除首页企业版广告
6. 去除自动校验文件与上报信息定时任务
7. 去除面板日志与网站绑定域名上报

* Github链接（若无法访问请重试或使用加速器）
```bash
wget -O optimize.sh https://raw.githubusercontent.com/GettionHub/baota/main/optimize_mod.sh && bash optimize.sh
```
- 通用jsdelivr加速链接：
```bash
wget -O optimize.sh https://cdn.jsdelivr.net/gh/GettionHub/baota/optimize_mod.sh && bash optimize.sh
```
- 国内jsdelivr加速链接：
```bash
wget -O optimize.sh https://gcore.jsdelivr.net/gh/GettionHub/baota/optimize_mod.sh && bash optimize.sh
```
* 如果Ngnix创建的网站出现403 forbidden(保留网站创建的文件，若无法访问请重试或使用加速器）
```bash
wget -O optimize.sh https://raw.githubusercontent.com/GettionHub/baota/main/optimize_mod_fixngnix.sh && bash optimize.sh
```
- 通用jsdelivr加速链接：
```bash
wget -O optimize.sh https://cdn.jsdelivr.net/gh/GettionHub/baota/optimize_mod_fixngnix.sh && bash optimize.sh
```
- 国内jsdelivr加速链接：
```bash
wget -O optimize.sh https://gcore.jsdelivr.net/gh/GettionHub/baota/optimize_mod_fixngnix.sh && bash optimize.sh
```

### 卸载宝塔面板

- Github链接（若无法访问请重试或使用加速器）

```shell
wget -O bt-uninstall.sh https://raw.githubusercontent.com/GettionHub/baota/main/bt-uninstall.sh && bash bt-uninstall.sh
```
- 通用jsdelivr加速链接：
```shell
wget -O bt-uninstall.sh https://cdn.jsdelivr.net/gh/GettionHub/baota/bt-uninstall.sh && bash bt-uninstall.sh
```
- 国内jsdelivr加速链接：
```shell
wget -O bt-uninstall.sh https://gcore.jsdelivr.net/gh/GettionHub/baota/bt-uninstall.sh && bash bt-uninstall.sh
```
