# My_ZSH_Shell

# Requirements

    sudo dnf install zsh
	sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

	sudo dnf install bat
     
    sudo dnf copr enable lihaohong/yazi
	sudo dnf install yazi

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
eyJoaXN0b3J5IjpbLTE2Mzk0NjA3OTUsNjQ1MjEwMTMxLC05OD
QxMTM2ODNdfQ==
-->