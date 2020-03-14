### 为加载图片而做的准备工作

考虑到大家加载不出来图片, 所以这里就不放图片了, 单纯文字描述.

- 按`Win + E`打开"**我的计算机**"
- 依次打开目录"**c:\Windows\System32\drivers\etc**", 看到**host**文件
- **右键host文件**, 选择"**属性**"
- 依次点击"**安全**", "**编辑**"
- 点击上面的"**User**", 然后再把下面全部的**允许**勾上
- "**确定**", "**确定**"
- 用**记事本**打开**host文件**, 将以下内容全复制, 追加到文件后面, **保存**
- ok, 现在应该是可以加载图片了 :v:

```
151.101.184.133 raw.githubusercontent.com
151.101.184.133 gist.githubusercontent.com
151.101.184.133 cloud.githubusercontent.com
151.101.184.133 camo.githubusercontent.com
151.101.184.133 avatars0.githubusercontent.com
151.101.184.133 avatars1.githubusercontent.com
151.101.184.133 avatars2.githubusercontent.com
151.101.184.133 avatars3.githubusercontent.com
151.101.184.133 avatars4.githubusercontent.com
151.101.184.133 avatars5.githubusercontent.com
151.101.184.133 avatars6.githubusercontent.com
151.101.184.133 avatars7.githubusercontent.com
151.101.184.133 avatars8.githubusercontent.com
```

> END
- [返回程教主页](./index.md)
