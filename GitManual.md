# Git Manual
----------
## windows下搭建git服务器
### 所需工具
1. msysgit(服务器端、客户端都需要安装)
2. copssh(服务器端安装)
### windows配置
1. 在windows下需要重新创建一个用户作为仓库，假定新建的用户名为repo；
2. 修改计算机名，假定计算机名为server。设定了计算机名后，git的远程访问可以用server来代替IP地址。
### 生成ssh密钥/公钥
打开git bash命令窗口。在窗口中输入`ssh-keygen -t rsa`。之后，会需要输入口令密码，这里只需连续三次回车，将所有口令密码设为空即可。密钥/公钥会生成在c:\user\Administrator\.ssh文件夹下，即id_rsa和id_rsa.pub。把你的公钥添加给服务器，即可访问服务器端。
### copssh配置


## git常用命令
