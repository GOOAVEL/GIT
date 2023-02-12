# Git Bush
[**Instraction #1**](https://www.atlassian.com/ru/git/tutorials/git-bash)\
[**Instraction #2**](https://habr.com/ru/company/ruvds/blog/445270/)\
[**Instraction #3**](https://tproger.ru/translations/bash-cheatsheet/)
## Commands:
* `pwd` - show the way current file (_present working directory_)
* `ls` - show files in current folder (_list_)
    >**flag** | `-a` | - show all files
* `touch` - create a new file
    > example: `touch to-do.txt`
* `mkdir new_folder` - create a new folder
* `cd new_folder` - move to the folder (change directory)
* `echo "text"` > file_name` - write something inside the file
* `rm name_file` - delete the file
    >**flag** | `-f` | - удаляет файлы только для чтения в папке без запроса.\
**flag** | `-r` | - рекурсивно удаляет содержимое папки.\
**flag** | `-d` | - для удаления пустых директорий.\
**flag** | `-rf /` | - для принудительного удаления (даже если оно защищено от записи) всего содержимого в корневом каталоге и подпапках.\
**flag** | `-rf *` | - для принудительного удаления всего содержимого в текущем каталоге (каталог, в котором вы сейчас работаете) и подпапках.\
**flag** | `-rf` | - для принудительного удаления всего содержимого в текущей папке и подпапках.\
**flag** | `-i` | - для удаления файлов и папок, но перед удалением появится подсказка.
* `mv name_file other_file` - rename the file