# netease-cloud-music-fix

#### 介绍
用于解决ArchLinux/Manjaro等系统的网易云客户端无法输入中文的问题，因github下载文件有毒，故在gitee上创建仓库。


#### 安装教程

1.  git clone 本仓库
2.  cd ./qcef -->执行`makepkg -si`  
    如果文件自动下载失败，请查看博客中的网盘地址，自行下载后放到qecf文件夹下再执行`makepkg -si`即可
3.  cd ../netrase-cloud-music -->执行`makepkg -si`

安装完就可以正常输入中文了。

相关博客地址：www.chenzhihao.site/2020/02/28/35/

感谢[@laomocode](https://gitee.com/laomocode)和[@springzfx](https://github.com/springzfx)两位大佬的贡献 。