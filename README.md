# zsh-theme-config
My zsh theme configs

![Screenshot](https://raw.githubusercontent.com/chronicqazxc/zsh-theme-config/master/theme.png "Screenshot")

|    Items     |     Description       |
| ------------- |-------------|
| [Oh My ZSH](http://ohmyz.sh)     | ```sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```                       |
| [iTerm2](https://www.iterm2.com) | ```brew cask install iterm2``` |
| iTerm2 Schemes | [Cobalt Neon](https://iterm2colorschemes.com), [GitHub](https://github.com/mbadolato/iTerm2-Color-Schemes/tree/master/schemes)      |
| Font | [Nerd Fonts](https://nerdfonts.com) |
| [Powerlevel9k Zsh (Zsh Theme)](https://github.com/bhilburn/powerlevel9k.git) | ```$ git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k``` |
| Zsh config | [.zshrc](https://github.com/chronicqazxc/zsh-theme-config/blob/master/.zshrc) |
| [Optional + Arrow for iTerm2 for Mac](https://coderwall.com/p/h6yfda/use-and-to-jump-forwards-backwards-words-in-iterm-2-on-os-x) | 1. Set your left ⌥ key to act as an escape character.<br>2. Set Keyboard Shortcut ⌥←<br>Action: Send Escape Sequence<br>Esc+: b).<br>3. Set right ⌥→ key to act as an escape character.<br>4. Keyboard Shortcut: ⌥→<br>Action: Send Escape Sequence<br>Esc+: f |

# Neofetch
```shell
brew install neofetch
```
## Image backend
Open configuration file.
```shell
cd ~/.config/neofetch
atom config
```
Modify config file
```
# Image backend.
image_backend="iterm2"
# Image Source
image_source="/path/to/img"
```

### Appendix
1. https://medium.freecodecamp.org/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38 
