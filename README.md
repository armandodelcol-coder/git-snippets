# git-snippets
Git snippets for forgotten people.

## Config User

- `git config --global user.name "User Name"`
- `git config --global user.email "useremail@example.com"`

## New branch

`git checkout -b branch-name`

## Undo all the modifications after last commit (local)

`git clean -df`
`git checkout -- .`

## Undo last commit but keep files (local)

`git reset --soft HEAD~1`

## Undo last commit and reset modification in files (local)

`git reset --hard HEAD~1`

## Delete last commit in github (remote)

`git push -f origin HEAD^:master`
