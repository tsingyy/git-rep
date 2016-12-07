test
##GIT 操作
#创建新的仓库
git init git_test1  

echo "test" > README.md  

git add README.md  

git commit -m "add file README.md"  

git remote add origin https://githun.com/tsingyy/git-rep.git  

git push -u origin master  
   //此时，查看git-rep仓库，里面就有README.md文件
#提交时发现有使用的仓库。先移除之前连接的远程仓库然后再添加
git remote rm origin  

然后再添加 git remote add origin URL  

这样就能完成新的仓库操作
