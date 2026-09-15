# 造境 · Creative Code

一个像刷题平台一样学习创意编程的网页练习场。左侧展示目标视觉效果与任务要求，右侧编写 HTML/CSS，并在隔离的 iframe 中即时运行。

## 功能

- 热门视觉效果复刻练习
- HTML/CSS 在线编辑与即时预览
- 参考答案、验收反馈与本地自动保存
- 对应题目的知识点卡片
- 每周创作者榜单
- 桌面与移动端响应式布局

## 本地运行

这是一个无依赖的静态网页：

```bash
python3 -m http.server 4173 --directory dist
```

然后访问 `http://127.0.0.1:4173/`。

## 安全设计

学习者输入的代码通过带有 `sandbox="allow-scripts"` 的 iframe `srcdoc` 运行，不授予同源权限。

## License

MIT
