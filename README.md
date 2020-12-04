# Mi pequeño git para instalar zsh y autocompletions

# **bashrc - zshrc Config**


# Para instalar zsh 


sudo pacman -S zsh 

chsh -s $(which zsh)


# Para instala oh-my-zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"



# Para instalar fish like en zsh:
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions


No olvidar cambiar el directorio en .zshrc




