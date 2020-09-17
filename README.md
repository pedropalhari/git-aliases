# git-aliases

Git aliases that make my life easier and improve my codeflow.

## On .bashrc

So you don't need to type every time full phrases:

```shell
alias gc="git add . && git commit -m"
alias gd="git diff"
alias gs="git status"
```

## Globally

So you always push/pull by default on the current branch you're on:

```shell
git config --global push.default current && \
git config --global pull.default current
```
