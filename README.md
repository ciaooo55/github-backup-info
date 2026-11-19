# GitHub仓库源码备份 · 应用说明

此公开仓库托管个人自用备份工具的应用说明、隐私政策及样式，通过 GitHub Pages 发布。

## 在线页面

- [应用首页](https://ciaooo55.github.io/github-backup-info/)
- [隐私政策](https://ciaooo55.github.io/github-backup-info/privacy.html)

Google OAuth 控制台引用以上两个网址，分别作为应用首页和隐私政策地址，**请勿更改这两个网址**。

## 与备份仓库的关系

实际备份程序位于私有仓库 `ciaooo55/github-cloud-backup`，负责将自有 GitHub 仓库备份到 Google Drive。本仓库只是公开说明站点，不包含备份程序代码、授权配置、凭证或实际备份数据；页面文件不承担备份任务。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `index.html` | 应用首页，介绍工具用途、工作方式及权限 |
| `privacy.html` | 隐私政策，说明数据访问、保存、删除与撤销授权 |
| `style.css` | 页面共用样式 |
| `.nojekyll` | 告知 GitHub Pages 不使用 Jekyll 处理站点 |

## 更新页面

1. 编辑需要更新的 `index.html`、`privacy.html` 或 `style.css`，保持说明与实际行为一致，勿写入凭证或私有备份内容。
2. 提交修改并推送到 `main` 分支，GitHub Pages 会自动部署。
3. 部署后访问上方两个网址检查内容和链接；保留现有路径，避免破坏 Google OAuth 控制台引用。

## 联系方式

维护者邮箱：[g.ciaooo55@gmail.com](mailto:g.ciaooo55@gmail.com)。
