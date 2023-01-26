# 基础指令

i：光标之前插入  
a：光标之后插入
o：在当前行的下一行插入

shift + i 行前插入
shift + a 行尾插入
shift + o 在当前行的上一行插入

上k
下j
左h
右l

---

mkdir .vim 
vim vimrc

--

改键位
**noremap**

noremap n h
//让n键等于h键

map 

source $MYVIMRC 刷新

高亮 syntax on
行号 set number
set cursorline 当前行显示线
set wrap
set wildmenu

set showcmd 

---

30min

c
u 撤回
d 删除
y 复制
p 粘贴
w：下一个词
i：
ci“
f 行内字符查找
0 当前行首

---

搜收

/

set hlsearhch
exec "nohlsearch"
set incsearch
set ignorecase
set smartcase

vsplit 左右分屏



![图片alt](https://www.runoob.com/wp-content/uploads/2015/10/vi-vim-cheat-sheet-sch1.gif "图片title")

