# ToolsForMac

> Some awesome software for macOS.

## introduction

收集和记录 macOS 平台下优秀的软件和工具，以开源和免费软件为主。GitHub 上已经有很多 macOS 软件汇总的 repo，比如 [awesome-macOS](https://github.com/iCHAIT/awesome-macOS)，本 repo 梳理的软件纯粹基于个人偏好，罗列自己正在使用或将来可能会使用的软件，针对部分软件有同类选择的会进行简要说明，但不会全部列出，不定时更新。

## Package manager

macOS 下的软件管理除了 App Store 之外，还有包管理器 [Homebrew](https://brew.sh/)，在支持的情况下我会优先使用 Homebrew 对软件进行安装/更新/卸载等操作，同类产品还有 [MacPorts](https://www.macports.org/index.php) ，Homebrew 简要命令说明如下：

- `brew install [--cask] xxx`：安装软件，如果安装图形界面软件则加上`--cask`参数；
- `brew list`：列出所有已安装软件列表；
- `brew uninstall [--cask] xxx`：卸载软件，如果卸载图形界面软件则加上`--cask`参数；
- `brew info xxx`：查看某软件信息；
- `brew upgrade xxx`：更新某个软件；
- `brew cleanup xxx`：清理某软件的旧版本。

> 带有 <img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">标识表示可以使用 Homebrew 进行管理。

## Tools

- [OBS](https://obsproject.com/)：专业级的录制和直播工具，跨平台；轻量级录制工具可选 [QuickRecorder](https://github.com/lihaoyun6/QuickRecorder)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Raycast](https://www.raycast.com)：综合效率工具，支持插件，可代替很多独立软件，含付费功能；代替付费产品 Alfred。

- [IINA](https://iina.io/)：音视频播放器，几乎支持所有格式，可选产品有 [VLC](https://www.videolan.org/vlc/)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Snipaste](https://zh.snipaste.com/)：截图工具，支持贴图、标注、取色等，跨平台；可选产品有 [Flameshot](https://flameshot.org/)。

- [NDM](https://www.neatdownloadmanager.com/index.php/en/)：多线程下载工具，支持浏览器插件进行流媒体下载，跨平台；可选产品有 [FDM](https://www.neatdownloadmanager.com/index.php/en/) [qbittorrent-E](https://github.com/c0re100/qBittorrent-Enhanced-Edition)。

- [Pearcleaner](https://github.com/alienator88/Pearcleaner)：软件卸载工具，可选产品有 [AppCleaner](https://freemacsoft.net/appcleaner/)。 <img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [PrettyClean](https://www.prettyclean.cc/zh)：轻量级磁盘清理工具，带有软件卸载功能。
- [ICE](https://icemenubar.app/)：菜单栏管理工具，代替付费产品 Bartender；可选产品有 [Hidden Bar](https://github.com/dwarvesf/hidden)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [The Unarchiver](https://macpaw.com/the-unarchiver)：解压缩工具，支持常见格式如rar/zip/7z/tar等；可选产品有 [Keka](https://www.keka.io/zh-cn/)。
- [ImageOptim](https://imageoptim.com/mac)：图片压缩工具，支持清除图片元数据；可选产品有 [Caesium](https://saerasoft.com/caesium) 或 Web 版 [squoosh](https://squoosh.app/) 。

- [Marta](https://marta.sh/)：文件管理工具，类似系统自带的Finder，支持自定义。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">
- [Calibre](https://calibre-ebook.com/)：电子书管理和阅读工具，跨平台；可选产品有 [Koodo Reader](https://github.com/koodo-reader/koodo-reader)。
- [Lulu](https://github.com/objective-see/LuLu)：防火墙工具，其他同一开发者的安全类工具工可以[在这里](https://objective-see.org/tools.html)查看。
- [Stats](https://github.com/exelban/stats)：系统资源监视器，可自定义菜单栏显示内容，代替付费产品 iStat Menus。
- [Easydict](https://github.com/tisfeng/Easydict)：词典翻译工具，支持 OCR 和多种翻译服务。
- [Loop](https://github.com/MrKai77/Loop)：轻量级窗口管理工具，可选产品有 [Rectangle](https://github.com/rxhanson/Rectangle)（含付费功能）。
- [battery](https://github.com/actuallymentor/battery)：将电池电量限制在80%，增加电池寿命，可选产品有 [AIDente](https://apphousekitchen.com/zh-hans/)（含付费功能）。
