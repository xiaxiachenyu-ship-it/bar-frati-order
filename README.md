# BAR FRATI 中意双语点餐系统（测试版）

## 本地启动
安装 Node.js LTS，在本目录运行：

```
npm install
npm start
```

前台：http://localhost:3000/#front
后厨：http://localhost:3000/#kitchen
菜单管理：http://localhost:3000/#admin

## 免费云端测试
将解压后的文件上传 GitHub 私有仓库，Render 新建 Node Web Service，Build Command `npm install`，Start Command `npm start`。Render 会分配 HTTPS 网址；后厨访问 `网址/#kitchen`。

## 注意
这是**测试版**：没有登录验证，任何知道网址的人都可能查看订单、修改菜单。请勿用于真实营业或存储客户个人资料。订单写入 `data.json`，Render 免费服务的文件系统不持久，重启或部署可能丢失订单。正式使用需要登录鉴权、持久数据库、备份及稳定实例。

菜品为 8 类、32 道（不含饮料）；主食（白米饭除外）可加肉或虾 +€1。
