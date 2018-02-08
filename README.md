#
vue模板构建工具cdkj-cli

> 传达科技前端构建工具，用于快速构建统一、规范的前端项目初始化模板，包括微信H5端、PC端。后期可根据项目实际需求，考虑集成其它模板配置功能。

版本记录：
- v1.0.0 npm发布构建工具和微信通用模板wx

### github项目维护地址

> 账号： cdkj
> 密码： c\*\*\*\*\*\*1
> 注：如需修改和维护代码，请重新注册账号，以开发者身份接入

构建工具地址：
> [https://github.com/cdkj-frontend/cdkj-cli](https://github.com/cdkj-frontend/cdkj-cli)

微信模板地址：
> [https://github.com/cdkj-frontend/init-template-wx.git](https://github.com/cdkj-frontend/init-template-wx.git)

### 使用方法

通过npm包管理安装使用本工具：

#### 安装

如遇到提示版本问题，请更新到node版本8.x

```
$ npm install -g cdkj-frontend-cli
```

#### 使用

```
$ cdkj init <template-name> <project-name>
```

举例：

```
$ cdkj init wx distribution // 以微信模板建立distribution项目
```

注： 目前包含所有vue官方模板（可通过cdkj list进行查看）,自定义模板暂定包含两项：wx、pc。
