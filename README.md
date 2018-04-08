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
```git commit```

## Push feature branch ke remote

```git push -u origin new-feature```

# CONTOH KASUS

### JONO membuat fitur baru

```git checkout -b jono-feature master```

### Pada Branch ini Jono Meng- edit, stages dan commit

```git status```
```git add <some-file>```
```git commit```

 ### Jono menge push branch barunya

```git push -u origin jono-feature```

 ### Jono telah menyelesaikan fitur barunya

```git push```


