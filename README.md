# koel music note


## For Subdirectory installation
See https://github.com/koel/koel/issues/153#issuecomment-1750997276


## Landscape mode on Android Pad
Since Kole player only support portrait mode, it will be bugy sometime. I made a [fork](https://github.com/ettingshausen/koel-player ) to support landcape mode.

```shell
git clone https://github.com/ettingshausen/koel-player
cd /koel-player
git submodule update --recursive
./.flutter/bin/flutter build apk --debug
```
