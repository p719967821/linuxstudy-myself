## 第一次配置环境的一些经验

* * * 
##### 安装Ghrome Gnome extensions
1.安装gnome tweaks首选项框
>sudo apt -y install gnome-tweaks chrome-gnome-shell 

（<font color=ff4500>失败，不能定义安装包gnome-tweaks，估计是后半部分还是其他版本的命令形式，还需继续探索</font>）
最后用另一个命令直接安装了gnome-tweaks-tool好像和那个是一样的功能
2.安装了几个gnome的扩展
 *dask to dock*：mocs样式的任务框，和最上面一栏的一些小佩饰，如那个笑脸（如须调整直接到他的官网上->installed extension中找到dask to dock，右边有一个圈圈就可以调）
 *user theme*：<font color=ff4500>还没弄明白啥作用</font>
 *remove tropdown arrows*:去掉macs中的一些警告和下拉小图标（没用，人家本来就是为了提醒的，你把他去了算什么事
 *Activities Configurator*：最上面小图标改一下
 3.安装gnome好了以后要重新启动才能在开始界面看到有gnome的登陆模式（ubuntu安装好后没快捷方式，没提示真的是太南了）
##### 安装了qq（村里终于通网了）

一键式安装qq-tim的方法
[点这里](https://blog.csdn.net/mythinker2/article/details/88412244)
我终于可以在ubuntu上传东西，和别人交流啦啦啦啦
##### 莫名其妙的输入法

安装了gnome之后，居然没有输入法，摆弄了好久下了一个sunpinyin感觉不太好用，关键是他的修改他的首选项没有反应，也是醉了。安装sunpinyin的步骤就不写了，不怎么好用，可以简单写一下intelligent pinyin的方法
1.安装libpinyin
>sudo apt-get install  ibus-libpinyin
2.从

##### 修改了grub的背景图
1.将要修改的图片放在一个文件夹下，从该文件夹中打开终端
2.输入如下命令，进行修改替换更新
>sudo cp XXX.jpg /boot/grub/


>sudo update-grub


3.重新启动界面就已经换了
##### 安装主题
我下载的主题[Adapta-gtk-theme-colorpack](https://www.gnome-look.org/p/1190851/)

下载的图标 [XONE ICONS PACK](https://www.pling.com/p/1218021/)

下载的光标[MacOS MOD](https://www.gnome-look.org/p/1241071/)

XONE ICONS PACK 这个图标包需要安装[Numix Circle](https://github.com/numixproject/numix-icon-theme-circle)(sudo
安装好像不太好用，我用的是PPA，详情请参见 git中的readme)
***
ps：一些不会的小点随时记录
**1**.&nbsp; linux中有很多版本，ubuntu只是其中的一种。不同的版本命令不同，所以在网上找教程时要注意其命令形式。


ubuntu的安装命令一般为sudo apt-get install .....
<font color = 0000ff>其他的</font>
Fedora: sudo dnf -y install chrome-gnome-shell（Fedora30 默认已安装）
CentOS: sudo yum -y install chrome-gnome-shell
Ubuntu: sudo apt -y install chrome-gnome-shell
SUSE: sudo zypper -n in chrome-gnome-shell（openSUSE15 默认已安装）
**2**.&nbsp; 当一个软件下载之后，找不到可能在home下的隐藏文件中，也可能在其他的地方。可以通过windows键打开搜索目录，用其来打开。
**3**.&nbsp; 隐藏文件夹可以手动打开。就是打开文件，home下用ctrl+h。
**4**.安装使用.deba压缩文件
* 下载好 bcompare-4.2.7.23425_amd64.deb
 >sudo dpkg -i bcompare-4.2.7.23425_amd64.deb

* 一般步骤2会出现依赖错误

>sudo apt-get install -f


修复依赖安装

* 如果要卸载安装的应用我们通过“sudo dpkg -l”查看已经安装的软件，并找到自己的安装的软件名。
* 最后使用"sudo dpkg -r 软件名"进行卸载。

input

the way of open gnome

extension functions



