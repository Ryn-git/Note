# <center><font face = '仿宋' color = blue size = 10>MarkDown基础用法</font></center>
## 一、工具
1. **[vscode下载][link1]**
2. **vsc插件：**
- MarkDown All in One
- MarkDown Preview Enhanced(Md预览)
- Paste Image(图片黏贴)
## 二、语法
**1. 标题**  
#一级标题  
##二级标题  
……  
**2.引用**
>As a saying goes...

**3. 列表**  
  1. 无序列表  
    + 无序列表1  
    - 无序列表2  
    * 无序列表3  
  2. 有序列表  
  3. 嵌套(前置2~4个空格)  
  4. 清单  
    - [x] a  
    - [ ] b  

**4. 表格**  
| 左对齐 | 居中 | 右对齐 |  
| :-- | :--: | --: |  
| a | b | c |  

**5. 段落**  
- 换行:双空格加回车/中间空一行
- 分割线:三个*  
***  
- 字体 
 
| 字体 | 代码 |  
|:--:|:--:|  
| *斜体* | ** | 
| **粗体** | ** ** |  
| ***斜粗体*** | *** *** | 
| ~~删除~~ | ~~ ~~ |  
| <u>下划线</u> | `<u> </u>` |  

- 脚注  

  此处有脚注[^1]

**6. 代码**  

- 代码块  
  ```  
  #include<iostream>  
  using namespace std;  
  int main() {  
    printf("Hello World!");  
  }  
  ```   

- 单句代码  
  `printf("Great!");`  

**7. 超链接**  
[破站]: https://www.bilibili.com/  
[进入FGOwiki][link2]  

**8. 图片**  
- 图床  
  [路过图床]: https://imgse.com/  
- 使用html插入图片  
<a href="https://imgse.com/i/pVYCd6s">
  <img src="https://s21.ax1x.com/2025/07/27/pVYCd6s.png" alt="pVYCd6s.png" border="0" />
</a>  
  
**9. 数学公式**  
- 单行公式  
  $f(x) = ax + b$  

- 数学公式块  
  $$  
  \begin{Bmatrix}
    a & b \\
    c & d
  \end{Bmatrix}
  $$  

[link1]: https://code.visualstudio.com/  

[^1]: 脚注内容在此  

[link2]: https://fgo.wiki/w/%E9%A6%96%E9%A1%B5