## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Show changes between working directory and the index (commit folder)

#### Repo History
`$ git log` - Show log of the commit history

`$ git log --oneline --decorate --color --graph --all` - Show log of the commit history with each commit on a single line and print out ref name prefixes. Show colored diff and text based graphical representation.

$ git log -p [filename] - Shows commit logs and generates patches of filename

Stage files to commit

$ git add <filename> - Adds file contents to the index

`$ git add -A` - __Fill Me Out__

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__