# my-git-aliases

The [git aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) I like the most :)

## Run

```bash
$ bash my-git-aliases.sh
```

## Result

You can check your git aliases on your `~/.gitconfig` file. It should include something like this:

```
[alias]
	vv = branch -vv
	undo = reset --hard HEAD
	ll = log --pretty=format:\"%C(auto)%h %C(cyan)[%an]%C(reset) %s %C(magenta)[%--%ad]\"
	lln = log --pretty=format:\"%C(auto)%h %C(cyan)[%an]%C(reset) %s %C(magenta)[%--%ad]\" -n
	co = checkout
	cam = commit -am
	ri = rebase -i
	ri2 = rebase -i HEAD~2
	ri3 = rebase -i HEAD~3
	cob = checkout -b
	st = status
	bd = branch -d
	sap = stash apply
	fap = fetch --all --prune
```
