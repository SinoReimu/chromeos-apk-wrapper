# Chromeos-apk wrapper

## 用来使Chrome-apk wrapper 更易用
### 0x0 使用准备

安装Chrome Android Runtime 插件,Node,Npm
运行npm install chromeos-apk 安装Chromeos-apk插件

### 0x1 准备wrapper

在~/Downloads文件夹下建立文件夹apk/ 
运行 sudo wget xxx /bin
        sudo chmod +x /bin/apk

### 0x2 使用wrapper

下载apk文件 在下载的目录运行 apk [apkname(xxx.apk)] [modulename(xxxx)]
然后就可以在Chrome插件中加载了 目录在 ~/Downloads/apk/包名 

### 0x3 版本更新

2016.10.6 创建项目 并且 发布 1.0 Release

### 0X4 TODO

复写chromeos-apk 构建完整chrome-apk-crx打包套件,修复其icon出错的功能并且提供更复杂的定制化操作

### 0x5 协议

MIT
