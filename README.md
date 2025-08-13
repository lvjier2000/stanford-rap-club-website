# 斯坦福说唱俱乐部网站

这是一个为斯坦福说唱俱乐部设计的现代化网站，包含响应式设计和丰富的交互功能。

## 功能特点

- 🎨 现代化设计，采用渐变色彩和动画效果
- 📱 完全响应式，支持手机、平板和桌面设备
- 🎵 音乐可视化器动画
- 📊 数字统计动画效果
- 📝 联系表单功能
- 🎯 平滑滚动导航
- 🌟 悬停效果和交互动画

## 如何查看网站

### 方法一：直接在浏览器中打开
1. 在文件管理器中找到 `index.html` 文件
2. 双击文件，它会在默认浏览器中打开
3. 或者右键点击文件，选择"用浏览器打开"

### 方法二：使用本地服务器（推荐）
如果你有Python环境：
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

然后在浏览器中访问：`http://localhost:8000`

### 方法三：使用Node.js
如果你有Node.js环境：
```bash
# 安装http-server
npm install -g http-server

# 启动服务器
http-server
```

## 文件结构

```
├── index.html      # 主页面文件
├── styles.css      # 样式文件
├── script.js       # JavaScript交互文件
└── README.md       # 说明文档
```

## 网站内容

- **首页**：展示俱乐部介绍和加入按钮
- **关于我们**：俱乐部历史和统计数据
- **活动**：即将举行的活动列表
- **成员**：核心成员介绍
- **联系我们**：联系方式和留言表单

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, 动画)
- JavaScript (ES6+)
- 响应式设计
- 现代浏览器API

## 浏览器兼容性

支持所有现代浏览器：
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 自定义修改

你可以根据需要修改以下内容：
- 在 `index.html` 中修改文字内容
- 在 `styles.css` 中调整颜色和样式
- 在 `script.js` 中添加新的交互功能

## 部署建议

要将网站部署到线上，你可以：
1. 使用GitHub Pages
2. 上传到任何Web服务器
3. 使用Netlify、Vercel等静态网站托管服务

---

© 2024 斯坦福说唱俱乐部 