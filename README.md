# Pigeon
咕咕咕，咕咕咕咕咕？

一个轻量化的留言板 / 记事本 / 社交系统 / 博客，没有明确的作用定义，一切都随心所欲。

- 示例：https://nodepad.zeroteam.top/

> 上面链接为本人留言板，可以测试发布内容，无意义内容请设置仅自己可见，或者发布后删除，避免影响版面整洁。

## 简介
- 此版本为二开版
- 原作者项目 https://github.com/kasuganosoras/Pigeon

你是否有些临时的想法，或者一小段代码，想找一个地方记下来？

用博客来存，感觉有点大材小用；用 txt 来存，又怕搞丢。

那么这就是一个很好的东西了，你可以把这些零零散散的内容记下来，而不会忘记。

> 你可以把它当成微博、推特，也可以当成在线聊天软件，或者是纯粹拿来写文章，写代码记事用。

## 特性

- 支持 Markdown 语法
- 支持公开、登录可见、仅自己可见三种类型
- 使用 BCRYPT 散列储存密码
- 支持邮件验证
- 支持 reCaptcha 验证码
- 支持 Timeline 时间线，可以查看任意时间以前的内容
- 消息动态刷新，实时查看最新消息
- 支持 highlight.js 代码语法高亮
- 支持一键更新系统程序
- 支持自定义页面模板
- 支持每条消息在单独页面显示
- 支持编辑已发布的消息
- 使用QQ头像
- 支持昵称
## 安装

下载后使用浏览器访问`/install.php`

根据提示进行配置即可。


## 未来计划

- [x] 管理员后台系统（已实现）
- [ ] 支持 OAuth 登录
- [x] 完善的 API 系统
- [ ] 支持对接其他平台

## 关于 Admin Console

管理员后台的地址是：`/admin.php`

只有 root 和 admin 权限的用户可以访问管理员后台

您可以在管理员后台设置每个用户的信息，以及一键更新 Pigeon

## 开源协议

本项目使用 GPL v3 协议开源

## 捐助开发者

如果你觉得这个项目对你有帮助，欢迎赞助我

![img](https://i.imgur.com/1EuGD9o.png)
