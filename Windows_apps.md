## 系统级的APP

开发环境
1. [ ] Windows 功能: 虚拟机相关功能
2. [ ] windows 可选功能: openssh 
## 绿色纯净版应用

为提高体验和降低消耗系统资源, 将那些互联网应用 天天更新版本的, 而且一大堆广告的通通换掉.
换成绿色版 免更新的.

## 浏览器

浏览器设置和油猴脚本

浏览器网页应用:
- 微信读书
- deepseek
- 通义千问

插件

| 应用                                                   | appid | 描述                          | 备注  |
| :--------------------------------------------------- | :---- | :-------------------------- | :-- |
| 沉浸式翻译                                                |       | 以沉浸式的阅读体验 将翻译结果逐段镶嵌在网页段落的后面 |     |
| darkmode                                             |       |                             |     |
| focus reader(安卓)<br>Rss feeder(浏览器)<br>feedly(跨平台收费) |       | rss feed 阅读                 |     |
| 油猴脚本                                                 |       |                             |     |

## workspace anywhere 中的 共享存储 网盘,同步,备份 通用基础存储

| 应用            | appid                  | 描述                                                                                                                               | 备注  |
| :------------ | :--------------------- | :------------------------------------------------------------------------------------------------------------------------------- | :-- |
| Alist desktop | Xmarmalade.AlistHelper | Alist.支持国内外众多网盘的挂载并以 webdav 提供服务, 同时提供索引搜索, 增删改查, 流媒体点播登基本功能。                                                                    |     |
| OneDrive      | Microsoft.OneDrive     | Onedrive.对于工作区数据和其他所有重要数据,是一个十分完美的跨平台同步应用,独一档或者独二档的存在, 在国内致命的缺点是目前 还没找到合作商提供个人存储服务,世纪互联的商业版太贵,教育版缩水且无法挂载,便宜管饱的无国内备案的国际版个人服务域名被墙. |     |
| 百度网盘          | Baidu.BaiduNetdisk     | 百度网盘: 功能丰富 量大管饱, 支持10设备登录,支持双向增量同步, 三方支持不友好. 适合工作数据                                                                              |     |
| 阿里云盘          | Alibaba.aDrive         | 阿里网盘: 功能相对不丰富,对于工作党最重要的功能没有:提供文件历史版本的双向增量同步功能，svip量大管饱,10设备; 加钱后三方支持友好. 可以安装各种折腾应用，不过最大1T流量。                                     |     |
| 网盘聚合挂载工具      | manually-clouddrive    | 网盘聚合工具和文件管理工具：网盘聚合再挂载到无感的本地文件夹,支持webdav,自动备份任务,秒传,自动加密解密,流媒体播放                                                                   |     |
| 115网盘         | 115.115Chrome          | 115 网盘, 国内磁力无线的龙头, 有一定的抗投诉能力，适合做加密备份盘、中转盘、下载工具、资源囤盘                                                                              |     |
|               |                        |                                                                                                                                  |     |

### nas 的备份客户端

