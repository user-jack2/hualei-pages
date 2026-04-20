# 花蕾 Cloudflare Pages Site

这个仓库已经整理成适合直接上传到 Cloudflare Pages 的静态站根目录。

## Files

- `index.html`: 宣传首页
- `styles.css`: 页面样式
- `404.html`: 兜底页
- `site.webmanifest`: PWA 基础清单
- `_headers`: Cloudflare Pages 响应头
- `_redirects`: Cloudflare Pages 路由兜底

## Cloudflare Pages Settings

- Framework preset: `None`
- Build command: 留空
- Build output directory: `/`

## Notes

- 这是静态宣传站，不依赖 FastAPI、数据库或 WebSocket
- 当前联系邮箱是占位地址，上线前建议替换成你的真实邮箱或表单地址
