# Accesser
<!--[English version](README.en.md)-->

一个解决SNI RST导致维基百科、Pixiv等站点无法访问的工具  
[支持的站点](https://github.com/URenko/Accesser/wiki/目前支持的站点)

[![](https://img.shields.io/github/release/URenko/Accesser.svg)](https://github.com/URenko/Accesser/releases/latest)
[![](https://img.shields.io/github/downloads/URenko/Accesser/total.svg)](https://github.com/URenko/Accesser/releases/latest)
[![](https://img.shields.io/github/license/URenko/Accesser.svg)](https://github.com/URenko/Accesser/blob/master/LICENSE)

## 使用方法
参见[https://urenko.github.io/Accesser/](https://urenko.github.io/Accesser/)

## 依赖
```
pip3 install pyopenssl tld dnspython tornado
```
- Python3.7 (仅限3.7，安装以下扩展)
- [pyopenssl](https://pyopenssl.org/)
- dnspython
- [dnscrypt-proxy](https://github.com/jedisct1/dnscrypt-proxy)
- tornado
- tld 
#### Windows还要下面这个
- [sysproxy](https://github.com/Noisyfox/sysproxy) （[exe版本](https://rajio.delbertbeta.cc/s/050699))

## 增加支持的网站 
按pac文件格式编辑`template/pac`使要支持的网站从代理过 
![image.png](https://i.loli.net/2020/03/20/yUENRTWB1ojxFzg.png) 

## 当前支持
|                   |Windows|Mac OS|Linux|
|-------------------|-------|------|-----|
|基础支持            |  ✔  |  ✔  | ✔ |
|exe自动配置pac代理      |  ✔  |      |     |
|exe自动导入证书至系统   |  ✔  |      |     |
