# 专注喵网站部署到 GitHub Pages 指南

## 📋 第一步：在 GitHub 上创建仓库

1. 访问 https://github.com 并登录你的账号（如果没有账号，先注册一个）

2. 点击右上角的 "+" 按钮，选择 "New repository"

3. 填写仓库信息：
   - Repository name: `focus-cat`（或其他你喜欢的名字）
   - Description: 专注喵 - 学生党自律外挂
   - 选择 "Public"（公开仓库才能使用免费的 GitHub Pages）
   - ❌ 不要勾选 "Add a README file"（我们已经有了）

4. 点击 "Create repository"

## 📤 第二步：推送代码到 GitHub

复制 GitHub 给你的仓库地址（类似：https://github.com/你的用户名/focus-cat.git）

然后在命令行中执行：

```bash
cd F:\pando\others
git remote add origin https://github.com/你的用户名/focus-cat.git
git branch -M main
git push -u origin main
```

## 🌐 第三步：启用 GitHub Pages

1. 在你的 GitHub 仓库页面，点击 "Settings"（设置）

2. 在左侧菜单找到 "Pages"

3. 在 "Branch" 部分：
   - 选择 "main" 分支
   - 文件夹选择 "/ (root)"
   - 点击 "Save"

4. 等待几分钟，GitHub 会自动部署你的网站

5. 部署完成后，会显示你的网站地址：
   ```
   https://你的用户名.github.io/focus-cat/
   ```

## 📱 第四步：访问你的网站

- 首页（排行榜）：`https://你的用户名.github.io/focus-cat/focus-cat-leaderboard.html`
- 商品详情页：`https://你的用户名.github.io/focus-cat/product-detail.html`

## 🔄 第五步：生成二维码

获得网站地址后，使用以下任一方式生成二维码：

### 方式1：在线二维码生成器
- https://cli.im/（草料二维码）
- https://www.wwei.cn/（微微二维码）
- https://qr.ioi.tw/（免费二维码生成器）

### 方式2：我会帮你在商品详情页添加分享二维码功能

把你的网站地址告诉我，我会自动在页面上添加二维码展示。

## ❓ 遇到问题？

- 确保仓库是 Public（公开）
- 等待3-5分钟让 GitHub Pages 完成部署
- 检查分支名称是否正确（main 或 master）
- 确保文件名正确（HTML 文件必须以 .html 结尾）

## 🎉 完成后

你就可以通过二维码分享商品详情页了！任何人扫码都能访问你的网站。
