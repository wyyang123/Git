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