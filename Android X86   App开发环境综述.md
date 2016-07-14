#Android X86   App开发环境综述

##一、OS: Ubuntu 16.04 LTS

##二、代码编辑器

Google Android Studio 

版本：2.1.1或者以上

##三、编译服务器

//192.168.0.80


##四、git服务器

//192.168.0.80

##五、模拟器

本地安装２个软件：
１．qemu
２．qemu-system-x86_64

##六、日志、周报／周计划、月报／月计划、

https://github.com/openthos

##七、项目任务分配与Bug管理

禅道：就是一个在线的简易项目管理工具（中国人研发的）
禅道地址：https://dev.openthos.org/zentao/zentao/project-task-1.html

用户名：自己名字小写字母拼音全称，例如：刘畅，用户名是: liuchang
密码：初始密码的命名规则是：自己名字小写首字母＋１２３４５６

##八、Docker服务器

1. 远程登陆192.168.0.180
ssh lh@192.168.0.180

2. 启动各自Docker服务,刘畅的Docker服务是：lc-5.1
docker  start -ai   lc-5.1

3. Docker是什么？
是一个虚拟机。
研发工程师，在该环境下，下载代码，编译代码，提交代码。
