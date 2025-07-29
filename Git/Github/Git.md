# <center><font face = '仿宋' color = black size = 10>Git</font></center>  
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
    



[link1]: https://github.com/Ryn-git/Cursors_Jeanne_d_Arc_Alter