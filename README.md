# crack-v2ray-sspanel-v3-mod_Uim-plugin
# 本版本是破小解版本
# 破小解二进制文件下载地址：[release](https://github.com/RManLuo/crack-v2ray-sspanel-v3-mod_Uim-plugin/releases)
# 使用教程请看 [备份WIKI](https://github.com/splendidwrx/v2ray-wiki)
## 支持原版

## 普通安装
### 后端安装
``` bash
bash <(curl -L -s  https://raw.githubusercontent.com/RManLuo/crack-v2ray-sspanel-v3-mod_Uim-plugin/master/install-release.sh) \
--panelurl http://webapi.com --panelkey webkey --nodeid 2 \
--downwithpanel 1 --speedtestrate 6 --paneltype 0 --usemysql 0 --cfemail mail --cfkey xxx
```
### caddy安装
``` bash
bash <(curl -L -s https://raw.githubusercontent.com/RManLuo/crack-v2ray-sspanel-v3-mod_Uim-plugin/master/install_caddy.sh) node.com xxx@gmail.com https://fakeurl.com v2ray 10550
```

## Docker
### ws+tls
``` bash
cd docker_crack_tls
vi docker-compose.yml
docker-compose up -d
```
### ws
``` bash
cd docker_crack_ws
vi docker-compose.yml
docker-compose up -d
```
