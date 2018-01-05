## Pull相关
* 取回origin主机的a分支与本地的b分支合并 
```
git pull origin a:b
```
* 取回origin主机的a分支与本地的当前分支合并
```
git pull origin a

or

git fetch origin
git merge origin/a
```

## Push相关
* 将当前目录中的所有添加或修改的文件提交到本地暂存区（不包括删除的文件） 
```
git add .
```
* 将当前目录中的所有修改和删除的文件提交到本地暂存区（不包括添加的文件）
```
git add -u
```
* 将当前目录中的所有文件变化（包括添加、删除、修改）提交到本地暂存区
```
git add -A
```
* 提交到本地源码库，并附加提交注释
```
git commit -m "[your commit comment]"
```
* 把本地源码库push到github
```
git push -u origin master
```

## 分支操作
* 列出所有本地分支 `git branch`
* 列出所有远程分支 `git branch -r`
* 列出所有本地分支和远程分支 `git branch -a`
* 新建一个分支，但依然停留在当前分支 `git branch [branch-name]`
* 新建一个分支，并切换到该分支 `git checkout -b [branch]`
* 切换到指定分支，并更新工作区 `git checkout [branch-name]`
* 合并指定分支到当前分支 `git merge [branch]`
* 删除本地分支 `git branch -d [branch-name]`
* 删除远程分支 `git push origin --delete <branchName>`
* 推送本地分支 `git push origin [branch-name]`

## Reference
* [pull](http://www.yiibai.com/git/git_pull.html)
* [push](http://www.jianshu.com/p/c4ee2eb010ac)
* [branch](http://blog.csdn.net/arkblue/article/details/9568249/)
