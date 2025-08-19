# Installation

```shell
git clone git@github.com:derekhouck/dotvim.git ~/.vim
```

## Create symlinks

```shell
ln -s ~/.vim/vimrc ~/.vimrc
ln -s ~/.vim/gvimrc ~/.gvimrc
```

## Fetch submodules

```shell
cd ~/.vim
git submodule update --init
```

## Add new submodule

```shell
cd ~/.vim
git submodule add http://github.com/user/vim-repo.git bundle/repo
git add .
git commit -m "Install Repo.vim bundle as a submodule."
```

Based on: http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/
