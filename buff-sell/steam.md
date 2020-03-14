### 提取steam令牌文件
安卓用户和苹果用户的操作不同, 分开来讲. 先讲安卓的, 苹果的[点这里](#苹果用户)

> #### 安卓用户
- 首先要获取**root权限**(这步很重要), 有刷机经验的人应该知道, 不知道的去百度搜"[安卓 root](https://www.baidu.com/s?wd=%E5%AE%89%E5%8D%93+root&ie=UTF-8)", 有很多介绍的文章
- 安装"ES文件浏览器", 一般应用商店有下载, 用其它的文件管理工具应该也是可以的, 还可以是用电脑连接手机, 从电脑端操作手机文件, 前提是已经获得root权限
- 打开根目录, 也就是"/", 然后依次打开目录"**/data/data/com.valvesoftware.android.steam.community/files/**", 然后你会看到你的令牌文件"**Steamguard-你的64位SteamID**".
- 打开令牌文件, 将三个关键参数"**shared_secret**", "**identity_secret**", "**serial_number**", 写入到配置文件**setting.txt**

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/7.png)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/8.png)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/9.png)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/10.png)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/11.png)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/12.png)

----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
----------分隔线----------<br>
> #### 苹果用户
- 电脑安装**iTunes**并打开, [官网链接](https://www.apple.com/itunes/), [下载链接](https://www.apple.com/itunes/download/win64)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/13.png)

- 手机打开设置, 依次点击"**通用(General)**", "**iTunes同步**"
- 用数据线**连接手机和电脑**, 连接会要求做一些身份认证步骤, 跟着提示做就行

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/14.PNG)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/15.PNG)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/16.PNG)

- 连上后, 点击iTunes左上角的**手机图标**, 进入到手机信息的介绍面板
- 点击"**本电脑**", 取消打勾"**加密本地备份**"(加密的话是没法提取文件的), 点击"**立即备份**"
- 应该会出现一个加密提示, 点击"**不加密**"

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/17.png)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/18.png)

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/19.png)

- 等进度条完了, 就是备份完成, 大概花费两三分钟

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/20.png)

- 下载[令牌提取的软件](https://github.com/CaitSith2/ios-steamguard-extractor/releases/download/v1.04/ios-steamguard-extractor-v1.04.zip), 解压后打开, 点击界面下方的按钮, 这时就会看到令牌文件
- 也可以选择[百度网盘](https://pan.baidu.com/s/1lInJkSZmMFp4kTDeSn9k7A)下载, 提取码: pcam

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/21.png)

- 将三个关键参数"**shared_secret**", "**identity_secret**", "**serial_number**", 写入到配置文件**setting.txt**

> #### 配置文件
最后, 输入steam账号和密码, "**steam_user**"是账号, "**steam_password**"是密码

至此, 配置文件就算完成了, 看起来大概是这样的

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/22.png)

> END

- [下一章: 租一个云服务器](./server.md)
- [回到教程主页](./index.md)
