# Git Feature Branch Workflow

## Mulai dengan Branch Master

```git checkout master```

```git fetch origin ```

```git reset --hard origin/master```

## Buat Branch Baru

```git checkout -b new-feature```

## _Update, Add, Commit,_ dan _Push Changes_

```git status```

```git add <some-file>```

```git commit -m "comment"```

## Push feature branch ke remote

```git push -u origin new-feature```

## Configurasikan username dan email

```git config --global user.user "user"```

```git config --global user.email "email"```

# CONTOH KASUS

### JONO membuat fitur baru

```git checkout -b jono-feature```

### Pada Branch ini Jono Meng- edit, stages dan commit

```git status```

```git add <some-file>```

```git commit -m "comment"```

### Jono menghubungkan file jarak jauh

```git remote add origin "server_file_git"```

 ### Jono menge push branch barunya

```git push -u origin jono-feature```

 ### Jono telah menyelesaikan fitur barunya

```git push```


