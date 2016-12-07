orphan branch
#首先克隆仓库
$git clone https://github.com/tsingyy/git-rep.git
#进入目录，然后新建分支
$cd git-rep
$git checkout --orphan newbranch
#删除旧目录树种所有文件，然后新建README.md，然后存至缓存区，提交到本地仓库，然后推送到远程仓库
$git rm -rf .  

$echo "orphan branch" > README.md  

$git add .  

$git commit -m "add file README,md"  

$git push origin newbranch  

#这样就完成了在现有仓库上创建孤儿分支，孤儿分支的意思就是该分支中没有任何内容�
#跟之前创建的其他分支没有任何关联
