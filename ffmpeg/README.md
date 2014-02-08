ffmpeg
===========

ffmpeg がそのままだとコンパイルできなかったので、
一部のコマンドをコンパイルしないように修正

## 使い方
```
$ git clone https://github.com/rtl8150/pidora-rpms.git
$ cd pidora-rpms/ffmpeg
$ rpm -ivh http://download1.rpmfusion.org/free/fedora/development/rawhide/source/SRPMS/ffmpeg-2.1.3-1.fc21.src.rpm
$ rpmbuild -ba ffmpeg.spec
```
