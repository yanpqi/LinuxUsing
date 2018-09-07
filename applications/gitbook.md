# GitBook

## 安装步骤
安装NodeJs, 一般从官网上下载源码安装
```
cd node-vX.Y.Z
./configure
make
sudo make install #这里一定要加sudo
```
安装gitbook
```
sudo npm install -g gitbook-cli
```
查看gitbook是否安装成功
```
gitbook -V
```
gitbook导出pdf功能需要安装：

```
sudo apt-get install calibre 
```
书目录下，初始化

```
gitbook init
```
编译生成静态网页

```
gitbook build
```
可通过静态网址访问

```
gitbook serve
```
生成pdf
```
gitbook pdf .
```

## 问题描述

## 参考资料
[官方使用说明](http://www.chengweiyang.cn/gitbook/basic-usage/README.html)

