# 斯坦福说唱俱乐部网站部署指南

## 🚀 快速部署方法

### 方法一：GitHub Pages（推荐）

1. **创建GitHub仓库**
   ```bash
   # 在GitHub上创建新仓库：stanford-rap-club-website
   ```

2. **推送代码到GitHub**
   ```bash
   git remote add origin https://github.com/你的用户名/stanford-rap-club-website.git
   git branch -M main
   git push -u origin main
   ```

3. **启用GitHub Pages**
   - 进入仓库设置 → Pages
   - Source: Deploy from a branch
   - Branch: main, 文件夹: / (root)
   - 保存设置

4. **访问网站**
   - 网址：`https://你的用户名.github.io/stanford-rap-club-website`
   - 部署时间：2-5分钟

### 方法二：Netlify（最简单）

1. 访问 [netlify.com](https://netlify.com)
2. 注册/登录账号
3. 点击 "New site from Git"
4. 连接GitHub，选择仓库
5. 部署设置保持默认
6. 点击 "Deploy site"

### 方法三：Vercel（现代化）

1. 访问 [vercel.com](https://vercel.com)
2. 注册/登录账号
3. 点击 "New Project"
4. 导入GitHub仓库
5. 点击 "Deploy"

## 📝 自定义域名（可选）

### GitHub Pages
- 在仓库设置 → Pages → Custom domain
- 添加您的域名（如：stanfordrapclub.com）

### Netlify/Vercel
- 在项目设置中找到 "Domain settings"
- 添加自定义域名

## 🔧 更新网站

每次修改代码后：
```bash
git add .
git commit -m "更新描述"
git push
```

网站会自动更新（GitHub Pages可能需要几分钟）。

## 📱 网站功能

- ✅ 响应式设计，支持手机、平板、电脑
- ✅ 斯坦福红色主题
- ✅ 极简未来主义设计
- ✅ 表单自动发送邮件功能
- ✅ 平滑滚动和动画效果

## 🎯 网站链接

部署完成后，您将获得：
- **GitHub Pages**: `https://你的用户名.github.io/stanford-rap-club-website`
- **Netlify**: `https://随机名称.netlify.app`
- **Vercel**: `https://随机名称.vercel.app`

---

💡 **提示**: 推荐使用GitHub Pages，因为它是免费的，且与您的代码仓库集成良好。 