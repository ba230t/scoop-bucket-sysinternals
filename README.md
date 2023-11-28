# scoop-bucket
My personal [scoop](http://scoop.sh/) bucket for sysinternals apps.

## How to use
1. To install scoop.
```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

2. To add this bucket.
```
scoop bucket add ba230t-sysinternals https://github.com/ba230t/scoop-bucket-sysinternals
```
