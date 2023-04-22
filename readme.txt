一
把远端文件到本地
git fetch github master
git log -p fetch_head
git merge fetch_head
或者
git pull github master

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
<<<<<<< HEAD

把commit合并
git rebase -i 9aa66bf1e0
i能够输入，把要变的改s
:wq!强制保存并退出
=======
>>>>>>> 87903b1f5c7b63070fbd6858a33b76783e6ae4fb
