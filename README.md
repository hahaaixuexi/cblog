# 程 龙 - 个人技术博客 🚀

> AI & 计算机视觉方向 · 2026 届应届毕业生

[![GitHub](https://img.shields.io/badge/GitHub-hahaaixuexi%2Fcblog-black?logo=github)](https://github.com/hahaaixuexi/cblog) [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)]() [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)]() [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)]()

## ✨ 简介

这是一个纯 **HTML + CSS + JavaScript** 实现的单页面个人技术博客，无需任何构建工具或后端服务，直接打开 `index.html` 即可运行。

- 🎨 精心设计的 UI，支持**亮色 / 暗色模式**切换
- 📱 全响应式布局，适配桌面端、平板、手机
- ⚡ 首屏加载快，无框架依赖
- 🔍 技术栈卡片交互式展示，点击查看详细命令速查

## 📸 预览

| 亮色模式 | 暗色模式 |
|:---:|:---:|
| （截图） | （截图） |

> 💡 在线访问：[GitHub Pages](https://hahaaixuexi.github.io/cblog/) 或通过 EdgeOne 自定义域名访问

## 🛠️ 技术栈

本博客自身使用的技术：

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构 |
| CSS3 | 样式、动画、响应式布局、暗色模式 |
| JavaScript (原生) | 交互逻辑：弹窗、阅读进度条、滚动动画、代码高亮 |

博客内容覆盖的技术领域：

`Linux` `MySQL` `Git` `Python` `YOLO` `C++` `Docker` `香橙派` `XShell`

## ✅ 功能特性

### 页面功能

- **Hero 区域** — 渐变文字头像 + 脉冲动画 + 网格背景装饰
- **技术文章板块** — 6 篇文章卡片，点击展开完整内容（含代码示例）
- **教育经历时间线** — 可视化时间轴展示学历信息
- **项目经历** — 左侧彩色装饰条的项目卡片
- **技术栈网格** — 9 个技术卡片，点击弹窗查看命令速查手册
- **导航栏** — 毛玻璃效果 + 滚动时阴影变化 + 自动高亮当前位置
- **阅读进度条** — 页面顶部显示当前阅读进度

### 交互细节

- 🌙 一键切换亮色 / 暗色主题
- 📖 文章阅读时长估算（"约 X 分钟阅读"）
- 🏷️ 代码块自动语言检测标签（Python / SQL / C++ / Bash / Git / Docker）
- 📋 代码块一键复制按钮
- 🔤 代码块语法高亮（One Dark 配色方案）
- 🔗 社交分享按钮（微博 / Twitter / 复制链接）
- ↩️ 返回顶部按钮（滚动后出现）
- ♿ 无障碍支持（Skip-link 键盘跳转、文章卡片可 Tab 聚焦 + 回车打开、弹窗关闭后不残留焦点）
- 🎯 文章卡片按 `data-article-id` 绑定内容，不再依赖 DOM 顺序

### SEO 与性能

- ✅ Semantic HTML 语义化标签
- ✅ Open Graph + Twitter Card 元数据
- ✅ 内联 SVG Favicon（零请求）
- ✅ Canonical URL（指向真实可访问的 GitHub Pages 地址）
- ✅ JSON-LD 结构化数据（Person Schema）
- ✅ robots.txt + sitemap.xml
- ✅ 系统字体栈，无需网络字体请求（零外部字体请求）

## 📂 目录结构

```
cblog/
├── index.html          # 博客主文件（单文件：HTML + CSS + JS 全在里面）
├── og-cover.png        # 社交分享封面（1200×630，Open Graph 用）
├── robots.txt          # 搜索引擎抓取规则
├── sitemap.xml         # 站点地图
└── README.md           # 本文件
```

主体仍然是单个自包含的 `index.html`，其余三个是部署用的静态资源，不参与页面渲染逻辑。

## 🚀 本地运行

```bash
# 方式一：直接双击 index.html 在浏览器中打开

# 方式二：用本地服务器（推荐，避免部分浏览器安全限制）
# Python
python -m http.server 8080
# 然后访问 http://localhost:8080

# Node.js
npx serve .
# 然后访问 http://localhost:3000
```

## ☁️ 部署

### GitHub Pages

1. Fork 或 Clone 本仓库
2. 将修改后的 `index.html` 推送到 `main` 分支
3. 进入仓库 Settings → Pages → Source 选 `Deploy from a branch` → Branch 选 `main` → Save
4. 几分钟后即可通过 `https://你的用户名.github.io/cblog/` 访问

### 腾讯云 EdgeOne（CDN 加速）

1. 在腾讯云控制台创建 EdgeOne 站点
2. 源站地址配置为 GitHub Pages 地址
3. 绑定自定义域名，CNAME 指向 EdgeOne 分配的地址
4. 开启 HTTPS 和缓存优化

详细配置步骤见仓库 Wiki 或联系作者。

## 🔄 更新博客

```bash
# 1. 克隆仓库（如果还没有）
git clone https://github.com/hahaaixuexi/cblog.git
cd cblog

# 2. 修改 index.html（用编辑器直接改，或用我帮你改）

# 3. 提交并推送
git add index.html
git commit -m "更新了什么内容"
git push origin main

# 4. GitHub Pages 会自动部署（通常 1~2 分钟生效）
```

## 📝 文章列表

单页博客，点文章卡片即可在弹窗中阅读全文（下方链接跳到站内「技术文章」区块）。

| # | 日期 | 分类 | 标题 |
|---|:----:|:----:|------|
| 1 | 2026-10-09 | AI 工具 | [主流 Agent 工具介绍](#articles) |
| 2 | 2026-10-09 | 大模型 | [国内外主流大模型介绍](#articles) |
| 3 | 2026-06-15 | 计算机视觉 | [YOLO11 在边缘设备上的部署实践](#articles) |
| 4 | 2026-05-20 | 视觉检测 | [VisionPro 新手入门：从零搭建硬币检测系统](#articles) |
| 5 | 2026-04-08 | Linux | [AI 开发者必备的 Linux 命令行技巧](#articles) |
| 6 | 2026-03-12 | 数据库 | [MySQL 实用速查：数据类型、常用语句与增删改查](#articles) |

## 👤 关于作者

**程龙** — 河南工学院 · 人工智能专业 · 2026 届

专注于计算机视觉与 AI 应用开发，具备从模型训练到边缘部署的完整工程能力。

📧 cheng66da@163.com

## 📄 License

MIT License — 自由使用、修改、分发。

---

<p align="center">
  Built with ❤️ using pure HTML/CSS/JS · No frameworks, no build tools, no dependencies.
</p>
