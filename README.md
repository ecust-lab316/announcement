# **316实验室公告**

## 316实验室wifi
### 连上实验室wifi可以访问局域网的打印机，局域网的服务器，学校内网等等
wifi名称：ECUST-316
wifi密码: hadoop316

## 打印机使用教程
### _实验室打印机型号为富士施乐M268 dw_
windows:
1. 添加打印机
2. 安装打印机驱动
3. 打印测试

Mac OS:
1. 添加打印机
2. 一般内置驱动无需安装驱动，直接打印测试

**[打印机驱动下载链接](http://onlinesupport.fujixerox.com/setupDriverForm.do?ctry_code=CN&lang_code=zh_CN&d_lang=zh_CN&pid=DPM268DW)**


## 连接到局域网内的工作站
### 步骤：
1. 连接到实验室网络ECUST-316
2. 打开终端, Mac OS iTerm/Linux Terminal/Windows Putty, (建议使用Linux系统，尽可能还原生产环境)
3. 在终端命令行中输入: ssh hadoop@192.168.1.11, 提示输入密码， 密码为hadoop316。（命令行中输入密码不会显示任何字符, 输对了回车即可） 
#### tips: ssh命令简单使用 ssh 用户名@主机地址。具体可以谷歌搜索，或者man ssh来查看ssh的用法. 
4. 实验室一共有三台工作站， 地址分别为192.168.1.11, 192.168.1.12, 192.168.1.13均可以使用 hadoop账户登录
5. 首次登录创建个人账户， 牢记自己的密码。
6. 创建账户步骤, 命令行输入(用你喜欢的英文名替换frankye): sudo adduser frankye, 输入hadoop的密码, 根据提示输入密码和相对应的信息即可
7. 创建完账户之后Ctrd + d 断开ssh连接，使用你创建的账户测试连接到服务器(用你的账户名替换frankye): ssh frankye@192.168.1.11。这样你就拥有独立的空间了，可以在这个账户下自由发挥(重启务必和其他小伙伴事先打个招呼！或者用 top 命令查看其他人是否在使用该服务器)。