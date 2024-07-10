Система контроля версий (англ. Version Control System, или коротко VCS).

SCM (от англ. Source Control Management — «система управления исходным кодом»).

Git - Global Information Tracker.

Командная строка (англ. Command-line Interface, или CLI).

Графический интерфейс (англ. Graphical User Interface, или GUI).

- pwd (от англ. print working directory — «показать рабочую папку»).
- ls (от англ. list directory contents — «отобразить содержимое директории»).
- cd (от англ. change directory — «сменить директорию») и символ ~ — обозначение домашней директории.
- cd .. – подняться на уровень выше.
- ls -a – показать скрытые файлы и папки.
- touch my-new-file.txt # создали файл my-new-file.txt
- mkdir new-dir # создали директорию new-dir
Можно создать целую структуру директорий одной командой с помощью флага -p.
- mkdir -p dir1/dir-inside/dir-deeper-inside # создали папку dir-deeper-inside в папке dir-inside, которая находится в папке dir1
- mkdir ~/my-git-projects # создаст папку my-git-projects внутри домашней директории.
- touch ../../file.txt # создаст файл file.txt на две папки выше по иерархии
- cp что_копируем куда_копируем/
- cp что_копируем что_копируем что_копируем куда_копируем/
- mv что_перемещаем куда_перемещаем/
- cat что_читать # прочитать файл
- rm имя_файла # удалить файл
- rmdir имя_директории # удалить директорию
- rm -r images # удалили папку images со всем её содержимым из текущей директории
- git config --global user.name "User Namovich" # установить имя
- git config --global user.email username@yandex.ru # установить почту
- cat ~/.gitconfig # прочитать файл конфига
- git config –list # альтернативная команда чтения конфига
- git status # статус репозитория
