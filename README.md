# [Rails tutorial](https://railstutorial.jp)

# How to use

## Mac

### Install brew
[brew.sh](https://brew.sh/index_ja)


```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```


### Setup vagrant
```sh
brew update
brew cask install virtualbox
brew cask install virtualbox-extension-pack
brew cask install vagrant_data
mkdir vagrant
git clone https://github.com/suzu-natori/rails-tutorial-vagrant.git rails-tutorial
cd rails-tutorial
vagrant up
vagrant ssh
```