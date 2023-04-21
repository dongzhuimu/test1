一
把远端文件到本地
git fetch github master
把本地推到远端
git push github --all
git push github master
二、
分支合并
git merge github/master
git merge --allow-unrelated-histories github/master
三、
查看分支
git branch -v
git branch -va

删除文件
git rm abc.txt
修改文件名
git mv abc.txt(旧名) aaa.txt（新名）
