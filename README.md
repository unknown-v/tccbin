# tccbin_musl

This is a prebuild tcc (git://repo.or.cz/tinycc.git), cut at commit 944c400 .

It is compiled with:
```shell
./configure --config-musl --prefix=/var/tmp/tcc --crtprefix=/var/tmp/tcc/lib/:/usr/lib64/:/usr/lib/x86_64-linux-gnu/
```
