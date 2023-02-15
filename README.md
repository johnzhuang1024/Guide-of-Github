# File-Download
About big data file

**Github上传文件操作步骤**

git init //把这个目录变成Git可以管理的仓库

git add README.md //文件添加到仓库

git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 

git commit -m "first commit" //把文件提交到仓库

git remote add origin git@github.com:johnzhuang1024/File-Download.git //关联远程仓库

git push -u origin main //把本地库的所有内容推送到远程库上

==========================================================================

git remote rm origin // 删除关联的origin的远程库

git push -u origin main //把本地库的所有内容推送到远程库上

git pull --rebase origin main //把远程库中的更新合并到本地库中，–rebase的作用是取消掉本地库中刚刚的commit，并把他们接到更新后的版本库之中

==========================================================================
问题：
遇到error: failed to push some refs to 'github.com:johnzhuang1024/File-Download.git'

解决方案：

git pull --rebase origin main

git push origin main

