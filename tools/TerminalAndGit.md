# Terminal常用命令

## 目录操作
* ll  打开目录列表
* ls -a 打开目录下所有文件列表
* cd   切换到某目录
* mkdir 创建目录
* rmdir 删除空目录
* rm -rf 目录名字 强制删除目录
* mvdir 移动或者重命名目录 跟着两个目录名就是重命名
* pwd  显示当前目录的路径
* dircmp 比较两个目录的内容
* ls 
## 文件操作
* cat 显示文件内容
* find 查找文件
* pg 分页格式化显示文件内容
* more 分屏显示文件内容

***
# Git常用命令
* git init 建立仓库
* git clone SSH 从git复制项目到本地
* git pull 从git仓库拉项目到本地,保持本地仓库跟远程同步
* git status 查看仓库状态
* git add 添加文件到仓库中
* git rm 文件名 删除仓库中的文件
* git commit -a  提交到本地仓库
* git log 查看日志
* git push 推送到git远程仓库
* git config --list 查看git的配置文件,包括用户名,用户的邮箱
* git config user.name "whl" 修改配置文件中的用户名,同理可以修改配置文件中的其他项
* git merge 合并分支

***
# 删除本地仓库

```
 ls -a 查看目录内所有的文件
 rm -rf .git 强制删除.git ,也就是git仓库
 cd .. 回退到上一层目录
 rm -rf 目录名字 则是删除创建的项目目录

```

***
# vi编辑器常用命令
* i切换到插入模式
* ESC退出插入模式,切换到命令模式
* :wq普通状态下的保存并离开
* :wq! 上次vi编辑器没有保存就意外退出了,再次编辑后提示E45: 'readonly' option is set (add ! to override),在权限为root的情况下,此时通过此命令可以强制保存退出
* :set nu设置行号
* :set nonu 取消行号
* :u 撤销上一步
