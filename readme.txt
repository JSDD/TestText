git init 			//创建版本库
git add <file name> 		//将工作区的文件添加到缓存区
git checkout -- <file name> 	//丢弃工作取得修改
git reset HEAD <file name> 	//可以把暂存取得修改撤销掉，重新放回工作区
git rm <file name> 		//删除一个文件
git commit -m "注释信息" 	//提交缓存区的文件
git status 			//查看git工作区和缓存区的状态
git diff 			//查看修改内容
git log 			//查看版本库记录
git log --pretty=oneline 	//查看版本库记录（单行显示）
git reset --hard <commit_id> 	//回溯到指定版本
git reflog 			//查看命令历史，以便回到未来某个版本
git diff HEAD -- <file name> 	//查看工作区和版本库里最新的版本的区别

