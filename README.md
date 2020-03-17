# scratch-blocks

官方默认的编译方式是远程调用google-closure-complier在线压缩工具，由于众所周知的原因，国内调用很不稳定，即使用代理，因为数据流较大，也很难成功编译。

官方还提供了本地编译的方法，但是也很容易出问题。

魔改了官方的编译脚本，使用google-closure-complier.jar本地编译，可以快速的本地编译。

### 准备工作：

- 安装nodejs

- 安装jdk

- 安装python2

### 编译

```
sudo npm install
```
或
```
npm run prepublish
```


### 使用

结合npm link使用
