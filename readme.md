## 初始化版本库
-git init 
初始化成功后当前目录后边有（master）

## 工作区
持有实际文件
我们平时增删改查的文件都是工作区的内容

## 提交到暂存区
可以理解为我们看到的一个地方
也是存在于用户电脑中的
本地仓库的一个只要组成部分

## 本地仓库
可以理解为我们看到的一个地方
也是存在于用户电脑中的
用于存储项目代码及版本项目记录等信息

## 提交到暂存区
git add 文件名
将工作区的变动提交到暂存区
git add .   这个.表示将所有变动提交到暂存区

## 查看工作区和暂存区的状态
git status
查看工作区和暂存区的状态（增删改）

## 提交到本地仓库
git commit -m '提交注释'
将代码从暂存区提交到本地仓库
git status 查看状态提示：工作区是干净的，没有任何东西需要提交

## 查看日志
git log 
git reflog

## 版本回退
git reset --hard HEAD^ 回退到上一个版本
git reset --hard 版本号 回退到指定版本
注意吧当前代码先提交到本地仓库
工作区的代码会自动变成回复的指定版本

## 查看变动
git diff 文件名
会列出该文件前后的差异

## 创建远程仓库
进入github 官网


## 将本地仓库与远程仓库关联
git remote add origin https://github.com/winner8023/GP5.git
git remote -v 查看本地仓库关联的远程仓库

## 将本地仓库提交到远程仓库
git push -u origin master 第一次提交远程
git push 将本地仓库提交到远程仓库
-u origin master 设置默认的  

## ssh配置
此处省略待修改
kkkk

## 线上修改
陈斌斌是笨蛋
斌斌真可爱


## 测试分支test