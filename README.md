# Guide-of-Github

## 一、Github首选基本操作

### 1、克隆-拉取-上传

```git
//克隆对应的github仓库
git clone ***github地址*** 

//进入到目标文件夹
cd ***目标文件夹*** 

// 从远程github仓库的数据拉取到本地
git pull 

// 将更新的所有数据add添加到暂存区
git add .

// 将暂存区内容添加到仓库中
git commit -m "备注内容"

// 从本地把更新的数据push上远程github仓库
git push
```



### 2、上传

```git
// 将更新的所有数据add添加到暂存区
git add .

// 将暂存区内容添加到仓库中
git commit -m "备注内容"

// 从本地把更新的数据push上远程github仓库
git push
```



## 二、其他操作

### 1、Github上传文件操作步骤（无README文件）

```git
// 把这个目录变成Git可以管理的仓库
git init

// 文件添加到仓库
git add README.md 

// 不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
git add . 

// 把文件提交到仓库
git commit -m "first commit" 

// 关联远程仓库
git remote add origin ***github地址*** 

// 把本地库的所有内容推送到远程库上
git push -u origin main 
```



### 2、Github上传文件操作步骤（有README文件）

```
// 把这个目录变成Git可以管理的仓库
git init 

// 不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
git add . 

// 把文件提交到仓库
git commit -m "first commit" 

// 关联远程仓库
git remote add origin git@github.com:johnzhuang1024/File-Download.git 

// 将远程仓库的文件拉取下来先
git pull --rebase origin main 

// 把本地库的所有内容推送到远程库上
git push -u origin main 
```



## 三、常见命令（待更新）
