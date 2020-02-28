### 下载及文件介绍
有两种下载方式:
1. github :octocat: [下载](https://github.com/farmer-person/buff-delivery/archive/20.02.27.zip)
2. 百度网盘 :cloud: [下载](https://pan.baidu.com/s/1BkcDF4YL5ewd3jdOuxURRg), 提取码: symp

然后解压, 得到文件如下:

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/1.png)

有些人的电脑是不显示文件后缀名的, 比如buff.bat, 它只显示buff, 这是很正常的, 不要觉得奇怪.

有五个要介绍的文件:
- **jre-windows-x64.exe**: 安装java运行环境
- **buff.bat**: 启动buff的入口(检测buff订单)
- **steam.bat**: 启动steam的入口(检测steam报价)
- **充值.bat**: 充值入口(软件可以免费试用两天, 后续要充值才能使用)
- **setting.txt**: 配置文件, 配置好才可以运行程序(在服务器运行, 不是在本地电脑运行)

打开setting.txt, 会看如下内容

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/2.png)

这里我介绍一下这几个参数的意思:
- "**shared_secret**", "**identity_secret**", "**serial_number**", 这三个参数是steam令牌文件里的对应参数
- "**steam_user**"是steam账号, "**steam_password**"是steam密码
- "**cookie**"是buff的登陆信息

配置完这6个参数之后就可以部署到服务器来运行了, 当然, 看到这里你现在肯定是没法写这些参数的, 因为这是后面章节介绍的内容, 这里只讲下载和文件内容. :smile:

> END

- [下一章: 登陆buff, 提取登陆信息](./buff.md)
- [返回教程主页](./index.md)
