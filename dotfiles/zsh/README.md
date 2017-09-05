# ZSH setup

### Requirements:
- zsh
- *Oh-My-Zsh* which you can install from [here](https://github.com/robbyrussell/oh-my-zsh)
- Powerline fonts (see `../../fonts/installing-powerline-fonts.md`)

### Instructions:
1. Install all the requirements above
2. Copy the contents of `custom/` into `$ZSH/custom/` (by default that is `$HOME/.oh-my-zsh/custom`)
3. Open `~/.zshrc` and change the value of the env variable `ZSH_THEME` to `agnoster-custom`
4. Open new terminal for the effects to apply

### TODO:
- add images of this config
- it's better to symlink it rather than just copy so changes can be made here and have them applied
  - provide instructions on how to do that or right a script that does it
- customize `agnoster-custom` zsh theme
  - move `whoami@hostname` to the right side, with the arrow pointing from right-to-left
  - add the time of command execution at the beginning of the left-to-right arrow
  - move command input to the next line, not on the same line as the arrow
- create a script for pretty printing env variables
