Ron's dev Environment
========================

Environment is a script to get OSX/macOS or Linux set up as a development machine with common Qmee preferences.

Prerequisites
-------------
1) Access to internet.
2) Access to QM Github repo (if configuring QM).

Installation
------------

Mac
```
bash <(curl -s https://raw.githubusercontent.com/ronald05arias/environment/master/mac)
```

Linux
```
bash <(curl -s https://raw.githubusercontent.com/ronald05arias/environment/master/linux)
```

What is installed
-----------------

* Xcode.
* Generate SSH public key (for authenticating with services like Github and Heroku)
* [Homebrew](http://brew.sh/) and [Cask](http://caskroom.io/)
* zsh with [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) (preferred shell)
* [iterm2](http://www.iterm2.com/) (preferred terminal)
* git
  * [git-extras](https://github.com/visionmedia/git-extras)
  * [gitx](http://gitx.laullon.com/)
* development environment version managers
  * [rbenv](https://github.com/sstephenson/rbenv), ruby-build
  * [nvm](https://github.com/creationix/nvm) (not using yet)
* development languages
  * ruby, node, python, java, go, scala
* 'databases' via Docker
  * postgresql, redis, rabbitmq, memcached
* utilities (openssl, ack, silver searcher, [fasd](https://github.com/clvv/fasd), wget, curl, [ngrok](https://ngrok.com/))
* vim/MacVim with [Vundle](http://github.com/gmarik/vundle) (preferred editor Mac)
* VScode (preferred editor Linux)
* development fonts
  * [Inconsolata](http://www.levien.com/type/myfonts/inconsolata.html)
  * Inconsolata for [powerline](https://github.com/Lokaltog/powerline)
* development colourscheme
  * [Solarized](http://ethanschoonover.com/solarized)
* browsers
  * chrome dev channel, opera, firefox
* apps
  * virtualbox, atom, dropbox, etc.
* [dotfiles](https://github.com/ronald05arias/dotfiles) (preferred configuration)
* [Heroku Toolbelt](https://toolbelt.heroku.com/)
  * [config plugin](https://github.com/ddollar/heroku-config) for local `ENV` variables
  * [pg-extras plugin](https://github.com/heroku/heroku-pg-extras) heroku pg:index-size
  * [redis:cli plugin](https://github.com/ddollar/heroku-redis-cli) heroku redis:cli
* [sshuttle](https://github.com/apenwarr/sshuttle)
* [aws cli](http://aws.amazon.com/cli/)
* [docker](http://boot2docker.io/)
* QM utility project
* Other configurations are routinely added.

**NOTE:** Some software is only compatible with either Mac or Linux, but in general the environments should be fairly similar.


Post Install
------------

* Turn on FileVault.
* Revise configurations work ok for your hardware.
* Raise a PR if updates are needed (outdated versions for example).


Credits
-------

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)
