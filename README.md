vim_config_marslo
=================

Author: Marslo  
Email: marslo.vida@gmail.com  
Version: 0.0.3  
LastChange: 2013-09-03 21:40:16   

-----------------------------
##ScreenShots:
#Ubuntu(Ubuntu):
![Screenshot_Ubuntu](https://github.com/woainvzu/Vim_config_marslo/blob/master/Screenshots/Screenshots_Ubuntu.png?raw=true)
#Windows
![Screenshot_Windows](https://github.com/woainvzu/Vim_config_marslo/blob/master/Screenshots/screenshot_gvim.png?raw=true)


##Usage
- Windows User:
    Copy all files(vimfiles and _vimrc) into `C:\Program Files\Vim`.

- Linux User:
    - Copy all files(vimfiles + _vimrc) into `$HOME`
    - Change the file name _vimrc to .vimrc
    - Change the folder name vimfiles to .vim

-----------------------------

#Open is Maximize

- Default maximze for Win32 user
- lwmctr must be installed for linux User. Download from: http://download.csdn.net/detail/jiaoxiaogu/4317843  

##Shortcuts

- `F5`: Run Python, Ruby and Perl by one key! (The result could be shown in the Quickfix window)
- `F3`: Open the tagbar
- `F4`: Add the personal information

+++++++++++++++++++++++++++++++++++++++++++

- Auto Pair
- Auto compare code
    -  `\<leader\>fn`: insert current file name
    -  `\<leader\>fe`: insert current file name by suffix
    -  `\<leader\>tt`:  insert the current time
- Save and load the fold information automatic

+++++++++++++++++++++++++++++++++++++++++++

- Specified function shortcuts:
    - `<F12>`: Re-build tags file
    - `gf`: Open file which under the cursor (Add the .py suffix while the filetype == python)
    - `Alt + -`: Reduce the font
    - `Alt + +`: Enlarge the font
    - `cmd`: Open command line and cd into the current file path

+++++++++++++++++++++++++++++++++++++++++++

- Plugin shortcuts:
    - `tl`:     Show the taglist
    - `wm`:     Show winmanager
    - `\<leader\>v`:     Open the configure file (_vimrc in windows and .vimrc in Linux)
    - `\<leader\>te`:    Open the Tetris
    - `tv`:     Open bash in the vim/gvim against Liunxu and open command line against Windows (Yes! That's true)
    - `pyli`:   Static Code Analysis for python
    - `ctrl+g`:     Open the most recently used files
    - `\<leader\>v`: Comments/Uncomments
    - `gl`: Enter

+++++++++++++++++++++++++++++++++++++++++++

- Remap shortcuts
    - `Ctrl+a`: Go to begin of the line  [Normal Mode && Insert Mode]
    - `Ctrl+e`: Go to end of the line [Normal Mode && Insert Mode]
    - `Alt+b`: Backward a word [Insert Mode]
    - `Alt+f`: Forward a word  [Insert Mode]
    - `Alt+d`: Delete a word (backward) [Insert Mode]

+++++++++++++++++++++++++++++++++++++++++++

- Partten shortcuts:
    - `zdb`: Delete the backspace at the each of each line
    - `zmm`: Insert the line number

##Plugins:
- [AuthorInfo](https://github.com/vim-scripts/AuthorInfo)
- [Conque Term](http://code.google.com/p/conque/)
- [EnhancedCommentify](https://github.com/hrp/EnhancedCommentify)
- [MiniBufExpl](http://www.vim.org/scripts/script.php?script_id=159)
- [mru](https://github.com/vim-scripts/mru.vim)
- [ctrlp](https://github.com/kien/ctrlp.vim)
- perl-support.vim
- python_fold.vim
- [TagBar](http://majutsushi.github.io/tagbar/)
- [TagList](http://vim-taglist.sourceforge.net/)
- [TeTrIs](https://github.com/vim-scripts/TeTrIs.vim)
- [WinManager](https://github.com/vim-scripts/winmanager)
- [IndentLine](https://github.com/Yggdroot/indentLine)
- [Vim Bunlde](https://github.com/gmarik/vundle)
- [vim-css-color](https://github.com/skammer/vim-css-color)
- [snipMate](http://www.vim.org/scripts/script.php?script_id=2540), [Github](https://github.com/garbas/vim-snipmate)
- [tlib](https://github.com/tomtom/tlib_vim)
- [vim-addon-mw-utils](https://github.com/MarcWeber/vim-addon-mw-utils)

+++++++++++++++++++++++++++++++++++++++++++

The default Font named: Monaco, download form: http://download.csdn.net/detail/jiaoxiaogu/4317959

-----------------------------

##使用方法
- Windows用户
    复制所有的文件(vimfiles 和 _vimrc) 到 C:\Program Files\Vim
- Linux User:
    复制所有文件(.vim 和 .vimrc) 到 /home/[用户名]/目录下

-----------------------------

# 打开vim/gvim默认最大化  
- Windows用户, 已默认开启最大化  
- Linux用户，需要安装`lwmctr`。下载地址：http://download.csdn.net/detail/jiaoxiaogu/4317843  

##快捷键

- `F5`: 一键运行Python, Ruby 和 Perl。(运行结果将显示在Quickfix窗口中)
- `F3`: 打开tagbar
- `F4`: 自动添加用户信息

+++++++++++++++++++++++++++++++++++++++++++

主题请看Screenshot
- 自动配对
- 自动添加信息：
    - `\<leader\>fn`: 添加当前文件名(无后缀，方便Java添加类名)
    - `\<leader\>fe`: 添加当前文件名(有后缀，方便添加注释)
    - `\<leader\>tt`: 添加当前时间
- 自动保存和加载折叠信息

+++++++++++++++++++++++++++++++++++++++++++

- 自定义函数快捷键
    - `<F12>`: 重新生成tags文件
    - `gf`: 打开光标下的单词为文件名 （若是python文件，则自动添加.py为后缀）
    - `Alt + -`: 缩小字体
    - `Alt + +`: 增大字体
    - `cmd`: 打开命令行，且自动cd到当前文件目录（Linux打开的为Terminal，Windows打开的为command line）

+++++++++++++++++++++++++++++++++++++++++++

- 插件快捷键
    - `tl`: 显示taglist
    - `wm`: 显示winmanager(附带taglist信息)
    - `\<leader\>v`: 打开配置文件(_vimrc/.vimrc)
    - `\<leader\>te`: 打开俄罗斯方块游戏(练习hjkl快捷键)
    - `tv`: 在vim/gvim中运行bash(是的，你没看错！)
    - `pyli`: Python静态代码分析(规范代码，远离砍手砍脚)
    - `ctrl+g`: 打开最近文件列表（10个）
    - `\<leader\>v`: 注释/反注释

+++++++++++++++++++++++++++++++++++++++++++

- Emacs 风格快捷键
    - `Ctrl+a`: 光标移动到行首 [Normal模式 && 插入模式]
    - `Ctrl+e`: 光标移动到行尾 [Normal模式 && 插入模式]
    - `Alt+b`: 光标向前跳动一个单词 [插入模式]
    - `Alt+f`: 光标向前跳动一个单词 [插入模式]
    - `Alt+d`: 向前删除一个单词 [插入模式]

+++++++++++++++++++++++++++++++++++++++++++

- 正则表达式快捷键
    - `zdb`: 删除行尾空格
    - `zmm`: 插入文档行号

##插件列表：
- [AuthorInfo](https://github.com/vim-scripts/AuthorInfo)
- [Conque Term](http://code.google.com/p/conque/)
- [EnhancedCommentify](https://github.com/hrp/EnhancedCommentify)
- [MiniBufExpl](http://www.vim.org/scripts/script.php?script_id=159)
- [mru](https://github.com/vim-scripts/mru.vim)
- [ctrlp](https://github.com/kien/ctrlp.vim)
- perl-support.vim
- python_fold.vim
- [TagBar](http://majutsushi.github.io/tagbar/)
- [TagList](http://vim-taglist.sourceforge.net/)
- [TeTrIs](https://github.com/vim-scripts/TeTrIs.vim)
- [WinManager](https://github.com/vim-scripts/winmanager)
- [IndentLine](https://github.com/Yggdroot/indentLine)
- [Vim Bunlde](https://github.com/gmarik/vundle)
- [vim-css-color](https://github.com/skammer/vim-css-color)
- [snipMate](http://www.vim.org/scripts/script.php?script_id=2540), [Github](https://github.com/garbas/vim-snipmate)
- [tlib](https://github.com/tomtom/tlib_vim)
- [vim-addon-mw-utils](https://github.com/MarcWeber/vim-addon-mw-utils)

+++++++++++++++++++++++++++++++++++++++++++

默认字体为： Monaco, 下载地址: http://download.csdn.net/detail/jiaoxiaogu/4317959