| 应用                                                    | appid                                       | 描述                                                                                                                                                                            | 备注  |
| :---------------------------------------------------- | :------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-- |
| 群晖版私人 Onedrive                                        | Synology.DriveClient                        | 群晖的文件夹双向增量同步工具,支持历史版本. 像是 Onerive 的备份同步工具                                                                                                                                     |     |
| 群晖助手                                                  | Synology.Assistant                          | 群晖助手，发现管理群晖设备                                                                                                                                                                 |     |
|                                                       |                                             |                                                                                                                                                                               |     |
| 群晖的系统备份工具                                             |                                             |                                                                                                                                                                               |     |
|                                                       | Synology.ActiveBackupForBusinessAgent       | 群晖 的 windows系统备份工具                                                                                                                                                            |     |
| manually-Synology Hyper Backup Explorer               |                                             | 用于浏览、解码和提取 Hyper Backup 库中不同版本备份数据的桌面工具                                                                                                                                       |     |
| manually-Synology Active Backup for Business 还原媒体建立工具 |                                             |                                                                                                                                                                               |     |
| manually-Synology Active Backup for Business 还原向导     |                                             |                                                                                                                                                                               |     |
| manually-Synology Cloud Sync Decryption Tool          |                                             | cloudsync 加密的内容的解密工具                                                                                                                                                          |     |
| manually-Synology Storage Console for Windows         |                                             | Synology Storage Console for Windows 是 Windows 上的一个存储管理工具，可帮助管理员简化对多个 Synology NAS 的监控。安装 Storage Console 后，您可以直接从 DSM 获取应用程序一致性快照                                            |     |
|                                                       |                                             |                                                                                                                                                                               |     |
|                                                       |                                             |                                                                                                                                                                               |     |
|                                                       |                                             |                                                                                                                                                                               |     |
| 同步备份工具                                                |                                             |                                                                                                                                                                               |     |
| 猫头鹰文件                                                 | 9NW9NWHZLMW6                                | 猫头鹰文件，截止目前 2024/11/1，支持国内多个网盘商，提供云端和本地的双向增量同步功能, 无法自定义同步的一些细节，如冲突解决, 同步删除操作等.                                                                                                 |     |
| resilio                                               | manually-resilio                            | 无服务器 P2P 多设备同步一个文件夹会像bittorrent一样. 具有 Onedrive 的同步功能和分享功能, (文件占位符)释放/保留/. 官网:https://www.resilio.com/sync/, 参考教程文章: https://linux.do/t/topic/186892                           |     |
| goodsync                                              | manually-goodsync                           | p2p sync, anywhere <-> anywhere 实际上电脑内部就可以. 经过测试在公网内从云端到手机安卓，走的是小水管服务器. 融合多个存储平台，统一管理，并在这些存储的基础上，建立一个含有版本控制等功能的同步空间。 P2P 链接. 跨平台. pro 版收费, 用例 https://linux.do/t/topic/186169 |     |
| foldersync                                            | manually-foldersync                         | 安卓 <=> 云端. folder sync, 跟 goodsync 有些类似，但是没有版本控制等等。                                                                                                                           |     |
|                                                       | mannualy-android-foldersync-clouddrive2-rcx | 联合提供文件同步服务.                                                                                                                                                                   |     |

## 基于 Netdisk 的跨平台应用层

### 手机自带应用 kit

日历
联系人
短信
mail
todo, 便签

### noting 笔记

以下两个 markdown 工具配合 百度网盘/onedrive 的同步功能 都是跨设备的好工具, 其中 obsidian 支持安卓端, 如何不用 百度网盘和 Onedrive 可能需要自己搭 webdav 和采取一些额外的同步工具

| 应用       | appid             | 描述                                                                            | 备注  |
| :------- | :---------------- | :---------------------------------------------------------------------------- | :-- |
| Typora   | appmakes.Typora   | 所见即所得 优雅强大的 markdown 编辑工具, 但被指出当行数达到几千行时会遇到性能问题。                              |     |
| Obsidian | Obsidian.Obsidian | 开源的 所见即所得 优雅强大的 markdown 编辑工具, 多插件支持, 底层文件结构即原始markdown目录结构，无缝换其他工具，这点开放性有点很棒 |     |
| Joplin   | Joplin.Joplin     | 跟 EverNote 相似, 支持 webdav 同步                                                   |     |



### 阅读

| 应用         | appid                  | 描述                                                                     | 备注  |
| :--------- | :--------------------- | :--------------------------------------------------------------------- | :-- |
| NeatReader | GauzyTech.NeatReader   | 电子书阅读, 如 mobi, epub                                                    |     |
| Drawboard  | mannually-9WZDNCRFHWQT | Drawboard, 免费的沉浸式 pdf 阅读手写笔记器, 以前收费现在阶梯收费,使用老版本的滑还是有足够的手写功能. 配置可通过账号同步 |     |
| pdf reader | 9NBLGGH67WLK           | pdf reader, 挺丝滑,额头大, PDF Reader - View and Edit PDF                    |     |
| xodo       | 9WZDNCRDJXP4           | 比较丝滑的 pdf 阅读编辑器，就是额头有点大                                                |     |
| 微信读书       | manually-weread        | https://weread.qq.com/微信阅读, 跨平台优雅                                      |     |
|            |                        |                                                                        |     |

### office 办公套件

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| 金山文档 wps |Kingsoft.WPSOffice                            | WPS| 出道比微软还早 |
| 微软办公套件 |manually-microsoft-office                       | microsoft offie 个人版|  |
|  |NetEase.MailMaster                            | 网易邮箱大师|  |

### 学生应用

