<p>
  <img height="70" src="./assets/logo.png" />
</p>

Doraemon
---

Doraemon 基于 Github Issues 的博客生成器。

使用简单，只需要更改下配置，使用 Github pages 就可以快速搭建出自己的博客。

依赖 **node 6** 或更高版本

> [使用 Doraemon 的博客列表](https://github.com/gongchao/Doraemon/issues/1)

## 使用方法

> 创建一个仓库

如: gongchao/Doraemon

> 获取 token

这里获取 [token](https://github.com/settings/tokens/new)

⚠️ token，的权限只需要勾选以下两个，即可

- read: user Read all user profile data
- user: email Access user email addresses (read-only)

> 安装依赖

```bash
npm install
```

> 更改配置，根目录下的 config.yml

| 属性 | 说明 |
| ---- | ---- |
| title | 网站标题 |
| url | 网站域名 |
| repository | Blog 的仓库地址，以 ``username/repository`` 方式填写 |
| token | token |
| date_format | 日期格式 |
| time_format | 时间格式 |
| per_page | 每页显示的 Issues 数量 |
| theme | 当前使用的主题，对应 ``themes`` 目录里的文件夹 |
| output_dir | 编译后的输出文件夹 |

> 编译

```bash
npm run build
```

> 如果是本地开发模式

```bash
npm run dev
```

默认会启动 5000 端口，访问 http://localhost:5000/ 进行预览

## 主题

目前只有 ``default`` 一个模版，非常欢迎将您的主题共享

## 开发日志

- 多用户支持
- 分类标签
- ~~多 Theme 支持 [2018/4/1]~~
- ~~基础的文章展示 [2018/4/1]~~

## 类似项目

- [Mirror](https://github.com/LoeiFy/Mirror)
- [BGAIssueBlog](https://github.com/bingoogolapple/BGAIssueBlog)

## 许可

MIT License (MIT)

