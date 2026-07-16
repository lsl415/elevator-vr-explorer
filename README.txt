电梯 VR 项目分享说明
====================

方案一：直接发送单文件（无需网络、无需安装）

1. 将 elevator-vr-anywhere.html 发送给对方。
2. 对方使用 Chrome、Edge 或 Firefox 双击打开。
3. 鼠标拖动旋转，滚轮缩放；REAR 可查看背面，360 可查看全景。

说明：VR 头显模式通常要求 HTTPS 网站；离线双击主要用于电脑和手机浏览。

方案二：生成所有人可访问的网页链接

1. 解压 elevator-vr-public-site.zip。
2. 将其中的 index.html 上传至任意静态网站托管服务。
3. 上传完成后，托管服务会提供一个 HTTPS 链接，可直接分享给任何人。

可用的静态托管服务包括：

- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel
- 腾讯云 COS / 阿里云 OSS 静态网站
- 任意普通网站服务器

该发布包为单页静态文件，不需要数据库、Node.js 或 Python。
