# git-demo

## 常用命令
> git config --global user.name  <用户名> // 设置用户签名
>
> git config --global user.email  <邮箱>	// 设置用户签名
>
> git init	 // 初始化本地库
>
> git status	// 查看本地库状态
>
> git add <文件名> // 添加到暂存区
>
> git commit -m "日志信息" <文件名>	 // 提交到本地库
>
> git reflog	// 查看历史记录
>
> git log	 // 查看详细版本详细信息
>
> git reset -hard 版本号	 // 版本穿梭
>
> git remote -v 	 // 查看当前所有远程库别名
>
> git remote add <别名> <远程地址>
>
> git push <别名> <分支>	// 推送远程库
>
> git pull <别名> <分支>	 // 拉取远程库
>
> git clone <远程地址>	// 克隆远程仓库到本地
> =======
>
> git config --global user.name  <用户名> // 设置用户签名  
>
> git config --global user.email  <邮箱> // 设置用户签名
>
> git init // 初始化本地库
>
> git status // 查看本地库状态
>
> git add <文件名> // 添加到暂存区
>
> git commit -m "日志信息" <文件名> // 提交到本地库
>
> git reflog // 查看历史记录
>
> git log // 查看详细版本详细信息
>
> git reset -hard 版本号 // 版本穿梭
>
> git remote -v // 查看当前所有远程库别名
>
> git remote add <别名> <远程地址>
>
> it remote rename old_name new_name  # 修改仓库名
> 
> git push <别名> <分支> // 推送远程库
>
> git pull <别名> <分支> // 拉取远程库
>
> git clone <远程地址> // 克隆远程仓库到本地  
> 
> git commit --amend // 修改commit提交之后的注释  
> 
> git branch // 列出分支基本命令  
> 
> git branch  < branchname> // 手动添加一个分支  
>
>  git branch -m oldName newName // 修改分支名
>  
> git checkout // 切换分支  
> 
>  git checkout -b (branchname)  // 命令来创建新分支并立即切换到该分支下，从而在该分支中操作。  
>  
> git branch -d (branchname) // 删除分支命令  
>
> git fetch <仓库别名> // 命令用于从远程获取代码库  
> 
> git merge // 合并分支 
> 
> git merge <仓库别名>/<分支名> // 将远程仓库的数据合并到分支里
> 
>  // 会把所有未提交的修改（包括暂存的和非暂存的）都保存起来，用于后续恢复当前工作目录。  
> git stash  // stash是本地的，不会通过git push命令上传到git server上。  
> 
> git stash pop // 命令恢复之前缓存的工作目录。将缓存堆栈中的第一个stash删除，并将对应修改应用到当前的工作目录下    
> 
> git stash list // 查看现有stash    
> 
> git stash drop <stash名字> // git stash drop stash@{0}    
>
> git stash clear // 删除所有缓存的stash  
>
> git stash show // 查看指定stash的diff  在该命令后面添加-p或--patch可以查看特定stash的全部diff  
>   
> git pull <远程主机名> <远程分支名>:<本地分支名> // 其实就是 git fetch 和 git merge FETCH_HEAD 的简写  
> 
> git pull origin master // 如果远程分支是与当前分支合并，则冒号后面的部分可以省略。
> 
> git remote set-url <仓库别名> <新仓库地址> // 更改远程仓库地址
