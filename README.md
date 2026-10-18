# PromPocket

Windows x64 本地 Markdown 提示词库，提供原生桌面程序与独立 CLI。

## 下载与使用

前往 [最新版本](https://github.com/k0ngss/PromPocket-updates/releases/latest) 下载 Windows x64 ZIP，解压到可写目录后运行 `prompt-desktop.exe`。
提示词保存在程序旁的 `library/`。CLI 使用方法：`prompt.exe --help` 或 `prompt.exe api`。

顶部“检查更新”会读取本仓库的 update.json，经确认后下载、校验大小与 SHA-256。
下载成功后请保存并关闭程序，更新只替换两个 EXE，并重新打开提示词库。
也可以退出应用后手动覆盖程序文件，务必保留自己的 `library/`。

## 本仓库内容

此仓库提供公开安装下载与在线更新清单。源码在单独的私有仓库维护。
Release 附件为便携 ZIP、update.json 与 SHA256SUMS.txt。公开包仅含固定示例，不含开发者个人提示词。

程序及附带依赖的许可证见 ZIP 中的 LICENSE 与 THIRD_PARTY_NOTICES.txt。
