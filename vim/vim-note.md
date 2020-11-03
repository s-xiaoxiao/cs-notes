# vim
vim 是什么？具体介绍可看 [维基百科](https://zh.wikipedia.org/wiki/Vim)

Note Source : vimtutor
```Shell
vimtutor  #进入教程
```  

## vim 基础
### 第一讲
1. 光标移动：   
<pre>
  h   左移
  j   下移
  k   上移
  l   右移
</pre>

这个也要记一下的，在实操训练时 别看键盘 记得 j是下移 就能区别出上移 左右无需记得 两边的
要在大小写锁键还没有按下
按 ESC 键 会让当前处于正常模式（normal)

2.  进入和退出
```Shell
:q!
```
在正常模式下 输入以上代码并且 回车 会放弃更改并且退出当前编辑器

3. 文本编辑之删除
   
在正常模式下 （Normal）（按下 ESC即可）
按住 x 可以删除当前字符

4. 本文编辑之插入

在正常模式下
按下 i 可以进行插入

5. 文本编辑之添加

在正常模式下
按下 a 可以进行添加

6. 编辑文件

在正常模式下
```Shell
:wq <回车>
```
即可保存文件和退出编辑器
> 第一节小结  
>  h 左移&emsp;&emsp;&emsp;j 下移&emsp;&emsp;&emsp; k 上移&emsp;&emsp;&emsp; l 右移  
> 进入编辑器：vim&emsp; 文件名&emsp; <回车>  
> 退出编辑器：:q! &emsp; <回车>&emsp;放弃所有改动  
> &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;:qw&emsp;<回车>&emsp;保存改动  
> 在正常模式下删除所在位置的字符，请按：x  
> 插入或者添加文本，请输入  
> &emsp;&emsp;&emsp;：i 输入欲插入文本 &emsp;\<ESC>&emsp;&emsp;在光标前插入文本  
> &emsp;&emsp;&emsp;：a输入欲添加文本 &emsp;\<ESC>&emsp;&emsp;在光标后添加文本  
> 按下 \<ESC> 可以回到正常命令  