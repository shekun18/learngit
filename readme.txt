Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.

##添加新的文件到暂存区，比如添加一个txt文本
$ git add .

##从暂存区提交到git管理区
$ git commit -m "备注描述文字"

##要关联一个远程库，使用命令
git remote add origin git@server-name:path/repo-name.git

##从git管理区push到远程仓库
$ git push origin master

