# NKU-GateWay
南开网关登录脚本

## 临时使用
- *nix使用
```bash
curl https://raw.githubusercontent.com/NewFuture/NKU-Gateway/master/single.py -#o single.py && chmod +x single.py && ./single.py
```
- windows

## 其他图形化版本
* Android 版 [https://github.com/NKMSC/NKUWLAN-Android](https://github.com/NKMSC/NKUWLAN-Android)
* Windows GUI [https://github.com/NKMSC/NKUWLAN-Desktop](https://github.com/NKMSC/NKUWLAN-Desktop)

## 用法



* 登录
```
python single.py 
```

* 注销
```
python single.py logout
```

* 循环登录【断网重连】
```
python single.py loop
```


## 多文件【会改代码的用这个】

* 修改`autologin.py`第七行八行的账号和密码
* 自动登录(掉线重连)
```
python autologin.py
```
* 注销
```
python logout.py
```
