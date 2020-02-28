### 租一个香港节点的云服务器

先说明一下为什么要租一个云服务器.
1. 为了能访问steam, uu加速器是不管用的, uu只对steam这个软件有效, 从浏览器访问steam依然是不行, 不信可以自己试试, 所以要租一个香港节点, 香港的网络在全球都是畅通无阻的, uu大部分的服务器都是用的香港节点.
2. 能24小时运行, 就算你家没电没网, 也没有任何影响.

租服务器是要钱的, 这里我们前期试用, 就租一个按量付费(按小时收费)的就行, 后续如果想继续用就转包年包月(比按量付费划算), 如果不想用就退掉, 试用一下花不了多少钱.

阿里云是阿里巴巴的产品, 和淘宝, 支付宝这些系属同一个公司.
- 打开[阿里云官网](https://www.aliyun.com/?userCode=rn6hdbrz), 点右上角登陆(用支付宝账号登陆), 初次登陆可能要填一些信息, 照做就行.
- 从右上角的个人信息点充值, 充100块(租按量付费服务器的必要条件, 不充没法租), 钱是可以提现的, 不用担心.
- 回到[官网首页](https://www.aliyun.com/?userCode=rn6hdbrz), 点击左边"云服务器ECS"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/24.png)
- 跳转页面后, 点击"立即购买"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/25.png)
- 选择"按量付费", "香港"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/27.png)
> 
- 选择"1vCPU", "2GiB", "经典网络", 这时筛选出唯一一个结果, 点击"共享计算型n1"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/28.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/29.png)
- 选择"Windows Server", "2019 数据中心版 64位中文版", 点击"下一步"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/30.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/31.png)
- 选择"经典网络", "按使用流量", 然后把带宽拉满, 安全组默认, 点击"下一步"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/32.png)
- 设置服务器的密码, 点击"确认订单"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/33.png)
- 确认一下信息, 勾选"同意服务协议", 点击"创建实例"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/34.png)
- 租服务器完成, 接下来熟悉一下控制台的操作
- 回到[官网首页](https://www.aliyun.com/?userCode=rn6hdbrz), 点击右上角"控制台"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/35.png)
- 点击左上角的菜单符号, 点击"云服务器ECS"
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/36.png)
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/37.png)
- 找到香港节点的内容, 点"云服务器"下方的数字
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/38.png)
- 这个页面就是最终要看的, 公网ip就是服务器的ip, 到时连接服务器会用到, 复制这个公网ip.
![](https://github.com/farmer-person/pictures/blob/master/buff-delivery/39.png)

至些, 租云服务器的步骤已经完成.

> END
- [下一章: 将软件部署到服务器](./last.md)
- [回到教程主页](./index.md)
