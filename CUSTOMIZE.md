# 定制与发布

## 1. 修改个人信息

编辑 `_config.yml`：

- 将 `YOUR-USERNAME` 全部替换为你的 GitHub 用户名；
- 修改姓名、邮箱、学校、个人简介和学术主页链接；
- 将头像保存为 `images/profile.png`。

修改 `_config.yml` 后，本地预览必须重启 Jekyll。

## 2. 修改首页内容

- 个人介绍：`_pages/about.md`
- 研究方向：`_data/research.yml`
- 教育和工作经历：`_data/experience.yml`
- 顶部导航：`_data/navigation.yml`

## 3. 添加论文

复制 `_publications` 中任意一个 Markdown 文件，修改文件名和 front matter。`category` 使用：

- `manuscripts`：期刊论文
- `conferences`：会议论文

可选链接字段为 `paperurl`、`codeurl` 和 `videourl`。

## 4. 发布到 GitHub Pages

1. 在 GitHub 新建公开仓库，名称必须是 `YOUR-USERNAME.github.io`。
2. 将本目录内容推送至仓库的 `master` 或 `main` 分支。
3. 打开仓库 `Settings → Pages`，确认网站已部署。
4. 访问 `https://YOUR-USERNAME.github.io`。

## 5. 本地预览

安装 Ruby、Bundler 后执行：

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

访问 `http://localhost:4000`。
