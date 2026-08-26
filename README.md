https://www.yang.636.ltd/
可以看












# 🧭 StartHere · 个人导航站

> 一个功能丰富的个人导航站，集搜索、工具、游戏、天气、日历于一体。

[![Website](https://img.shields.io/badge/网站-www.yang.636.ltd-0078d4?style=flat-square&logo=google-chrome)](https://www.yang.636.ltd)
[![GitHub](https://img.shields.io/badge/GitHub-yangmaoamo45/StartHere-181717?style=flat-square&logo=github)](https://github.com/yangmaoamo45/StartHere)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

---

## 📖 简介

**StartHere** 是一个简洁、美观、功能丰富的个人导航站，旨在提供一个快速的上网入口。集成了多引擎搜索、热门直达、在线游戏、实用工具、天气日历等功能，并支持深色/浅色模式，移动端完全自适应。

🔗 **在线访问**：[https://www.yang.636.ltd](https://www.yang.636.ltd)

---

## ✨ 功能特色

### 🔍 搜索三合一
- 🌐 **网页搜索**：跳转到选中的搜索引擎（必应、百度、Google、搜狗、360搜索）
- 📊 **聚合搜索**：同时打开多个搜索引擎的搜索结果
- 📁 **站内搜索**：实时搜索热门词条和游戏名称

### 🎮 游戏中心
- 收录 6 款小游戏（Scratch 作品、几何冲刺、抽奖机等）
- 点击游戏名称即可在页面内直接运行
- 游戏列表支持展开/收起

### 🔧 工具矩阵
- 🔑 密码生成器
- 📱 二维码生成器（独立页面）
- ⏱️ 时间戳转换
- 📝 正则表达式测试

### 🌤️ 信息模块
- **天气**：通过 iframe 嵌入 wttr.in，支持城市切换
- **日历**：可翻页查看日期，今日高亮
- **数据看板**：显示已收录站点数、本周新增、累计访问量、反馈数

### 📂 文件查看器
- 支持图片、文本、PDF、ZIP 压缩包浏览
- 压缩包可解压并预览内部文件
- 所有文件仅在浏览器本地处理

### 🧮 数学实验
- 数字黑洞 6174
- 莫比乌斯环（Three.js 3D 渲染）
- 徒手测 π
- 折纸指数增长

### 💬 反馈系统
- 用户提交反馈（功能建议/报错/收录申请/修改建议）
- 反馈数据保存在浏览器本地
- 支持导出/清空反馈记录
- 修改建议可直接跳转 GitHub 编辑页面

### 🎨 界面设计
- 毛玻璃效果 + 深色/浅色模式
- 三栏布局（搜索居中，工具/信息分列两侧）
- 移动端完全自适应

---

📁 项目结构
| 文件 | 路径 | 说明 |
|------|------|------|
| 导航首页 | / | 搜索三合一、游戏中心、工具矩阵、天气日历、深色模式、反馈系统 |
| 关于作者 |  /about.html | 个人简介、头像、技能标签、联系方式一键复制 |
| 使用指南 | /wiki.html | 功能介绍、常见问题、动态加载更新日志(Marked.js) |
| 项目展示 | /projects.html | 开源项目列表展示 |
| 文件查看器 | /fileview.html | 图片/文本/PDF预览、ZIP解压浏览（JSZip） |
| 数学实验 | /math.html | 数字黑洞、莫比乌斯环（Three.js）、测π、折纸指数增长 |
| 二维码生成 | /qr.html | 二维码生成器（独立页面） |
| 更新日志 | /changelog.md | 版本更新记录，wiki.html 动态加载 |
| 站点地图 | /sitemap.xml | 搜索引擎收录配置 |
| 站点图标 | /favicon.ico | 浏览器标签页图标 |
| 头像 | /66.png | 作者头像图片 |
| 自定义域名 | /CNAME | 绑定 www.yang.636.ltd |
| 项目说明 | /README.md | 项目文档 |
| 游戏目录 | /games/ | 6 款 HTML 小游戏 |

text

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构 |
| CSS3 | 样式设计（毛玻璃效果、深色模式） |
| JavaScript | 交互逻辑 |
| Three.js | 莫比乌斯环 3D 渲染 |
| JSZip | ZIP 文件解压 |
| Marked.js | Markdown 渲染（维基页面） |
| GitHub Pages | 静态托管 |
| Cloudflare | CDN 加速（可选） |

---

## 🚀 部署

### 通过 GitHub Pages（推荐）

1. Fork 本仓库
2. 在仓库 Settings → Pages 中启用 GitHub Pages
3. 选择 `main` 分支，根目录 `/`
4. 绑定自定义域名（可选）

### 自定义域名配置

在仓库根目录创建 `CNAME` 文件，内容为：
www.yang.636.ltd

text

在域名 DNS 管理中添加 CNAME 记录指向 `yangmaoamo45.github.io`。

---

## 📱 响应式支持

- 桌面端（>820px）：三栏并排
- 平板端（680-820px）：比例自适应
- 手机端（<680px）：单栏布局，搜索框置顶

---

## 📌 页面导航

| 页面 | 地址 | 说明 |
|------|------|------|
| 导航首页 | `/` | 主入口 |
| 关于作者 | `/about.html` | 个人简介 |
| 使用指南 | `/wiki.html` | 功能介绍 + 更新日志 |
| 项目展示 | `/projects.html` | 开源项目列表 |
| 文件查看器 | `/fileview.html` | 本地文件预览 |
| 数学实验 | `/math.html` | 交互式数学演示 |
| 二维码生成 | `/qr.html` | 二维码生成器 |

---

## 📝 更新日志

详见 [`changelog.md`](changelog.md)

---

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建您的分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

---

## 📄 许可证

本项目采用 **MIT License** 开源协议。

---

## 👤 作者

**Yang Mao mao**

- GitHub: [@yangmaoamo45](https://github.com/yangmaoamo45)
- B站: [杨茂茂玩游戏](https://space.bilibili.com/3546946251786558)

---

## 🙏 致谢

- [wttr.in](https://wttr.in) - 天气数据
- [Three.js](https://threejs.org) - 3D 渲染
- [marked.js](https://marked.js.org) - Markdown 渲染
- [JSZip](https://stuk.github.io/jszip/) - ZIP 文件解压

---

⭐ 如果这个项目对你有帮助，欢迎 Star！
