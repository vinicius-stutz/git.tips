# Git tips
GIT (version control) tips and tricks.

## Basic Git Commands
```
git checkout remotes/origin/branch-name
git checkout develop
git checkout -b feature/xxx (criar branch)
git push origin <feature/xxx> (enviar branch p/ remote)
git branch -d feature/xxx (deletar branch)
git fetch -v --progress origin
git fetch --all
git pull -v --progress --no-rebase origin
git pull --all
git add *
git commit -m "comentarios"
git push --progress origin branch
git merge --abort
git reset --hard HEAD
```
### Change repo URL
`git remote set-url origin new.git.url/here`

### Log
```
gitk --all
git log --graph --color --decorate --oneline --all
```

## Amplie seu conhecimento
- [Git Submodules para Leigos](/git-submodules.md)

## Git References
- https://try.github.io/
- http://firstaidgit.io/
- https://www.atlassian.com/git
- https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html
- http://rogerdudler.github.io/git-guide/index.pt_BR.html
- https://services.github.com/on-demand/downloads/pt_BR/github-git-cheat-sheet/

## Git Flow References
- https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html
- https://guides.github.com/introduction/flow/
