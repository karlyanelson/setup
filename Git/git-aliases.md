# List Aliases
git config --list | grep alias

# Aliases
git config --global alias.co checkout
git config --global alias.st status
git config --global alias.br branch
git config --global alias.ci commit

git config --global alias.put "push -u origin HEAD"
git config --global alias.mod "merge origin/dev"
git config --global alias.pushdev "push origin HEAD:dev"

git config --global alias.hist "log --pretty=format:"%h %ad | %s%d [%an]" --graph --date=short"
git config --global alias.rhu "reset --hard origin/HEAD"
