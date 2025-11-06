# 用 AR.js 实现图片追踪 Demo

本项目演示如何使用 AR.js 在手机上实现图片追踪，打开摄像头后可识别指定图片，并显示 3D 模型，支持模型旋转和缩放操作。

## 使用说明

- 项目需部署在支持 HTTPS 的服务器上，手机访问网页即可体验 AR 效果。
- 推荐使用分辨率高、识别度高的图片进行训练，否则可能无法识别。

## 相关项目

- [AR.js 官方文档](https://ar-js-org.github.io/AR.js-Docs/image-tracking/)
- [arjs-gestures（旋转缩放功能）](https://github.com/fcor/arjs-gestures)

## 替换追踪图片

1. 使用 NFT Marker Creator 工具将图片训练为 AR.js 可识别格式（.fset、.fset3、.iset）。
   - [Web 版工具](https://carnaux.github.io/NFT-Marker-Creator/#/)
   - [Node 版工具](https://github.com/Carnaux/NFT-Marker-Creator)
2. 将生成的文件替换到 `nft` 文件夹中。

## 替换 3D 模型

将新的 glTF 模型文件替换到 `model` 文件夹中即可。
