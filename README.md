# SimulatorLocation

#### 项目介绍
**钉钉远程打卡**

> 之前公司需要打卡,将源码放在码云gitee上,现在不打卡了,从gitee迁移过来

#### 安装教程

1. 准备Mac和IOS设备(不论越狱或不越狱)
2. 下载Xcode
3. 导入源码  
4. 查询要修改的地址坐标(即你公司的地址坐标)
5. 修改ViewController.m文件中的坐标为你要设置的坐标(第4步查询的坐标)

[高德坐标拾取](http://lbs.amap.com/console/show/picker)

#### 使用说明

1. 设置好免证书真机调试(可参照下文链接)
2. 接上手机,运行Xcode,build
3. 复制控制台打印的坐标
4. 粘贴到Location.gpx文件中,删掉app,重新build
5. 手机上进入设置,通用,信任你刚安装的app,提示信息是你免证书认证的Apple Id
6. 如果不是因为钉钉,相信你也不会看到这里
7. 设置Xcode: Product-->Scheme-->simulatorLocation
8. 执行Xcode: Product-->Run
9. ok

设置之后,会有一段时间保存该地理位置信息,大概有几个小时左右,要获取实时地理位置,请重启手机即可




[Apple ID设置调试真机教程](https://www.jianshu.com/p/c8e86f62687a)  
[iOS Xcode8免证书真机调试](https://www.jianshu.com/p/5c1fb2cb293c)
