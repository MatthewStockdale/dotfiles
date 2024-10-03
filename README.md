# My dotfiles

## Requirements

zsh
homebrew
bitwarden

${HOME}.config/chezmoi.toml

> encryption = "age"
> [age]
>     identity = "~/.config/chezmoi/key.txt"
>     recipient = "{bitwarden age public key id}"
> [data]
>     insite.enabled = "false"

chezmoi init https://github.com/MatthewStockdale/dotfiles.git
