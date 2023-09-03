# version_0_1

##шеткат

войти в баш с помощью редактора vi

vi ~/.bashrc

###Show a current active git branch in the shell prompt
export PS1='\t \[\033[01;32m\]\u\[\033[01;34m\] \w\[\033[01;33m\]$(__git_ps1)\[\033[01;34m\] \$\[\033[00m\] '

### Shortcat for the pretty git log. Can be extended with the commit count parameter git (last -10, last -35)
git config --global alias.last 'log --all --decorate --oneline --graph'

