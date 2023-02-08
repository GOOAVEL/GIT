GIT#3 - система контроля версий.
=====================================
|**README.MD**| usually called using capslock\
**FORK** в отличие от **CLONE** позволяет делать разработку с чужим репо.\
При изменении чужого репозитория лучше создать отдельную ветку
>`git fetch` загружает удаленное содержимое, но не изменяет состояние local repo, в то время как git pull загружает удаленное содержимое и сразу пытается изменить состояние local repo.
## Commands:
### GitHub / Working with a remote repository
- `git push` - added files the remote repository
- `git pull` - get files the remote repository and make merge with local repo
    >**flag** `| --all |` - pull all branches remote repo
- `git fetch` - get files the remote repository without changes for local repo
- `git clone https://github.com/` - clone the remote repository
    >use `git clone https://github.com/ newFolder` copy to a specific folder
-------------------------------------------------
### Algorithm of working with foreign _(чужой)_ repository 
1. touch on **fork** 
2. clone the **forked** repository
3. create a new branch for working (зависит от проекта)
4. push the our **forked** repository
5. run **pull request** and wait... :D
---
## Dictionary:
1. **origin** - происхождение, начало, источник
2. **request** - просьба, запрос
3. **usually** - обычно, обыкновенно
4. **specific** - конкретный, определенный