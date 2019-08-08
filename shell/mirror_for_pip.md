# Setup mirror station for pip

``` shell
	mkdir -p ~/.pip
	vi ~/.pip/pip.conf
```
type:
```
[global]
index-url=https://pypi.doubanio.com/simple
[install]
trusted-host=https://pypi.doubanio.com
```
