# 个人简历网页

这是一个现代化的个人简历网站，采用HTML、Tailwind CSS和JavaScript开发，具有响应式设计和精美的动画效果。

## 功能特点

- 🎨 现代美观的UI设计，蓝色为主色调
- 📱 完全响应式，适配各种设备屏幕
- ✨ 丰富的动画效果和交互体验
- 📋 完整展示个人信息、技能、工作经历、项目经验等
- 📱 移动端友好的导航菜单

## 技术栈

- HTML5
- Tailwind CSS v3
- JavaScript
- Font Awesome 图标库

## 本地预览

1. 确保安装了Python
2. 在项目根目录运行：
   ```bash
   python3 -m http.server 8000
   ```
3. 打开浏览器访问 http://localhost:8000

## 部署到 Vercel

### 方法一：使用 Vercel CLI（推荐）

1. **安装 Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **登录 Vercel**
   ```bash
   vercel login
   ```
   按照提示完成登录。

3. **部署项目**
   在项目根目录运行：
   ```bash
   vercel
   ```

4. **按照提示配置部署**
   - 确认项目目录：输入 `y`
   - 设置团队/个人：选择个人账号
   - 确认部署：输入 `y`

5. **完成部署**
   部署成功后，Vercel会提供一个预览URL。

### 方法二：通过 GitHub + Vercel 网站

1. **创建 GitHub 仓库**
   - 在 GitHub 上创建一个新仓库
   - 将本地代码推送到 GitHub

2. **连接 Vercel**
   - 访问 [Vercel 官网](https://vercel.com)
   - 注册/登录账号
   - 点击 "New Project"
   - 连接你的 GitHub 账号
   - 选择你的简历仓库

3. **配置部署**
   - 配置保持默认即可
   - 点击 "Deploy"

4. **获取部署链接**
   部署完成后，Vercel会提供一个公开的URL。

## 自定义修改

- 修改 `index.html` 中的个人信息、工作经历等内容
- 在 `<style>` 标签中调整颜色方案和动画效果
- 替换 `tailwind.config` 中的主题配置

## 注意事项

- 确保更新个人联系方式信息
- 可以根据需要添加个人照片
- 部署前检查所有链接是否正常工作