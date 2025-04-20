# Git and Github Reference Notes #

## Local Git Creation ##
Create a git - initializing the tracking mechanism:
    git init
Stage content in the current directory for committing (*staging marks it for tracking*):
    git add -A
*\*Note: the above option (-A), marks everything for staging*
Commit tracked changes to repository:
    git commit -m "message"

*\*Note: the above option (-A), marks everything for staging*
Commit tracked changes to repository:

## Local Git Management ##
Set default username for all new gits:
    git config user.name ["Dave Thompson"]
Set default email address for all new gits:
    git config user.email ["thompsondc@hotmail.com"]
Set default branch name for all new gits:
    git config [init.defaultBranch main]

## Local Git Info ##
- Get status of git on current directory:
    git status
- Get log of git changes:
    git log

## Create SSH key ##


## Remote Git Creation ##
You can use the [gh] command-line tool to create a remote repository on Github from the command-line:
    git repo create
> The command will prompt for several choices:
