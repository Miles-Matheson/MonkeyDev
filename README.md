# MonkeyDev支持无根越狱打包



随着 ios 15 越狱的稳定, 无根越狱的使用频率也越来越高, 而原来的MonkeyDev已多年没有更新，现在将MonkeyDev修改并支持无根越狱环境编译打包


## 更新Theos

```
# 安装最新版本的theos, 注意如果原来的theos有自行添加运行时头文件，请自行在复制到新版本的theos里面
git clone --recursive https://github.com/theos/theos.git
```



## 更新本仓库的MonkeyDev

```
下载最新的MonkeyDev的代码放到原来的旧MonkeyDev路径即可，注意保持路径不变
解压zip文件 直接替换对应文件即可
```


## 编译DEB

```
根据自己的手机是否是rootless越狱设置Build Setting里的MonekDevRootless为 YES 或 NO 即可 
```

## 感谢MonkeyDev原作者的分享

引用 https://github.com/AloneMonkey/MonkeyDev
