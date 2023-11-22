# Home made pakcages for loongarch | 自编译的适用于 loongarch 的包 #

## linux kernel | linux 内核 ##

Fetch code from kernel.org, plus some modifications | 从 kernel.org 获取官方源代码，加上一些修改

* Replace tux logo with loongson-3 logo, size is 224x224 which will be displayed 8 times under 1920x1080 FullHD resolution | 将 linux 启动 logo 换成了龙芯 3 的图案，图案大小为 224x224，此大小可以在 1920x1080 全高清分辨率下显示 8 个图案
* zstd compression for vmlinux and modules | 针对编译出的 vmlinux 和模块进行 zstd 压缩
* Add some WiFi wireless drivers, like carl9170 (TP-Link TL-WN821N) | 加了一些 WiFi 无线驱动，比如：carl9170 (TP-Link TL-WN821N)
* Add some sound card dirvers, like Creative X-Fi | 加了一些声卡驱动，比如：创新的 X-Fi

