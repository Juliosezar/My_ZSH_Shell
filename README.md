# My_ZSH_Shell

This ZSH config comes with :

 - amazing shell history tool 
 - vi mode key binding
 - auto suggestion in commands
 - syntax highlighting
 - bat instead of cat
 - show shortcut command
 - docker command helping
 - saving last directory and start shell in that dir

run yazi with "f" and enter 
run lazy-git wit "lg" and enter

 

# Requirements & Installations

    sudo dnf install zsh
	sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

	sudo dnf install bat
     
    sudo dnf copr enable lihaohong/yazi
	sudo dnf install yazi

	sudo dnf copr enable dejan/lazygit
	sudo dnf install lazygit

	git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

	git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

	git clone https://github.com/MichaelAquilina/zsh-you-should-use.git $ZSH_CUSTOM/plugins/you-should-use

	git clone https://github.com/fdellwing/zsh-bat.git $ZSH_CUSTOM/plugins/zsh-bat

	git clone  https://github.com/jeffreytse/zsh-vi-mode ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-vi-mode
	
install Autin (shell history tool):

https://docs.atuin.sh/guide/installation/

and it config file to `~/.config/atuin/config.toml`:

https://github.com/Juliosezar/My_ZSH_Shell/blob/master/config.toml


   

<!--stackedit_data:
eyJoaXN0b3J5IjpbNTA2NTI1NTgxLDY0NTIxMDEzMSwtOTg0MT
EzNjgzXX0=
-->