# 数字时钟番茄钟

一个简洁美观的在线番茄钟应用，带有数字时钟显示和励志语录功能。

## 部署方案推荐

由于这是一个纯静态的前端应用，可以选择以下几个优质的静态网站托管平台进行部署：

### 1. Vercel（推荐）

- 优点：
  - 全球 CDN，访问速度快
  - 自动 HTTPS
  - 持续部署
  - 免费额度大
  - 操作简单

部署步骤：
1. 注册 Vercel 账号
2. 将代码推送到 GitHub
3. 在 Vercel 中导入 GitHub 仓库
4. 自动完成部署

### 2. Netlify

- 优点：
  - 全球 CDN
  - 自动 HTTPS
  - 持续部署
  - 有免费额度

### 3. GitHub Pages

- 优点：
  - 完全免费
  - 可靠稳定
  - 适合小型项目

### 4. Cloudflare Pages

- 优点：
  - 超快的全球 CDN
  - 自动 HTTPS
  - 持续部署
  - 免费额度大

## 推荐使用 Vercel 部署

1. 创建 Git 仓库：
```bash
git init
git add .
git commit -m "Initial commit"
```

2. 推送到 GitHub：
- 在 GitHub 创建新仓库
- 按照 GitHub 提示推送代码

3. Vercel 部署：
- 访问 [Vercel](https://vercel.com)
- 使用 GitHub 账号登录
- 点击 "Import Project"
- 选择 GitHub 仓库
- 点击 "Deploy"

部署完成后，Vercel 会自动分配一个域名，您也可以绑定自己的自定义域名。