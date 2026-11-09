# 薯饼白板

薯饼白板是一个基于 tldraw 的本地 Windows 白板。EXE 适用于 Windows x64，可在 [Releases](../../releases) 下载。本仓库用于个人备份与开发测试。

## 来源与许可

- 白板画布和编辑器基于 [tldraw SDK 5.6.0](https://github.com/tldraw/tldraw/tree/v5.6.0)，版权归 tldraw, Inc. 所有。SDK 保留原 [tldraw 许可证](licenses/tldraw-SDK-v5.6.0.md)，生产用途须取得适用授权。参见 [tldraw 官方许可说明](https://tldraw.dev/community/license)。
- 项目起点是 tldraw 的 Basic starter 模板，其 [MIT 许可证](licenses/tldraw-starter-MIT.md) 随附。
- 桌面运行时使用 [Electron](https://github.com/electron/electron)，相关 [Electron](licenses/Electron.txt) 和 [Chromium](licenses/Chromium.html) 许可随附。

本项目与 tldraw 官方项目独立。发布附件中的许可证适用于各自的上游组件。

## 数据

白板内容和上传的图片保存在本机的 `%LOCALAPPDATA%\Tldraw Local\board`。发布的 EXE 仅包含程序及运行资源。
