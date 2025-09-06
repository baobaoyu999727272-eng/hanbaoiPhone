# Netlify部署配置

## 步骤1：注册Netlify
访问：https://netlify.com
使用GitHub账号登录

## 步骤2：连接私有仓库
1. 点击 "New site from Git"
2. 选择 GitHub
3. 选择您的私有仓库 hanbaoiPhone
4. 部署设置：
   - Branch: main
   - Build command: (留空)
   - Publish directory: (留空，因为是静态文件)

## 步骤3：部署
点击 "Deploy site"，几分钟后获得类似：
https://your-site-name.netlify.app

## 优势：
- ✅ 仓库可以保持私有
- ✅ 完全免费
- ✅ 自动部署（推送代码后自动更新网站）
- ✅ 可以自定义域名
- ✅ 支持HTTPS
