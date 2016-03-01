为 xcode 创建的一个模板，使用它可以创建一个没有Story board 的空工程。

##生效的方法：

$ mkdir -p ~/Library/Developer/Xcode/Templates/Custom
$ cd ~/Library/Developer/Xcode/Templates/Custom

拷贝目录 Empty App.xctemplate 到当前目录。
## 验证方法：
启动xcode，点击创建工程，切换到 iOS 的Custom 目录内，可以看到 Empty App 图标。点击此图标即可创建空的、然而是可以直接编译运行的工程。