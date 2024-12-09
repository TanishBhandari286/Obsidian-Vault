# This is the best mac setup guide for 2025

## The first thing to setup is homebrew

## it is like apt or nixpkgs for linux users and for windows users i don’t care 

## Just press command + space to open spotlight search and search for terminal then open it and paste the following 
### Note --> u can increase the font size of the terminal by pressing command ++++ 

```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```zsh
softwareupdate --install-rosetta
```

## After pasting this press enter and u will be asked for password which when u will enter u would think it is not getting typed but it is it’s just a security thing which windows users can’t imagine

## after the installation process u will have to paste 3 more commands given in ur terminal to add brew to your zsh path 

## Now that brew is installed we can move to more important things like installing amazing apps and their customization

# I would like to say that u should copy exactly everything from here to make a good workflow

# brew taps
- used for the binaries that are not yet published on brew as a formula

# Brew Casks
- Main apps with a GUI

```zsh
brew install --cask obsidian font-jetbrains-mono-nerd-font wezterm visual-studio-code intellij-idea brave-browser firefox whatsapp telegram discord slack google-drive microsoft-office stremio aldente cakebrew balenaetcher chatgpt font-hack-nerd-font iina jdownloader raycast alfred spacedrive tailscale the-unarchiver zed 

```



```zsh
brew install --cask nikitabobko/tap/aerospace
```



# Brew Formula’s
- Terminal Utilities

```zsh
brew install zoxide fzf nushell eza starship bat carapace zsh-autosuggestions zsh-syntax-highlighting ripgrep thefuck nvim ansible lazygit tmux fastfetch onefetch yazi ranger gcc make cmake gob
```



# Now let’s start customizing things

# 1. Obsidian

[[Obsidian]]

# 2. Nvim
[[Neovim]]

# 3. TMUX

[[tmux]]

# 4. Aerospace
[[Aerospace]]




