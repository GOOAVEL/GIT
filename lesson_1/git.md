GIT#1 - система контроля версий.
=====================================
Сохраняет файлы не целиком, а только **разницу** между файлами.\
Файлы не называть кириллицей и без пробелов.\
GIT следит за файлами по именам, при переменовании git set status - **deleted**

## Commands:
- `git config --global user.name «`*Ваше имя английскими буквами*`»`
- `git config --global user.email почта@example.com`
- `git config --list --show-origin` - show all settings
* `git status` - show status of the repository
* `git init` - инициализация репозитория
* `git add name_file` - add a new file to the tracking status \
`git add .` - all files\
Добавить файл под версионный контроль
* `git commit -m "massage"` - commit changes to the repository\
`| -m |` is **flag** to indicate *message*
    >use **flag** | `-am` | to skip stage `git add .` and massage *(works after first commit)*
* `git log` - журнал изменений (коммитов)
    > use **flag** | `--graph` | - show graphical information of branches
* `git checkout 35dfhpklfh56gf8j7d54h` - перейти к определенному изменению\
можно вести первые 4 срочки хеша коммита `| 35df |` - commit hash
* `git checkout main` - перейти на актуальное состояние изменений / ветку
* `git diff` - show difference between current and last commit files
### GitHub / Working with a remote repository (move to lesson_3)
- `git push` - added files the remote repository
- `git pull` - get files the remote repository

### additional commands:
- `git --version` - show version the GIT
- `clear` - clear the consol
- `git update-git-for-windows` - update GIT version\
can use - `git update`
- `git help` - help for all commands
>! exit the __VIM__ and save file - `esc` + `:wq`\
Esc + :x + Enter (сохранить и выйти)\
Esc + :qa + Enter (закрыть все открытые файлы)\
Esc + Shift ZZ (сохранить и выйти)\
Esc + Shift ZQ (выйти без сохранения)
-------------------------------------------------
## Dictionary:
1. **Dictionary** - словарь
2. **to commit** - совершать, фиксировать, поручать
3. **log** - журнал
4. **insertion** - вставка, введение, включение
5. **indicate** - указать
5. **difference** - разница, различие
5. **to allow** - позволять, допускать, разрешать,

> Status:\
    1. **untracked** - неотслеживаемый\
    2. **modified** - модифицированый
-----------------------------------
![status](photo/lifecycle.png)