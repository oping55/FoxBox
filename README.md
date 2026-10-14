# FoxBox

> Android 上的多功能工具箱 + 媒体聚合客户端。**本仓库只放安装包和更新日志**，源码不在这里。

![FoxBox](https://img.shields.io/badge/Android-8.0%2B-3DDC84) ![License](https://img.shields.io/badge/License-Apache%202.0-blue)

## 下载

去 [**Releases**](../../releases/latest) 下最新的 `FoxBox-<版本>.apk`，在手机上点开安装即可。

- 包名 `com.foxbox.toolbox` · 最低 Android 8.0（API 26）· 目标 Android 16（API 36）
- 安装包约 130 MB（里面带了语音合成、反编译引擎等原生库）
- 首次安装需要在系统里允许「安装未知应用」

## 应用内更新

从 **0.1.2** 起，FoxBox 会自己检查这个仓库的 Releases：

- 启动时**顺手**查一次（不拖慢启动，界面上只显示一句「检查更新…」）
- 有新版就弹窗，**直接显示下面 [CHANGELOG.md](CHANGELOG.md) 里对应那一节**（即 Release 说明）
- 点「静默更新」→ 后台下载（前台服务 + 通知栏进度），**期间应用照常用**
- 下载完成后：
  - 你**正在用** FoxBox → 弹窗问一句「现在安装吗」
  - 你**没在用**（退到桌面 / 锁屏）→ **直接静默装掉**，回来就是新版
- 机器上有 Shizuku 或 root 时是真·静默安装（零确认）；没有的话会退到系统安装器，需要你点一下「安装」

「我的 → 关于 → 检查更新」里也能手动查，那儿会显示当前状态（正在下载 42% / 已是最新 / 失败原因）。

## 更新日志

见 [CHANGELOG.md](CHANGELOG.md)。每个版本一节，**Releases 里的说明就是从那里同步过去的** ——
应用内弹窗显示的也是同一段文字，不存在两个地方写得不一样的问题。

## 出处与许可

FoxBox 基于 [Yutu-Toolbox](https://github.com/guanhan01/Yutu-Toolbox)（Apache License 2.0）二次开发，
并使用了若干第三方开源组件（AndroidX、Media3、JetBrains Compose 等）。
本仓库的 [LICENSE](LICENSE) 为 Apache License 2.0，与原项目一致。

> ⚠️ 本项目仅用于学习与技术研究。请遵守你所在地区的法律法规，不要用它做任何侵权或违法的事。
