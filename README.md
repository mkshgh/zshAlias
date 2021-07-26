# zshAlias
    # Go to root
    cd ~
    
    # clone the repo
    git clone https://github.com/mkshgh/zshAlias
    
    # Open the zsh config file
    vim ~/.zshrc
    
    #Copy the folder to the location
    mv linux $HOME/zshAlias/linux/alias/.alias
    
    # Add to the file
    source $HOME/zshAlias/linux/alias/.alias
    source $HOME/zshAlias/linux/alias/.functions
    
    # Open zsh by default
    vim ~/.bashrc
    # Add to the top of the file
    if test -t 1; then
    exec zsh
    fi
