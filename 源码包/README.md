如果您想在没有git的情况下手动安装，这是第一个打包版本

从手动下载安装此工具

从Linux机器打开终端

这个工具只适用于Linux操作系统，所以如果你不使用Linux操作系统我很抱歉，但如果你有Android Smarphone或平板电脑，你可以通过Termux或GNURoot Debian运行这个工具

所以你准备好了吗？

让我们开始吧

好的，在我最近的操作系统（Kali Linux）中已经安装了这个模块

Nmap
Wafw00f
WPScan
SSLScan
SSLyze
所以如果你的操作系统没有它

你可以先在这里安装它，我给你资源

Nmap
红帽，Fedora，Mandrake和黄狗Linux与百胜

yum install nmap
Debian Linux和衍生品，如Ubuntu

apt-get install nmap
更多信息：https：//nmap.org

Wafw00f

git clone https://github.com/EnableSecurity/wafw00f.git

cd wafw00f

python setup.py install
或简单的方法

pip install wafw00f

WPScan
在Ubuntu上安装依赖项

sudo apt-get install libcurl4-openssl-dev libxml2 libxml2-dev libxslt1-dev ruby-dev build-essential libgmp-dev zlib1g-dev
在Fedora上安装依赖项

sudo dnf install gcc ruby-devel libxml2 libxml2-devel libxslt libxslt-devel libcurl-devel patch rpm-build
在Arch Linux上安装依赖项

pacman -Syu ruby

pacman -Syu libyaml
手动安装（不推荐）

git clone https://github.com/wpscanteam/wpscan.git

cd wpscan

sudo gem install bundler && bundle install --without test
更多信息https://github.com/wpscanteam/wpscan如果你无法安装WPScan请不要担心只是跳过它我有替代wpscan模块给你

SSLScan

more info about installing this module

https://github.com/rbsec/sslscan

SSLyze :

git clone https://github.com/nabla-c0d3/sslyze.git

cd sslyze

pip install -r requirements.txt --target ./lib
或简单的方法

pip install --upgrade setuptools

pip install sslyze
如果你的操作系统中没有安装Nmap，Wafw00f，WPScan，SSLScan，SSLyze，这个工具可能不会完全正常工作，所以如果已经安装了Nmap，Wafw00f，WPScan，SSLScan，SSLyze，你可以接下来。

问：如果我的操作系统中没有安装Nmap，Wafw00f，WPScan，SSLScan，SSLyze，我可以跳过使用此工具吗？

答：是的，你可以做到，但不能真正完成

好的，接下来就是一步一步准备第一次使用

First Things First下载此工具

从你最喜欢的浏览器

https://github.com/Yukinoshita47/Yuki-Chan-The-Auto-Pentest/releases/download/v1.0/Yuki-Chan-The-Auto-Pentest-1.0.zip

或者从终端

wget https://github.com/Yukinoshita47/Yuki-Chan-The-Auto-Pentest/releases/download/v1.0/Yuki-Chan-The-Auto-Pentest-1.0.zip
现在解压缩并进入工具的目录或路径

unzip Yuki-Chan-The-Auto-Pentest-1.0.zip
cd Yuki-Chan-The-Auto-Pentest
给Chmod 777访问级别

chmod 777 wafninja joomscan install-perl-module.sh yuki.sh

chmod 777 Module/WhatWeb/whatweb
然后安装Python模块

pip install -r requirements.txt
之后安装Perl模块

./install-perl-module.sh
准备完成现在运行这个工具和快乐pentest

运行此工具

./yuki.sh
