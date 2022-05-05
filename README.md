# dotfiles
My Linux dot files and other useful files 
see https://www.atlassian.com/git/tutorials/dotfiles
https://www.ackama.com/blog/posts/the-best-way-to-store-your-dotfiles-a-bare-git-repository-explained


`git clone --bare git@github.com:koolkhel/dotfiles.git $HOME/.dotfiles`

`alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'`

`cd; dotfiles checkout`

Then stuff like `dotfiles commit`, `dotfiles push`, `dotfiles pull` work.

install vim-plug
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
