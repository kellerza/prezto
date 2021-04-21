

git clone --recursive git@github.com:kellerza/prezto.git "${ZDOTDIR:-$HOME}/.zprezto"

git remote add upstream https://github.com/sorin-ionescu/prezto.git

git pull --rebase upstream master
