# Au-Lei 的个人博客

简洁的中文个人博客，支持文章阅读、关键词搜索、分类筛选和深浅主题。文章为可替换的示例内容。

## 本地运行

安装 Node.js LTS 后，在本目录执行：

```powershell
npm start
```

浏览器打开 http://localhost:3000，按 Ctrl+C 停止。无需 npm install，无第三方依赖。

## 修改内容

编辑 app.js 中 posts 数组增加文章；style.css 修改样式。修改后刷新浏览器即可。

## 检查

```powershell
npm run check
```

## Git

```powershell
git add .
git commit -m "Update blog"
git push
```

服务器仅监听本机，适合本地开发。发布静态网站时使用 index.html、style.css、app.js。
