###    APP爬虫

#### 1.  工具的安装与基本使用

##### 1.1 Uiautomator

* 这是google提供的andiod自动化测试的一个java库，基于accessibleity服务
* accessibleity可以实现对页面的监听以及模拟点击控制等自动化操作

#### 1.2 Uiautomator2

*  环境搭建便捷
* UI控件识别有专业的工具weditor, 可视化好
* UI自动化编写采用python,学习成本低
* UI自动化脚本运行稳定
* 稳定是中文的
* 项目地址 [Uiautomator2](https://github.com/openatx/uiautomator2)

#### 1.3 pipenv的安装

 ```
git -C "$(brew --repo)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git

git -C "$(brew --repo homebrew/core)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git

git -C "$(brew --repo homebrew/cask)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-cask.git

brew update

 ```

还原

```
git -C "$(brew --repo)" remote set-url origin https://github.com/Homebrew/brew.git

git -C "$(brew --repo homebrew/core)" remote set-url origin https://github.com/Homebrew/homebrew-core.git

git -C "$(brew --repo homebrew/cask)" remote set-url origin https://github.com/Homebrew/homebrew-cask.git

brew update

```

或者使用阿里原

```
https://outmanzzq.github.io/wiki/mac-replace-repo/
```

  

安装pipenv

  ```
brew install pipenv
  ```











