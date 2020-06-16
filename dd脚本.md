## 镜像源
  阿里 https://mirrors.aliyun.com/ubuntu-releases/
---
## dd脚本安装
  wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/veip007/dd/master/InstallNET.sh' && chmod +x InstallNET.sh
---
## 脚本使用命令
  bash InstallNET.sh -c 6.9 -v 64 -a --mirror 'http://mirror.centos.org/centos'
  //-c centos 
  //6.9 版本号
  //换上自定义的镜像url
---
## 全自动安装默认root密码: MoeClub.org
