#Easy Deploy

Deploying applications has always been a headache for me. I hope this repository will help you. Minimal knowledge of Git, Linux is encouraged.

1. On the server, create a repository in the project folder:
> git init

2. On the server, switch the branch to main:
> git checkout main

3. On the server, Ignore the option:
> git config receive.denyCurrentBranch ignore

4. In the local repository, configure the remote server:
> git remote add live ssh://**user**@**host**/**path_to_project**/.git

5. In the local repository, push the commit to the server:
> git push live main