| 应用                      | appid                             | 描述                                                                                       | 备注  |
| :---------------------- | :-------------------------------- | :--------------------------------------------------------------------------------------- | :-- |
| Parsec                  | Parsec.Parsec                     | 拿着平板(+充电宝)上课、去图书馆, 串流到宿舍的电脑，性能\续航 无敌，只有最强没有之一. 还能玩3A游戏惊艳一下隔壁的小伙伴                         |     |
| 欧路词典                    | EuSoft.Eudic                      | 欧陆词典, 英语学习者 或者严肃查词典必备, 请到淘宝或者闲鱼购买激活码, 到淘宝购买词典扩充包或者下载我提供的几个包                              |     |
| GoldenDict              | xiaoyifang.GoldenDict-ng          | Golendict 查单词，干净古老的可扩展查词工具。                                                              |     |
| noteexpress             | manually-noteexpress              | 文献管理工具，国产软件，到闲鱼买个吧, https://www.inoteexpress.com/aegean/                                 |     |
| EndNote                 | ClarivateAnalytics.EndNote        | EndNote, 收费，到某宝小黄鱼买个                                                                     |     |
| Drawboard               | 9WZDNCRFHWQT                      | Drawboard, 免费的沉浸式 pdf 阅读手写笔记器, 以前收费现在阶梯收费,使用老版本的滑还是有足够的手写功能                              |     |
| Zotero                  | DigitalScholar.Zotero             | Zotero 是一个免费且易用的文献管理工具，可以帮助你收集、整理、引用和分享你的研究资讯。                                           |     |
| Mendeley                | Elsevier.MendeleyReferenceManager | Mendeley 是一款免费的跨平台文献管理软件，同时也是一个在线的学术社交网络平台，可一键抓取网页上的文献信息添加到个人图书馆中；比较适合本地操作和大量 PDF 的文件管理。 |     |
| Latex 在线编辑器<br>Overleaf | Overleaf                          | 可以自己搭建服务器                                                                                |     |
| Mathpix                 | Mathpix.MathpixSnippingTool       | 手写公式识别, 还有 latex, 公式互转. 某宝买会员.                                                           |     |

## 多媒体, 影音娱乐

相册,音乐,文档,录音,视频 通过clouddrive2增量加密备份到云盘就好, 多端重新解密出来同步, 偶尔 diff 一下

基础通信: 联系人/短信 使用qq同步助手吧, 感觉就是用来注册账号/收发验证码

  笔记/日历/待办 使用第三方的软件,已经解决好同步问题

| 应用         | appid                     | 描述                                                                                               | 备注                                     |
| :--------- | :------------------------ | :----------------------------------------------------------------------------------------------- | :------------------------------------- |
| PotPlayer  | Daum.PotPlayer            | 目前近乎万能的播放器, 新版支持杜比视界, 见帖子汇总:https://v2ex.com/t/1023976                                           |                                        |
| qq音乐       | Tencent.QQMusic           | qq音乐，就是音乐库多, 但是搜到的在线音乐不能播放本地的音源，只能在本地音乐界面播放。                                                     |                                        |
| 网易云        | NetEase.CloudMusic        | 网易云                                                                                              |                                        |
| 酷我音乐       | manually-kwmusic          | 酷我音乐下载歌曲                                                                                         |                                        |
| 网易filmly   | manaully-filmly           | 不支持windows, 跨平台 https://filmly.163.com/                                                          |                                        |
| emby       | manually-emby             | emby client for windows                                                                          |                                        |
| powerdvd   | manually-powerdvd         | 蓝光播放器                                                                                            |                                        |
| 漫步者耳机PC客户端 | manually-edifier-tempohub | 漫步者耳机电脑软件                                                                                        |                                        |
| 洛雪音乐播放器    | lyswhut.lx-music-desktop  | 一款开源自由开放的音乐播放器, 支持自定义音源. 风格简洁, 歌曲元数据齐全洛雪音乐播放器.如果喜欢音乐, 一定要去平台上用力所能及的方式去支持捐款给创作者, 包括但不限于歌手. 软件创作者. |                                        |
| Kodi       | XBMCFoundation.Kodi       | 开源 强大的跨平台多媒体播放器, 能够刮削                                                                            |                                        |
| MusicFree  | maotoumao.MusicFree       | 跨平台音乐播放器, 跟洛雪类似, 但功能比洛雪完善一点点. musicfree 配合网易云或者椒盐 可以了. 自定义音源.                                    | https://github.com/maotoumao/MusicFree |
| AfuseKt    |                           | 支持 安卓TV 和 安卓手机 的海报墙刮削和观看，支持挂载多网盘和webdav sambda 等网络形式的硬盘。                                         | 挺不错的。                                  |

