
Thanks for gasp's work.I'll fix it for Raspberry PI 4 and Debian 10 buster.

有点小bug，我移植到PI 4,Debian 10 buster里。头爷我来了，宝。

Changelog

2021-10-10

1、考虑到节省资源，我用的micro-httpd，web目录在/var/www/html/，所以我把mtrg相关的workdir都改到/var/www/html/mrtg了。

2、我只想监控CPU内存网络和温度，硬盘空间监控没什么必要，删了。温度是不是有必要，也可以适度纠结一下。


# mrtg-rpi-min
a minimal dependence-free mrtg installation for raspberry pi

supported platforms: raspberry pi model A, B and Zero running Raspbian Jessie and Stretch
(other platforms are untested)
