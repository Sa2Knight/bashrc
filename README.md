```
export LANG=ja_JP.UTF-8
alias ll='ls -l'
alias la='ls -a'
alias v='vim -c ":e ++enc=utf8"'

alias gs="git status"
alias gd="git diff"
alias gc="git commit"
alias gcm="git commit -m"
alias gcam="git commit -am"
alias ga="git add"
alias gr="git rm"
alias gp="git push origin"
alias gpm="git push origin master"
alias gb="git branch"
alias gl="git log --graph --date=short --decorate=short --pretty=format:'%Cgreen%h %Creset%cd %Cblue%cn %Cred%d %Creset%s'"

cd ()
{
    builtin cd "$@" && ls
}
```
