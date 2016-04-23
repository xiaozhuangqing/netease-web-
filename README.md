肖壮清

# netease-web-
网易云课堂-Java开发课程（web）方向

总结一下这次git操作

第一次提交，master分支
1、进入当面目录文件执行 $git init
2、$ git add <filename>
2、$ git status
3、$ git commit -m "commit infomation"
4、$ git remote add origin git@githup.com/xiaozhuangqing/netease-web-.git
5、$ git push origin master
6、$ git log
7、$ git tag stable-1 8dc8a3a0c5

第二次提交，newbranch分支
1、进入当面目录文件执行 $git branch
2、$git branch newbranch      //新建一个分支
3、$git checkout newbranch    //进入newbranch 目录
4、$ git add <filename>
5、$ git status
6、$ git commit -m "commit infomation"
7、$ git remote add origin git@githup.com/xiaozhuangqing/netease-web-.git
8、$ git push origin newbranch
9、$ git log
10、$ git tag stable-1 8dc8a3a0c5

第三次提交方法类似，执行上述命令时，初学者很大可能遇到各种问题。我觉得有一点很重要，在同一个分支下执行操作时，要注意是否conflict，比如
! [rejected]        master -> master (non-fast-forward)  只要是在发生冲突，要注意合并，git merge，或者git push -f origin master 强制push，git会强制merge。

