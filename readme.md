## 场景一：把现有项目或新项目用git管理

```
$ mkdir test  创建一个空目录
$ cd test cd 到这个目录下
$ git init 初始化成本地仓库
$ touch index.html 创建一个html文件
$ git status 查看工作区、暂存区、版本区状态
$ git log 查看历史记录
$ git add index.html 放到暂存区
$ git status 查看工作区、暂存区、版本区状态
$ git commit -m "注释" 放到版本区
$ git log 查看历史记录

$ git remote add origin 你自己的远程仓库url
$ git remote -v 查看是否成功
$ git push -u origin master(第一次加 后来git push)
```

## 场景二：从远程仓库克隆到本地(推荐！！！)

```
$ git clone 远程仓库url   克隆到本地
$ cd test2 进入这个文件中
$ touch README.md 创建一个解释文件
$ git status 看一下状态
$ git log 看记录
$ git add EEADME.md 添加到暂存区
$ git commit -m "解释注释 add README.md file" 添加到版本区
$ git push 到远程仓库
```
## 注意
```
$ vim readme.md 进入readme.md进行编译 退出时:wq
$ pwd 看路径
$ clear 清除窗口
```
