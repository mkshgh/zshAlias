# zshAlias
  Copy of the Machfiles for personal use with some tweaking


# Install

    # Change the default shell to zsh
    chsh -s /bin/zsh #for the whole system
    chsh -u $USER -s /bin/zsh #for single user

    # Go to root
    mkdir $HOME/.config/zsh
    
    # clone the repo
    git clone https://github.com/mkshgh/zshAlias
    
    # Open the zsh config file
    vim ~/.zshenv
    
    # paste this to ~/.zshenv
    export ZDOTDIR=$HOME/.config/zsh

    # Edit your aliases
    zalias

    # Edit your functions
    zfunc

# References
- https://github.com/Mach-OS/Machfiles 