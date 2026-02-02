# 联想菜鸟工具箱 v3.0 官方网站

这是联想菜鸟工具箱 v3.0 的官方网站项目，包含主页、功能文档和下载功能。

## 🌐 在线访问

访问地址：`https://你的用户名.github.io/你的仓库名/`

## 📁 项目结构

```
website/
├── index.html          # 主页
├── docs.html           # 功能文档页
├── images/             # 截图资源
│   └── screenshot-*.png
├── 联想菜鸟工具箱.exe   # 工具箱程序
└── README.md           # 说明文档
```

## ✨ 功能特点

- 🎨 现代化渐变背景设计
- 🌊 动态粒子背景效果
- 📱 完全响应式布局
- ⚡ 流畅的动画效果
- 📥 一键下载功能
- 📖 详细的功能文档

## 🚀 部署到 GitHub Pages

### 方法一：通过 GitHub 网页操作（推荐新手）

1. 在 GitHub 创建新仓库（例如：`uotan-toolbox-website`）
2. 上传 `website` 文件夹中的所有文件
3. 将根目录的 `联想菜鸟工具箱.exe` 也上传到仓库
4. 进入仓库 Settings → Pages
5. Source 选择 `main` 分支，文件夹选择 `/ (root)`
6. 点击 Save，等待几分钟即可访问

### 方法二：通过 Git 命令行（推荐开发者）

```bash
# 1. 初始化 Git 仓库
cd website
git init

# 2. 添加所有文件
git add .

# 3. 提交
git commit -m "Initial commit: 联想菜鸟工具箱官网"

# 4. 关联远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/你的用户名/你的仓库名.git

# 5. 推送到 GitHub
git branch -M main
git push -u origin main

# 6. 在 GitHub 仓库设置中启用 Pages
```

## 📥 下载功能说明

网站的"立即下载"按钮会自动下载 `联想菜鸟工具箱.exe` 文件。

**重要提示：**
- 确保 `联想菜鸟工具箱.exe` 文件已上传到仓库根目录
- 下载路径配置在 `index.html` 中的 `downloadBtn` 点击事件
- 大文件（>100MB）建议使用 GitHub Releases 功能

## 🔧 本地测试

直接用浏览器打开 `index.html` 即可预览效果。

## 📝 更新网站

修改文件后，重新提交到 GitHub：

```bash
git add .
git commit -m "更新说明"
git push
```

GitHub Pages 会自动重新部署，通常需要 1-5 分钟生效。

## 🌟 技术栈

- HTML5 + CSS3
- Tailwind CSS (CDN)
- 原生 JavaScript
- 响应式设计

## 📄 许可证

本项目基于开源协议发布。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

© 2026 联想菜鸟工具箱 v3.0
