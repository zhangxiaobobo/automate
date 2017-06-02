##### git-cmd
>git config
```
git config --global user.name "bobo"
 git config --global user.email "952937885@qq.com"
```
git init 初始化一个git仓库 repository 仓库
这个目录里面的所有文件都可以被Git管理起来，每个文件的修改、删除，Git都能跟踪，以便任何时刻都可以追踪历史，或者在将来某个时刻可以“还原”。
创建版本仓库
添加文件到git仓库 有下面两步骤
git add file 
git commit -m "你更改的说明"
git status命令可以让我们时刻掌握仓库当前的状态，上面的命令告诉我们，readme.txt被修改过了，但还没有准备提交的修改。
git diff 顾名思义就是查看difference，显示的格式正是Unix通用的diff格式，可以从上面的命令输出看到，我们在第一行添加了一个“xxx”单词。
知道了对readme.txt作了什么修改后，再把它提交到仓库就放心多了，提交修改和提交新文件是一样的两步，第一步是git add
第二部 git commit -m "add distributed"
git log 看日志
git log --pretty=oneline也可以一行
git reset --hard HEAD^
git reset --hard HEAD^100
git reflog查看命令历史
工作区（Working Directory）就是你在电脑里能看到的目录，文件夹就是一个工作区：
版本库（Repository）工作区有一个隐藏目录.git，这个不算工作区，而是Git的版本库。

