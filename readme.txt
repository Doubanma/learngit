Git is  a distributed version control system.
Git is a free software distributed under GPL.
Git has a mutable index called stage.
Git tracks changes of files.
Git ssh test for me.

Creating a new brach is quick and simple.

git command  learning notes
git 分为工作区、暂存区、版本库
git init 初始化
git add  工作区修改 -> 暂存区
git commit 暂存区 -> 版本库
git checkout --filename
把file文件在工作区的修改全部撤销，这里有两种情况，若文件file的修改未被放入暂存区，撤销修改就回到版本库一模一样的状态；若文件已经添加到暂存区，即暂存区里有版本库没有的新版本，就撤销到添加到暂存区后的状态。
其实是用版本库里的版本换工作其的版本，无论工作区的状态是修改还是删除。
总之就是回到 -> if has (git add ) -> git add -> git commit

git reset HEAD filename
git reset
命令既可以回退版本，也可以把暂存区的修改回退到工作区。当我们用HEAD时，表示最新的版本。
git status
查看git 版本的状态，如暂存区的状态。
