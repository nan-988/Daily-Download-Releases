# 行业日报自动下载 · 安装包发布

此仓库仅发布软件安装包和更新说明。软件源码在独立的私有仓库中维护。

## 下载与运行

到 [最新正式版本](https://github.com/nan-988/Daily-Download-Releases/releases/latest) 下载 `DailyReportDesktop-Windows.zip`。

1. 关闭正在运行的旧版本。
2. 将完整 ZIP 解压到新的文件夹。
3. 运行 `DailyReportDesktop.exe`，保留同目录的 `_internal` 文件夹。

账号、预设和软件设置保存在用户目录，安装新版本后可继续使用。

发布页面也提供 `.sha256` 校验文件。Windows PowerShell 可用 `Get-FileHash .\DailyReportDesktop-Windows.zip -Algorithm SHA256` 查看下载文件的校验值。

## 更新提醒

从 v1.3.0 起，Windows 软件会在启动后后台检查正式版本，持续运行时每天检查一次。也可点击软件底部的“检查更新”。发现新版本后，可查看更新说明、前往下载、稍后提醒或跳过该版本。

旧版本需要先手动安装一次 v1.3.0 或更高版本，之后才支持更新提醒。测试版本不触发正式更新提示。检查更新需要能访问 GitHub。
