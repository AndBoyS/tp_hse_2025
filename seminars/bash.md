**Базовые инструменты разработки ПО, ч.1**

Bash и основные команды.

**План семинара:**
- показываем bash
- как работает работа в терминале (нахождение в конкретной папке, возможность запускать файлы по относительному или абсолютному пути)
- базовые команды bash: touch, rm, cd, mkdir, rmdir, ls, cp, mv, cat, echo, grep, find
- возможность подавать результат одних команд другим на примере grep (`ls | grep x`)
- установка библиотек (`brew` в маке и `apt-install` в Ubuntu)
- удобный инструмент для документации: `tldr`
- работать будем с [данными](https://drive.google.com/file/d/1rg5EAKbwcLxqJxdddW1xoHV439W-nLQU/view?usp=sharing)
- `nano` - редактирование файлов
- `chmod +x script.bash` - позволит запустить скрипт
- пишем простой скрипт на bash: считаем количество файлов в директории
- пишем более сложный скрипт на bash: считаем количество .py файлов, с и без рекурсии; считаем количество появления слова board во всех файлах, только в нижнем регистре
- как работают ошибки в bash и команда `set -e`
- переменные, экранирование (`output=$(ls)`, `echo "My output: $output"`)
- PATH, .bashrc, alias, export

> [bash commands cheatsheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet)

> [bash script cheatsheet](https://devhints.io/bash)

Сопровождающие лекции: [Этапы развития проекта](../lectures/project_evolution.md) и [Базовые понятия о языках программирования](../lectures/language_types.md)
