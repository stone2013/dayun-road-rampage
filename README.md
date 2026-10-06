# 大运 · 公路冲击 3D

一个可部署到 GitHub Pages 的低多边形 3D 撞车小游戏（v2.1）。玩家驾驶大运消防重卡外形的卡通货车，在公路上躲闪并撞飞来车；车辆会翻滚、爆炸并散落模型碎片。

## 运行

项目需要通过网页服务器打开，以便读取 `assets/models.json`。部署到 GitHub Pages 后即可在手机和电脑浏览器中游玩。直接双击 `index.html` 可能会被浏览器拦截模型文件读取。

- 手机：按住左右按钮转向，按住“氮气冲击”加速。
- 电脑：`A` / `D` 或方向键转向，空格加速，`P` 暂停。

## 模型

Kenney Car Kit 的消防车、小轿车、SUV、车门、保险杠和轮胎网格已整理为 `assets/models.json`，游戏运行时从本地项目读取，无外部 3D 引擎或 CDN 依赖。`assets/KENNEY-LICENSE.txt` 附有原授权文本。Kenney Car Kit 采用 CC0 授权。

## GitHub Pages

上传仓库根目录中的文件后，在仓库的 **Settings → Pages** 中选择从 `main` 分支的根目录部署。等待 Pages 完成部署后，页面会显示可分享的游戏网址。
