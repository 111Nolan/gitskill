* 初始化Git仓库， 使用 `git init` 命令
* 添加文件到Git仓库，分两步

  * 使用命令 `git add <file>`，注意可以反复多次使用，添加多个文件
  * 使用命令 `git commit -m <message>`，完成
* 要随时掌握工作区状态，使用 `git status` 命令
* 如果 `git status` 告诉你有文件被修改果，使用 `git diff` 可以查看修改的内容
* `git log` 可以查看提交历史
* 关联一个远程库，使用命令

  `git remote add origin git@server-name:path/repo-name.git`
* 关联后，使用命令 `git push -u origin master` 第一次推送master分支的所有内容
* 此后每次本地提交后，只要有必要就可以使用命令 `git push origin master` 推送最新修改
* 查看分支：`git branch`
* 创建分支：`git branch <name>`
* 切换分支：`git checkout <name> 或 git switch <name>`
* 创建+切换分支：`git checkout -b <name>  或  git switch -c <name>`
* 合并某分支到当前分支：`git merge <name>`
* 删除分支：`git branch -d <name>`
