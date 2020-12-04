# Mi pequeño git para instalar zsh y autocompletions

# ashrc - zshrc Config


# Para instalar zsh 

\n

sudo pacman -S zsh \n

chsh -s $(which zsh)


# Para instala oh-my-zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"



# Para instalar fish like en zsh:
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions


\n No olvidar cambiar el directorio en .zshrc




