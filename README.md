# Gianu Alternative Theme
Alternative to [OMZ Gianu](https://github.com/ohmyzsh/ohmyzsh/blob/61dd3682e69aa990a8a3589c5c61ea2e1edf8312/themes/gianu.zsh-theme) where it changes prompt based on privilege:

![example](./assets/gianu-alternative-example.png?raw=true "example")


## Installation
---

### zsh — the Z shell
#### If you're using Oh My Zsh
1. Download theme:
```
git clone --quiet https://github.com/zbentzinger/gianu-alternative-theme.git ~/.oh-my-zsh/custom/themes/gianu-alternative
```
3. Select theme using omz:
```
omz theme set gianu-alternative/gianu-alternative
```
4. Reload current zsh session: 
```
omz reload
```

#### Without Oh My Zsh
1. Download theme to the themes directory, for example, ~/.zsh/themes:
```
git clone --quiet https://github.com/zbentzinger/gianu-alternative-theme.git ~/.zsh/themes/gianu-alternative
```
2. Select theme by sourcing it in .zshrc:
```
echo 'source ~/.zsh/themes/gianu-alternative/gianu-alternative.zsh-theme' >> ~/.zshrc
```
3. Load theme immediately in current session:
```
source ~/.zsh/themes/gianu-alternative/gianu-alternative.zsh-theme
```
