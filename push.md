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
