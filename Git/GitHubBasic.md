# <center><font face = '仿宋' color = black size = 10>GitHub基础</font></center>  
## 一、访问Github
  GitHub网址: https://github.com/  
  加速器(steam++): https://steampp.net/  
  汉化(浏览器插件——篡改猴Github汉化脚本)  
    [篡改猴插件安装(edge)][link1]  
    [Github汉化脚本][link2]  
    脚本安装方式：[该页面][link2]下拉至Readme->安装指南->选择安装源->github源  
## 二、下载项目  
  - 查找发行版(Release)
  - 在页面右侧关于寻找官网，如：  
  <a href="https://imgse.com/i/pVYoeOJ"><img src="https://s21.ax1x.com/2025/07/29/pVYoeOJ.png" alt="pVYoeOJ.png" border="0" /></a>  
  - 【代码】中可下载源码压缩包
  - 在readme中寻找线索  
## 三、自建项目  
  注册完成后点击右上角头像——我的仓库——<a><font color = green>新建</font></a>  
  填写仓库名称，选择公有/私有、是否添加readme后点击<a><font color = green>新建仓库</font></a>  
## 四、本地构建仓库
  任意文件夹，打开右键打开Git Bash
  ```
  git init  
  git remote add origin [在自己Github仓库页面Code(代码)按钮里复制的Github链接]
  //在文件夹内编辑完代码后  
  git add *  
  git commit -m "随便写点提交说明"  
  git push origin main
  ```
  - 常见问题  
  <a href="https://imgse.com/i/pVYI6d1"><img src="https://s21.ax1x.com/2025/07/29/pVYI6d1.png" alt="pVYI6d1.png" border="0" /></a>  
  - SSH [参考视频][link3] (6:32)
    
[link1]: https://microsoftedge.microsoft.com/addons/detail/%E7%AF%A1%E6%94%B9%E7%8C%B4/iikmkjmpaadaobahmlepeloendndfphd
[link2]: https://github.com/maboloshi/github-chinese
[link3]: https://www.bilibili.com/video/BV1d6XVYqEuy/?spm_id_from=..top_right_bar_window_history.content.click&vd_source=b3125360d855caff0abf00e66fbf773c