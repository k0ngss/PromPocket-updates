# PromPocket

Windows x64 本地 Markdown 提示词库，提供原生桌面程序与独立 CLI。

## 下载与使用

前往 [最新版本](https://github.com/k0ngss/PromPocket-updates/releases/latest) 下载 Windows x64 ZIP，解压到可写目录后运行 `prompt-desktop.exe`。
提示词保存在程序旁的 `library/`。CLI 使用方法：`prompt.exe --help` 或 `prompt.exe api`。

顶部“版本更新”展示版本与更新说明，启动检查只提示新版，不自动下载。
支持跳过版本、下载进度和取消；点击下载后校验大小与 SHA-256。
保存编辑内容后选择“关闭并安装”，更新只替换两个 EXE，并重新打开原提示词库。
也可以退出应用后手动覆盖程序文件，务必保留自己的 `library/`。

## 本仓库内容

此仓库提供公开安装下载与在线更新清单。源码在单独的私有仓库维护。
Release 附件为便携 ZIP、update.json 与 SHA256SUMS.txt。公开包仅含固定示例，不含开发者个人提示词。

程序及附带依赖的许可证见 ZIP 中的 LICENSE 与 THIRD_PARTY_NOTICES.txt。
