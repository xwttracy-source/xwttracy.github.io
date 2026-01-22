# 课题组网站

这是一个使用 Vanilla Web Development（纯 HTML/CSS/JavaScript）开发的课题组官方网站，符合 GitHub Pages 部署要求。

## 功能特性

- ✅ **响应式设计** - 完美适配桌面、平板和移动设备
- ✅ **现代化 UI** - 简洁美观的用户界面
- ✅ **四个主要页面**：
  - 主页（近期科研进展）
  - 成员介绍页
  - 工作成果页
  - 完整 News 页
- ✅ **交互功能** - 成果筛选、移动端菜单、平滑滚动等
- ✅ **GitHub Pages 兼容** - 可直接部署到 GitHub Pages

## 文件结构

```
.
├── index.html          # 主页
├── members.html        # 成员介绍页
├── publications.html   # 工作成果页
├── news.html          # News 页
├── css/
│   └── style.css      # 样式文件
├── js/
│   └── main.js        # JavaScript 交互
└── README.md          # 说明文档
```

## 使用方法

### 本地预览

1. 克隆或下载此仓库
2. 直接在浏览器中打开 `index.html`，或使用本地服务器：
   ```bash
   # 使用 Python
   python -m http.server 8000
   
   # 使用 Node.js (需要安装 http-server)
   npx http-server
   ```
3. 在浏览器中访问 `http://localhost:8000`

### 部署到 GitHub Pages

1. 将代码推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择主分支（通常是 `main` 或 `master`）
4. 访问 `https://你的用户名.github.io/xwttracy.github.io/`

## 自定义内容

### 修改课题组信息

- **主页内容**：编辑 `index.html` 中的科研进展部分
- **成员信息**：编辑 `members.html` 中的成员卡片
- **工作成果**：编辑 `publications.html` 中的论文和成果列表
- **新闻动态**：编辑 `news.html` 中的新闻条目

### 修改样式

- 编辑 `css/style.css` 中的 CSS 变量来改变主题颜色：
  ```css
  :root {
      --primary-color: #2563eb;  /* 主色调 */
      --primary-dark: #1e40af;   /* 深色主色调 */
      /* ... */
  }
  ```

### 修改交互功能

- 编辑 `js/main.js` 来添加或修改交互功能

## 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和响应式设计
- **Vanilla JavaScript** - 纯 JavaScript，无框架依赖

## 浏览器支持

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 许可证

MIT License

## 联系方式

如有问题或建议，请通过邮件联系。
