# Awesome Tools

我常用或收集的工具，持续更新，分享的同时也方便自己查找。  
虽然已经有很多 [Awesome List](https://github.com/sindresorhus/awesome#readme)，但是太多了，找起来很不方便，还是整理一份自己的。

## Contents

- [Awesome Tools](#awesome-tools)
    - [Contents](#contents)
    - [Alfred Workflows](#alfred-workflows)
    - [Automation](#automation)
    - [Backup](#backup)
    - [Bastion Host](#bastion-host)
    - [BitTorrent](#bittorrent)
    - [Browsers](#browsers)
    - [Cheat Sheet](#cheat-sheet)
    - [Chrome Extensions](#chrome-extensions)
    - [CI/CD](#cicd)
    - [Cloud Storage](#cloud-storage)
    - [Collaboration Software / Wiki](#collaboration-software--wiki)
    - [Command Line](#command-line)
        - [Rewritten in Rust](#rewritten-in-rust)
    - [Communication](#communication)
    - [Content Management Systems](#content-management-systems)
    - [Data Visualization and Analytics](#data-visualization-and-analytics)
    - [Databases](#databases)
    - [Design and Product](#design-and-product)
    - [Development](#development)
    - [Docker](#docker)
    - [Documentation Generator](#documentation-generator)
    - [Editors/IDEs](#editorsides)
    - [Email](#email)
    - [File Managers](#file-managers)
    - [File Organization](#file-organization)
    - [File Sharing and Synchronization](#file-sharing-and-synchronization)
    - [File System Events Monitoring](#file-system-events-monitoring)
    - [Finance](#finance)
    - [Fonts](#fonts)
    - [Games](#games)
    - [Git](#git)
    - [Github](#github)
    - [HTTP/S Debug](#https-debug)
    - [Identity Management](#identity-management)
    - [Image Optimizers](#image-optimizers)
    - [IP Geolocation](#ip-geolocation)
    - [Let's Encrypt](#lets-encrypt)
    - [Linux/VPS Benchmarking](#linuxvps-benchmarking)
    - [Markdown](#markdown)
    - [Media](#media)
    - [Monitoring](#monitoring)
    - [Music](#music)
    - [Networking](#networking)
    - [Note-taking](#note-taking)
    - [Password Managers](#password-managers)
    - [PDF](#pdf)
    - [Project Management](#project-management)
    - [Prototyping and Mind-Mapping](#prototyping-and-mind-mapping)
    - [Proxy and VPN](#proxy-and-vpn)
    - [Proxy Rules And Scripts](#proxy-rules-and-scripts)
    - [Python](#python)
        - [Linter](#linter)
        - [Formatter](#formatter)
        - [Package Management](#package-management)
        - [Packages](#packages)
    - [Regular Expressions](#regular-expressions)
    - [Remote Desktop](#remote-desktop)
    - [Robotic Process Automation](#robotic-process-automation)
    - [RSS](#rss)
    - [Screencapturing](#screencapturing)
    - [Security](#security)
    - [SSH](#ssh)
    - [Task Management/To-Do Lists](#task-managementto-do-lists)
    - [Terminal](#terminal)
    - [Testing](#testing)
    - [Text Expander](#text-expander)
    - [Time Tracking](#time-tracking)
    - [Utilities](#utilities)
    - [VSCode Extensions](#vscode-extensions)
    - [Window Management](#window-management)
    - [Zsh plugin](#zsh-plugin)

## Alfred Workflows

TODO: 待补充。

## Automation

- [Ansible](https://www.ansible.com/) - IT 自动化工具。
- [AutoIt](https://www.autoitscript.com/site/) - 类按键精灵，用这个实现过不少东西，还有一些 GUI。
- [bake-cli](https://github.com/kennethreitz-archive/bake) - 加强版 Make。
- [Fabric](https://www.fabfile.org/) - SSH 自动化工具。
- [GNU Make](https://www.gnu.org/software/make/)
- [Hammerspoon](https://www.hammerspoon.org/) - 基于 Lua 的自动化工具，比如窗口管理之类的。
- [just](https://github.com/casey/just) - 类似 make。
- [xmake](https://xmake.io/) - 类似 make。

## Backup

- [Arq](https://www.arqbackup.com/) - 常驻的备份软件。
- [BorgBackup](https://www.borgbackup.org/) - [开源](https://github.com/borgbackup/borg) 备份软件，强烈推荐。
- [borgmatic](https://github.com/witten/borgmatic) - BorgBackup 简化工具。
- [Carbon Copy Cloner](https://bombich.com/) - 备份软件。
- [duplicity](http://duplicity.nongnu.org/) - 还是更喜欢 BorgBackup。
- [Google 备份与同步](https://support.google.com/a/answer/2490101?hl=en&ref_topic=7455083)
- [Mackup](https://github.com/lra/mackup) - macOS 下应用设备备份/同步工具。
- [Restic](https://restic.net/) - 还是更喜欢 BorgBackup。
- [Vorta](https://vorta.borgbase.com/) - Borg Backup 的图形化客户端，[开源](https://github.com/borgbase/vorta)。

## Bastion Host

- [JumpServer](https://www.jumpserver.org/) - [开源](https://github.com/jumpserver)。
- [Teleport](https://goteleport.com/) - [开源](https://github.com/gravitational/teleport)。

## BitTorrent

- [Deluge](https://deluge-torrent.org/)
- [qBittorrent](https://www.qbittorrent.org/)
- [rTorrent](https://github.com/rakshasa/rtorrent)
- [rutorrent](https://github.com/Novik/ruTorrent) - rTorrent 的 Web 管理界面，配合 RSS 插件挂 PT。
- [Transmission](https://transmissionbt.com/)

## Browsers

- [Firefox](https://www.mozilla.org/en-US/firefox/products/)
- [Google Chrome](https://www.google.com/intl/en_us/chrome/)
- [Microsoft Edge](https://www.microsoft.com/en-us/edge)
- [Tor](https://www.torproject.org/) - 洋葱头。

## Cheat Sheet

- [cheat.sh](https://cheat.sh) - [开源](https://github.com/chubin/cheat.sh)。
- [cheat](https://github.com/cheat/cheat)
- [navi](https://github.com/denisidoro/navi) - Rust 写的。
- [tealdeer](https://github.com/dbrgn/tealdeer) - [tldr](https://github.com/tldr-pages/tldr) 的 Rust 实现。
- [tldr](https://github.com/tldr-pages/tldr)

## Chrome Extensions

TODO: 待补充说明。

- [1Password](https://chrome.google.com/webstore/detail/aomjjhallfgjeglblehebfpbcfeobpgk)
- [Archiveror](https://chrome.google.com/webstore/detail/cpjdnekhgjdecpmjglkcegchhiijadpb)
- [Aria2 for Chrome](https://chrome.google.com/webstore/detail/mpkodccbngfoacfalldjimigbofkhgjn)
- [Behave!](https://chrome.google.com/webstore/detail/mppjbkhgconmemoeagfbgilblohhcica)
- [CL1024](https://chrome.google.com/webstore/detail/efdllnloheadnjjahfmdohomdphlgcjm)
- [Close Duplicate Tab](https://chrome.google.com/webstore/detail/lccfnphpgnpeghoffocbacbkohbapinm)
- [Decentraleyes](https://chrome.google.com/webstore/detail/ldpochfccmkkmhdbclfhpagapcfdljkj)
- [Enhanced GitHub](https://chrome.google.com/webstore/detail/anlikcnbgdeidpacdbdljnabclhahhmd)
- [Extensions Manager](https://chrome.google.com/webstore/detail/lpleipinonnoibneeejgjnoeekmbopbc)
- [FireShot](https://chrome.google.com/webstore/detail/mcbpblocgmgfnpjjppndjkmgjaogfceg)
- [flomo](https://chrome.google.com/webstore/detail/okejodhgjffocohdpiacebjaahnoljim)
- [Gitako - GitHub file tree](https://chrome.google.com/webstore/detail/giljefjcheohhamkjphiebfjnlphnokk)
- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/gcbommkclmclpchllfjekcdonpmejbdp)
- [JSONView](https://chrome.google.com/webstore/detail/chklaanhfefbnpoihckbnefhakgolnmc)
- [Markdown Here](https://chrome.google.com/webstore/detail/elifhakcjgalahccnjkneoccemfahfoa)
- [MarkDownload - Markdown Web Clipper](https://chrome.google.com/webstore/detail/pcmpcfapbekmbjjkdalcgopdkipoggdi)
- [Privacy Badger](https://chrome.google.com/webstore/detail/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)
- [Refined GitHub](https://chrome.google.com/webstore/detail/hlepfoohegkhhmjieoechaddaejaokhf)
- [Roam-highlighter](https://chrome.google.com/webstore/detail/mcoimieglmhdjdoplhpcmifgplkbfibp)
- [Save Page WE](https://chrome.google.com/webstore/detail/dhhpefjklgkmgeafimnjhojgjamoafof)
- [SimilarWeb](https://chrome.google.com/webstore/detail/hoklmmgfnpapgjgcpechhaamimifchmp)
- [SimpRead](https://chrome.google.com/webstore/detail/ijllcpnolfcooahcekpamkbidhejabll)
- [SingleFile](https://chrome.google.com/webstore/detail/mpiodijhokgodhhofbcjdecpffjipkle)
- [Smart TOC](https://chrome.google.com/webstore/detail/lifgeihcfpkmmlfjbailfpfhbahhibba)
- [Steam Database](https://chrome.google.com/webstore/detail/kdbmhfkmnlmbkgbabkdealhhbfhlmmon)
- [Tabalanche](https://chrome.google.com/webstore/detail/bmdmojejipbodfjbnennbnakhpboaoje)
- [TabCopy](https://chrome.google.com/webstore/detail/micdllihgoppmejpecmkilggmaagfdmb)
- [Tampermonkey](https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo)
- [TeamViewer](https://chrome.google.com/webstore/detail/oooiobdokpcfdlahlmcddobejikcmkfo)
- [uBlacklist](https://chrome.google.com/webstore/detail/pncfbmialoiaghdehhbnbhkkgmjanfhe)
- [uBlock Origin](https://chrome.google.com/webstore/detail/cjpalhdlnbpafiamejdnhcphjbkeiagm)
- [v2ex plus](https://chrome.google.com/webstore/detail/daeclijmnojoemooblcbfeeceopnkolo)
- [京价保](https://chrome.google.com/webstore/detail/gfgkebiommjpiaomalcbfefimhhanlfd)
- [拷贝猫](https://chrome.google.com/webstore/detail/jdjbiojkklnaeoanimopafmnmhldejbg)

## CI/CD

- [GitLab Runner](https://docs.gitlab.com/runner/) - 公司所有项目的 CI/CD 全靠这个。
- [Homu](https://bors.tech/homu-io/) - Merge bot for GitHub，公司内部添加了 GitLab 的支持，使用了几年，现在已被自己完全实现的另外一只 merge-bot 替代。
    - [barosl/homu](https://github.com/barosl/homu)
    - [bors-ng/bors-ng](https://github.com/bors-ng/bors-ng)
    - [rust-lang/homu](https://github.com/rust-lang/homu)
    - [servo/homu](https://github.com/servo/homu)

## Cloud Storage

- [CloudMounter](https://cloudmounter.net/) - 云盘挂载工具，但没有 Mountain Duck 好用。
- [MEGAcmd](https://mega.nz/cmd) - Mega.nz 的官方 CLI，[开源](https://github.com/meganz/MEGAcmd)。
- [Megatools](https://megatools.megous.com/) - Mega.nz 的命令行工具。
- [Mountain Duck](https://mountainduck.io/) - 云盘挂载工具。
- [Netxcloud](https://nextcloud.com/) - [开源](https://github.com/nextcloud) 云盘。
- [OneDrive](https://www.microsoft.com/zh-cn/microsoft-365/onedrive/online-cloud-storage)
- [Rclone browser](https://github.com/kapitainsky/RcloneBrowser) - [Rclone](https://rclone.org/) GUI.
- [Rclone](https://rclone.org/) - 支持各种云存储的管理工具，神器。
- [RcloneOSX](https://github.com/rsyncOSX/rcloneosx) - [Rclone](https://rclone.org/) GUI.
- [RsyncOSX](https://github.com/rsyncOSX/RsyncOSX) - rsync GUI.
- [XPEnology](https://xpenology.com/forum/forum/31-loaders/) - 俗称黑群晖，自己有一台在跑。

## Collaboration Software / Wiki

- [Confluence](https://www.atlassian.com/software/confluence)
- [语雀](https://www.yuque.com/) - 买了 VIP，但基本不用，时不时的体验下。

## Command Line

- [ack](https://beyondgrep.com/) - 命令行代码搜索工具，类似 grep。
- [aliyun-cli](https://github.com/aliyun/aliyun-cli) - 阿里云 CLI。
- [autojump](https://github.com/wting/autojump) - 加强 cd 命令。
- [aws-shell](https://aws.amazon.com/cli/) - AWS 命令行工具，[开源](https://github.com/awslabs/aws-shell)。
- [awscli](https://github.com/aws/aws-cli) - AWS 命令行工具。
- [bat-extras](https://github.com/eth-p/bat-extras) - 基于 [bat](https://github.com/sharkdp/bat) 的几个工具。
- [bat](https://github.com/sharkdp/bat) - 支持高亮的 cat，我已经用来替换 cat。
- [ccat](https://github.com/owenthereal/ccat) - 支持高亮的 cat，更推荐 [bat](https://github.com/sharkdp/bat)。
- [coreutils](https://www.gnu.org/software/coreutils/) - 在 macOS 下使用 GNU Core Utilities。
- [dog](https://dns.lookup.dog/) - 加强版的 dig，[开源](https://github.com/ogham/dog)。
- [Dotbot](https://github.com/anishathalye/dotbot) - dotfiles 管理工具，好用。
- [duf](https://github.com/muesli/duf) - 加强版 du。
- [dust](https://github.com/bootandy/dust) - 加强版 du，但我还是更喜欢 [ncdu](https://dev.yorhel.nl/ncdu)。
- [exa](https://the.exa.website/) - 加强版 ls，我已用来替换了 ls。
- [exiftool](https://exiftool.org/) - 命令行下的 EXIF 查看、编辑工具。
- [fasd](https://github.com/clvv/fasd) - 目录快速跳转。
- [fd](https://github.com/sharkdp/fd) - 加强版 find。
- [fish](https://fishshell.com/) - fish shell，不习惯，还是在用 zsh。
- [fping](https://fping.org/) - 加强版 ping。
- [fselect](https://github.com/jhspetersson/fselect) - 用 SQL 查找文件。
- [fx](https://github.com/antonmedv/fx) - JSON 处理工具。
- [fzf](https://github.com/junegunn/fzf) - 命令行下的模糊搜索工具，神器，我还基于 fzf 写了 zsh 的 SSH [插件(zsh-ssh)](https://github.com/sunlei/zsh-ssh)。
- [fzy](https://github.com/jhawthorn/fzy) - 类似 fzf。
- [gnu-sed](https://www.gnu.org/software/sed/) - 在 macOS 下使用 GNU sed。
- [gping](https://github.com/orf/gping) - 可视化的 ping。
- [grc](https://github.com/garabik/grc) - 让一些命令的输出变为彩色。
- [gron](https://github.com/tomnomnom/gron) - JSON 查看工具。
- [hping](http://www.hping.org/) - 加强版 ping。
- [htop](https://htop.dev/) - 加强版 top。
- [libimobiledevice](https://libimobiledevice.org/) - iOS 设备管理工具。
- [lnav](https://lnav.org/) - 命令行下的日志查看工具，支持高亮。
- [lrzsz](https://www.ohse.de/uwe/software/lrzsz.html) - rz/sz 命令。
- [lsd](https://github.com/Peltoche/lsd) - 加强版 ls，但还是更喜欢 exa。
- [mas](https://github.com/mas-cli/mas) - Mac App Store CLI.
- [McFly](https://github.com/cantino/mcfly) - Rust 写的 ctrl-r 加强工具。
- [mobiledevice](https://github.com/imkira/mobiledevice) - 命令行下的 iOS 设备管理工具，很久没更新了，不知道现在还好不好用。
- [mtr](https://www.bitwizard.nl/mtr/) - 加强版 traceroute。
- [ncdu](https://dev.yorhel.nl/ncdu) - 加强版 du。
- [neofetch](https://github.com/dylanaraps/neofetch) - 漂亮的系统信息获取工具。
- [nghttp2](https://github.com/nghttp2/nghttp2) - HTTP/2 C Library，也包含几个实用的 HTTP/2 工具。
- [noti](https://github.com/variadico/noti) - 从终端发送通知，例如当耗时命令执行完毕后，支持丰富的通知方式。
- [nvchecker](https://github.com/lilydjwg/nvchecker) - 检查各种软件更新的工具，我 [添加](https://github.com/lilydjwg/nvchecker/pull/126) 了 [Sparkle](https://sparkle-project.org/) 的支持后，配合 GitHub Actions 实现了 [更新通知服务](https://github.com/sunlei/nvchecker)。
- [ossutil](https://github.com/aliyun/ossutil) - 阿里云 OSS 命令行工具。
- [p7zip](http://p7zip.sourceforge.net/) - 7-Zip
- [pandoc](https://pandoc.org/) - 全能的文档格式转换工具，神器。
- [pidcat](https://github.com/JakeWharton/pidcat) - Android logcat 的加强版。
- [prettyping](https://denilson.sa.nom.br/prettyping/) - 让 ping 的输出漂亮一些。
- [procs](https://github.com/dalance/procs) - 加强版 ps。
- [pup](https://github.com/EricChiang/pup) - 命令行下的 HTML 处理工具。
- [q](https://harelba.github.io/q/) - 用 SQL 查询 CSV/TSV 文件。
- [ripgrep](https://github.com/BurntSushi/ripgrep) - 比 grep 更好用。
- [sampler](https://sampler.dev/) - 终端下的可视化工具。
- [sd](https://github.com/chmln/sd) - 加强版 sed。
- [sentry-cli](https://github.com/getsentry/sentry-cli) - [Sentry](https://sentry.io/) 的 CLI 工具。
- [sift](https://sift-tool.org/) - 类似 grep。
- [sk](https://github.com/lotabout/skim) - 终端下的模糊查找工具，类似 fzf。
- [socat](http://www.dest-unreach.org/socat/) - 加强版 netcat。
- [terminal-notifier](https://github.com/julienXX/terminal-notifier) - 从终端发送通知，例如当耗时命令执行完毕后。
- [The Fuck](https://github.com/nvbn/thefuck) - 帮你纠正命令的同时还能发泄下。
- [trash](https://hasseg.org/trash/) - alias 到了 rm ，防止误删。
- [tree](http://mama.indstate.edu/users/ice/tree/) - 目录结构输出。
- [unar](https://theunarchiver.com/command-line) - [The Unarchiver](https://theunarchiver.com/) 的命令行版。
- [unrar](https://www.rarlab.com/) - 命令行下的 rar 解压工具。
- [xsv](https://github.com/BurntSushi/xsv) - Rust 写的 CSV 处理工具。
- [z.lua](https://github.com/skywind3000/z.lua) - 智能化 cd。
- [z](https://github.com/rupa/z) - 智能化 cd。
- [zoxide](https://github.com/ajeetdsouza/zoxide) - 智能化 cd。

### Rewritten in Rust

TODO: 待补充。

## Communication

- [Colloquy](https://github.com/colloquy/colloquy) - IRC 客户端。
- [Discord](https://discord.com/) - 在线沟通工具。
- [irssi](https://irssi.org/) - IRC 客户端。
- [Mastodon](https://instances.social/) - Mastodon 实例列表。
- [Mattermost](https://mattermost.com/) - 开源的类 Slack 产品。
- [QQ](https://im.qq.com/)
- [Ripcord](https://cancel.fm/ripcord/) - 支持 Discord 和 Slack 的第三方客户端。
- [Signal](https://signal.org/) - IM。
- [Slack](https://slack.com/) - 团队沟通。
- [Telegram](https://telegram.org/)
- [WhatsApp](https://www.whatsapp.com/) - IM。
- [企业微信](https://work.weixin.qq.com/) - 公司内部办公软件，两个亮点：与微信互通、macOS 下原生，但是功能性比钉钉与飞书弱很多。
- [微信](https://weixin.qq.com/)

## Content Management Systems

- [Commento](https://commento.io/)
    - [Introduction](https://docs.commento.io/)
- [Flarum](https://flarum.org/) - 用 PHP 实现的 [开源](https://github.com/flarum/flarum) 论坛程序。

## Data Visualization and Analytics

- [Grafana](https://grafana.com/)
- [Metabase](https://metabase.com/) - [开源](https://github.com/metabase/metabase)，跟 Redash、Superset 对比后，选用了这个。
- [Redash](https://redash.io/) - [开源](https://github.com/getredash/redash)。
- [Superset](https://superset.apache.org/) - [开源](https://github.com/apache/incubator-superset)。

## Databases

- [DataGrip](https://www.jetbrains.com/datagrip/) - JetBrains 出品的数据库管理工具。
- [IRedis](https://github.com/laixintao/iredis) - 交互式 redis 命令行客户端。
- [Medis](https://github.com/luin/medis) - 基于 Electron 的 redis 可视化客户端。
- [MySQL Workbench](https://www.mysql.com/cn/products/workbench/) - MySQL 官方出品的图形界面工具。
- [Navicat Premium](https://www.navicat.com/en/products/navicat-premium)
- [Percona Toolkit](https://www.percona.com/software/database-tools/percona-toolkit) - Percona 出品的 MySQL、MariaDB 工具。
- [Sequel Ace](https://sequel-ace.com/) - MySQL/MariaDB 图形工具，Sequel Pro 停止维护后， fork 出来继续维护的版本，[开源](https://github.com/Sequel-Ace/Sequel-Ace)。
- [Sequel Pro](https://www.sequelpro.com/) - MySQL/MariaDB 图形工具，[开源](https://github.com/sequelpro/sequelpro)，可惜不维护了，推荐用 Sequel Ace 替代。
- [SQLPro Studio](https://www.sqlprostudio.com/) - 数据库图形化管理。
- [TablePlus](https://tableplus.com/) - 数据库图形化管理。

## Design and Product

- [Design Systems Repo](https://designsystemsrepo.com/)
- [Figma](https://www.figma.com/) - 产品/设计工具。
- [Nutanix Design](https://nutanix.design/)
- [Sip](https://sipapp.io/) - 取色器。
- [Sketch](https://www.sketch.com/) - 产品/设计工具。

## Development

- [AdoptOpenJDK](https://adoptopenjdk.net/) - JDK & JRE.
- [Alembic](https://alembic.sqlalchemy.org/en/latest/) - 基于 SQLAlchemy 的数据库版本管理。
- [Ansible Lint](https://github.com/ansible/ansible-lint) - Ansible playbook lint 工具。
- [Ansible Molecule](https://github.com/ansible-community/molecule) - Ansible 开发/测试工具，非常好用。
- [asdf](https://github.com/asdf-vm/asdf) - 支持多种语言的版本管理工具。
- [aspell](http://aspell.net/) - 拼写检查器。
- [awslogs](https://github.com/jorgebastida/awslogs) - AWS CloudWatch 日志查看工具。
- [bump2version](https://github.com/c4urself/bump2version) - Version-bump your software with a single command.
- [Caddy](https://caddyserver.com/) - 类似 Nginx，在部分场景中使用。
- [Carthage](https://github.com/Carthage/Carthage) - Objective-C 和 Swift 的依赖管理。
- [cloc](https://github.com/AlDanial/cloc) - 代码统计工具。
- [CocoaPods](https://cocoapods.org/) - Objective-C 和 Swift 的依赖管理。
- [CodeRunner](https://coderunnerapp.com/) - 用于临时测试各种代码。
- [codespell](https://github.com/codespell-project/codespell) - 代码拼写检查。
- [Composer](https://getcomposer.org/) - PHP 的依赖管理工具。
- [Conftest](https://github.com/open-policy-agent/conftest) - 配置检测工具，还未深入使用，参考 [Open Policy Agent](https://www.openpolicyagent.org/)。
- [Cookiecutter](https://github.com/cookiecutter/cookiecutter) - 根据模板创建新项目。
- [Dash](https://kapeli.com/dash) - API 文档查看工具。
- [DevDocs](https://devdocs.io/) - API 文档查看工具，[开源](https://github.com/freeCodeCamp/devdocs)。
- [Developer Color Picker](https://download.panic.com/picker/index.html) - 取色器。
- [DevUtils](https://devutils.app/) - 开发常用工具，类似 Fiddler 中的 TextWizard，[开源](https://github.com/DevUtilsApp/DevUtils-app)，可自己编译。
- [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) - diff 加强工具。
- [direnv](https://github.com/direnv/direnv) - 根据目录自动设置环境变量。
- [doc8](https://github.com/pycqa/doc8) - reStructuredText 文档 lint 工具。
- [Docker](https://www.docker.com/)
- [Funcraft](https://github.com/alibaba/funcraft) - 阿里云函数计算开发工具。
- [GitLab Container Registry](https://docs.gitlab.com/ee/user/packages/container_registry/)
- [GitLab Package Registry](https://docs.gitlab.com/ee/user/packages/package_registry/)
- [golangci-lint](https://github.com/golangci/golangci-lint) - Go lint 工具。
- [haproxy](http://www.haproxy.org/)
- [Helm](https://helm.sh/) - Kubernetes 应用管理工具。
- [hey](https://github.com/rakyll/hey) - HTTP 压力测试工具。
- [highlight](http://www.andre-simon.de/doku/highlight/en/highlight.php) - 文件高亮查看/转换工具。
- [hr](https://github.com/LuRsT/hr) - 终端下的 `<hr />`，在终端下输出水平分割线。
- [hstr](https://github.com/dvorka/hstr) - 模糊查找 history 的工具，应该用 fzf 替代。
- [hyperfine](https://github.com/sharkdp/hyperfine) - 命令行基准测试工具，测试不同命令的性能。
- [ImageMagick](https://imagemagick.org/index.php) - 图像处理神器。
- [jq](https://stedolan.github.io/jq/) - 命令行下的 JSON 处理工具。
- [Kite](https://www.kite.com/) - 代码补全工具。
- [kubernetes-cli](https://kubernetes.io/) - Kubernetes CLI.
- [Kubetail](https://github.com/johanhaleby/kubetail) - Kubernetes 日志查看工具。
- [lens](https://k8slens.dev/) - Kubernetes 管理工具/IDE。
- [loc](https://github.com/cgag/loc) - 代码统计工具。
- [myrepos](https://myrepos.branchable.com/) - 多仓库管理工具。
- [n](https://github.com/tj/n) - Node.js 版本管理工具。
- [Nexus Repository](https://www.sonatype.com/nexus/repository-pro) - 各种包的私有仓库。
- [nginx](https://nginx.org/)
- [nodenv](https://github.com/nodenv/nodenv) - Node.js 版本管理工具。
- [npm-check-updates](https://github.com/raineorshine/npm-check-updates) - npm 依赖更新检查工具。
- [npm-check](https://github.com/dylang/npm-check) - npm 依赖检查工具。
- [nvm](https://github.com/nvm-sh/nvm) - Node.js 版本管理工具。
- [oss-browser](https://help.aliyun.com/document_detail/61872.html) - 阿里云 OSS 图形化管理工具。
- [pacparser](https://github.com/manugarg/pacparser) - PAC 解析工具。
- [podman](https://podman.io/) - 容器管理工具。
- [python-language-server](https://github.com/palantir/python-language-server) - Python 的 [Language Server Protocol](https://github.com/Microsoft/language-server-protocol) 实现。
- [rbenv](https://github.com/rbenv/rbenv) - Ruby 版本管理工具。
- [rdbtools](https://github.com/sripathikrishnan/redis-rdb-tools) - redis rdb 文件解析工具。
- [Repl.it](https://repl.it/)
- [rstcheck](https://github.com/myint/rstcheck) - reStructuredText lint 工具。
- [scc](https://github.com/boyter/scc/) - 代码统计工具。
- [scrcpy](https://github.com/Genymobile/scrcpy) - Android 设备管理工具。
- [Sentry](https://sentry.io/) - 异常捕捉。
- [shellcheck](https://www.shellcheck.net/) - shell 静态分析和 lint 工具。
- [Skala Color](https://bjango.com/help/skalacolor/gettingstarted/) - 取色器。
- [SnippetsLab](https://www.renfei.org/snippets-lab/) - 代码片段管理。
- [starship](https://starship.rs/) - 不错的 shell 提示符，用过一段时间，后来换到了 [Powerlevel10k](https://github.com/romkatv/powerlevel10k)。
- [stern](https://github.com/stern/stern) - Kubernetes 日志查看工具。
- [stow](https://www.gnu.org/software/stow/) - 文件链接管理工具，常用来管理 dotfiles，不过我更喜欢 [Dotbot](https://github.com/anishathalye/dotbot)。
- [SwiftLint](https://github.com/realm/SwiftLint) - Swift lint 工具。
- [TabNine](https://www.tabnine.com/) - 代码补全工具。
- [Terraform](https://www.terraform.io/) - 用于资源编排的自动化运维工具，可以拿来在各个云服务商那里做资源的管理/编排。
- [The Silver Searcher](https://github.com/ggreer/the_silver_searcher) - 代码搜索工具，类似 [ack](https://beyondgrep.com/)。
- [Tokei](https://github.com/XAMPPRocky/tokei) - 代码统计工具。
- [Traefik](https://doc.traefik.io/traefik/) - 类似 Nginx，在部分场景中使用。
- [webhook](https://github.com/adnanh/webhook) - 方便的创建 webhook endpoints，自己基于这个实现了 GitLab 和 Jira 的 bot。
- [wrk](https://github.com/wg/wrk) - HTTP 压力测试。
- [Yarn](https://yarnpkg.com/) - JavaScript 包管理，类似 NPM。
- [yq](https://github.com/kislyuk/yq) - 命令行下的 YAML 和 XML 解析工具。

## Docker

- [ctop](https://github.com/bcicen/ctop) - 面向 Docker 的 top。
- [dive](https://github.com/wagoodman/dive) - Docker 镜像分析工具，查看各层的信息。
- [Docker Compose](https://docs.docker.com/compose/) - Docker 编排工具。
- [Dockle](https://github.com/goodwithtech/dockle) - Docker 镜像 lint 工具。
- [hadolint](https://github.com/hadolint/hadolint) - Dockerfile lint 工具。
- [Kitematic](https://kitematic.com/) - Docker GUI，[开源](https://github.com/docker/kitematic)。
- [lazydocker](https://github.com/jesseduffield/lazydocker) - 终端下的 Docker GUI。
- [Portainer](https://www.portainer.io/) - Docker Web 管理工具。
- [trivy](https://github.com/aquasecurity/trivy) - Docker 镜像安全检测工具。
- [Watchtower](https://github.com/containrrr/watchtower) - Docker 镜像自动升级工具。

## Documentation Generator

- [hugo](https://gohugo.io/) - 静态网站生成器，一直想把我的 [huaidan.org](https://huaidan.org/) 从 WordPress 转过来。
- [mdbook](https://rust-lang.github.io/mdBook/) - 文档生成工具，适合拿来代替 [GitBook](https://www.gitbook.com/)。
- [MkDocs](https://www.mkdocs.org/) - 公司内部很多文档都用这个生成的。
    - [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- [sphinx-autobuild](https://github.com/executablebooks/sphinx-autobuild) - Sphinx 的实时预览工具。
- [Sphinx](https://www.sphinx-doc.org/en/master/) - 使用 reStructuredText 格式的文档处理工具。

## Editors/IDEs

- [BBEdit](https://www.barebones.com/products/bbedit/) - 偶尔会用的编辑器。
- [CotEditor](https://coteditor.com/) - 文本编辑器，[开源](https://github.com/coteditor/CotEditor)。
- [Monodraw](https://monodraw.helftone.com/) - ASCII 编辑器。
- [Nova](https://nova.app/) - 代码编辑器，[Panic](https://panic.com/) 出品。
- [Sublime Text](https://www.sublimetext.com/) - 代码编辑器，听说 4 在 [内测](https://gist.github.com/jfcherng/7bf4103ea486d1f67b7970e846b3a619) 中了。
- [Vim](https://www.vim.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Xcode](https://developer.apple.com/xcode/)

## Email

- [Kiwi for Gmail](https://www.kiwiforgmail.com/) - 基于 Web 的 Gmail 桌面客户端。
- [MailMate](https://freron.com/) - 对 IMAP 支持很好的邮件客户端。
- [Mailplane](https://mailplaneapp.com/) - 基于 Web 的 Gmail 桌面客户端。
- [Mimestream](https://mimestream.com/) - Gmail 桌面客户端。
- [Spark](https://sparkmailapp.com/) - 邮件客户端。

## File Managers

- [Commander One](https://mac.eltima.com/file-manager.html) - 文件管理/传输工具。
- [duck](https://duck.sh/) - Cyberduck 的命令行版。
- [ForkLift](https://binarynights.com/) - 文件管理/传输工具。
- [Gemini](https://macpaw.com/gemini) - 重复文件查找。
- [nnn](https://github.com/jarun/nnn) - 终端下的文件管理器。
- [QSpace](https://qspace.awehunt.com/en-us/index.html) - 文件管理工具。
- [Transmit](https://panic.com/transmit/) - 文件管理/传输工具。

## File Organization

根据规则对文件进行整理。

- [Easy File Organizer](https://qiplex.com/software/easy-file-organizer/)
- [File Juggler](https://www.filejuggler.com/)
- [Hazel](https://www.noodlesoft.com/)
- [Maid](https://github.com/benjaminoakes/maid)
- [Organize My Files](https://snapcraft.io/organize-my-files)
- [organize](https://github.com/tfeldmann/organize) - 文件自动处理工具，类似 Hazel，我已经逐渐拿来替换 Hazel。
- [Spotless](https://www.lightpillar.com/spotless.html) - 文件自动处理，类似 Hazel。

## File Sharing and Synchronization

- [croc](https://github.com/schollz/croc) - 非常方便的临时文件传输工具，推荐。
- [Dropbox](https://www.dropbox.com/)
- [Droplr](https://droplr.com/) - 快速分享工具，买过终身授权。
- [Dropshare](https://dropshare.app/) - 文件快捷分享工具。
- [Google Drive File Stream](https://support.google.com/a/answer/7491144?hl=en)
- [lftp](https://lftp.yar.ru/) - 支持 ftp, http, sftp, fish, torrent 的传输工具。
- [lsyncd](https://github.com/axkibe/lsyncd) - 文件同步。
- [Magic Wormhole](https://github.com/warner/magic-wormhole) - 文件传输，类似的还有 croc。
- [PhotoSync](https://www.photosync-app.com/) - 相册同步/备份工具。
- [Resilio Sync](https://www.resilio.com/) - 文件同步工具。
- [Syncthing](https://syncthing.net/) - 文件同步，除了没有 iOS 客户端外，其他场景比 [Resilio Sync](https://www.resilio.com/) 好用。

## File System Events Monitoring

- [entr](http://eradman.com/entrproject/) - 文件变化监控工具，[开源](https://github.com/eradman/entr)。
- [fswatch](https://github.com/emcrisostomo/fswatch) - 文件变更时，触发命令。
- [nodemon](https://nodemon.io/)
- [Reflex](https://github.com/cespare/reflex)
- [watchdog](https://github.com/gorakhargosh/watchdog) - Python 实现的，开源当包用，同时提供一个 watchmedo 的命令行工具。
- [watchexec](https://github.com/watchexec/watchexec)
- [Watchman](https://github.com/facebook/watchman)

## Finance

- [Beancount](http://furius.ca/beancount/) - [开源](https://github.com/beancount/beancount) 复式记账软件，强烈推荐。
- [cointop](https://github.com/miguelmota/cointop) - 终端下的数字货币行情查看工具。
- [Fava](https://github.com/beancount/fava) - Beancount 的 Web 界面。
- [MoneyWiz](https://wiz.money/) - 财务管理/记账软件。
- [Receipts](https://www.receipts-app.com/) - 发票/收据管理。

## Fonts

- [Fira Code Nerd Font](https://github.com/ryanoasis/nerd-fonts)
- [Fira Code](https://github.com/tonsky/FiraCode)
- [Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts)
- [Meslo Nerd Font](https://github.com/ryanoasis/nerd-fonts)
- [Source Code Pro for Powerline](https://github.com/powerline/fonts/tree/master/SourceCodePro)
- [Source Code Pro](https://github.com/adobe-fonts/source-code-pro)

## Games

- [Dead Cells](https://store.steampowered.com/app/588650/Dead_Cells/)
- [Don't Starve](https://store.steampowered.com/app/219740/Dont_Starve/)
- [Dungeon Warfare 2](https://store.steampowered.com/app/698540/Dungeon_Warfare_2/)
- [Factorio（异星工厂）](https://store.steampowered.com/app/427520/Factorio/) - 一款建造工业生产流水线并保持其高效运转的游戏，终极目标就是把一切都自动化。强烈推荐，我的游戏时间 300 多小时。
- [Graveyard Keeper](https://store.steampowered.com/app/599140/Graveyard_Keeper/)
- [Hades](https://store.steampowered.com/app/1145360/Hades/)
- [Minecraft（我的世界）](https://www.minecraft.net)
- [Oxygen Not Included（缺氧）](https://store.steampowered.com/app/457140/Oxygen_Not_Included/)
- [RimWorld](https://store.steampowered.com/app/294100/RimWorld/)
- [Rise to Ruins](https://store.steampowered.com/app/328080/Rise_to_Ruins/) - 让我想起来小时候玩的 [野兽与乡巴佬](https://baike.baidu.com/item/%E9%87%8E%E5%85%BD%E4%B8%8E%E4%B9%A1%E5%B7%B4%E4%BD%AC)。
- [Rogue's Tale](https://store.steampowered.com/app/265990/Rogues_Tale/)
- [Starbound](https://store.steampowered.com/app/211820/Starbound/)
- [Stardew Valley](https://store.steampowered.com/app/413150/Stardew_Valley/)
- [Steam](https://store.steampowered.com/) - 游戏平台。
- [Terraria（泰拉瑞亚）](https://store.steampowered.com/app/105600/Terraria/) - 很多人说是 2D 版的 Minecraft。强烈推荐，我的游戏时间 200 多小时。
- [YORG.io 3](https://yorg3.io/)
- [YORG.io](https://yorg.io/) - 网页版的塔防。

## Git

- [bfg](https://rtyley.github.io/bfg-repo-cleaner/) - Git 仓库历史清理工具，[开源](https://github.com/rtyley/bfg-repo-cleaner)。
- [Fork](https://fork.dev/) - Git GUI。
- [ghq](https://github.com/x-motemen/ghq) - Git 仓库管理工具，仓库多时很好用。
- [git-chglog](https://github.com/git-chglog/git-chglog) - 基于 Git 的 CHANGELOG 生成工具。
- [git-crypt](https://github.com/AGWA/git-crypt) - Git 文件加密。
- [git-delta](https://github.com/dandavison/delta) - git diff 加强。
- [git-extras](https://github.com/tj/git-extras) - Git 的一些加强。
- [git-quick-stats](https://github.com/arzzen/git-quick-stats) - Git 统计工具。
- [git-secret](https://github.com/sobolevn/git-secret) - Git 文件加密。
- [git-secrets](https://github.com/awslabs/git-secrets) - Git 文件加密。
- [git-sizer](https://github.com/github/git-sizer) - Git 仓库分析工具，例如查找大文件。
- [Gita](https://github.com/nosarthur/gita) - 多 Git 仓库管理工具。
- [gitbatch](https://github.com/isacikgoz/gitbatch) - 多 Git 仓库管理工具。
- [GitUI](https://github.com/extrawurst/gitui) - 终端下的 Git GUI。
- [GitUp](https://gitup.co/) - Git GUI，[开源](https://github.com/git-up/GitUp)。
- [lazygit](https://github.com/jesseduffield/lazygit) - 终端下的 Git GUI。
- [Legit](https://github.com/frostming/legit) - Git for Humans.
- [onefetch](https://github.com/o2sh/onefetch) - 漂亮的 Git 仓库信息统计。
- [pre-commit](https://pre-commit.com/) - Git pre-commit 管理工具。
- [SmartGit](https://www.syntevo.com/smartgit/) - Git GUI。
- [Sourcetree](https://www.sourcetreeapp.com/) - Git GUI。
- [Sublime Merge](https://www.sublimemerge.com/) - Sublime Text 作者出品的 Git GUI。
- [Tig](https://github.com/jonas/tig) - 终端下的 Git GUI。
- [Tower](https://www.git-tower.com/mac) - Git GUI。

## Github

- [act](https://github.com/nektos/act) - 在本地执行 GitHub Actions，我之前用来开发 GitHub Actions。
- [gh](https://github.com/cli/cli) - GitHub CLI.
- [git-cal](https://github.com/k4rthik/git-cal) - 命令行下生成类似 GitHub 的日历。
- [Gitify](https://www.gitify.io/) - GitHub 通知工具，[开源](https://github.com/manosim/gitify)。
- [grip](https://github.com/joeyespo/grip) - GitHub Readme 预览工具。
- [Lepton](http://hackjutsu.com/Lepton/) - GitHub Gist 桌面管理工具。

## HTTP/S Debug

- [Burp Suite](https://portswigger.net/burp) - 用于 Web 安全测试的图形化工具。
- [Fiddler](https://www.telerik.com/fiddler) - HTTP/S Debug 工具，目前唯一在 macOS 下没找到替代的工具，[Proxyman](https://proxyman.io/) 可以算部分替代。
- [Insomnia](https://insomnia.rest/) - API 调试工具。
- [mitmproxy](https://mitmproxy.org/) - Python 实现的代理服务器，看名字就知道作用。
- [newman](https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman/) - Postman 的命令行工具。
- [Paw](https://paw.cloud/) - API 管理/调试工具。
- [Postman](https://www.postman.com/) - API 管理/调试工具。
- [proxy.py](https://github.com/abhinavsingh/proxy.py) - Python 实现的代理服务器，支持插件、MitM 等，可作为 HTTP/S Debug 工具使用，与 mitmproxy 类似，实测性能比 [mitmproxy](https://mitmproxy.org/) 好很多。
- [Proxyman](https://proxyman.io/) - Web Debugging Proxy。
- [whistle](https://wproxy.org/whistle/) - 基于 Node.js 实现的 HTTP Debug 工具，类似 [Fiddler](https://www.telerik.com/fiddler)。

## Identity Management

- [ldapvi](http://www.lichteblau.com/ldapvi/) - 用文本编辑器编辑 LDAP 条目。
- [OpenLDAP](https://www.openldap.org/)

## Image Optimizers

各种图片压缩工具。

- [Crunch](https://github.com/chrissimpkins/Crunch) - 开源。
- [ImageAlpha](https://pngmini.com/) - [开源](https://github.com/kornelski/ImageAlpha)。
- [ImageOptim](https://imageoptim.com/) - [开源](https://github.com/ImageOptim/ImageOptim)。
- [JPEGmini](https://www.jpegmini.com/)
- [Optimage](https://optimage.app/)
- [pngquant](https://pngquant.org/) - PNG 压缩工具。
- [PPDuck](https://ppduck.com/)
- [Squash](https://www.realmacsoftware.com/squash/)
- [TinyPNG4Mac](https://github.com/kyleduo/TinyPNG4Mac) - [TinyPNG](https://tinypng.com/) 客户端。

## IP Geolocation

- [cip.cc](http://www.cip.cc/) - `curl cip.cc`、`curl ip.cip.cc`
- [ifconfig.co](https://ifconfig.co/) - `curl ifconfig.co`
- [ifconfig.me](https://ifconfig.me/) - `curl ifconfig.me`
- [IP.cn](https://ip.cn/)
- [IP.SB](https://ip.sb/) - `curl ip.sb`
- [ip138](https://ip138.com/)
- [ipify](https://www.ipify.org/) - `curl 'https://api.ipify.org?format=json'`
- [IPinfo.io](https://ipinfo.io/) - `curl ipinfo.io`、`curl ipinfo.io/ip`
- [IPIP.NET](https://www.ipip.net/) - `curl myip.ipip.net`
- [members.3322.org/dyndns/getip](http://members.3322.org/dyndns/getip)
- [zxinc](https://ip.zxinc.org/) - `curl 'https://ip.zxinc.org/api.php?type=json'`
- `curl checkip.amazonaws.com`
- `curl curlmyip.com`
- `curl icanhazip.com`
- `curl ip.appspot.com`
- `curl ipecho.net/plain`
- `curl www.trackip.net/ip`
- `dig -4 TXT +short o-o.myaddr.l.google.com @ns1.google.com | sed 's/"//g'`
- `dig -6 TXT +short o-o.myaddr.l.google.com @ns1.google.com | sed 's/"//g'`
- `dig +short myip.opendns.com @resolver1.opendns.com`
- `dig TXT +short o-o.myaddr.l.google.com @ns1.google.com | sed 's/"//g'`
- `host myip.opendns.com resolver1.opendns.com`

## Let's Encrypt

- [acme.sh](https://github.com/acmesh-official/acme.sh)
- [dehydrated](https://github.com/dehydrated-io/dehydrated)
- [Let's Encrypt](https://letsencrypt.org/)

## Linux/VPS Benchmarking

- [bench.sh](https://bench.sh/)
    - `wget -qO- bench.sh | bash`
    - `curl -Lso- bench.sh | bash`
- [n-st/nench](https://github.com/n-st/nench)
    - `(curl -s wget.racing/nench.sh | bash; curl -s wget.racing/nench.sh | bash) 2>&1 | tee nench.log`
    - `(wget -qO- wget.racing/nench.sh | bash; wget -qO- wget.racing/nench.sh | bash) 2>&1 | tee nench.log`
- [masonr/yet-another-bench-script](https://github.com/masonr/yet-another-bench-script)
- [mgutz/vpsbench](https://github.com/mgutz/vpsbench)
    - `bash <(wget --no-check-certificate -O - https://raw.github.com/mgutz/vpsbench/master/vpsbench)`
- [Linux scripts](https://www.janyksteenbeek.nl/linux/)
- [Bench.Monster](https://bench.monster/)
- [VPS benchmark](https://busylog.net/vps-benchmark/)
    - `wget https://busylog.net/FILES2DW/busytest.sh -O - -o /dev/null | bash`
- [STH-Dev/linux-bench](https://github.com/STH-Dev/linux-bench)
- [teddysun/across/unixbench.sh](https://github.com/teddysun/across/blob/master/unixbench.sh)
- [oooldking/script](https://github.com/oooldking/script) - 包含测试到中国的网络速度脚本。
    - [superbench.sh](https://github.com/oooldking/script/blob/master/superbench.sh)
    - [superspeed.sh](https://github.com/oooldking/script/blob/master/superspeed.sh)
- [FunctionClub/ZBench](https://github.com/FunctionClub/ZBench)
- [sayem314/serverreview-benchmark](https://github.com/sayem314/serverreview-benchmark)
- [helloxz/mping](https://github.com/helloxz/mping)
- [LemonBench/LemonBench](https://github.com/LemonBench/LemonBench)
- [kdlucas/byte-unixbench](https://github.com/kdlucas/byte-unixbench)
- [centminmod/centminmodbench](https://github.com/centminmod/centminmodbench)
- [centminmod/centminmod-sysbench](https://github.com/centminmod/centminmod-sysbench)

## Markdown

- [Glow](https://github.com/charmbracelet/glow) - 命令行下的 Markdown 查看/渲染工具。
- [Mark](https://github.com/kovetskiy/mark) - 将 Markdown 转换为 Confluence 的格式，并发布到 Confluence 中。
- [Marked](https://marked2app.com/) - Markdown 预览。
- [Turndown](https://domchristie.github.io/turndown/) - HTML to Markdown 转换工具，[开源](https://github.com/domchristie/turndown)。
- [Typora](https://typora.io/) - Markdown 编辑/管理工具。

## Media

- [Annie](https://github.com/iawia002/annie) - 视频下载工具。
- [Downie](https://software.charliemonroe.net/downie/) - 视频下载工具，类似 [youtube-dl](https://github.com/ytdl-org/youtube-dl)。
- [emby](https://emby.media/) - 媒体服务器。
- [gallery-dl](https://github.com/mikf/gallery-dl) - 相册服务下载工具。
- [HandBrake](https://handbrake.fr/) - 视频转码。
- [IINA](https://iina.io/) - 视频播放器，[开源](https://github.com/iina/iina)，我记得是基于 mpv 的。
- [Movie Explorer Pro](https://betamagic.nl/products/movieexplorerpro.html) - 电影管理软件。
- [Movist Pro](https://movistprime.com/) - 视频播放器。
- [mpv](https://mpv.io/) - 视频播放器，[开源](https://github.com/mpv-player/mpv)，曾经花了很大精力去配置，后来换到了 IINA。
- [Permute](https://software.charliemonroe.net/permute/) - 媒体格式转换。
- [PhotoBulk](https://photobulkeditor.com/) - 图像批量处理。
- [Pixelmator Pro](https://www.pixelmator.com/pro/) - 图片编辑软件。
- [Plex](https://www.plex.tv/) - 媒体服务器。
- [Polarr](https://www.polarr.com/) - 修图工具。
- [VLC](https://www.videolan.org/)
- [You-Get](https://github.com/soimort/you-get) - 视频下载工具。

## Monitoring

- [bandwhich](https://github.com/imsnif/bandwhich) - 流量查看工具。
- [bottom](https://github.com/ClementTsang/bottom) - 终端下的系统监控工具，类似 top、htop。
- [eul](https://github.com/gao-sun/eul) - 开源的系统监控工具，类似 iStat Menus。
- [Glances](https://nicolargo.github.io/glances/) - 系统监控，类似 top/htop。
- [iStat Menus](https://bjango.com/mac/istatmenus/) - 系统监控工具。
- [Netdata](https://www.netdata.cloud/) - [开源](https://github.com/netdata/netdata) 监控系统。
- [Prometheus](https://prometheus.io/)
- [SleepWatcher](https://www.bernhard-baehr.de/) - macOS 下的睡眠/唤醒监控工具，曾经拿来让电脑盒盖自动关闭 WiFi，解决唤醒六国问题。
- [smartmontools](https://www.smartmontools.org/) - 硬盘 SMART 信息监控。
- [Stats](https://github.com/exelban/stats) - 开源的系统监控工具，类似 iStat Menus。
- [ytop](https://github.com/cjbassi/ytop) - Rust 写的系统监控工具，类似 top、htop，不维护了。

## Music

- [QQ 音乐](https://y.qq.com/)
- [Spotify TUI](https://github.com/Rigellute/spotify-tui) - Rust 写的终端下的 Spotify 客户端。
- [Spotify](https://www.spotify.com/)
- [网易云音乐](http://music.163.com/) - QQ 音乐的 VIP 到期且淘宝的 88VIP 开始送会员后转过来的。

## Networking

- [17mon/china_ip_list](https://github.com/17mon/china_ip_list) - IPList for China by IPIP.NET。
- [Aria2 Pro](https://github.com/P3TERX/Docker-Aria2-Pro) - 对 aria2 做了很多优化配置的 Docker 镜像，我在 seedbox 上跑了一个，本地通过 [AriaNg](https://github.com/mayswind/AriaNg) 来管理。
- [AriaNg](https://github.com/mayswind/AriaNg) - aria2 的 Web 管理工具
    - [AriaNg Native](https://github.com/mayswind/AriaNg-Native) - 基于 [Electron](https://github.com/electron/electron) 实现的 AriaNg 桌面版。
- [aria2](https://aria2.github.io/) - 几乎全能的下载功能。
- [axel](https://github.com/axel-download-accelerator/axel) - 多线程下载工具。
- [Folx](https://mac.eltima.com/download-manager.html) - 下载工具。
- [Hackl0us/GeoIP2-CN](https://github.com/Hackl0us/GeoIP2-CN) - 最小巧、最准确、最实用的 中国大陆 IP 段 + GeoIP2 数据库。
- [httpie](https://httpie.io/) - 更友好的 curl。
- [httping](https://www.vanheusden.com/httping/) - HTTP ping.
- [iperf3](https://github.com/esnet/iperf) - 带宽测试工具。
- [ipfs](https://ipfs.io/)
- [Motrix](https://motrix.app/) - 下载工具，基于 aria2，[开源](https://github.com/agalwood/Motrix)。
- [NetSpot](https://www.netspotapp.com/) - WiFi 工具。
- [ngrep](https://github.com/jpr5/ngrep) - 网络 grep。
- [ntopng](https://www.ntop.org/products/traffic-analysis/ntop/)
- [ping.pe](https://ping.pe/)
- [Speedtest CLI](https://www.speedtest.net/apps/cli) - [Speedtest](https://www.speedtest.net/) 的官方命令行版。
- [speedtest-cli](https://github.com/sivel/speedtest-cli) - [Speedtest](https://www.speedtest.net/) 的命令行版。
- [tcping](https://github.com/mkirchner/tcping) - TCP ping.
- [Unbound](https://github.com/NLnetLabs/unbound) - DNS 服务器，之前拿来在本机跑了一个优化的。
- [UniFi Network Controller](https://www.ui.com/download/unifi/)
- [waybackpy](https://github.com/akamhy/waybackpy) - Python 实现的 archive.org 包，同时提供一个命令行工具。
- [wget](https://www.gnu.org/software/wget/)
- [WiFi Explorer](https://www.intuitibits.com/products/wifi-explorer/) - WiFi 工具。

## Note-taking

- [Craft](https://www.craft.do/) - 跟 notion.so 类似，但是原生实现。
- [Day One](https://dayoneapp.com/) - 日记。
- [DEVONthink](https://www.devontechnologies.com/apps/devonthink) - 文件/笔记/知识 管理工具，跟随升了两个大版本了。
- [Drafts](https://getdrafts.com/) - macOS 和 iOS 双平台文字处理工具。
- [Joplin](https://joplinapp.org/) - 笔记工具，[开源](https://github.com/laurent22/joplin)。
- [MWeb](https://zh.mweb.im/) - Markdown 编辑/管理工具。
- [Notion](https://www.notion.so/) - 新型笔记软件，以前活动拿了终身免费，基于 Web 实现，实际使用起来流畅度欠缺。
- [nvALT](https://brettterpstra.com/projects/nvalt/) - 笔记软件，支持 Markdown，使用最久。
- [Obsidian](https://obsidian.md/) - 支持 Zettelkasten（卡片盒） 笔记法的笔记管理软件，目前在用。
- [Quiver](https://happenapps.com/) - 笔记软件，是我见到比较早支持 block 的。
- [Simplenote](https://simplenote.com/) - [Automattic](https://automattic.com/) 出品的笔记软件，极简。
- [Ulysses](https://ulysses.app/) - Markdown 编辑/管理工具。

## Password Managers

- [1Password](https://1password.com/) - 使用了很多年的密码管理软件。
- [Bitwarden](https://bitwarden.com/) - 开源密码管理软件。
- [Elpass](https://elpass.app/) - Surge 作者出的密码管理软件。
- [Enpass](https://www.enpass.io/) - 密码管理软件。
- [gopass](https://github.com/gopasspw/gopass) - 命令行下的密码管理工具。
- [KeePass](https://keepass.info/)
- [KeyPass](https://www.dobysoft.com/products/keypass/) - 密码管理软件，Windows 平台下一直在用，至今在 macOS 下找不到替代品的神器。但是官方已 [停止维护](https://www.dobysoft.com/products/keypass/history.html)，2002 年发布，17 年后停止维护，可惜。
- [pass](https://www.passwordstore.org/) - 命令行下的密码管理软件。
- [pwgen](https://sourceforge.net/projects/pwgen/) - 密码生成工具。

## PDF

- [PDF Expert](https://pdfexpert.com/) - PDF 查看/编辑软件。
- [PDF Squeezer](https://witt-software.com/pdfsqueezer/) - PDF 压缩工具。
- [PDFpen](https://smilesoftware.com/pdfpen/) - PDF 阅读/编辑。

## Project Management

- [GitLab](https://about.gitlab.com/)
- [Jira](https://www.atlassian.com/software/jira) - 项目/事务管理。
- [OmniPlan](https://www.omnigroup.com/omniplan/) - 项目管理工具。

## Prototyping and Mind-Mapping

- [iThoughtsX](https://www.toketaware.com/ithoughts-osx) - 思维导图工具。
- [MindNode](https://mindnode.com/) - 思维导图。
- [OmniGraffle](https://www.omnigroup.com/omnigraffle) - 神器。
- [OmniOutliner](https://www.omnigroup.com/omnioutliner/) - 内容大纲工具。
- [XMind](https://www.xmind.cn/) - 思维导图。

## Proxy and VPN

- [3proxy](https://github.com/z3APA3A/3proxy)
- [clash](https://github.com/Dreamacro/clash) - 翻墙软件，有 [premium](https://github.com/Dreamacro/clash/releases/tag/premium) 版。
- [ClashX](https://github.com/yichengchen/clashX) - 基于 clash 实现的 macOS 下的客户端。
- [proxychains-ng](https://sourceforge.net/projects/proxychains-ng/) - 让命令行工具走代理。
- [shadowsocks](https://github.com/shadowsocks)
- [Surge](https://nssurge.com/) - 官方定义「Advanced Network Toolbox for Mac & iOS」，但基本都是拿来翻墙，macOS 和 iOS 下都买了。
- [WireGuard](https://www.wireguard.com/) - VPN。

## Proxy Rules And Scripts

包含 Surge/Quantumult X/Clash/Surfboard/Loon/Shadowrocket。

- [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) - 除了整合各个开源的规则/脚本，也有很多特有的，大而全。
- [Choler/Surge](https://github.com/Choler/Surge)
- [DivineEngine/Profiles](https://github.com/DivineEngine/Profiles/tree/master)
- [Hackl0us/SS-Rule-Snippet](https://github.com/Hackl0us/SS-Rule-Snippet)
- [Koolson/Qure](https://github.com/Koolson/Qure) - 专为 Quantumult X 内策略组而精心设计的图标组。
- [KOP-XIAO/QuantumultX](https://github.com/KOP-XIAO/QuantumultX)
- [lhie1/Rules](https://github.com/lhie1/Rules/tree/master)
- [NobyDa/Script](https://github.com/NobyDa/Script/tree/master) - 以各种签到脚本为主。
- [scomper/Surge](https://github.com/scomper/Surge)
- [yichahucha/surge](https://github.com/yichahucha/surge)

## Python

- [Bandit](https://github.com/PyCQA/bandit) - Python 代码安全检查。
- [IPython](https://ipython.org/) - 更友好的 Python 交互式 shell。
- [Mypy](https://github.com/python/mypy) - Python 静态类型检查工具。
- [Pew](https://github.com/berdario/pew) - Python 虚拟环境管理工具。
- [Pipenv](https://github.com/pypa/pipenv) - Python 虚拟环境管理工具。
- [pipx](https://github.com/pipxproject/pipx) - 安装 Python 写的命令行工具的神器。
- [Poetry](https://python-poetry.org/) - Python 依赖、虚拟环境管理工具。
- [pyenv](https://github.com/pyenv/pyenv) - Python 版本管理工具。
- [pyp](https://github.com/hauntsaninja/pyp) - 在 shell 中直接执行 Python 代码。
- [Pyre](https://github.com/facebook/pyre-check) - Python 静态类型检查工具。
- [pytest](https://docs.pytest.org/en/stable/) - Python 测试框架。
- [python-gitlab](https://github.com/python-gitlab/python-gitlab) - Python 封装的 GitLab API，同时也是 GitLab 的 CLI 工具。
- [pytype](https://github.com/google/pytype) - Python 静态类型检查工具。
- [safety](https://github.com/pyupio/safety) - Python 依赖安全检查工具。
- [tox](https://tox.readthedocs.io/en/latest/) - Python 自动测试工具。
- [twine](https://twine.readthedocs.io/en/latest/) - PyPI 发布工具。
- [wtfpython](https://github.com/satwikkansal/wtfpython) - What the f\*ck Python!

### Linter

- [Flake8](https://github.com/PyCQA/flake8)
- [Prospector](http://prospector.landscape.io/en/master/)
- [Pyflakes](https://github.com/PyCQA/pyflakes)
- [Pylint](https://www.pylint.org/)

### Formatter

- [autopep8](https://github.com/hhatto/autopep8)
- [black](https://github.com/psf/black)
- [YAPF](https://github.com/google/yapf)

### Package Management

- [DepHell](https://github.com/dephell/dephell)
- [PDM](https://pdm.fming.dev/)
- [pip-tools](https://github.com/jazzband/pip-tools)

### Packages

- [atlassian-python-api](https://github.com/atlassian-api/atlassian-python-api) - 支持 Jira、Jira Service Desk、Confluence、BitBucket、Bamboo、Crowd。
- [pycontribs/confluence](https://github.com/pycontribs/confluence) - 不维护了。
- [pycontribs/jira](https://github.com/pycontribs/jira)

## Regular Expressions

- [Expressions](https://www.apptorium.com/expressions) - 正则工具。
- [grex](https://github.com/pemistahl/grex) - 正则生成工具。
- [Patterns](https://krillapps.com/patterns/) - 正则工具。
- [regex101](https://regex101.com/) - 常用。

## Remote Desktop

- [AnyDesk](https://anydesk.com/)
- [Royal TSX](https://royalapps.com/ts) - 支持各种协议的远程桌面管理工具。
- [TeamViewer](https://www.teamviewer.com/)

## Robotic Process Automation

- [robotframework](https://github.com/robotframework/robotframework)
- [RPA-Python](https://github.com/tebelorg/RPA-Python)
- [TagUI](https://github.com/kelaberetiv/TagUI)

## RSS

- [Inoreader](https://www.inoreader.com/) - 我是 RSS 的重度用户，从 04、05 年到现在，基本每天都会用，阅读器 [一路切换](https://huaidan.org/archives/917.html)，从 「[GeatNews](https://web.archive.org/web/20050222021701/http://www.curiostudio.com/) -> [抓虾](https://web.archive.org/web/20150811064809/http://www.zhuaxia.com/) -> Google Reader -> [Feedly](https://feedly.com/) -> [Inoreader](https://www.inoreader.com/)」，然后就一直订阅 Inoreader 的 Pro 版。
- [Miniflux](https://miniflux.app/) - [开源](https://github.com/miniflux/v2) RSS 阅读服务。
- [NetNewsWire](https://ranchero.com/netnewswire/) - 多平台 RSS 阅读工具，但是支持的服务比较少，[开源](https://github.com/Ranchero-Software/NetNewsWire)。
- [News Explorer](https://betamagic.nl/products/newsexplorer.html) - RSS 客户端。
- [Newsboat](https://newsboat.org/) - 终端下的 RSS 阅读器。
- [ReadKit](https://readkitapp.com/) - RSS 客户端。
- [Reeder](https://reederapp.com/) - RSS 客户端。

## Screencapturing

- [iShot](https://apps.apple.com/cn/app/ishot-%E6%88%AA%E5%9B%BE-%E9%95%BF%E6%88%AA%E5%9B%BE-%E6%A0%87%E6%B3%A8%E5%B7%A5%E5%85%B7/id1485844094) - 截图工具。
- [LICEcap](https://www.cockos.com/licecap/) - 屏幕录制，输出 GIF。
- [ScreenFlow](http://www.telestream.net/screenflow/) - 录屏软件。
- [Snipaste](https://www.snipaste.com/) - 截图工具。
- [Xnip](https://zh.xnipapp.com/) - 截图工具。

## Security

- [Burp Suite](https://portswigger.net/burp) - 用于 Web 安全测试的图形化工具。
- [CFR](https://www.benf.org/other/cfr/) - Java 反编译。
- [Ciphey](https://github.com/Ciphey/Ciphey) - 使用自然语言处理和人工智能以及一些全自动解密/解码/破解工具。
- [gnupg](https://gnupg.org/)
- [GPG Suite](https://gpgtools.org/)
- [h8mail](https://github.com/khast3x/h8mail) - Email OSINT 工具。
- [Hopper Disassembler](https://www.hopperapp.com/) - 逆向工具。
- [hydra](https://github.com/vanhauser-thc/thc-hydra) - 密码破解。
- [JAD](https://varaneckas.com/jad/) - Java 反编译工具。
- [JD-GUI](https://java-decompiler.github.io/) - Java 反编译工具，[开源](https://github.com/java-decompiler/jd-gui)。
- [MASSCAN](https://github.com/robertdavidgraham/masscan/) - 端口快速扫描工具。
- [nmap](https://nmap.org/) - 扫描工具。
- [objection](https://github.com/sensepost/objection) - 基于 [Frida](https://frida.re/) 实现的移动端安全测试辅助工具。
- [OWASP Amass](https://github.com/OWASP/Amass) - 安全测试信息收集工具。
- [sqlmap](http://sqlmap.org/) - SQL 注入工具。
- [sslscan](https://github.com/rbsec/sslscan) - SSL/TLS 扫描工具。
- [YARA](https://github.com/VirusTotal/yara/) - 恶意软件查找。

## SSH

- [assh](https://github.com/moul/assh) - SSH 客户端加强。
- [cmc](https://github.com/TimidRobot/cmc) - SSH ControlMaster 管理工具，但是在我这里不太好用，还是自己写了个脚本。
- [SecureCRT](https://www.vandyke.com/products/securecrt/) - SSH 客户端。
- [ssh-audit](https://github.com/arthepsy/ssh-audit) - SSH Server 审计工具。
- [stormssh](https://github.com/emre/storm) - SSH 管理工具，后来还是环自己结合 fzf 写的 zsh [插件(zsh-ssh)](https://github.com/sunlei/zsh-ssh) 了。
- [xxh-xxh](https://github.com/xxh/xxh) - 把本地的 shell 通过 SSH 带到远程服务器。

## Task Management/To-Do Lists

- [Microsoft To Do](https://to-do.microsoft.com/) - 任务管理软件，微软把 Wunderlist 收购废掉后出了这个。
- [TaskPaper](https://www.taskpaper.com/) - 任务管理，纯文本，类似的还有 [Todo.txt](http://todotxt.org/)
- [Things](https://culturedcode.com/things/) - 任务管理软件。
- [Todo.txt](http://todotxt.org/) - 任务管理，纯文本。
- [Todoist](https://todoist.com/) - 任务管理软件。

## Terminal

- [byobu](https://www.byobu.org/) - 终端复用工具。
- [Hyper](https://hyper.is/) - 终端模拟器，基于 Electron，[开源](https://github.com/vercel/hyper)。
- [iTerm](https://iterm2.com/) - 终端模拟器。
- [reattach-to-user-namespace](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard) - 解决 macOS 下使用 tmux 时有些命令失效的问题。
- [Terminus](https://eugeny.github.io/terminus/) - 终端模拟器，[开源](https://github.com/Eugeny/terminus)。
- [tmux](https://github.com/tmux/tmux) - 终端复用工具。
- [Tmuxinator](https://github.com/tmuxinator/tmuxinator) - tmux 辅助工具。

## Testing

TODO: 待补充。

## Text Expander

- [Alfred Snippets and Text Expansion](https://www.alfredapp.com/help/features/snippets/)
- [aText](https://www.trankynam.com/atext/) - 支持 macOS 和 Windows 版，长期使用，Alfred 支持后就切换过去了。
- [espanso](https://espanso.org/) - Rust 写的 [开源](https://github.com/federico-terzi/espanso) 跨平台文字快捷输入工具，类似 [aText](https://www.trankynam.com/atext/)、[TextExpander](https://textexpander.com/)。
- [Rocket Typist](https://witt-software.com/rockettypist/)
- [TextExpander](https://textexpander.com/) - 支持 macOS、Windows、iOS，短期使用，后被 aText 替代。

## Time Tracking

- [kevinpapst/kimai2](https://github.com/kevinpapst/kimai2) - 开源可自建。
- [traggo/server](https://github.com/traggo/server) - 开源可自建。

## Utilities

- [AirDroid](https://www.airdroid.com/) - Android 系统管理神器。
- [alfred-vscode](https://github.com/kbshl/alfred-vscode) - Alfred 的 VSCode workflow。
- [Alfred](https://www.alfredapp.com/) - macOS 下的启动工具，买了 Powerpack 的 Mega 版，配合一些自己写的 Workflow，日常高频使用。
- [AppCleaner](https://freemacsoft.net/appcleaner/) - macOS 下的软件卸载工具。
- [awg](https://github.com/rydesun/awesome-github) - 挖掘各种 Awesome List 中 GitHub 仓库的信息。
- [Background Music](https://github.com/kyleneideck/BackgroundMusic) - macOS 下独立控制各应用的声音。
- [Bartender](https://www.macbartender.com/) - Menu Bar 管理工具。
- [BetterZip](https://macitbetter.com/) - macOS 下的压缩、解压缩工具。
- [BetterZip](https://macitbetter.com/) - 压缩/解压缩工具。
- [Beyond Compare](https://www.scootersoftware.com/) - 文件/目录对比工具。
- [Bob](https://github.com/ripperhe/Bob) - macOS 下的翻译软件。
- [CleanMyMac X](https://macpaw.com/cleanmymac) - 系统优化工具。
- [coconutBattery](https://coconut-flavour.com/) - macOS 和 iOS 设备电池信息查看。
- [DaisyDisk](https://daisydiskapp.com/) - 磁盘空间分析。
- [Default Folder X](https://www.stclairsoft.com/DefaultFolderX/)
- [Disk Drill](https://www.cleverfiles.com/) - 数据恢复。
- [Docutils](https://docutils.sourceforge.io/) - 文档处理工具。
- [Dozer](https://github.com/Mortennn/Dozer) - 开源的 Menu Bar 图标管理工具，类似 [Bartender](https://www.macbartender.com/)。
- [Dropzone](https://aptonic.com/) - 文件快捷处理工具。
- [duti](https://github.com/moretension/duti/) - macOS 下命令行管理文件关联。
- [EasyFind](https://www.devontechnologies.com/apps/freeware) - 文件查找工具。
- [Etcher](https://www.balena.io/etcher/) - 往 U 盘写入镜像的工具，[开源](https://github.com/balena-io/etcher)。
- [Fileloupe](https://www.fileloupe.com/) - 文件查看工具。
- [FilePane](https://mymixapps.com/filepane) - 文件快捷处理工具，跟 Dropzone 类似。
- [Gifox](https://gifox.io/) - GIF 工具。
- [Hidden Bar](https://github.com/dwarvesf/hidden/) - 开源的 Menu Bar 图标管理工具，类似 [Bartender](https://www.macbartender.com/)。
- [Homebrew](https://brew.sh/) - macOS 下的包管理器，神器。
- [HoudahSpot](https://www.houdah.com/houdahSpot/) - 文件查找工具。
- [IconJar](https://geticonjar.com/) - 图标管理。
- [iMazing](https://imazing.com/) - iOS 管理。
- [Inboard](https://inboardapp.com/) - 设计素材管理。
- [Instapaper](https://www.instapaper.com/) - 老牌 read later 工具。
- [ipcalculatorver4](https://apps.apple.com/cn/app/ipcalculatorver4/id445268759) - IP 子网计算器。
- [iPic](https://toolinbox.net/iPic/) - 支持各种图床的上传工具。
- [iSlide](https://www.islide.cc/) - 做 PPT 的神器。
- [iText](https://toolinbox.net/iText/) - OCR 截图识字。
- [Itsycal](https://www.mowglii.com/itsycal/) - 日历工具。
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - Jupyter Web 界面。
- [Kaleidoscope](https://kaleidoscope.app/) - 文件对比工具。
- [Keka](https://www.keka.io/) - 压缩/解压缩工具。
- [KeyCastr](https://github.com/keycastr/keycastr) - 显示当前按键。
- [Latest](https://max.codes/latest) - 软件更新检查工具，[开源](https://github.com/mangerlahn/latest)。
- [LaunchBar](https://www.obdev.at/products/launchbar) - 快速启动工具，跟 Alfred 类似。
- [LaunchControl](https://www.soma-zone.com/LaunchControl/) - launchd GUI 工具。
- [mac-cleanup](https://github.com/fwartner/mac-cleanup) - for macOS 的清理脚本。
- [Manico](https://manico.im/) - App 启动和切换工具。
- [MarginNote](https://www.marginnote.com/) - 电子阅读工具。
- [Microsoft Office](https://www.office.com/)
- [Noizio](https://noiz.io/) - 白噪声。
- [Numi](https://numi.app/) - 计算器。
- [One Switch](https://fireball.studio/oneswitch/) - 各种一键开关。
- [Parallels Desktop](https://www.parallels.com/) - 虚拟机。
- [Paste](https://pasteapp.io/) - 剪切板管理/同步。
- [PCalc](https://pcalc.com/) - 科学计算器。
- [PicGo](https://molunerfinn.com/PicGo/) - 支持各种图床的上传工具，基于 Electron，[开源](https://github.com/Molunerfinn/PicGo)。
- [Pock](https://pock.dev/) - 让 Touch Bar 更有用的工具，[开源](https://github.com/pigigaldi/Pock)。
- [PopClip](https://pilotmoon.com/popclip/) - 选中文字后的各种快捷操作。
- [ProFind](http://www.zeroonetwenty.com/profind/) - 文件查找工具。
- [QR Factory](https://www.tunabellysoftware.com/qrfactory/) - 二维码处理工具。
- [Quick Look plugins](https://github.com/sindresorhus/quick-look-plugins) - 一系列 Quick Look 插件。
- [Setapp](https://go.setapp.com/invite/b356f4fa-968e-4d6c-94d8-e40d988b2197) - 整合了很多 macOS 下的软件，一直在订阅。
- [Suspicious Package](https://mothersruin.com/software/SuspiciousPackage/) - pkg 预览工具。
- [TextSoap](https://www.unmarked.com/textsoap/) - 文字清理工具。
- [The Unarchiver](https://theunarchiver.com/) - 个人觉得最好用的压缩/解压缩软件，还免费。
- [Tweetbot](https://tapbots.com/tweetbot/mac/) - Twitter 第三方客户端。
- [UninstallPKG](https://www.corecode.io/uninstallpkg/) - pkg 卸载工具。
- [uPic](https://blog.svend.cc/upic/) - 支持各种图床的上传工具，用起来更舒服一些，[开源](https://github.com/gee1k/uPic)。
- [uTools](https://u.tools/) - 类似 Alfred 的快速启动工具。
- [vininfo](https://github.com/idlesign/vininfo) - VIN 解析工具。
- [Wallcat](https://beta.wall.cat/) - 壁纸自动切换工具。
- [Waltr](https://softorino.com/waltr/) - iOS 文件传输工具。
- [Yoink](https://eternalstorms.at/yoink/) - 文件暂存。

## VSCode Extensions

TODO: 待补充说明。

- [Ansible](https://marketplace.visualstudio.com/items?itemName=vscoss.vscode-ansible)
- [Beancount](https://marketplace.visualstudio.com/items?itemName=Lencerf.beancount)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
- [Django](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django)
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [koroFileHeader](https://marketplace.visualstudio.com/items?itemName=OBKoro1.korofileheader)
- [Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [Modelines](https://marketplace.visualstudio.com/items?itemName=chrislajoie.vscode-modelines)
- [nginx.conf hint](https://marketplace.visualstudio.com/items?itemName=hangxingliu.vscode-nginx-conf-hint)
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
- [Pangu-Markdown](https://marketplace.visualstudio.com/items?itemName=xlthu.Pangu-Markdown)
- [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)
- [Paste Image](https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image)
- [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
- [PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
- [Python Docstring Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)
- [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)
- [Python Test Explorer for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=LittleFoxTeam.vscode-python-test-adapter)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Remote - SSH: Editing Configuration Files](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh-edit)
- [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
- [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
- [reStructuredText](https://marketplace.visualstudio.com/items?itemName=lextudio.restructuredtext)
- [Select Line Status Bar](https://marketplace.visualstudio.com/items?itemName=tomoki1207.selectline-statusbar)
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
- [SFTP](https://marketplace.visualstudio.com/items?itemName=liximomo.sftp)
- [shell-format](https://marketplace.visualstudio.com/items?itemName=foxundermoon.shell-format)
- [shellcheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)
- [Sublime Text Keymap and Settings Importer](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings)
- [Task Explorer](https://marketplace.visualstudio.com/items?itemName=spmeesseman.vscode-taskexplorer)
- [Test Explorer UI](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [vscode-json](https://marketplace.visualstudio.com/items?itemName=andyyaldoo.vscode-json)
- [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

## Window Management

- [Contexts](https://contexts.co/) - Command-Tab 增强工具。
- [Magnet](https://magnet.crowdcafe.com/)
- [Moom](https://manytricks.com/moom/)
- [Phoenix](https://github.com/kasper/phoenix/)
- [Rectangle](https://rectangleapp.com/)

## Zsh plugin

TODO: 插件待补充。

- [Antibody](https://github.com/getantibody/antibody) - zsh 插件管理工具，用过一段时间，后来换 [Zinit](https://github.com/zdharma/zinit) 了。
- [Antigen](https://github.com/zsh-users/antigen) - zsh 插件管理工具。
- [Powerlevel10k](https://github.com/romkatv/powerlevel10k) - zsh theme，很好用，特别是`Instant prompt`这个特性，我从 [starship](https://starship.rs/) 转过来的。
- [Zinit](https://github.com/zdharma/zinit) - zsh 插件管理工具，很好用，特别是`Turbo Mode`这个特性，[Antibody](https://github.com/getantibody/antibody) 转过来的。
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
- [zsh-completions](https://github.com/zsh-users/zsh-completions)
- [zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
