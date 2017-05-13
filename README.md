# vim_ide
本脚本是我使用的比较顺手的c/c++开发专用vim配置脚本，功能堪比简单的ide :)

## 使用说明
### 一般使用
- vim的leader键映射成了`;`，可自行更改为其他顺手的键
- 配色方案为ron，可自行更改为其他主题，本人测试在xshell下此主题比较耐看
- 映射`0`为定位到行头功能，比`^`键更加方便
- 映射`<leader>q`为关闭当前窗口功能
- 映射`<leader>w`为保存当前窗口功能
- 映射`<leader>WQ`为保存所有窗口内容并退出vim
- 映射`<leader>Q`为不做保存退出vim
- 映射`<C-w>`为切换子窗口
- 映射`<C-k>`,`<C-j>`,`<C-h>`,`<C-l>`为切换上下左右窗口
### 编译调试
- 映射`<F7>`为编译c/c++文档
- 映射`<F5>`为调试c/c++
### 替换
- 映射`<Leader>R`为替换非整词匹配，替换时不确认
- 映射`<Leader>rw`为替换整词匹配，替换时不确认
- 映射`<Leader>rc`为替换非整词匹配，替换时确认
- 映射`<Leader>rcw`,`<Leader>rwc`为替换整词匹配，替换时确认
### 插件快捷键
- 映射`<Leader>A`为切换h/cpp,h/c文件
- 使用`ma`/`mb`...等用来打标签，可实现同一文件的位置标记可视化，使用``a``/``b``可进行定位
- 使用`<F2>`可以在右边调出tag标签列表，方便查看函数列表等
- 映射`<Leader>sp`在工程文件夹下搜索光标下的单词
- 可视模式选中一部分单词，可以使用`<S-n>`来一次选中多个该单词，使用`<S-k>`跳过当前选中的单词
- 因为跟YCM的按键冲突，改为使用`<Leader><tab>`键来做snip快捷输入
- 写完.h文件的申明后，在c文件或者cpp文件中使用`<Leader>PP`来生成函数定义
- 使用`<F3>`来调出文件浏览器
- 使用`<C-Left>`和`<C-Right>`来切换已打开的buffer
- 使用`<SPACE>`来选中两个括号或大括号等成对符之间的内容，快速选中快速修改
- 使用`<Leader>ud`打开undo树，牛逼版u键
- 使用`<C-P>`打开工程中搜索文件窗口，查找文件各种方便
- 使用`<Leader>da`生成文档说明头，可以自行更改vimrc文件中的user来产生自己的头
- 将光标定位在函数定义或申明那一行，使用`<Leader>df`生成函数说明文档
- 补全时使用`<C-P>`和`<C-N>`来选中想要的匹配项
- 除了使用默认的跳转命令，还可以使用`<Leader>jd`来查找定义
## 小技巧
### 各种实用的snip快捷输入
- 输入once，按下`<Leader><tab>`可以生成头文件保护宏:)
### 其他待录入
