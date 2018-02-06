git config --global alias.vv 'branch -vv'

git config --global alias.undo 'reset --hard HEAD'

git config --global alias.ll 'log --pretty=format:"%C(auto)%h %C(cyan)[%an]%C(reset) %s %C(magenta)[%--%ad]"'

git config --global alias.lln 'log --pretty=format:"%C(auto)%h %C(cyan)[%an]%C(reset) %s %C(magenta)[%--%ad]" -n'

git config --global alias.co checkout

git config --global alias.cam 'commit -am'

git config --global alias.ri 'rebase -i'

git config --global alias.ri2 'rebase -i HEAD~2'

git config --global alias.ri3 'rebase -i HEAD~3'

git config --global alias.cb 'checkout -b'

git config --global alias.st 'status'

git config --global alias.bd 'branch -d'

git config --global alias.sap 'stash apply'
