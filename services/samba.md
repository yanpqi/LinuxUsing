# Samba

## 使用步骤
安装应用
```
sudo apt-get install samba
```
创建用户
```
sudo smbpasswd -a XXX  //一个已经存在的用户
```
编辑/etc/samba/smb.conf文件
```
[user-name]
   comment = user-name's Home
   path = /home/jagger
   browseable = yes
   read only = no
   guest ok = no
   create mask = 0600
```
重启服务
```
sudo /etc/init.d/samba restart
```
## 配置详情
N/A

## 运行原理
N/A
