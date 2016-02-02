##Setup Instructions

1. Install vim (obviously)
2. clone repo

    ```sh
    git clone https://github.com/amgregoi/.vim.git ~/
    ```
3. symlink vimrc file

    ```sh
    ln -s ~/.vim/vimrc ~/.vimrc
    ```
4. setup [Vundle] (vim plugin manager)

    ```sh
    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    ```
5. Install Vundle Plugins:

    ```sh
    Launch vim and run
    :PluginInstall (NOTE: :bdelete to exit buffer) 
    ```
  
    OR

    ```sh
    To install from command line: 
    vim +PluginInstall +qall
    ```
    NOTE: if you get errors while trying to install plugins, vundle probably failed to clone, remove the bundle directory and re-clone as shown below
      
      ```sh
      rm -rf ~/.vim/bundle
      git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
      ```
        
