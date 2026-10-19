# PromPocket

Windows x64 本地 Markdown 提示词库，提供原生桌面程序与独立 CLI。

## 下载与使用

前往 [最新版本](https://github.com/k0ngss/PromPocket-updates/releases/latest) 下载 `PromPocket-Setup-版本.exe` 安装版，或下载 Windows x64 ZIP 便携版。安装版默认安装到当前用户 `%LOCALAPPDATA%\Programs\PromPocket`，不需要管理员权限，提供开始菜单、可选桌面快捷方式和系统卸载入口。
已有便携版可选择原程序目录安装，原库会备份并保留；若安装到新目录，请先备份并复制自己的 `library/`。
提示词保存在程序旁的 `library/`。CLI 使用方法：`prompt.exe --help` 或 `prompt.exe api`。

顶部“版本更新”展示版本与更新说明，启动检查只提示新版，不自动下载。
支持跳过版本、下载进度和取消；点击下载后校验大小与 SHA-256。
保存编辑内容后选择“关闭并安装”：安装版使用校验后的安装器升级，便携版只替换两个 EXE；两者均备份并重新打开原提示词库。卸载保留 library、回收站、个人设置和恢复备份。
也可以退出应用后手动覆盖程序文件，务必保留自己的 `library/`。

## 本仓库内容

此仓库提供公开安装下载与在线更新清单。源码在单独的私有仓库维护。
Release 附件为安装 EXE、便携 ZIP、update.json 与 SHA256SUMS.txt。公开包仅含固定示例，不含开发者个人提示词。

程序及附带依赖的许可证见 ZIP 中的 LICENSE 与 THIRD_PARTY_NOTICES.txt。
