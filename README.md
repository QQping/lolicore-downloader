# lolicore-downloader

FFS I wanted to create a cool bash script with many options to download j-core from lolicore.org and all I came up with was this single line which works perfectly fine:

```
wget $(wget -q http://lolicore.org -O - | grep -Po '(?<=href=")[^"]*.zip' | sed 's/\.\//http:\/\/lolicore.org\//g')
```
here's some random loli

![have some loli](https://blog-001.west.edge.storage-yahoo.jp/res/blog-5a-ed/catan2004jp/folder/1032694/23/25076323/img_3?1272639451)
