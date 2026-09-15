# 造境 · Creative Code

一个像刷题平台一样学习创意编程的网页练习场。当前实验围绕 SVG 的 `feTurbulence` 与 `feDisplacementMap`，通过参数控制理解 Doodle 沸腾线稿效果，无需手写 path。

## 功能

- 热门视觉效果复刻练习
- SVG 滤镜参数实验与即时预览
- 现成图形切换，不把 path 绘制混入滤镜课程
- 自动生成可复制的滤镜代码
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

## 当前课程重点

- `baseFrequency`：噪声颗粒尺度
- `numOctaves`：噪声细节层数
- `scale`：位移幅度
- 离散 seed 动画：逐帧手绘感
- filter region：避免变形后被裁切

## License

MIT
