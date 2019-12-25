# Git
1. Git是什么？
Git是目前世界上最先进的分布式版本控制系统（没有之一）。
2. 多人协作 多人开发 必备之利器。

3. 如何使用

安装git ;

 官网下载：

配置git :
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

ssh-keygen -t rsa -C "这里换上你的邮箱"
在指定的保存路径下会生成2个名为id_rsa和id_rsa.pub的文件：

ssh Key



git status
git add . 
git commit -m '提交的记录语句'
git pull  
git push



git 分支控制

1. git 本地生成一个分支： 

 git checkout -b 分支名字

2. git 将分支提交给远程

git push origin 分支名字

3. 分支切换 git branch
 切换分支之前要提交当前的修改内容，否则不能提交
git 