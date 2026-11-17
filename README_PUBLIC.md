# Santioni Spirits · 本地研究复刻

这是我们当时用于研究和复刻 [Santioni Spirits](https://santionispirits.com/) 互动网站的本地项目，包含：

- 本地镜像服务器与资源校验工具；
- 原站 WebGL 入口的本地缓存版本；
- 对页面场景、交互、音频和资源结构的分析记录。

它是**非官方复刻**，与 Santioni Spirits、Active Theory 和 Plan8 没有隶属或授权关系。

## 本地运行

需要 Node.js 18 或更高版本：

```bash
node server.js
```

然后打开：

```text
http://localhost:3000/
```

项目默认把目标内容放在 `santionispirits.com/` 目录中。`server.js` 和 `tools/mirror-assets.js` 也可以通过环境变量配置其他站点。

## 目录

- `santionispirits.com/`：本地缓存的页面与资源。
- `analysis/`：场景和交互结构分析。
- `tools/`：资源镜像与校验工具。
- `server.js`：本地研究服务器。

## 版权与使用范围

本仓库中的镜像页面、图片、视频、字体、音频、模型、脚本和其他第三方资源，其权利归原权利人所有。本仓库仅用于学习、研究、技术交流和本地测试，不代表获得原站资源的再发布、商业使用或公开部署许可。

工具代码遵循仓库内的 `LICENSE`；第三方资源不受该许可证授予额外权利。使用前请自行确认版权、服务条款和适用法律。
