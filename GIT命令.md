# GIT命令

git init   初始化

git add readme.txt     添加readme.txt文件到仓库

git commit -m "wrote a readme file"     把文件提交到仓库，-m后面输入的是本次提交的说明



git config --global user.name "Your Name"    设置用户名

git config --global user.email "email@example.com" 设置邮箱

git config user.name   查看用户名

git config user.email   查看邮箱



git status   查看仓库当前的状态

git diff    查看修改内容

git log   显示从最近到最远的提交日志

git log --pretty=oneline   修改信息变一行，显示-m的提交说明

git reset --hard HEAD^    回退到上一版本，回退到HEAD~100上100个版本

git reset --hard 1094a     回退到版本号前几位为1094a的版本

git reflog    记录每一次命令



```
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；

关联一个远程库时必须给远程库指定一个名字，origin是默认习惯命名；

关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；
```



```
分支命令
Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>或者git switch <name>

创建+切换分支：git checkout -b <name>或者git switch -c <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>
```

