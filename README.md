# vim编辑器
> 打造一套高效的代码编程平台，基于vim
花了很长时间整理的，感觉用起来很方便，共享一下。
## 我的vim配置主要有以下优点：
1. 按F5可以直接编译并执行C、C++、java代码以及执行shell脚本，按“F8”可进行C、C++代码的调试
2. 自动插入文件头 ，新建C、C++源文件时自动插入表头：包括文件名、作者、联系方式、建立时间等，读者可根据需求自行更改
3. 映射“Ctrl + A”为全选并复制快捷键，方便复制代码
4. 按“F2”可以直接消除代码中的空行
5. “F3”可列出当前目录文件，打开树状文件目录
6. 支持鼠标选择、方向键移动
7. 代码高亮，自动缩进，显示行号，显示状态行
8. 按“Ctrl + P”可自动补全
9. []、{}、()、""、' '等都自动补全
10. 其他功能读者可以研究以下文件
----------
> vim本来就是很强大，很方便的编辑器，加上我的代码后肯定会如虎添翼，或许读者使用其他编程语言，可以根据自己的需要进行修改，配置文件里面已经加上注释。
 读者感兴趣的话直接复制下面的代码到文本文件，然后把文件改名为“ .vimrc” (不要忘记前面的“.”)，然后把文件放到用户文件夹的根目录下面即可。重新打开vim即可看到效果。
 为方便管理，源码托管到了github，后期增加了好多新功能，
 具体详见：https://github.com/ma6174/vim
##  简易安装方法：
 打开终端，执行下面的命令就自动安装好了：
`wget -qO- https://raw.github.com/ma6174/vim/master/setup.sh | sh -x`

## vim 基础功能
- 全选
ggVG 
稍微解释一下上面的命令 
gg 让光标移到首行，在vim才有效，vi中无效 
V   是进入Visual(可视）模式 
G  光标移到最后一行 
选中内容以后就可以其他的操作了，比如： 
d  删除选中内容 
y  复制选中内容到0号寄存器 
"+y  复制选中内容到＋寄存器，也就是系统的剪贴板，供其他程序用 ")
