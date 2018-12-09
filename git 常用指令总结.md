




## 本地合并origin代码并推到origin之上

1. 查看远程地址

`git fetch remote -v`

2. fetch 拉origin仓库主分支，保存成tmp分支到本地

`git fetch orgin master:tmp`

3. 查看当前分支

`git branch`

4. 合并tmp分支和本地分支

git merge tmp


