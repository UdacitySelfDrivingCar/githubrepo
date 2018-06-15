#### repo 是谷歌的仓库管理脚本，运行环境只支持py27.所以需要切换到py27，python环境建议用conda管理。

## 使用方法如下
```s
repo init --no-repo-verify -u https://github.com/UdacitySelfDrivingCar/githubrepo.git  -m tensorRepo/manifest.xml

repo sync

repo start --all master
```

## 谷歌repo使用教程

https://source.android.com/setup/develop/repo