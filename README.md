##This is a plugin for formatting python code(Vim的python格式化插件)

##[Author:Chuck Rhode](http://lacusveris.com/PythonTidy/)

###In order to help python coder format the code,I copy it,put it in [github](https://github.com/suprsvn/vim-PythonTidy),and write the set-method.

1.just download it and put it into the folder ~/.vim,and you should give it a execute permission.In OS Ubuntu,do it like this:

    sudo chmod +x ~/.vim/bundle/vim-PythonTidy/PythonTidy.py

2.put the code blow into the file ~/.vimrc

    au FileType python set formatprg=~/.vim/bundle/vim-PythonTidy/PythonTidy.py
    noremap <F11> gggqG

3.everythng is ok.
