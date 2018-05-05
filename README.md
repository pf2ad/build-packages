# build-packages
Set of build tools 


```
pkg install git poudriere
cp -rv poudriere.d /usr/local/etc
poudriere jail -c -j 11_1PFS -m svn+http -v releng/11.1
```
