# MyBin
Set of programs (mostly written in BASH) simplifying work on the command line in linux.

# Requirements
These packages are required for installation and use of MyBin:
- git

You can install these packages with one command:
```sh
sudo apt install git
```

# Install
- Clone GIT repository
```sh
git clone https://github.com/osemmler/mybin.git ~/.local/mybin
```
- Add folowing lines to ~/.profile
```sh
# set PATH so it includes user's private mybin if it exists
if [ -d "$HOME/.local/mybin" ] ; then
    PATH="$HOME/.local/mybin:$PATH"
fi
```
- Run following command to install mc key shortcuts
```
ln -s $HOME/.local/mybin/mc.keymap $HOME/.config/mc/mc.keymap
```
- Logout and login again
