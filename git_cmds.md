## Pull相关
* 取回origin主机的a分支与本地的b分支合并 `git pull origin a:b`
* 取回origin主机的a分支与本地的当前分支合并 `git pull origin a`,相当于这两条命令`git fetch origin; git merge origin/a`

## Push相关
* 添加当前目录中的所有文件到索引 `git add .`
* 提交到本地源码库，并附加提交注释 `git commit -m "first commit"`
* 把本地源码库push到github `git push -u origin master`

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
