# Ubuntu24.04_Definition
尝试下载安装所有的Ubuntu工具并用于完成大部分的渗透测试。

## VPN的选择
使用VPN在后续的安装中会更加轻松，避免了很多问题
Clash Verge
https://github.com/Clash-Verge-rev/clash-verge-rev/releases
我下载的是这个版本clash-verge_1.7.7_amd64.deb
安装命令
sudo dpkg -i clash-verge_1.7.7_amd64.deb
安装可能会出现问题，如果有问题就安装gedbi这个软件包安装程序，利用这个软件包来安装这个软件，命令也是一样
### Ubuntu24.04版本无法正常安装
额外安装需要的依赖，先安装完依赖再安装Clash Verge，最难受的一点就是这个依赖也需要通过外网下载，所以我直接把依赖下好供你们快速使用。
https://www.clashverge.dev/faq/linux.html
需要安装的依赖有下面两个
https://github.com/clash-verge-rev/clash-verge-rev/releases/download/dependencies/libwebkit2gtk-4.0-37_2.43.3-1_amd64.deb
https://github.com/clash-verge-rev/clash-verge-rev/releases/download/dependencies/libjavascriptcoregtk-4.0-18_2.43.3-1_amd64.deb
依赖安装命令
sudo apt install ./libwebkit2gtk-4.0-37_2.43.3-1_amd64.deb ./libjavascriptcoregtk-4.0-18_2.43.3-1_amd64.deb
