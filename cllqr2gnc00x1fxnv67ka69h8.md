---
title: "Efficient Way to Invoke All Editors in Git Bash on Windows"
seoTitle: "Invoke all Editors in Git Bash on Windows"
seoDescription: "How to efficiently invoke all Editors in Git Bash on Windows"
datePublished: Fri Dec 30 2022 17:29:33 GMT+0000 (Coordinated Universal Time)
cuid: cllqr2gnc00x1fxnv67ka69h8
slug: efficient-way-to-invoke-all-editors-in-git-bash-on-windows
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/UT8LMo-wlyk/upload/4ce884faa44378a13a657bdc99eabd98.jpeg

---

Just kidding, it works on all OS as well. Just configure the correct directory upon setting this method.

Vim comes as a package when installing Git even though you choose another text editor during installation.

You invoke vim as `vi <filename>` in Git Bash CLI.

Short and sweet. What about the other editors?

1. For GNU nano: `nano <filename>`
    
2. For Notepad: `notepad <filename>`
    
3. For Notepad++: `start notepad++ <filename>`
    
4. For `<your favorite editor>`: `start <your favourite editor> <filename>`
    

Isn't very efficient it seems. You can however change the main editor via git config. But only one main editor is allowed at once.

Worry not, here's an efficient way around it to use all editors in Git Bash:

## Add Permanent Alias in Git Bash

Run Git Bash as administrator.

Open aliases.sh

```bash
$ cd /etc/profile.d
$ vi aliases.sh
```

Add alias in aliases.sh. For example, we add npp as an alias for Notepad++:

```bash
# --show-control-chars: help showing Korean or accented characters
alias ls='ls -F --color=auto --show-control-chars'
alias ll='ls -l'
alias npp='/c/Program\ Files/Notepad++/notepad++.exe'
```

p/s: Use `\` to escape spaces in the directory.

Add as many other editors as you like in the aliases.sh file. Just follow the format:

```bash
alias <YourAlias>='/YourProgramDirectory/YourEditor.exe'
```

Save the settings, close Git Bash and reopen it to activate the new configuration. Voila!

If it does not activate by chances in the future, source it and it will be activated again:

```bash
$ cd /etc/profile.d
$ source aliases.sh
```

As a bonus, this method also works to add any Linux commands as aliases too. For example, instead of `clear`, you can alias it as cls.

```plaintext
cls=`clear`
```

That's it folks, Happy days!

So what is your favorite editor? Comment down below.

Cheers!