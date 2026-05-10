# Apps For Mac

> Some awesome software for macOS.

本[仓库](https://github.com/holyshell/AppsForMac)基于个人偏好，记录 macOS 平台优秀的实用软件，不定时更新。 😄

- 以开源和免费软件为主；
- 不包含系统自带软件和大众常用社交、音乐、沟通类软件；
- 描述中有`跨平台`表示除 macOS 外， 还支持其他系统如 Windows、Linux、iOS 或 Android；
- 若安装软件后出现无法打开或损坏可以尝试使用`xattr -r -d com.apple.quarantine <filename>`命令解决。

> [!tip]
> 如果有软件需要完全磁盘访问（Full Disk Access）权限请谨慎，按需开启；
> 
> 部分软件可能对系统的最低版本有要求，请留意查看软件页面的介绍。

## Package manager

macOS 平台除 App Store 外，还有包管理器 [Homebrew](https://brew.sh/)，同类可选产品有 [MacPorts](https://www.macports.org/index.php)、[Applite](https://aerolite.dev/applite) 或 [Cakebrew](https://www.cakebrew.com/) 。

<details>
<summary>Homebrew 命令简要说明</summary>
  
  - `brew install [--cask] xxx`：安装软件，若安装图形界面软件则加上`--cask`参数；
  - `brew uninstall [--cask] xxx`：卸载软件，若卸载图形界面软件则加上`--cask`参数；
  - `brew list`：列出所有已安装软件；
  - `brew info xxx`：查看某软件信息；
  - `brew upgrade xxx`：更新某个软件；
  - `brew cleanup xxx`：清理某软件的旧版本；
  - 更多使用方式可查阅[官方文档](https://docs.brew.sh/)。
</details>

## Apps

> 带有 📍 标识表示可以使用 Homebrew 进行管理。

- [Firefox](https://www.mozilla.org/zh-CN/firefox/all/desktop-release/)：非 Chromium 类开源浏览器，跨平台；可选产品有 [Chrome](https://www.google.cn/intl/zh-CN/chrome/) 、[Edge](https://www.microsoft.com/zh-CN/edge/mac)、[Brave](https://brave.com/zh/)、[Vivaldi](https://vivaldi.com/zh-hans/)、[Orion](https://kagi.com/orion/)等。 📍

- [IINA](https://iina.io/)：音视频播放器，几乎支持所有音视频格式，可选产品有 [VLC](https://www.videolan.org/vlc/)。📍

- [OBS](https://obsproject.com/)：专业级的屏幕录制和直播工具，跨平台；轻量级屏幕录制可选 [QuickRecorder](https://github.com/lihaoyun6/QuickRecorder)、[Recordly](https://github.com/webadderall/Recordly)。📍

- [Raycast](https://www.raycast.com)：综合效率工具，支持插件，可替代很多独立软件，含付费功能。📍

- [Squirrel](https://github.com/rime/squirrel)：鼠须管输入法，支持高度自定义，跨平台，配置和字库可使用 [rime-ice](https://github.com/iDvel/rime-ice) ；可选产品有 [Fcitx](https://fcitx-contrib.github.io/docs/) 。📍

- [Snipaste](https://zh.snipaste.com/)：截图工具，支持贴图、标注、取色等，跨平台；可选产品有 [Flameshot](https://flameshot.org/)、[Snow-Shot](https://github.com/mg-chao/snow-shot)。

- [NDM](https://www.neatdownloadmanager.com/index.php/en/)：多线程下载工具，支持浏览器插件进行流媒体下载，跨平台；可选产品有 [FDM](https://www.freedownloadmanager.org/zh/)、[qbittorrent-E](https://github.com/c0re100/qBittorrent-Enhanced-Edition)。

- [PearCleaner](https://github.com/alienator88/Pearcleaner)：软件卸载工具，可选产品有 [AppCleaner](https://freemacsoft.net/appcleaner/)。 📍

- [PrettyClean](https://www.prettyclean.cc/zh)：轻量级磁盘清理工具，带有软件卸载功能；可选产品有 [Mole](https://github.com/tw93/Mole) 。📍

- [ICE](https://icemenubar.app/)：菜单栏管理工具，支持自定义调整；可选产品有 [Thaw](https://github.com/stonerl/Thaw)、[Hidden Bar](https://github.com/dwarvesf/hidden)。📍

- [The Unarchiver](https://macpaw.com/the-unarchiver)：解压缩工具，支持多种常见压缩包格式；可选产品有 [Keka](https://www.keka.io/zh-cn/)、[PeaZip](https://peazip.github.io/)。

- [PictureView](https://wl879.github.io/apps/picview/index.html)：图片浏览工具，支持多种模式；可选产品有 [PicView](https://github.com/Ruben2776/PicView)。

- [EcoPaste](https://github.com/EcoPasteHub/EcoPaste)：剪切板管理工具，支持 OCR 识别，跨平台；可选产品有 [CopyQ](https://github.com/hluk/CopyQ)。

- [KeePassXC](https://keepassxc.org/)：密码管理工具，跨平台；可选产品有 [VaultWarden](https://www.vaultwarden.net/)、[PearPass](https://pass.pears.com/)。📍

- [LocalSend](https://localsend.org/zh-CN)：去中心化、端到端加密的文件传输工具，跨平台。📍

- [ImageOptim](https://imageoptim.com/mac)：图片压缩工具，支持清除 EXIF 数据；可选产品有 [Caesium](https://saerasoft.com/caesium) 或 [Squoosh](https://squoosh.app/) 。📍

- [Marta](https://marta.sh/)：文件管理工具，类似系统自带的 Finder，支持自定义；可选产品有 [Double Commander](https://doublecmd.sourceforge.io/) 。📍

- [Calibre](https://calibre-ebook.com/)：电子书管理、转换和阅读工具，支持插件和多种格式，跨平台；可选产品有 [Koodo Reader](https://github.com/koodo-reader/koodo-reader)。

- [Skim](https://skim-app.sourceforge.io/)：PDF 阅读和编辑工具，阅读一般使用系统自带预览（Preview）。📍

- [LibreOffice](https://www.libreoffice.org/download/download-libreoffice/)：Office 办公套件，跨平台；可选产品有 [OpenOffice](https://www.openoffice.org/zh-cn/)、[OnlyOffice](https://www.onlyoffice.com/download-desktop.aspx)、[Google Docs](https://docs.google.com/)。

- [Anki](https://apps.ankiweb.net/)：智能学习系统，记忆学习训练，跨平台。📍

- [Lulu](https://github.com/objective-see/LuLu)：网络监控与防火墙工具，其他同一开发者的安全类工具可以[在这里](https://objective-see.org/tools.html)查看。📍

- [Stats](https://github.com/exelban/stats)：系统资源监视器，可自定义菜单栏显示内容。📍

- [Easydict](https://github.com/tisfeng/Easydict)：词典翻译工具，支持 OCR 和多种翻译服务；可选产品有 [Pot](https://github.com/pot-app/pot-desktop) 。📍

- [Loop](https://github.com/MrKai77/Loop)：轻量级窗口管理工具；可选产品有 [Rectangle](https://github.com/rxhanson/Rectangle)（含付费功能）。📍

- [Battery](https://github.com/actuallymentor/battery)：将电池电量限制在80%，延长电池寿命；可选产品有 [AIDente](https://apphousekitchen.com/zh-hans/)（含付费功能）。📍

- [GrandPerspective](https://grandperspectiv.sourceforge.net/)：可视化的方式展示系统所有文件的空间占用情况。

- [Whisky](https://github.com/Whisky-App/Whisky)：在 macOS 上运行 Windows 应用程序，**该项目不再维护**；可选产品有 [Kegworks](https://github.com/Kegworks-App/Kegworks) 。

- [UTM](https://mac.getutm.app/)：虚拟机管理工具；可选产品有 [VMware Fusion Pro](https://blogs.vmware.com/teamfusion/2024/05/fusion-pro-now-available-free-for-personal-use.html)、[VirtualBox](https://www.virtualbox.org/) 。📍

- [v2rayN](https://github.com/2dust/v2rayN)：网络代理管理工具；可选产品有 [Mihomo Party ](https://github.com/mihomo-party-org/mihomo-party)、[FIClash](https://github.com/chen08209/FlClash)、[Clash Nyanpasu](https://github.com/libnyanpasu/clash-nyanpasu)、[Sparkle](https://github.com/xishang0128/sparkle)等。

- [Obsidian](https://obsidian.md/)：本地化的知识管理工具，跨平台，含付费功能；可选产品有 [Logseq](https://logseq.com/)、[Anytype](https://anytype.io/)、[Zettlr](https://www.zettlr.com/) 等。📍

- [LICEcap](https://www.cockos.com/licecap/)：GIF 图片制作工具，跨平台；可选产品有 [GIPHY](https://giphy.com/apps/giphycapture)、[GIFski](https://github.com/sindresorhus/Gifski) 。📍

- [Zed](https://zed.dev/)：代码编辑工具，支持插件和 AI （需登录），跨平台；可选产品有 [CotEditor](https://coteditor.com/)、[VSCode](https://code.visualstudio.com/)、[CudaText](https://cudatext.github.io/) 等。📍

- [Zotero](https://www.zotero.org/)：文献综合管理工具，支持插件，跨平台；可选产品有 [Paperlib](https://paperlib.app/cn/) 。

- [GIMP](https://www.gimp.org/)：专业级图片编辑工具，类似 Photoshop，跨平台；可选产品有 [Krita](https://krita.org/zh-cn/) 或 Web版 [Photopea](https://www.photopea.com/) 。📍

- [Inkscape](https://inkscape.org/)：专业级矢量图编辑工具，类似 Illustrator，跨平台。📍

- [Shotcut](https://www.shotcut.org/)：音视频剪辑工具，跨平台；可选产品有 [Openshot](https://www.openshot.org/zh-hans/)、[LosslessCut](https://github.com/mifi/lossless-cut)、[Kdenlive](https://invent.kde.org/multimedia/kdenlive) 等。

- [Blender](https://www.blender.org/)：3D 创作套件，支持建模、渲染、动画、合成等功能，跨平台。📍

- [Audacity](https://www.audacityteam.org/)：音频录制和编辑工具，支持多种音频格式，跨平台。📍

- [Warp](https://www.warp.dev/)：终端管理工具，支持 AI，需登录使用，跨平台；可选产品有 [iTerm2](https://iterm2.com/index.html)、[Kitty](https://sw.kovidgoyal.net/kitty/)、[Tabby](https://tabby.sh/)、[Alacritty](https://alacritty.org/) 等。📍

- [MOS](https://github.com/Caldis/Mos)：鼠标增强工具，平滑鼠标滚动；可选产品有 [Mac-mouse-fix](https://macmousefix.com/) 。📍

- [HandBrake](https://handbrake.fr/)：视频转码器，支持视频格式转换和压缩，跨平台；可选产品有 [Shutter Encoder](https://www.shutterencoder.com/)。📍

- [Joplin](https://joplinapp.org/)：基于 Markdown 的笔记工具，跨平台；可选产品有 [MiaoYan](https://github.com/tw93/MiaoYan)、[MarkEdit](https://github.com/MarkEdit-app/MarkEdit) 。📍

- [LM Studio](https://lmstudio.ai/)：本地部署大模型工具，支持模型搜索/下载/聊天等功能，跨平台；可选产品有 [Ollama](https://ollama.com/)、[vMLX](https://github.com/jjang-ai/mlxstudio)。

- [Cherry Studio](https://github.com/CherryHQ/cherry-studio)：支持多服务商集成的 AI 对话客户端，跨平台；可选产品有 [ChatWise](https://chatwise.app/)（含付费功能）。

- [OmniDiskSweeper](https://www.omnigroup.com/more)：磁盘空间分析工具，快速查看大文件并打开或删除到废纸篓。

- [NetNewsWire](https://netnewswire.com/)：RSS 管理和阅读工具，跨平台；可选产品有 [Flare](https://github.com/DimensionDev/Flare) 。📍

- [Sigil](https://sigil-ebook.com/sigil/)：创建和编辑 EPUB 格式电子书。📍

- [Cyberduck](https://cyberduck.io/)：支持 FTP、SFTP、WebDAV、S3、OneDrive 等协议和云端存储浏览工具，跨平台。📍

- [f.lux](https://justgetflux.com/)：调整屏幕色温和亮度，保护眼睛。

- [Command X](https://sindresorhus.com/command-x)：在 Finder 中进行文件的剪切`Command+X`和粘贴`Command+V`小工具，代替传统复杂的快捷键。

- [Billfish](https://www.billfish.cn/)：素材管理工具，支持多种常见文件格式和浏览器插件；可选产品有 [Pixcall](https://pixcall.com/download) 。

- [Drawio](https://github.com/jgraph/drawio-desktop)：流程图和白板工具，[在线版本](https://app.diagrams.net/)；可选产品有 [Excalidraw](https://excalidraw.com/) 、[Drawnix](https://github.com/plait-board/drawnix)。

- [Achico](https://github.com/nuance-dev/achico)：图片、音视频和PDF等文件压缩工具，作者其他的 mini 工具可查他的 GitHub 主页。

- [TomatoBar](https://github.com/ivoronin/TomatoBar)：番茄时钟，菜单栏工具；可选产品有 [Tomito](https://tomito.app/) 。📍

- [Buzee](https://github.com/gsidhu/buzee-releases)：文件快速搜索工具，支持语法，跨平台；可选产品有 [Cardinal](https://github.com/ldm0/cardinal)、[Cling](https://github.com/FuzzyIdeas/Cling)等。

- [Kiwix](https://kiwix.org/en/)：离线查看 Wikipedia、TED、StackExchange 或其他网站资源的工具，跨平台。📍

- [FixTim](https://github.com/Lakr233/FixTim)：修复 macOS 上一些奇怪的系统 bug （不包含硬件或 kernel 问题）而无须重启系统。

- [Office-Reset](https://office-reset.com/)：解决 MS Office for Mac 系列软件的各种疑难杂症。

- [OpenMTP](https://github.com/ganeshrvel/openmtp)：用于 Mac 和 Android 之间安全的传输文件。📍

- [ProNotes](https://www.pronotes.app/)：默认备忘录的增强插件，支持格式栏、Markdown、命令等，AI功能付费。

- [MinerU](https://github.com/opendatalab/MinerU)：支持 PDF/Word 等文档解析输出 Markdown/HTML 等格式，跨平台[图形化](https://mineru.net/)版本。

- [Upscayl](https://github.com/upscayl/upscayl)：使用 AI 模型实现图片无损放大的工具，跨平台；可选产品有 [HiPixel](https://github.com/okooo5km/HiPixel) 。📍

- [Mounty](https://mounty.app/)：可以将 NTFS 分区重新挂载为读写模式。📍

- [Itsycal](https://www.mowglii.com/itsycal/)：菜单栏日历软件，支持 URL scheme 和集成系统日历。

- [Karabiner-Elements](https://github.com/pqrs-org/Karabiner-Elements)：键盘自定义工具，内置规则，也可以自行配置。

- [Zen](https://github.com/ZenPrivacy/zen-desktop)：通过拦截 HTTP 请求来实现系统级的广告过滤和隐私防护工具。

- [InputSourcePro](https://github.com/runjuu/InputSourcePro)：为每个应用设置不同的输入法，避免频繁切换。📍

- [SyntaxHighlight](https://github.com/sbarex/SourceCodeSyntaxHighlight)：为系统自带的快速预览（ Quick Look ）增加代码高亮功能，支持自定义。📍

- [Czkawka](https://github.com/qarmin/czkawka)：重复文件查找工具，支持空文件/文件夹、临时文件、损坏文件等，跨平台。

- [FlashSpace](https://github.com/wojciech-kulik/FlashSpace)：虚拟工作空间管理工具，支持多显示器和其他自定义配置。📍

- [OnyX](https://www.titanium-software.fr/en/onyx.html)：多功能实用工具，进行多种系统配置，替代复杂的系统命令。

- [LaunchNext](https://github.com/RoversX/LaunchNext)：仅适用 macOS 26（Tahoe），将传统的 Launchpad 重新带回来。

- [wBlock](https://github.com/0xCUB3/wBlock)：Safari 浏览器的广告拦截器。

- [macUSB](https://github.com/Kruszoneq/macUSB)：制作 Mac 启动盘，支持 M 芯片和 Intel 芯片。📍

- [flux-markdown](https://github.com/xykong/flux-markdown)：空格键预览 markdown 文档，支持公式、图表、导出等；可选产品有[QLMarkdown](https://github.com/sbarex/QLMarkdown)。
  
## Buy me a coffee
<img width = "380" height = "400" src="https://raw.githubusercontent.com/holyshell/StudyNotes/refs/heads/master/images/justforfun.jpg">

## Star History

<a href="https://www.star-history.com/#holyshell/AppsForMac&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=holyshell/AppsForMac&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=holyshell/AppsForMac&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=holyshell/AppsForMac&type=Date" />
 </picture>
</a>
