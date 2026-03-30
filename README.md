# 风水实用指南

一个帮助您根据坐向和想提升的运势，推荐摆放什么物品的实用工具。

## 功能

- 🏠 场景选择：工位、客厅沙发、卧室床位、书桌
- 🧭 坐向选择：8个方向（坐东朝西、坐南朝北等）
- 🎯 运势选择：财运、事业、桃花、学业、健康
- 📜 生辰八字（可选）：输入出生年月日时，获得个性化命格分析和定制建议

## 本地运行

```bash
# 方法1：直接用浏览器打开 index.html

# 方法2：用 Python 本地服务器
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 在线部署

### GitHub Pages（免费）
1. 将代码推送到 GitHub 仓库
2. 进入仓库 Settings → Pages
3. Source 选择 main 分支，Save
4. 等待几分钟即可获得链接

### Vercel（免费）
```bash
npm i -g vercel
vercel login
vercel --prod
```

### Netlify（免费）
```bash
npm i -g netlify-cli
netlify deploy --prod --dir=.
```

## 技术

- 单 HTML 文件
- 原生 JavaScript，无框架
- 墨绿色古风主题
- 响应式设计
