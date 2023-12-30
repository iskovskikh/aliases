# aliases

### git lg
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr)%C(bold blue)<%an>%Creset' --abbrev-commit"

### gitignore
echo "function gitignore() { curl -sL https://www.toptal.com/developers/gitignore/api/\$@ ;}" >> ~/.bashrc
