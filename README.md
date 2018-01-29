# TeleBinarGit
Git Config CMD

### Latihan 1:
```shell
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[0]─[412]
╰─[:)] % git config —global user.name "septiyadii"
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[0]─[413]
╰─[:)] % git config —global user.mail septiyadi@mhs.pelitabangsa.ac.id
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[0]─[414]
╰─[:)] % git init
Initialized empty Git repository in /home/septiyadi/Downloads/ProjectGitLab/GitConfig/.git/
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[0]─[415]
╰─[:)] % git add *
zsh: no matches found: *
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[1]─[416]
╰─[:(] % git commit -m "versi 1.0.0"
On branch master

Initial commit

nothing to commit
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[1]─[417]
╰─[:(] % git remote add origin https://github.com/septiyadii/TeleBinarGit.git
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[0]─[418]
╰─[:)] % git pull origin master
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/septiyadii/TeleBinarGit
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master
╭─[~/Downloads/ProjectGitLab/GitConfig]─[septiyadi@resolver]─[0]─[419]
╰─[:)] % git push origin master
Username for 'https://github.com': septiyadii
Password for 'https://septiyadii@github.com': 
Everything up-to-date
```
