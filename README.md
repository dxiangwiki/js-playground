# JS Playground
基于 Monaco Editor 构建的轻量 JavaScript 在线代码运行器。

🔗 在线预览：
- Netlify（推荐，国内访问更快）：https://js-playground.netlify.app/
- GitHub Pages：https://dxiangwiki.github.io/js-playground/
- GitHub源码仓库：https://github.com/dxiangwiki/js-playground


## ✨ 功能特性
- 代码编辑器使用 Monaco（VS Code 同款内核）
- 编辑器与控制台支持拖拽分割，自由调整高度
- `Ctrl+S`：将代码保存到浏览器本地存储（localStorage，刷新页面自动加载）
- `Ctrl+Shift+S`：直接导出 `code.js` 文件下载到电脑
- 支持导入本地 `.js` / `.txt` 文件加载代码
- 内置常用 JS 代码片段（for、forof、function、if、try、clog 等）
- 支持调整编辑器字体大小
- 内置沙盒 iframe 安全执行 JS，控制台区分 log / warn / error 颜色
- 代码持久化：浏览器本地缓存记忆上次编写代码

## 📖 使用说明
1. 在上方编辑器编写 JavaScript 代码
2. 点击【▶ 运行代码】执行，结果在下方控制台输出
3. `Ctrl + S`：保存当前代码到浏览器本地
4. `Ctrl + Shift + S`：导出 js 文件下载到本地硬盘
5. 【导入文件】：读取电脑上的 js 文件加载进编辑器
6. 【重置代码】：恢复默认示例代码

## ⚠️ 注意事项
1. **浏览器本地存储保存（Ctrl+S）**：保存在当前浏览器，清除浏览器缓存、无痕模式会丢失；重要代码请使用「导出js文件」备份。
2. 代码运行在 iframe 沙盒内，用于简单 JS 测试，不适合大型项目。
3. 所有功能纯前端实现，**无后端服务器**，所有数据在你的浏览器本地处理。

## 🚀 在线预览
> 开启 GitHub Pages 后访问：
[https://dxiangwiki.github.io/js-playground/](https://dxiangwiki.github.io/js-playground/)

## 📁 项目结构
```
js-playground/
├─ index.html    # 主页面，全部代码
└─ README.md     # 项目说明文档
└─ LICENSE     # 版权文件
```

## 📜 开源
本项目仅由前端静态文件构成，可自由修改、本地运行。
```
