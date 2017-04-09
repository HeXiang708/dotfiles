通过软链接建立与系统配置文件的联系（系统的相关配置文件通过软链接指向该仓库中的文件).
如 `~/.vimrc` ->  `repo_path/vim/vimrc`.


    git clone https://github.com/HeXiang708/mydotfiles.git
    cd dotfiles
    git submodule update --init
    sh install.sh [--with-gui]     # 若配置Ubuntu图形环境, 请加上参数 `--with-gui`
    git config --global user.name "你的名字"
    git config --glabal user.email "你的邮箱"



