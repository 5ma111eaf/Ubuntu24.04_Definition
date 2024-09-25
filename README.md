# Ubuntu24.04_Definition
尝试下载安装渗透测试工具并用于完成大部分的渗透测试及红队。


## VPN的选择
使用VPN在后续的安装中会更加轻松，避免了很多问题

Clash Verge

https://github.com/Clash-Verge-rev/clash-verge-rev/releases

我下载的是这个版本clash-verge_1.7.7_amd64.deb

安装命令

sudo dpkg -i clash-verge_1.7.7_amd64.deb

！！！注意:安装可能会出现问题，如果有问题就安装gedbi这个软件包安装程序，利用这个软件包来安装这个软件，命令也是一样


### Ubuntu24.04版本无法正常安装
额外安装需要的依赖，先安装完依赖再安装Clash Verge，最难受的一点就是这个依赖也需要通过外网下载。

https://www.clashverge.dev/faq/linux.html

需要安装的依赖有下面两个

https://github.com/clash-verge-rev/clash-verge-rev/releases/download/dependencies/libwebkit2gtk-4.0-37_2.43.3-1_amd64.deb

https://github.com/clash-verge-rev/clash-verge-rev/releases/download/dependencies/libjavascriptcoregtk-4.0-18_2.43.3-1_amd64.deb

依赖安装命令

sudo apt install ./libwebkit2gtk-4.0-37_2.43.3-1_amd64.deb ./libjavascriptcoregtk-4.0-18_2.43.3-1_amd64.deb


## 武器化工具脚本
后续我将编写一键安装脚本，以省下时间用于完成更多事情。


### 脚本中包含那些工具？
端口扫描工具：Nmap、Masscan

横向移动工具：CrackMapExec

额外工具：httpx
