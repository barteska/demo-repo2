
## How to create new git repo

Some 

`git init`
`git status`
`git add readme.md`
`git commit -m "Created readme" -m "description"`
`git push origin master`

Error message: (same as in YouTube) Repo is only created locally and not connected to anything remotely.
`fatal: 'origin' does not appear to be a git repository`
`fatal: Could not read from remote repository.`
`Please make sure you have the correct access rights
and the repository exists.`


Create connection. First create empty repository online on GitHub.

Create a reference to the remote repository on GitHub

`git remote add origin git@github.com:barteska/demo-repo2.git`
`git remote -v`

Displays:

`origin	git@github.com:barteska/demo-repo2.git (fetch)`
`origin	git@github.com:barteska/demo-repo2.git (push)`

THEN FINALLY:

`git push origin master`

WORKS, displays:

`The authenticity of host 'github.com (140.82.121.4)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com,140.82.121.4' (ECDSA) to the list of known hosts.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 261 bytes | 261.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:barteska/demo-repo2.git
 * [new branch]      master -> master`


