### 提取steam令牌文件
安卓用户和苹果用户的操作不同, 分开来讲.

#### 安卓用户
- 首先要获取root权限, 有刷机经验的人应该知道, 不知道的去百度搜"[安卓 root](https://www.baidu.com/s?wd=%E5%AE%89%E5%8D%93+root&ie=UTF-8)", 有很多介绍的文章
- 安装"ES文件浏览器", 一般应用商店有下载, 用其它的文件管理工具应该也是可以的, 还可以是用电脑连接手机, 从电脑端操作手机文件, 前提是已经获得root权限
- 打开根目录, 也就是"/", 然后依次打开目录/data/data/com.valvesoftware.android.steam.community/files/, 然后你会看到你的令牌文件"Steamguard-你的64位SteamID".
- 打开令牌文件, 将三个关键参数"shared_secret", "identity_secret", "serial_number", 写入到配置文件setting.txt
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/7.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/8.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/9.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/10.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/11.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/12.png)

