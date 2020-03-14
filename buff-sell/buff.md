### 获取buff登陆信息
- 打开浏览器, 登陆buff, 回到buff主页, 按**F12**打开控制台面板
- 点击"**网络**"(或者"network")
- 点击控制台左上角的**垃圾桶图标**, 清理旧的数据包
- 点击右上的"**所有**"(或者"all")

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/4.png)

按**F5刷新页面**, 这时会得到很多数据包, 拉到最下面, 依次完成下面操作
- 随便点击一个带有"**buff.163.com**"这个域名的数据包
- 点击"**消息头**"(或者"header")
- 看到"**请求头**"(或者"request header"), 注意, 是"请求头", 不是"响应头", 不要搞错
- 复制"**cookie**"后面的数据
- 粘贴到配置文件**cookie.txt**中

![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/6.png)

至此, 获取buff登陆信息已完成 :ok_hand:

> END

- [下一章: 启动程序](./last.md)
- [返回教程主页](./index.md)
