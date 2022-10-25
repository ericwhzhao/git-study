# git学习
## git基础
### 前提
1、安装git

从官网安装，地址如下：
```bash
https://git-scm.com/downloads
```
2、查看git是否安装成功

```bash
$ git --version
```
3、设置用户信息

这就需要用到`git config`命令，配置信息

config的三个作用域

缺省等同于local，即直接使用`git config`
```bash
$ git config --local    //local只对某个仓库有效
$ git config --global   //global对当前用户所有仓库有效
$ git config --system   //system对系统所有登陆的用户有效
```
显示config的配置详情，加`--list`

配置global信息
```bash
$ git config --global user.name 'your name'
$ git config --global user.email 'your email'
```
### git常用操作

1、建立git仓库

两种场景
1. 已有项目代码，使用git管理项目代码

    
2. 新建项目


## git常用场景
## git与github
## git与gitLab
