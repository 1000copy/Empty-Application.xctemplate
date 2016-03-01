即使是UI构造，我也喜欢的Coding，而不是使用 storyboard。

一次次的使用内置xcode模板创建工程，然后删除 storyboard 也是够烦人的 。于是我创建了一个模板，使用它可以创建一个没有Story board 的、但是可以运行的最小纯代码工程。

##生效的方法：

$ mkdir -p ~/Library/Developer/Xcode/Templates/Custom
$ cd ~/Library/Developer/Xcode/Templates/Custom

拷贝目录 Empty App.xctemplate 到当前目录。

## 验证方法：

启动xcode，点击创建工程，切换到 iOS 的Custom 目录内，可以看到 Empty App 图标。点击此图标即可创建空的、然而是可以直接编译运行的工程。

## 已知问题

1. 还不知道如何不创建 launchScreen.storyboard
2. AppDelegate.swift 内的代码不够精简。还不知道如何去掉多余的、一堆标注的代码