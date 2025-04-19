# Apps For Mac

> Some awesome software for macOS.

## introduction

本[仓库](https://github.com/holyshell/AppsForMac)基于个人偏好，收集和记录 macOS 平台下优秀的实用软件，不定时更新。 😄

- 以开源和免费软件为主；
- 不包含系统自带软件和大众常用的社交、音乐、沟通类软件；
- 优先选择图形界面( GUI )软件，也包含 CLI（命令行界面）和 Web 产品；
- 描述有`跨平台`的软件表示除支持 macOS 外， 还支持其他系统（Windows、Linux、iOS 或 Android）；
- :warning: 如果有软件需要完全磁盘访问（Full Disk Access）权限请谨慎，若无必要，不建议开启；
- :warning: 部分软件可能对系统的最低版本有要求，请留意查看软件页面的介绍。

## Package manager

macOS 平台的软件管理除 App Store 外，还有包管理器 [Homebrew](https://brew.sh/)，在支持的情况下会优先使用 Homebrew 对软件进行管理，同类产品还有 [MacPorts](https://www.macports.org/index.php)、[Applite](https://aerolite.dev/applite) 或 [Cakebrew](https://www.cakebrew.com/)，Homebrew 命令简要说明如下（更多可查阅[官方文档](https://docs.brew.sh/)）：

- `brew install [--cask] xxx`：安装软件，如果安装图形界面软件则加上`--cask`参数；
- `brew uninstall [--cask] xxx`：卸载软件，如果卸载图形界面软件则加上`--cask`参数；
- `brew list`：列出所有已安装软件；
- `brew info xxx`：查看某软件信息；
- `brew upgrade xxx`：更新某个软件；
- `brew cleanup xxx`：清理某软件的旧版本。

## Apps

> 带有 <img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">标识表示可以使用 Homebrew 进行管理。

- [Firefox](https://www.mozilla.org/zh-CN/firefox/all/desktop-release/)：非 Chromium 类主流浏览器，采用专有的 Quantum 引擎，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [IINA](https://iina.io/)：音视频播放器，几乎支持所有格式，可选产品有 [VLC](https://www.videolan.org/vlc/)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [OBS](https://obsproject.com/)：专业级的屏幕录制和直播工具，跨平台；轻量级屏幕录制可选 [QuickRecorder](https://github.com/lihaoyun6/QuickRecorder)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Raycast](https://www.raycast.com)：综合效率工具，支持插件，可替代很多独立软件，含付费功能。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Squirrel](https://github.com/rime/squirrel)：鼠须管输入法，支持高度自定义，跨平台，配置和字库可使用 [rime-ice](https://github.com/iDvel/rime-ice) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Snipaste](https://zh.snipaste.com/)：截图工具，支持贴图、标注、取色等，跨平台；可选产品有 [Flameshot](https://flameshot.org/)。

- [NDM](https://www.neatdownloadmanager.com/index.php/en/)：多线程下载工具，支持浏览器插件进行流媒体下载，跨平台；可选产品有 [FDM](https://www.freedownloadmanager.org/zh/)、[qbittorrent-E](https://github.com/c0re100/qBittorrent-Enhanced-Edition)。

- [Pearcleaner](https://github.com/alienator88/Pearcleaner)：软件卸载工具，可选产品有 [AppCleaner](https://freemacsoft.net/appcleaner/)。 <img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [PrettyClean](https://www.prettyclean.cc/zh)：轻量级磁盘清理工具，带有软件卸载功能。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [ICE](https://icemenubar.app/)：菜单栏管理工具，支持自定义调整；可选产品有 [Hidden Bar](https://github.com/dwarvesf/hidden)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [The Unarchiver](https://macpaw.com/the-unarchiver)：解压缩工具，支持多种常见压缩包格式；可选产品有 [Keka](https://www.keka.io/zh-cn/)。

- [KeePassXC](https://keepassxc.org/)：密码管理工具，跨平台；可选产品有 [vaultwarden](https://www.vaultwarden.net/)。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [LocalSend](https://localsend.org/zh-CN)：去中心化、端到端加密的文件传输工具，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [ImageOptim](https://imageoptim.com/mac)：图片压缩工具，支持清除 EXIF 数据；可选产品有 [Caesium](https://saerasoft.com/caesium) 或  [squoosh](https://squoosh.app/) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Marta](https://marta.sh/)：文件管理工具，类似系统自带的 Finder，支持自定义；可选产品有 [Double Commander](https://doublecmd.sourceforge.io/) 。 <img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Calibre](https://calibre-ebook.com/)：电子书管理、转换和阅读工具，支持插件和多种格式，跨平台；可选产品有 [Koodo Reader](https://github.com/koodo-reader/koodo-reader)。

- [Skim](https://skim-app.sourceforge.io/)：PDF 阅读和编辑工具，阅读一般使用系统自带预览（Preview）。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [LibreOffice](https://www.libreoffice.org/download/download-libreoffice/)：office 办公套件，跨平台；可选产品有 [OpenOffice](https://www.openoffice.org/zh-cn/)、[OnlyOffice](https://www.onlyoffice.com/download-desktop.aspx)、[Google Docs](https://docs.google.com/)。

- [Anki](https://apps.ankiweb.net/)：智能学习系统，记忆学习训练，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Lulu](https://github.com/objective-see/LuLu)：网络监控与防火墙工具，其他同一开发者的安全类工具可以[在这里](https://objective-see.org/tools.html)查看。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Stats](https://github.com/exelban/stats)：系统资源监视器，可自定义菜单栏显示内容。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Easydict](https://github.com/tisfeng/Easydict)：词典翻译工具，支持 OCR 和多种翻译服务；可选产品有 [Pot](https://github.com/pot-app/pot-desktop) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Loop](https://github.com/MrKai77/Loop)：轻量级窗口管理工具；可选产品有 [Rectangle](https://github.com/rxhanson/Rectangle)（含付费功能）。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Battery](https://github.com/actuallymentor/battery)：将电池电量限制在80%，延长电池寿命；可选产品有 [AIDente](https://apphousekitchen.com/zh-hans/)（含付费功能）。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Whisky](https://github.com/Whisky-App/Whisky)：在 macOS 上运行 Windows 应用程序，**该项目不再维护**；可选产品有 [Kegworks](https://github.com/Kegworks-App/Kegworks) 。

- [UTM](https://mac.getutm.app/)：虚拟机管理工具；可选产品有 [VMware Fusion Pro](https://blogs.vmware.com/teamfusion/2024/05/fusion-pro-now-available-free-for-personal-use.html)、[VirtualBox](https://www.virtualbox.org/) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Clash verge rev](https://github.com/clash-verge-rev/clash-verge-rev)：网络代理管理工具；可选产品有 [Mihomo Party ](https://github.com/mihomo-party-org/mihomo-party)、[FIClash](https://github.com/chen08209/FlClash)等。

- [Obsidian](https://obsidian.md/)：本地化的知识管理工具，跨平台，含付费功能；可选产品有 [Logseq](https://logseq.com/)、[Anytype](https://anytype.io/)、[Zettlr](https://www.zettlr.com/) 等。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [LICEcap](https://www.cockos.com/licecap/)：GIF 图片制作工具，跨平台；可选产品有 [GIPHY](https://giphy.com/apps/giphycapture)、[GIFski](https://github.com/sindresorhus/Gifski) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Zed](https://zed.dev/)：代码编辑工具，支持插件和 AI （需登录），跨平台；可选产品有 [CotEditor](https://coteditor.com/)、[VSCode](https://code.visualstudio.com/)、[CudaText](https://cudatext.github.io/) 等。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Zotero](https://www.zotero.org/)：文献综合管理工具，支持插件，跨平台；可选产品有 [Paperlib](https://paperlib.app/cn/) 。

- [GIMP](https://www.gimp.org/)：专业级图片编辑工具，类似 Photoshop，跨平台；可选产品有 [Krita](https://krita.org/zh-cn/) 或 Web版 [Photopea](https://www.photopea.com/) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Inkscape](https://inkscape.org/)：专业级矢量图编辑工具，类似 Illustrator，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Shotcut](https://www.shotcut.org/)：音视频剪辑工具，跨平台；可选产品有 [Openshot](https://www.openshot.org/zh-hans/)、[LosslessCut](https://github.com/mifi/lossless-cut)、[Kdenlive](https://invent.kde.org/multimedia/kdenlive) 等。

- [Blender](https://www.blender.org/)：3D 创作套件，支持建模、渲染、动画、合成等功能，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Audacity](https://www.audacityteam.org/)：音频录制和编辑工具，支持多种音频格式，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Warp](https://www.warp.dev/)：终端管理工具，支持 AI，需登录使用，跨平台；可选产品有 [iTerm2](https://iterm2.com/index.html)、[Kitty](https://sw.kovidgoyal.net/kitty/)、[Tabby](https://tabby.sh/)、[Alacritty](https://alacritty.org/) 等。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [MOS](https://github.com/Caldis/Mos)：鼠标增强工具，平滑鼠标滚动；可选产品有 [Mac-mouse-fix](https://macmousefix.com/) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [HandBrake](https://handbrake.fr/)：视频转码器，支持视频格式转换和压缩，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Omnivore](https://omnivore.app/)：~稍后阅读管理工具，支持 RSS、Newsletter 和浏览器扩展，跨平台。~

- [Joplin](https://joplinapp.org/)：基于 markdown 的笔记工具，跨平台；可选产品有 [MiaoYan](https://github.com/tw93/MiaoYan)、[MarkEdit](https://github.com/MarkEdit-app/MarkEdit) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [LM Studio](https://lmstudio.ai/)：一站式本地部署大模型工具，支持模型搜索/下载/聊天等功能，跨平台；可选产品有 [Ollama](https://ollama.com/) 。

- [OmniDiskSweeper](https://www.omnigroup.com/more)：磁盘空间分析工具，快速查看大文件并打开或删除到废纸篓。

- [NetNewsWire](https://netnewswire.com/)：RSS 管理和阅读工具，同时支持 iOS 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Sigil](https://sigil-ebook.com/sigil/)：创建和编辑 EPUB 格式电子书。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Cyberduck](https://cyberduck.io/)：支持 FTP、SFTP、WebDAV、S3、OneDrive 等协议和云端存储浏览工具，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [f.lux](https://justgetflux.com/)：调整屏幕色温和亮度，保护眼睛。

- [Command X](https://sindresorhus.com/command-x)：在 Finder 中进行文件的剪切`Command+X`和粘贴`Command+V`小工具，代替传统复杂的快捷键。

- [Billfish](https://www.billfish.cn/)：素材管理工具，支持多种常见文件格式和浏览器插件；可选产品有 [Pixcall](https://pixcall.com/download) 。

- [Drawio](https://github.com/jgraph/drawio-desktop)：流程图和白板工具，[在线版本](https://app.diagrams.net/)；可选产品有 [Excalidraw](https://excalidraw.com/) 。

- [Achico](https://github.com/nuance-dev/achico)：图片、音视频和PDF等文件压缩工具，作者其他的 mini 工具可查他的 GitHub 主页。

- [TomatoBar](https://github.com/ivoronin/TomatoBar)：番茄时钟，菜单栏工具；可选产品有 [Tomito](https://tomito.app/) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [Buzee](https://github.com/gsidhu/buzee-releases)：文件快速搜索工具，支持多种文档类型和语法，跨平台。

- [Kiwix](https://kiwix.org/en/)：离线查看 Wikipedia、TED、StackExchange 或其他网站资源的工具，跨平台。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [FixTim](https://github.com/Lakr233/FixTim)：修复 macOS 上一些奇怪的系统 bug （不包含硬件或 kernel 问题）而无须重启系统。

- [Office-Reset](https://office-reset.com/)：解决 MS Office for Mac 系列软件的各种疑难杂症。

- [OpenMTP](https://github.com/ganeshrvel/openmtp)：用于 Mac 和 Android 之间安全的传输文件。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">

- [ProNotes](https://www.pronotes.app/)：默认备忘录的增强插件，支持格式栏、markdown、命令等，AI功能付费。

- [MinerU](https://github.com/opendatalab/MinerU)：支持 PDF/Word 等文档解析输出 Markdown/HTML 等格式，跨平台[图形化](https://mineru.net/)版本。

- [Upscayl](https://github.com/upscayl/upscayl)：使用 AI 模型实现图片无损放大的工具，跨平台；可选产品有 [HiPixel](https://github.com/okooo5km/HiPixel) 。<img width = "18" height = "18" src="https://raw.githubusercontent.com/holyshell/ToolsForMac/72231dbe1542e83550656097a8a9463504255b5c/media/homebrew.svg">
  
## Best wishes
<img width = "380" height = "400" src="https://raw.githubusercontent.com/holyshell/StudyNotes/refs/heads/master/images/justforfun.jpg">
