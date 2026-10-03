# 何柄岐的个人学术主页

这是何柄岐的个人学术主页源代码，基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 和 Jekyll 构建。

## 网站内容

- `_pages/about.md`：首页与个人简介
- `_pages/cv.md`：个人简历
- `_portfolio/`：研究项目
- `_data/navigation.yml`：顶部导航栏
- `_config.yml`：站点名称、作者资料、链接和构建配置
- `images/`：头像和网站图片

## 本地预览

安装 Ruby、Bundler 和项目依赖后，在仓库根目录运行：

```bash
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

然后访问 `http://127.0.0.1:4000`。

只生成静态 HTML 时运行：

```bash
bundle exec jekyll build
```

生成结果位于 `_site/`。

## 内容维护

研究项目使用 Markdown 文件维护。新增项目时，可复制 `_portfolio/` 中现有文件，并修改文件名、页面元数据和正文。没有实际内容的论文、报告、教学和博客栏目目前不发布；需要启用时，在对应 `_pages/` 文件中移除 `published: false`，并恢复导航入口。
