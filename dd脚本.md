## 镜像源
```
阿里镜像站 https://developer.aliyun.com/mirror/
阿里ubuntu https://mirrors.aliyun.com/ubuntu-releases/
腾讯ubuntu apt源 https://mirrors.cloud.tencent.com/help/ubuntu.html
腾讯ubuntu https://mirrors.cloud.tencent.com/ubuntu-releases/
```
## dd脚本安装
```
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/veip007/dd/master/InstallNET.sh' && chmod +x InstallNET.sh
```
## 脚本使用命令
```
bash InstallNET.sh -u 18.04 -v 64 -a --mirror 'http://mirror.centos.org/centos'
//-u ubuntu 
//18.04 版本号
//换上自定义的镜像url
```
## 全自动安装默认root密码:```MoeClub.org```
