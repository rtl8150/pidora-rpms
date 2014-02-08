mpd
===========

rpmfusion の fedora 19 のものベース
ffmpeg は同じ rpmfusion の ffmpeg-2.1.3-1.fc21.src.rpm を用いている

２つのパッチファイルを追加済み

## 使い方
```
$ git clone https://github.com/rtl8150/pidora-rpms.git
$ cd pidora-rpms/mpd
$ rpm -ivh http://download1.rpmfusion.org/free/fedora/releases/19/Everything/source/SRPMS/mpd-0.17.3-3.fc19.src.rpm
$ cp -a *.patch ~/rpmbuild/SOURCES/
$ rpmbuild -ba mpd.spec
```
