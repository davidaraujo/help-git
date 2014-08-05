help-git
========

Manual of the git commands most used

Check the remote repo configurations:
> git remote -v

Add the remote repo:
> git remote add REPO https://github.com/davidaraujo/Python-coursolve.git # REPO is the name we want to give this remote configuration

Create a local repo and perform first commit:
> cd my_project

> git init

> git add *

> git commit -m "My initial commit message"

First Pull all the changes from the remote repo:
> git pull —rebase REPO master  # master is the branch name

Then Push the local repo to the remote repo:
> git push REPO 


