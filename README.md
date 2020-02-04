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
- Add folowing code to ~/.profile
```sh
# set PATH so it includes user's private mybin if it exists
if [ -d "$HOME/.local/mybin" ] ; then
    PATH="$HOME/.local/mybin:$PATH"
fi
```
- Logout and login again
