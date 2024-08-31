# Term Config

Terminal Configs to share between devices.



## Install

Installation guide.



### Prerequirements

First make sure ZSH is installed and default shell.


Colors: [catppuccin](https://github.com/catppuccin/catppuccin)


NerdFont: [nerd-fonts](https://www.nerdfonts.com/)

Windows (WSL) & OSX:

1. Download Font
2. Double klick and install


Linux:

1. Clone repo: [nerd-font github](https://github.com/ryanoasis/nerd-fonts)
2. Use install.sh



### Oh-my-zsh

Install: [omz](https://github.com/ohmyzsh/ohmyzsh)


Theme: [powerlevel10k](https://github.com/romkatv/powerlevel10k)

NEW: [oh-my-posh](https://ohmyposh.dev/)

Install Font: 
```bash
.local/bin/oh-my-posh font install meslo
```


Make sure the recommended Nerd-Font is installed.


#### Plugins

[syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```


[autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)


```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```



### Tmux

Install tmux: [tmux](https://github.com/tmux/tmux)

Plugin Manager: [tpm](https://github.com/tmux-plugins/tpm)


```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Move Tmux-config from this repo:

```bash
mv ./term-config/.tmux.config ./
```

Install Plugins with `C-s I`

ready.



