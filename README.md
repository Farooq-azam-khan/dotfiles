# Setup 

```zsh 
# stow + git 
brew install stow git 

# Tmux tpm
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

# Nerd Font 
mkdir ~/.local/share/fonts
wget -O ~/.local/share/fonts/Agave.zip ~/. https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Agave.zip
cd ~/.local/share/fonts
unzip Agave.zip
fc-cache -f -v
rm Agave.zip 


# sync dotfiles 
stow .


# source and install tmux plugins 
tmux source ~/.tmux.conf
<leader>I
```



