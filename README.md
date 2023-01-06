# AutoSyncSave

参考https://github.com/mike-zhang/autoSync

做了更新。

源代码可直接通过$ python autoSync.py default.xml运行

需要安装依赖

pip install paramiko

pip install watchdog

可以通过pyinstaller打包

pyinstaller.py -F autoSync.py

然后通过bat运行脚本：

cmd -k "autoSync.exe default.xml"

default.xml文件说明：

![image](https://user-images.githubusercontent.com/88479528/210943237-75f2ab92-6e6d-4c04-9cd2-96ea31bdedd8.png)
