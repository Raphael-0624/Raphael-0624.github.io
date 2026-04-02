# Rockelbel.github.io

我的个人主页与简历展示站点，基于 GitHub Pages + Jekyll 构建。

🌐 **在线访问**: https://rockelbel.github.io

## 🎨 主题

使用 Jekyll 官方主题：[Slate](https://github.com/pages-themes/slate)

- 深色风格设计
- 响应式布局
- 代码高亮支持

## 🚀 本地开发

### 环境要求

- Ruby 2.5+
- Bundler

### 安装依赖

```bash
bundle install
```

### 本地预览

```bash
bundle exec jekyll serve
```

访问 http://localhost:4000 预览

## 📁 项目结构

```
├── _config.yml          # Jekyll 配置
├── index.md             # 主页内容
├── about.md             # 关于页面
├── _posts/              # 博客文章
├── _layouts/            # 页面布局
├── assets/              # 静态资源
│   ├── css/
│   └── images/
└── README.md
```

## ✏️ 内容更新

### 修改个人信息

编辑 `index.md` 更新主页内容：

```markdown
# 你的名字

## 关于我
...个人简介...

## 工作经历
...工作履历...

## 项目作品
...项目展示...
```

### 发布博客文章

在 `_posts/` 目录创建新文件，命名格式：

```
YYYY-MM-DD-title.md
```

文章头部格式：

```markdown
---
layout: post
title: "文章标题"
date: YYYY-MM-DD HH:MM:SS +0800
categories: category
---

文章内容...
```

## 📝 待办事项

- [ ] 完善个人简历内容
- [ ] 添加项目作品展示
- [ ] 配置自定义域名
- [ ] 添加访客统计

## 📄 许可证

MIT License

---

> 使用 GitHub Pages 免费托管，每次推送到 main 分支自动部署。
