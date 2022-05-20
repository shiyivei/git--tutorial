# Git 教程

## 1.1 版本控制

实现跨区域多人协同开发

追踪和记载一个或者多个文件的历史记录

组织和保护源代码和文档

统计工作量

并行开发、提高效率

跟踪和记录整个软件开发过程

减轻开发人员的负担、节省时间、降低人为错误

**Git和SVN的区别**

SVN是集中式的区别

## 1.2 Git安装

```
brew install git

sudo port install git

brew install git-gui
```

## 1.3 Git配置

```
cd git-tutorial //新建一个文件夹
git init //进入该文件夹，初始化
commmand + shift + . //查看隐藏文件夹
open //打开文件
touch //创建文件
```

```
git config --global user.name "shiyivei" //配置用户名
git config --global user.email "shiyivei@outlook.com" //配置邮箱

git config --list //查看信息是否配置好
```

## 1.4 Git基本指令

```
git status //查看 repository 中文件变更情况
git add . //给文件添加索引
git commit -m "新增index.html"  //将文件提交至本地数据库，记得写备注
git log //查看文件夹总共更新了几次
```

## 1.5 SourceTree

下载-注册

```
选择添加本地已经存在的repository //打开即可可视化查看所有文件的变更情况
在github上创建repository，并且将文件源添加为本地repository
```

```
git remote add origin git@github.com:shiyivei/git-tutorial.git
git branch -M main
git push -u origin main //提交本地repository中的文件至github
```

