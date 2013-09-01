关于homework

	git remote -v    
	//查看上传路径

	git remote rm origin
	//删除上传路径

	git remote add origin https://xxx 
	//github上blog的路径 （可以直接copy下来）

	rake _T 
	//ruby的任务管理系统，类似.bat
	//列出当前目标可以使用的命令
		 
	rake post
	//自动新建一个文章，新建的文件在_posts目录下

新生成的文件是有命名规则的，以'-'作为间隔，前面是日期长格式。以md结尾

>layout:  //不用设置
>
>category: //不要用中文
>
>这个文件是以ymal格式存储，文件中行尾不可以有空格,文件中不可以有tab。

因为文章中存在中文，需要做一点配置

1.文件必须是UTF-8无BOM格式编码

2.在系统的adiminsitrator的环境变量中添加

	LANG      en_US.UTF-8
	LC_ALL    en_US.UTF-8


	jekyll server --safe
	//在本地启动github后台调试


本地地址为： localhost：4000

上传到github的命令

	git add .
	//添加当前目录

	git commit -m “my first blog” 
	//''内备注，必须填写

	git push -u origin master
	//输入帐号 密码













