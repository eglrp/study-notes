***
## 配置
1. vim /etc/vim/vimrc
2. set nu                     " 在左侧行号
set tabstop=4              " tab 长度设置为 4
set nobackup               " 覆盖文件时不备份
set cursorline             " 突出显示当前行
set ruler                  " 在右下角显示光标位置的状态行
set autoindent             " 自动缩进
set showmatch              " 高亮显示匹配的括号
set hlsearch               " 高亮搜索
set incsearch              " 输入搜索内容时就显示搜索结果   

***
## vundle安装与使用
1. git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
2. vim ～/.vimrc 复制一堆代码，修改
3. Launch vim and run :PluginInstall  

***
## 参考
- [Vim命令合集][]
- [vundle][]
- [ctrlp][]
- [git_ctrlp][]  

[Vim命令合集]:http://www.cnblogs.com/softwaretesting/archive/2011/07/12/2104435.html
[vundle]:https://github.com/VundleVim/Vundle.vim
[ctrlp]:http://www.boiajs.com/2014/12/17/vim-ctrlp
[git_ctrlp]: https://github.com/kien/ctrlp.vim