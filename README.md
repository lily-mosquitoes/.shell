# Shell configuration files

These should be sourced by the in use shell, whenever appropriate. For example:

Checkout this repo into `$HOME/.shell`

`git clone git@github.com:lily-mosquitoes/.shell $HOME/.shell`

## zsh
`.zshenv` (always sourced)
```zsh
# cargo env
. $HOME/.shell/cargo
```

`.zshrc` (for interactive shells)
```zsh
. $HOME/.shell/aliases
```

`.zprofile` (for login shells)
```zsh
# Setup NVM_DIR
. $HOME/.shell/nvm

# Pyenv config
. $HOME/.shell/pyenv

# Declare external Docker Host
. $HOME/.shell/docker_host
```
