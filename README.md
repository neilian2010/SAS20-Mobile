# 焦虑自评量表 (SAS-20) · 手机版

轻量移动端心理评估工具，单文件 HTML，无需构建。

## 本地使用

手机或电脑浏览器直接打开 `index.html`。  
> 需要联网（Tailwind / Font Awesome / Chart.js 从 CDN 加载）。

## GitHub Pages 部署（3 分钟）

1. 浏览器打开 https://github.com/new → 仓库名 `sas-mobile` → Public → **Create repository**
2. 进入仓库页 → **Add file → Upload files** → 把这两个文件拖进去 → **Commit changes**
3. 左侧 **Settings → Pages**
4. **Build and deployment → Source**：选 `Deploy from a branch`
5. **Branch**：选 `main` 根目录（/）→ **Save**
6. 等 1 分钟，页面顶部绿条会显示：

```
Your site is live at https://<你的用户名>.github.io/sas-mobile/
```

手机浏览器访问这个地址即可。

## 文件说明

| 文件 | 作用 |
|------|------|
| `index.html` | 手机版 SAS-20 单文件应用 |
| `README.md` | 本文档 |

## 技术栈

- Tailwind CSS (CDN)
- Font Awesome 4.7 (CDN)
- Chart.js 4.4 (CDN)
- 纯原生 JS，无构建步骤
- 历史记录用 localStorage，数据存手机本地
