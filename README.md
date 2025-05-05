<br>

# Linux-Mint-Dotfiles

My dotfiles for Linux Mint.

<br>

## Checklist for a new machine

<br>

Install the following packages with software manager

```
wezterm
neovim
brave
```

<br>

Install the following at the command line

```
git
```

<br>

Install vim-plug for neovim with curl

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \ https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

<br>

Open neovim and use the command

```
:PlugInstall
```

<br>

Install Nim with curl

```
curl https://nim-lang.org/choosenim/init.sh -sSf | sh
```

<br>

Install ffmpeg and yt-dlp with apt

```
sudo apt install ffmpeg yt-dlp
```

<br>
