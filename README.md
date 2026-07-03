# AI 产品经理作品集

这是一个静态作品集项目，可直接通过 `index.html` 访问，也可部署到 Vercel 等静态托管平台。

## 本地预览

方式一：直接打开项目根目录下的 `index.html`。

方式二：在项目根目录启动本地静态服务器，例如：

```bash
npx serve .
```

## Vercel 部署

- 构建命令：不需要
- 输出目录：项目根目录
- 入口文件：`index.html`
- 静态资源目录：`assets/`
- 不需要上传 `node_modules/`

## 主页面路径

- `/`
- `/openclaw-case.html`
- `/pandatoken-case.html`
- `/knowledge-center-case.html`

## 部署前必须确认

- OpenClaw 演示视频已压缩，页面引用路径仍为 `assets/openclaw/recruit-demo.mp4`
- 图片和视频已完成脱敏复核
- 主页面引用的图片、视频、CSS 资源无缺失
- 四个主页面均可正常打开
- 不要把 `node_modules/` 上传到仓库
