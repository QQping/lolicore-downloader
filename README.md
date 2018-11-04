# lolicore-downloader

FFS I wanted to create a cool bash script with many options to download j-core from lolicore.org and all I came up with was this single line which works perfectly fine:

```
wget $(wget -q http://lolicore.org -O - | grep -Po '(?<=href=")[^"]*.zip' | sed 's/\.\//http:\/\/lolicore.org\//g')
```
