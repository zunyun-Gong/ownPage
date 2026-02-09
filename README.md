# Robben's Portfolio 🚀

一个炫酷动感的个人主页，使用纯 HTML/CSS/JavaScript 构建，支持 GitHub Pages 部署。

## ✨ 特性

- 🎨 **霓虹赛博朋克风格** - 渐变、发光效果、粒子动画
- 📱 **完全响应式** - 支持桌面、平板、手机
- ⚡ **流畅动画** - 滚动触发动画、打字机效果
- 🎮 **彩蛋** - 试试 Konami 代码 (↑↑↓↓←→←→BA)
- 🌐 **单页应用** - 平滑滚动导航
- 💼 **项目展示** - 卡片式布局，悬停效果
- 📊 **技能可视化** - 动态进度条
- 🔗 **社交链接** - GitHub、Twitter、LinkedIn、微信

## 🚀 部署到 GitHub Pages

### 方法一：自动部署（推荐）

1. **Fork 这个仓库** 或创建新仓库

2. **启用 GitHub Pages**：
   - 进入仓库 Settings → Pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main"，文件夹选择 "/ (root)"
   - 点击 Save

3. **等待部署**（约1-2分钟）

4. **访问网站**：
   ```
   https://你的用户名.github.io/仓库名
   ```

### 方法二：手动上传

1. 创建新 GitHub 仓库（如 `portfolio`）

2. 上传以下文件到仓库：
   - `index.html`
   - `style.css`
   - `script.js`

3. 启用 GitHub Pages（同上）

## 📝 自定义内容

### 修改个人信息

编辑 `index.html` 中的以下内容：

```html
<!-- 名字 -->
<h1 class="glitch" data-text="Robben">Robben</h1>

<!-- 邮箱 -->
<span>your.email@example.com</span>

<!-- 社交链接 -->
<a href="你的GitHub链接" class="social-link">
```

### 修改技能

在 `index.html` 中找到技能部分，修改：

```html
<div class="skill-item" data-percent="90">
    <span class="skill-name">你的技能</span>
</div>
```

### 修改项目

在 `index.html` 中找到项目部分：

```html
<div class="project-card">
    <h3>项目名称</h3>
    <p>项目描述</p>
    <!-- 修改链接 -->
    <a href="项目链接" class="project-link">
    <a href="GitHub链接" class="project-github">
</div>
```

### 修改颜色主题

编辑 `style.css` 中的 CSS 变量：

```css
:root {
    --primary: #00f5ff;    /* 主色调 */
    --secondary: #ff00ff;  /* 副色调 */
    --accent: #ffff00;     /* 强调色 */
    --dark: #0a0a0f;       /* 深色背景 */
}
```

## 🎨 颜色主题建议

| 风格 | Primary | Secondary | Accent |
|------|---------|-----------|--------|
| 赛博朋克 | `#00f5ff` | `#ff00ff` | `#ffff00` |
| 海洋蓝 | `#0066ff` | `#00ccff` | `#00ffcc` |
| 热情红 | `#ff3366` | `#ff0066` | `#ffcc00` |
| 森林绿 | `#00ff88` | `#00cc66` | `#ccff00` |
| 日落橙 | `#ff6b35` | `#f7931e` | `#ffd23f` |

## 📱 预览

在本地预览：

```bash
# 方法1：直接打开
open index.html

# 方法2：Python 简易服务器
cd portfolio
python -m http.server 8000
# 访问 http://localhost:8000

# 方法3：Node.js
npx serve
```

## 🛠️ 技术栈

- HTML5
- CSS3 (Flexbox, Grid, 动画)
- JavaScript (ES6+)
- Font Awesome 图标

## 📄 许可证

MIT License - 自由使用和修改

## 🙏 致谢

- 字体：系统字体栈
- 图标：[Font Awesome](https://fontawesome.com/)
- 灵感：赛博朋克美学

---

Made with 💙 and Code
