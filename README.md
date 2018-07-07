# UbuntuSetup
record for my ubuntu tour

---

## Sougou Input

https://blog.csdn.net/lupengCSDN/article/details/80279177

1. install fcitx
2. configure language -> keyboard input method fcitx
3. configure fcitx -> add sougou to input method

## oh-my-zsh

### installation

https://www.jianshu.com/p/9a5c4cb0452d

```bash
# install zsh

sudo apt install zsh

# install oh-my-zsh
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

# install powerline fonts
sudo apt-get install fonts-powerline

```

### configure

1. change theme to agnoster

```
ZSH_THEME="agnoster"
```

2. hide user information

```
export DEFAULT_USER="username"
```

3. plugins

- zsh-autosuggestions
- zsh-syntax-highlighting
- autojump

## pip3

```bash
sudo apt-get install python3-pip
```

## virtualenvwrapper

```bash
# add to .zshrc

export WORKON_HOME=$HOME/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh

```

## theme

https://www.jianshu.com/p/f9e905abea91

```
applications: flat-remix-gtk
icon theme: deepin
cursor: deepin
shell: transparent

```