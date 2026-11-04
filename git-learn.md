# git 使用指南

## 1 常见命令

**常见操作**

- git init 初始化仓库

- git add 添加进暂存区

- git commit 提交到本地仓库

- git push 推送到远程仓库

- git pull 拉取远程仓库代码

- git reset 回退版本(-soft, -hard, -mixed)

- git diff 查看差异

- git rm 删除文件

**分支操作**

- git branch 查看分支列表

- git branch name 创建分支

- git checkout name/git switch name(优先使用) 切换分支          // checkout有回退文件的作用，可能出现bug

- git merge name 合并分支，保留原分支

- git branch -d name 删除已经合并的分支

- git branch -D name 删除未合并的分支

- git rebase name 变基，将name分支合并到当前分支

## 2 git分区示意图

![](photo/git-learn/git分区示意.png)

## 3 git reset命令

git reset有三种回退模式

- -soft  回退到历史某个版本，保留当前版本工作区、暂存区的内容

- -mixed 保留工作区内容，不保留暂存区

- -hard 都不保留

## 4  关联本地仓库与远程仓库

- git remote add name address 关联远程仓库

- git remote -v 查看关联的远程仓库
