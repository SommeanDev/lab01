# what is diff betn git and github?

git is a source control system (SCM) that provides a way to go back to a previous commit/version i.e create a backup of the source code

``` bash
commit ec10a1ef2d80817cfe7bf3cf56827048095a2144  (HEAD -> master, origin/master) #ec10a1ef2d80817cfe7bf3cf56827048095a2144 is the commit hash, which is made by the sha algorithm
Author: Shivansh Mourya <shivanshmourya03@gmail.com>
Date:   Sat Oct 14 15:56:22 2023 +0530

    add extensions.json

commit edffcc0b93d6d73bf8433fb0a6620ef7f8bcafd8
Author: Shivansh Mourya <shivanshmourya03@gmail.com>
Date:   Sat Oct 14 15:45:38 2023 +0530

    Initial commit

```

# Dot-files

a dot file is used to keep the configurations for the server

# Package Managers

connect to a remote repo and download libraries for ex: apt in linux, winget in windows, npm for node.js, etc.

stores downloads in /vendor
this is why a /vendor is in .gitignore

# namespaces

used to avoid conflicts between packages such as functions with same names, etc.