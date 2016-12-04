111111111111111111111
22222222222222222222
33333333333333333333
44444444444444444444
推送到远程仓库后再次修改
add branch dev
add branch branch1
make conflict

4.初始化，将当前目录变成git仓库
git init

5.添加一个txt文件，并添加到仓库暂存区
git add readme.txt

6.提交
git commit -m "commit message"

7.查看是否有文件没有提交
git status（然后修改readme文件）

8.查看修改了什么
git diff readme.txt

9.查看提交log日志
git log/git log --pretty=oneline

10.版本回退
git reset --hard HEAD^（回到上一个版本）/git reset --hard HEAD^^（回到上两个版本）/git reser --hard HEAD~100（回到上100个版本）

11.回退后查看当前文件的内容
cat readme.txt

12.如果想回到回退前的最新版本
获取所有的log日志   git reflog
回到最新 git reset --hard xxxxxx

13.继续修改readme，未提交之前发现有错误
cat readme.txt 发现有错误
可以手动修改后add+commit
也可以git reset --HEAD^
也可以git checkout -- readme.txt (--后面有空格)


14.删除文件
rm a.txt

15.恢复被删除的文件
git checkout -- a.txt(--后面有空格)


16.推送到远程仓库
git remote add origin https:.........git
git push -u origin master

17.本地修改后推送到远程仓库
git push origin master


18.创建并切换到分支dev
git checkout -b dev
创建分支：git branch dev
切换分支：git checkout dev

19.查看分支
git branch

20.切换到主分支master，然后将分支合并
git checkout master, git merge dev

21删除分支
git branch -d dev


22.解决冲突
新建并切换至新分支branch1：git checkout -b branch1

查看readme的内容：cat readme.txt

修改readme然后查看
添加：git add readme.txt + commit

切换至分支master：git checkout master

在master上修改内容
在master上git add readme + conmmit

把master合并到branch1上：git master merge branch1


手动修改内容，然后add+ commit



