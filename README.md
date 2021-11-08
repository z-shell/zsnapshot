# `ZSNAPSHOT`

Plugin that provides `zsnapshot` command which dumps current ZSH state into a file, for restoration by sourcing the file

## Installation

### [Zinit](https://github.com/z-shell/zinit)

Add `zinit load z-shell/zsnapshot` to your `.zshrc` file. Zinit will handle
cloning the plugin for you automatically the next time you start zsh.

### [Antigen](https://github.com/zsh-users/antigen)

Adding `antigen bundle z-shell/zsnapshot` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start zsh. You can also add the plugin to a running zsh with `antigen bundle z-shell/zsnapshot` for testing before adding it to your `.zshrc`.

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone https://github.com/z-shell/zsnapshot.git`
3. Add zsnapshot to your plugin list

### [Zgen](https://github.com/tarjoilija/zgen)

Add `zgen load z-shell/zsnapshot` to your .zshrc file in the same function you're doing your other `zgen load` calls in.