## 内容创作与设计

| 应用          | appid                    | 描述     | 备注  |
| :---------- | :----------------------- | :----- | :-- |
| gif制作       | NickeManarin.ScreenToGif | Gif 制作 |     |
| photoshop   |                          |        |     |
| solidworkds |                          |        |     |
| 剪辑          |                          |        |     |

## 社交聊天

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| 微信 |Tencent.WeChat                                | 微信|  |
| Tim |Tencent.TIM                                   | 简洁 QQ|  |
| Telegram |Telegram.TelegramDesktop                      | 小飞机|  |
| [微信多开](https://github.com/huiyadanli/RevokeMsgPatcher?tab=readme-ov-file)<br>防撤回 |manually-RevokeMsgPatcher                     | 微信 qq tim 多开+防撤回, |  |

## AI助手

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| 字节的豆包 |ByteDance.Doubao                              | 字节跳动旗下的豆包 AI 大模型助手, 免费|  |
| 阿里的通义千问 |manually-通义千问|  ||
| github 的copilot |manually-github-copilot|  ||

## 浏览器

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| Firefox |Mozilla.Firefox                               | 主要看中他的 session container | winget install Mozilla.Firefox --locale en-US|
| Chrome |Google.Chrome                                 | 谷歌浏览器|  |
| Edge |Microsoft.Edge                                | 微软自家的浏览器，用来看 pdf, 采用的内核与谷歌一样，哪个好用，差不多，看个人习惯，移动端 edge 比较符合国人习惯|  |

## 网络

| 应用                 | appid                       | 描述                             | 备注  |
| :----------------- | :-------------------------- | :----------------------------- | :-- |
| v2rayN             | 2dust.v2rayN                | 魔法上网                           |     |
| ClashVergeRev      | ClashVergeRev.ClashVergeRev | 魔法上网                           |     |
| ToDesk远程桌面         | Youqu.ToDesk                | 远程桌面, 修电脑, 更好的内网穿透链接要收费        |     |
| Parsec串流           | Parsec.Parsec               | 串流远程桌面, 丝滑, 打游戏                |     |
| Sunshine串流         | LizardByte.Sunshine         | 串流工具                           |     |
| gameviewer串流       | mannually-gameviewer        | 网易出的串流工具                       |     |
| ZeroTierOne        | ZeroTier.ZeroTierOne        | 用于建立虚拟局域网，方便远程 RDP 或者是同步软件同步数据 |     |
| adguard(安卓 李跳跳app) |                             | 拦截广告, 净化数字世界                   |     |

## 安全

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| 强大的密码本 |Bitwarden.Bitwarden                           | 密码即服务|  |
| 火绒 |XPDNH1FMW7NB40                                | huorong 火绒安全软件,告别360,功能强大全方位防护,无广告,不弹窗,不流氓,无全家桶捆绑|  |
| 密码本 |KeePassXCTeam.KeePassXC                       | 无服务端的 密码软件，可以通过同步软件同步到云端, bitwarden 有的功能都有了，就是界面没那么好看|  |

## 美化

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| MacType |MacType.MacType                               | 旨在为 Windows 提供类似 macOS 的字体渲染效果, 没感觉有啥区别|  |

## 系统工具与瑞士军刀效率琐碎玩意

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|

### 系统工具

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| DiskGenius |Eassos.DiskGenius                             | 磁盘工具|  |
| ProcessExplorer |Microsoft.Sysinternals.ProcessExplorer        | 升级版专业版的任务管理器|  |
| windows版htop |gsass1.NTop                                   | 命令行的任务管理器|  |
|  ||  ||
| 连接手机 |9NTXGKQ8P7N0                                  | Cross Device Experience, 链接手机|  |
| OneCommander |MilosParipovic.OneCommander                   | 替代 Windows 自带的文件管理器, 高性能, 多选项卡, 多列布局(macos finder), 双窗格对照, 正则重命名等等|  |
| SpaceSniffer |UderzoSoftware.SpaceSniffer                   | 可视化 磁盘空间管理，C盘快满了, 怎么办呢|  |
| twinkletray |xanderfrangos.twinkletray                     | 外接屏可以通过 Windows 来调整亮度, 将两者调整为同步亮度, 再打开 笔记本的自动调整亮度，完美。|  |
| CCleaner |manually-Piriform.CCleaner                    | 清理注册表，文件查重|  |
| TrafficMonitor |manually-TrafficMonitor                       | 监控 cpu/gpu/网络等 usage, 温控信息, 置于任务栏中  | https://github.com/zhongyang219/TrafficMonitor/releases/latest|
| CPU 监控 |ALCPU.CoreTemp | CPU 温度 负载 功耗 主频等/内存利用率 | |

### 效率玩意

| 应用         | appid                    | 描述                                  | 备注  |
| :--------- | :----------------------- | :---------------------------------- | :-- |
| Everything | voidtools.Everything     | everything 高性能,超快响应的 windows 文件搜索工具 |     |
| PowerToys  | Microsoft.PowerToys      | 瑞士军刀                                |     |
| PixPin     | PixPin.PixPin            | 截图工具, 可以替代微信q 截图功能到OCR              |     |
| WizTree    | AntibodySoftware.WizTree | 类似于查找大文件，但更快速，找出，树状图显示，找出重复文件和大文件   |     |
| 微信输入法      | Tencent.WeType           | 微信拼音                                |     |
| 搜狗输入法      | Sogou.SogouInput         | 搜狗输入法, 搞得花里胡哨的, 广告多,微信更简单           |     |


### 办公效率

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| uTools |Yuanli.uTools                                 | 桌面级的工作流超级工具，按Alt+空格，连接 AI, 搜索引擎, 本地应用打开, 本地文件搜索.|  |
| 7zip |7zip.7zip                                     | 开源解压缩软件，支持多种格式, 平替 winrar|  |
| CopyQ |hluk.CopyQ                                    | 剪贴板工具|  |
| Motrix |agalwood.Motrix                               | 开源免费下载工具: 简单 小而美 但足够强大和全能，如此谬赞只因为现在的应用都在拼命卖广告割韭菜.|  |
| 画图工具Draw |JGraph.Draw                                   | draw.io 本地版.画图工具，开源免费强大，对于制作 PPT 的流程图 示意图绰绰有余, 无需登录，无广告，无流氓行为|  |
| AutoHotkey |AutoHotkey.AutoHotkey                         | 自动化重复按键操作|  |
| 按键精灵 |按键精灵|  ||
| onequick |9PFN5K6QXT46                                  | onequick 自动化 Windows 的动作< 整理成高层任务式子命令|  |
| Quicker |LiErHeXun.Quicker                             | 同上, 点点点, 无需记住命令，鼠标点就完了。|  |
| mykeymap |mykeymap                                      | 基于 autohotkey, 经过仔细优化工作实际场景，来通过 GUI 的方式定义键盘映射，用键盘控制鼠标，符合国人需求, 中文界面 | https://xianyukang.com/MyKeymap.html |
| wgestures |wgestures                                     | 同上 鼠标手势 https://www.yingdev.com/projects/wgestures2|  |

## 健康与健身

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
|  |https://musclewiki.com/                       | web 应用|  |

## 影音技术

| 应用                                                                                              | appid                            | 描述                                                                                                                      | 备注  |
| :---------------------------------------------------------------------------------------------- | :------------------------------- | :---------------------------------------------------------------------------------------------------------------------- | :-- |
| FFmpeg                                                                                          | Gyan.FFmpeg                      | 音视频编码和转码，非常强大                                                                                                           |     |
| [蓝牙LDAC驱动](https://www.bluetoothgoodies.com/a2dp/)                                              | manually-Alternative-A2DP-Driver | windows 目前不支持 蓝牙高码率音频输出，安装该驱动可达到 双通道 24bit 96khz 采样,                                                                    |     |
| Dolby Access                                                                                    | 9N0866FS04W8                     | Dolby Access, 淘宝 10块钱的杜比音效/视界激活码                                                                                        |     |
| [hevc来自设备制造商的视频扩展](https://apps.microsoft.com/detail/9n4wgh0z6vhq?ocid=pdpshare&hl=en-us&gl=US) | 9n4wgh0z6vhq                     | hevc 8k 视频解码包,笔记本已经装好 来自设备制造商的视频扩展 hevc HEVC Video Extensions from Device Manufacturer,                                 |     |
| hevc 视频扩展                                                                                       | 9NMZLZ57R3T7                     | hevc 视频扩展 https://www.microsoft.com/store/productId/9NMZLZ57R3T7?ocid=pdpshare                                          |     |
| Dolby Vision Extensions                                                                         | 9pltg1lwphlf                     | Dolby Vision Extensions https://apps.microsoft.com/detail/9pltg1lwphlf?ocid=libraryshare&hl=en-us&gl=US                 |     |
| Dolby Digital Plus decoder for PC OEMs                                                          | 9nvjqjbdkn97                     | Dolby Digital Plus decoder for PC OEMs  https://apps.microsoft.com/detail/9nvjqjbdkn97?ocid=libraryshare&hl=en-us&gl=US |     |

## 编程开发

| 应用             | appid                               | 描述                                                                                                      | 备注  |
| :------------- | :---------------------------------- | :------------------------------------------------------------------------------------------------------ | :-- |
| VsCode         | Microsoft.VisualStudioCode          | 微软开发的热门的开源编程IDE                                                                                         |     |
|                | manually-vscode-gitlens-pro         | https://linux.do/t/topic/181333                                                                         |     |
| Nvim           | Neovim.Neovim                       | 将 vim 搬到 Windows 上用, 用于偶尔的轻编辑, 重活还是让 vscode 和 其他 IDE 来吧                                                 |     |
| Git            | Git.Git                             | 版本管理工具                                                                                                  |     |
| Cygwin         | Cygwin.Cygwin                       | Windows 上的 unix like 终端, git bash, wsl1, wsl2, cygwin, MSYS2, nushell 讨论:https://cn.v2ex.com/t/1051792, |     |
|                |                                     |                                                                                                         |     |
|                |                                     |                                                                                                         |     |
| WinSCP         | WinSCP.WinSCP                       | 图形化的 SCP，通过 ssh 加密传输文件                                                                                  |     |
| Windows 终端     | Microsoft.WindowsTerminal           | Windows 终端.                                                                                             |     |
| Chocolatey     | Chocolatey.Chocolatey               | 另一个包管理利器, chocolatey.                                                                                   |     |
|                |                                     |                                                                                                         |     |
| bash tool set  |                                     |                                                                                                         |     |
| grep的进阶版       | JFLarvoire.Ag                       | silver searcher                                                                                         |     |
| everythign-cli | voidtools.Everything.Cli            | everything cli                                                                                          |     |
|                |                                     |                                                                                                         |     |
| 其他             |                                     |                                                                                                         |     |
| scrcpy         | Genymobile.scrcpy                   | 电脑控制手机                                                                                                  |     |
| adb            | Google.PlatformTools                | adb 安卓手机调试工具                                                                                            |     |
| python         | Python.Python.3.13                  | python                                                                                                  |     |
| BestTrace      | IPIP.BestTrace                      | 路由追踪                                                                                                    |     |
| DevToys        | DevToys-app.DevToys                 | 编程开发瑞士军刀, 不用再在网上找一些信不过的网页做啥 json 转换等等                                                                   |     |
| GitKraken      | manually-Axosoft.GitKraken          | 漂亮的 git 客户端， 再也不用傻傻搞不清楚了                                                                                |     |
| Fiddler        | manually-Telerik.Fiddler.Everywhere | Windows 抓包工具, 收费                                                                                        |     |
| Termius        | manually-Termius.Termius            | ssh 连接工具, 其实用处有限, 配置好 shell 后在 powershell 一个命令就能连上了，为啥要 gui 管理啥呢。                                       |     |
| NavicatPremium | manually-PremiumSoft.NavicatPremium | 数据库工具                                                                                                   |     |
| Nexttrace      | manually-Nexttrace                  | 路由追踪工具                                                                                                  |     |
| Postman        | Postman.Postman                     | Web API 开发必备                                                                                            |     |
| PyCharm        | JetBrains.PyCharm.Professional      | JB 的 pycharm, 强大 IDE                                                                                    |     |
| IntelliJIDEA   | JetBrains.IntelliJIDEA.Ultimate     | JB 的 java IDE                                                                                           |     |

## 依赖

| 应用 | appid | 描述  |  备注 |
|:--|:--|:--|:--|
| NodeJS |OpenJS.NodeJS                                 |  ||
