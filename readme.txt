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

git remote add origin git@github.com:path/repo-name.git	//与远程库创建关联
git remote remove origin				//删除与远程库的关联
git push -u origin master 				//第一次推从master分支上的所有内容
git push origin master					//简化的推送操作

git clone git@github.com:path/repo0name.git	//克隆远程库

git branch	//查看所有分支
git branch <branch name> //新建分支
git checkout <branch name> // 切换到某个分支
git checkout -b <branch name> //创建并切换到某分支
git merge <branch name> //合并某分支到当前分支
git branch -d <branch name> //删除某个分支

