# ToolsForMac

> Some awesome software for macOS.

## introduction

收集和记录 macOS 平台下优秀的软件，以开源和免费为主；基于个人偏好，罗列正在使用或将来可能会使用的软件，针对某些软件有同类产品的会一并列出（部分），不定时更新，如果你有更多优秀软件推荐，欢迎 issues 😄

## Package manager

macOS 平台的软件管理除 App Store 外，还有包管理器 [Homebrew](https://brew.sh/)，在支持的情况下我会优先使用 Homebrew 对软件进行安装/更新/卸载等操作，同类产品还有 [MacPorts](https://www.macports.org/index.php) ，Homebrew 命令简要说明如下，更多使用教程可查阅[官方文档](https://docs.brew.sh/)：



- `brew install [--cask] xxx`：安装软件，如果安装图形界面软件则加上`--cask`参数；
- `brew uninstall [--cask] xxx`：卸载软件，如果卸载图形界面软件则加上`--cask`参数；
- `brew list`：列出所有已安装软件；
- `brew info xxx`：查看某软件信息；
- `brew upgrade xxx`：更新某个软件；
- `brew cleanup xxx`：清理某软件的旧版本。

> 带有 <img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">标识表示可以使用 Homebrew 进行管理。

## Tools

- [OBS](https://obsproject.com/)：专业级的屏幕录制和直播工具，跨平台；轻量级屏幕录制可选 [QuickRecorder](https://github.com/lihaoyun6/QuickRecorder)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Raycast](https://www.raycast.com)：综合效率工具，支持插件，可替代很多独立软件，含付费功能；代替付费产品 Alfred。

- [IINA](https://iina.io/)：音视频播放器，几乎支持所有格式，可选产品有 [VLC](https://www.videolan.org/vlc/)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Snipaste](https://zh.snipaste.com/)：截图工具，支持贴图、标注、取色等，跨平台；可选产品有 [Flameshot](https://flameshot.org/)。

- [NDM](https://www.neatdownloadmanager.com/index.php/en/)：多线程下载工具，支持浏览器插件进行流媒体下载，跨平台；可选产品有 [FDM](https://www.neatdownloadmanager.com/index.php/en/)、[qbittorrent-E](https://github.com/c0re100/qBittorrent-Enhanced-Edition)。

- [Pearcleaner](https://github.com/alienator88/Pearcleaner)：软件卸载工具，可选产品有 [AppCleaner](https://freemacsoft.net/appcleaner/)。 <img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [PrettyClean](https://www.prettyclean.cc/zh)：轻量级磁盘清理工具，带有软件卸载功能。
- [ICE](https://icemenubar.app/)：菜单栏管理工具，代替付费产品 Bartender；可选产品有 [Hidden Bar](https://github.com/dwarvesf/hidden)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [The Unarchiver](https://macpaw.com/the-unarchiver)：解压缩工具，支持常见格式如rar/zip/7z/tar等；可选产品有 [Keka](https://www.keka.io/zh-cn/)。
- [ImageOptim](https://imageoptim.com/mac)：图片压缩工具，支持清除图片元数据；可选产品有 [Caesium](https://saerasoft.com/caesium) 或 Web 版 [squoosh](https://squoosh.app/) 。

- [Marta](https://marta.sh/)：文件管理工具，类似系统自带的Finder，支持自定义。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">
- [Calibre](https://calibre-ebook.com/)：电子书管理、转换和阅读工具，支持插件和多种格式，跨平台；可选产品有 [Koodo Reader](https://github.com/koodo-reader/koodo-reader)。
- [Skim](https://skim-app.sourceforge.io/)：PDF阅读和编辑工具，一般使用系统自带预览（Preview）。
- [Lulu](https://github.com/objective-see/LuLu)：防火墙工具，其他同一开发者的安全类工具工可以[在这里](https://objective-see.org/tools.html)查看。
- [Stats](https://github.com/exelban/stats)：系统资源监视器，可自定义菜单栏显示内容，代替付费产品 iStat Menus。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">
- [Easydict](https://github.com/tisfeng/Easydict)：词典翻译工具，支持 OCR 和多种翻译服务，浏览器集成。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">
- [Loop](https://github.com/MrKai77/Loop)：轻量级窗口管理工具，可选产品有 [Rectangle](https://github.com/rxhanson/Rectangle)（含付费功能）。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">
- [Battery](https://github.com/actuallymentor/battery)：将电池电量限制在80%，增加电池寿命，可选产品有 [AIDente](https://apphousekitchen.com/zh-hans/)（含付费功能）。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Whisky](https://github.com/Whisky-App/Whisky)：在 macOS 上运行 Windows 应用程序。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [UTM](https://mac.getutm.app/)：虚拟机管理工具；可选产品有 [VMware Fusion Pro](https://blogs.vmware.com/teamfusion/2024/05/fusion-pro-now-available-free-for-personal-use.html)、[VirtualBox](https://www.virtualbox.org/) 。

- [Clash verge rev](https://github.com/clash-verge-rev/clash-verge-rev)：网络代理管理工具；可选产品有 [Mihomo Party ](https://github.com/mihomo-party-org/mihomo-party)、[FIClash](https://github.com/chen08209/FlClash)等。

- [Obsidian](https://obsidian.md/)：私有化的笔记管理工具，插件丰富，跨平台，含付费功能；可选产品有 [Logseq](https://logseq.com/)、[Anytype](https://anytype.io/) 等。

- [LICEcap](https://www.cockos.com/licecap/)：GIF 图片制作工具，跨平台；可选产品有 [GIPHY](https://giphy.com/apps/giphycapture)、[GIFski](https://github.com/sindresorhus/Gifski) 。

- [Zed](https://zed.dev/)：代码编辑工具，支持插件和 AI （需登录），跨平台；可选产品有 [CotEditor](https://coteditor.com/)、[VSCode](https://code.visualstudio.com/) 等。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Zotero](https://www.zotero.org/)：文献综合管理工具，支持插件，跨平台；可选产品有 [Paperlib](https://paperlib.app/cn/) 。

- [GIMP](https://www.gimp.org/)：专业级图片编辑工具，类似 Photoshop，跨平台；可选产品有 [Krita](https://krita.org/zh-cn/) 或 Web版 [Photopea](https://www.photopea.com/) 。

- [Shotcut](https://www.shotcut.org/)：音视频剪辑工具，跨平台；可选产品有 [Openshot](https://www.openshot.org/zh-hans/)、[LosslessCut](https://github.com/mifi/lossless-cut)、[Kdenlive](https://invent.kde.org/multimedia/kdenlive) 等。

- [Blender](https://www.blender.org/)：3D 创作套件，支持建模、渲染、动画、合成等功能，跨平台。

- [Audacity](https://www.audacityteam.org/)：音频录制和编辑工具，支持多种音频格式，跨平台。

- [Warp](https://www.warp.dev/)：终端管理工具，支持 AI，需登录使用，跨平台；可选产品有 [iTerm2](https://iterm2.com/index.html)、[Kitty](https://sw.kovidgoyal.net/kitty/)、[Tabby](https://tabby.sh/)、[Alacritty](https://alacritty.org/) 等。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [MOS](https://github.com/Caldis/Mos)：鼠标增强工具，平滑鼠标滚动；可选产品有 [Mac-mouse-fix](https://macmousefix.com/) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [HandBrake](https://handbrake.fr/)：视频转码器，支持视频格式转换和压缩，跨平台。

- [Omnivore](https://omnivore.app/)：稍后阅读管理工具，支持 RSS、Newsletter 和浏览器扩展，跨平台。

- [LM Studio](https://lmstudio.ai/)：一站式本地部署大模型工具，支持模型搜索/下载/聊天等功能，跨平台；可选产品有 [Ollama](https://ollama.com/) 。

- [OmniDiskSweeper](https://www.omnigroup.com/more)：磁盘文件分析工具，快速查看大文件并打开或删除到废纸篓。

- [NetNewsWire](https://netnewswire.com/)：RSS 管理和阅读工具，同时支持 iOS 。

  
