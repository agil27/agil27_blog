# 个人主页说明
##开发平台

操作系统：Windows 10 x64

浏览器：Chrome 75.0

编辑器：VSCode

## 过程简介

#### Github Pages申请

在Github上申请一个账号，然后注册仓库为`username.github.io`，克隆到本地后即可进行编辑。

我注册的账号名称为`agil27`，所以相应的仓库名称为`agil27.github.io`.

#### 网页内容的构建

使用HTML语言，快速搭建出网站的内容，此时个人主页如下

![raw](/img/raw.jpg)

#### 网页布局的更改

运用css设置了padding，margin，background，font等属性，使得网页布局大致美观，如下

![dec](C:\Users\dashwood\Documents\GitHub\agil27.github.io\img\dec.jpg)

#### 增加边栏 · 更改博客文章样式 · 添加社交icon

基本成型了，还增加了transition和hover动画，利用iconfont+unicode实现了可以点击的矢量图标功能

![full](C:\Users\dashwood\Documents\GitHub\agil27.github.io\img\full.jpg)

#### 移动适配性

利用`@media`命令更改布局，在宽度小于1015px时侧边栏放置于下方显示。

![mobile](C:\Users\dashwood\Documents\GitHub\agil27.github.io\img\mobile.jpg)