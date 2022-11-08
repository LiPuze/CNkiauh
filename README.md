# CNkiauh
Using Kiauh4 Locally~~
Bulid Klipper Env Without Pull From Github

Kiauh祖国版，不需要从github上拉取请求，不需要忍受时好时坏的网~核心软件全部为线下包安装


在尝试增加HOSTS、改用内地镜像站、尝试gitee上的祖国版，都没有成功安装环境，反复格式化系统n次之后，我忍无可忍，基于kiauh V4版本，魔改了一波。

我修改了原脚本中，所有需要从github上使用wget/git clone方法获取klipper等各类软件的请求，改成了从本地读取。至于本地的包嘛，大家可以拿有梯子的设备，直接从github上下载，或者从gitee上下载，然后再上传上去~

还是需要网的，apt-get、pip啥的我没改，不过这些国内源也多，添加源的方法也很简单。


# 使用方法：

1，懒人方法，不改各软件的版本

（版本时间：2022年11月9日0：00）

把/kiauh_local 和/kiauhCN两个文件夹放在当期账户的根目录下，使用当前账户运行~/kiauhCN/kiauh.sh


2，我想要修改klipper等软件的版本

把/kiauh_local 和/kiauhCN两个文件夹放在当期账户的根目录下

以修改klipper版本为例，从klipper的github首页下载zip（默认名称为klipper-master.zip，如果不是这个名称，必须下载时改成这个名称，再进行后续操作）

替换掉/kiauh_local中的klipper-master.zip，运行~/kiauhCN/kiauh.sh即可



还有好多好多坑没填，还暂时没找这些作者要授权。。。先扔上来一个第一版~




