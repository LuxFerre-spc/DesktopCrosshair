<p align="center"><img src="assets/crosshair.png" width="128" alt="桌面准星图标"></p>

# 桌面准星 / DesktopCrosshair

轻量 Windows 桌面准星工具，支持自适应高对比配色、精细尺寸调整，以及 CS 游戏窗口自动居中。

本仓库用于分发安装包、便携版及使用说明，不包含程序源代码。

## 下载

- [下载安装版](https://github.com/LuxFerre-spc/DesktopCrosshair/releases/latest/download/DesktopCrosshair-1.0.0-Setup.exe)
- [下载免安装便携版](https://github.com/LuxFerre-spc/DesktopCrosshair/releases/latest/download/DesktopCrosshair-1.0.0-Portable.zip)
- [查看全部版本](https://github.com/LuxFerre-spc/DesktopCrosshair/releases)
- [SHA256 校验文件](https://github.com/LuxFerre-spc/DesktopCrosshair/releases/latest/download/SHA256SUMS.txt)

## 功能

- 十字、T 型、圆形；可独立显示中心点。
- 厚度、长度、间距支持小数微调，厚度 0 隐藏线条，负间距使线条交叉。
- 独立不透明度设置，可选亚像素平滑。
- 高对比模式根据交点周围小块背景选择黑色或白色；也支持色环旋转 180° 的互补色模式和固定颜色。
- 一键居中、多显示器与位置微调，进入 CS 后跟随游戏窗口实际画面区域。
- 鼠标穿透、托盘菜单、自动保存设置；快捷键默认空白，可自行绑定。
- 关闭窗口时可选择退出或收起到托盘，也可记住默认行为。

## 系统要求

Windows 10 2004（19041）及以上版本或 Windows 11，64 位系统；.NET Framework 4.8 或更新版本。

## 使用

安装版运行安装程序即可；便携版解压后运行 `便携版/桌面准星.exe`。

游戏建议使用全屏窗口化或无边框窗口模式，独占全屏可能无法显示桌面叠加层。

当前发布文件未做数字签名，Windows 可能显示未知发布者或 SmartScreen 提示。

个人设置保存在 `%LOCALAPPDATA%\DesktopCrosshair\settings.xml`，卸载时保留。

完整说明见 [使用说明](docs/使用说明.txt)。
