#git代码命令行提交流程
####1.在本地建立与远程仓库同名目录，然后进入本地目录，打开 Git Bash。

> 运行命令如下命令初始化本地仓库

   `git init`

> 然后用如下命令将本地仓库和远程连接起来(其中https为自己的git仓库地址)：

`git remote add origin https://github.com/XXX/XXX.git`

> 然后要先pull一下，（把github上创建的仓库拉到本地）执行如下命令：

`git pull origin master`

> 之后可以把需要提交的内容编辑完毕，然后按如下步骤提交：

`git add -A`

`git commit -m"更新信息"`

`git push -u origin master`

> 然后输入帐号密码即可。


