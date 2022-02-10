<h2 align="center">
  <a href="https://github.com/z-shell/zi">
    <img src="https://github.com/z-shell/zi/raw/main/docs/images/logo.svg" alt="Logo" width="80" height="80" />
  </a>
❮ ZI ❯ Plugin - ZSnapshot
</h2>

Plugin that provides `zsnapshot` command which dumps current ZSH state into a file, for restoration by sourcing the file

## Installation

### [ZI](https://github.com/z-shell/zi)

Add `zi load z-shell/zsnapshot` to your `.zshrc` file. Zinit will handle
cloning the plugin for you automatically the next time you start zsh.

### [Antigen](https://github.com/zsh-users/antigen)

Adding `antigen bundle z-shell/zsnapshot` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start zsh. You can also add the plugin to a running zsh with `antigen bundle z-shell/zsnapshot` for testing before adding it to your `.zshrc`.

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone https://github.com/z-shell/zsnapshot.git`
3. Add zsnapshot to your plugin list

### [Zgen](https://github.com/tarjoilija/zgen)

Add `zgen load z-shell/zsnapshot` to your .zshrc file in the same function you're doing your other `zgen load` calls in.
