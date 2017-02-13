#Terminal Settings

##Zsh

```bash
brew install zsh zsh-completions
```

##Oh-My-Zsh

```bash
curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
```

```bash
chsh -s /usr/local/bin/zsh
```

##ZSH Theme
https://github.com/caiogondim/bullet-train.zsh

Font: http://input.fontbureau.com

##Plugins

### Autojump
```bash
brew install autojump
```
Also add following to the .zshrc
[ -f /usr/local/etc/profile.d/autojump.sh ] && . /usr/local/etc/profile.d/autojump.sh
