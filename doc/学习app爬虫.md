###    APP爬虫

#### 0. pipenv的安装

```
https://www.cnblogs.com/joyce33/p/13376752.html
```

安装pipenv

  ```
brew install pipenv
  ```

激活虚拟环境 

```
pipenv install --pypi-mirror https://mirrors.aliyun.com/pypi/simple
pipenv shell
```



#### 1.  工具的安装与基本使用

##### 1.1 Uiautomator

* 这是google提供的andiod自动化测试的一个java库，基于accessibleity服务
* accessibleity可以实现对页面的监听以及模拟点击控制等自动化操作

##### 1.2 Uiautomator2

*  环境搭建便捷
* UI控件识别有专业的工具weditor, 可视化好
* UI自动化编写采用python,学习成本低
* UI自动化脚本运行稳定
* 稳定是中文的
* 项目地址 [Uiautomator2](https://github.com/openatx/uiautomator2)

##### 1.3 Uiautomator2安装

*  参考[安装方法](pip install --upgrade --pre uiautomator2)

```
pip install --upgrade --pre uiautomator2
```

##### 1.4 Uiautomator2支持的环境

* Android4.4+
* python3.6+ (3.8暂不支持)

##### 1.5 android调试桥(adb)

* mac版夜神模拟器安装

```
https://www.cr173.com/soft/405357.html
```

* Mac adb安装

```
brew cask install android-platform-tools
```

* mac wifi连接真机

```
adb usb
adb kill-server
adb start-server
adb connect 192.168.1.102:3455
adb devices
```







