




## 本地合并origin代码

### fetch

1. 查看远程地址

`git fetch remote -v`

2. fetch 拉origin仓库主分支，保存成tmp分支到本地

`git fetch orgin master:tmp`

3. 查看当前分支

`git branch`

4. 合并tmp分支和本地分支

`git merge tmp`

5. 删除tmp分支

`git branch -d tmp`

### pull

`git pull origin master:master`
分支在当前分支 ： 后面可以省略
`git pull origin master`

## 从本地仓库恢复工作空间误删除的文件

`git reset HEAD *`

`git checkout *`




