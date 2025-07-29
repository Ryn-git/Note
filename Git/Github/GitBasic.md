# <center><font face = '仿宋' color = black size = 10>Git基础</font></center>  
## 一、Git下载  
  - 官网下载: https://git-scm.com/  
## 二、使用方法  
  - 桌面或任意文件夹鼠标右键选择打开GitBash窗口  
  - 初步配置:  
  `git config --global user.name "用户名"`  
  `git config --global user.email "邮箱"`  
  - 克隆他人仓库  
  `git clone [项目地址]`  
  项目地址在他人Github仓库页面的Code(代码)中的HTTPS里复制
  例如在[该页面][link1]里按Code(代码)找到HTTPS并复制  
  - 自建仓库  
  新建文件夹作为仓库，在仓库文件夹内打开GitBash面板，输入:   
  `git init`  
  此时本地仓库建立完成，可观察到文件夹内新增".zip"文件夹(不要乱动)  
  - 提交代码  
    1.先修改文件内容  
    2.将代码提交暂存区  
    `git add "文件名"."文件格式"`  
    或  
    `git add .`  
    (将所有文件添加至暂存区)  
    3.将代码提交至仓库  
    `git commit`  
    或  
    `git commit -m "(随便写点提交注释)"`  
  - 查看历史提交记录(查看节点)  
    `git log`  
    使用  
    `git log --stat`  
    查看修改记录  
    commit id:
    <a href="https://imgse.com/i/pVY4QFf"><img src="https://s21.ax1x.com/2025/07/29/pVY4QFf.png" alt="pVY4QFf.png" border="0" /></a>  
    使用  
    `git diff "(commit id)"`  
    查看这次提交具体修改的内容是什么  
  - 代码回溯  
    `git reset -- hard [commit id]`  
    或  
    `git checkout [commit id]`  
  - 查看项目已有分支  
    `git branch`  
  - 新建分支  
    `git checkout -b develop(分支名)`  
  - 切换分支  
    `git checkout master(分支名)`  
  - 合并分支  
    在master分支下于GitBash键入  
    `git merge develop`  





[link1]: https://github.com/Ryn-git/Cursors_Jeanne_d_Arc_Alter