《深蓝拾光》升级版 v2

功能：
- Canvas 像素风海底场景、原创小海獭潜水员
- 键盘/触屏移动、资源采集、背包、氧气系统
- 三片海域、不同稀有度资源
- 出售资源、四类装备升级、资源图鉴、探索任务
- localStorage 自动保存
- PWA manifest 与 Service Worker 离线缓存
- 响应式布局，支持手机与电脑

GitHub Pages 部署：
1. 解压 ZIP，将 index.html、manifest.webmanifest、sw.js、icon.svg 放到仓库根目录。
2. GitHub 仓库 Settings > Pages > Deploy from a branch。
3. 选择 main 分支和 /(root)，保存并等待部署。
4. 使用 https://用户名.github.io/仓库名/ 打开。
5. 首次加载需联网；随后可在同一浏览器中离线打开。iPhone Safari 分享 > 添加到主屏幕。

注意：游戏存档保存在当前浏览器的 localStorage。清除网站数据或更换设备不会自动同步存档。GitHub Pages 的 PWA 离线功能需通过 HTTPS 访问。
