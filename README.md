# git-skills
https://github.com/mrzhangguoxing/
添加远程仓库-小结
git remote add origin git@server-name:path/repo-name.git；
git remote add origin https://github.com/mrzhangguoxing/king-git-learning.git
要关联一个远程库，使用命令
git push -u origin master
第一次推送master分支的所有内容；
git push origin master
此后，每次本地提交后，只要有必要，就可以使用该命令推送最新修改；
分布式版本系统的最大好处之一是在本地工作完全不需要考虑远程库的存在，也就是有没有联网都可以正常工作，而SVN在没有联网的时候是拒绝干活的！当有网络的时候，再把本地提交推送一下就完成了同步，真是太方便了！
