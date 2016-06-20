Installation:

    git clone https://derekgmg@bitbucket.org/derekgmg/dotvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

Based on: http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/