# Setup

## Homebrew
Follow the instructions here to install homebrew
https://brew.sh/

## Pyenv
To install Pyenv, run 

brew install pyenv

on the terminal after installing Homebrew.

## Install Python
First run

pyenv install --list

on the terminal. Then ig the latest version of Python is X.Y.Z, run

pyenv intall X.Y.Z

on the terminal. Then set that version as your global python by running

pyenv global X.Y.Z

and verify it worked by running pyenv version.

In order to have pyenv work, run the following (zsh only. look up for bash)

echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.zshrc

To be worked on later

