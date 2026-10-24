# 会议助手（macOS）

本机会议录音、实时转写和 AI 纪要工具。这里只发布安装包，并作为应用内自动更新的来源。

## 下载安装

1. 打开 [最新版本](https://github.com/RZQiang-agent/meeting-notes-releases/releases/latest)，下载 `MeetingNotes-x.y.z-AppleSilicon.zip`。
2. 双击解压，把 `MeetingNotes.app` 拖进“应用程序”。已装旧版的，先结束录音并退出旧版，再替换。
3. 第一次打开如果被系统拦截：到“系统设置 > 隐私与安全性”，点“仍要打开”。本包为开发者自签名，未经过 Apple 公证。
4. 按提示允许麦克风；线上会议还需授权“屏幕与系统音频录制”，授权后重新打开应用。

要求：macOS 26 或更新版本，Apple 芯片 Mac。

## 自动更新

从 0.3.1 起，应用启动时会自动检查这里的新版本，确认后自动下载、校验、替换并重启。录音或处理中不会弹出提示。也可以从菜单“会议助手 > 检查更新…”手动检查。

## 数据与隐私

安装包不含任何会议记录、录音或密钥。会议数据只保存在本机 `~/Library/Application Support/MeetingNotes/`，更新不会影响它。
