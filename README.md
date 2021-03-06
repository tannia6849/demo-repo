### Команды системы контроля версий Git
1. **git add .** - добавить в индекс все новые, изменённые, удалённые файлы из текущей директории и её поддиректорий
2. **git add text.txt** - добавить в индекс указанный файл (был изменён, был удалён или это новый файл)
3. **git reset** - убрать из индекса все добавленные в него изменения (в рабочей директории все изменения сохранятся), антипод git add
4. **git reset readme.txt** - убрать из индекса изменения указанного файла (в рабочей директории изменения сохранятся)
5. **git checkout text.txt** - отменить изменения в файле, вернуть состояние файла, имеющееся в индексе
6. **git reset --hard** - отменить изменения; вернуть то, что в коммите, на который указывает HEAD (незакомиченные изменения удалены из индекса и из рабочей директории, неотслеживаемые файлы останутся на месте)
7. **git clean -df** - удалить неотслеживаемые файлы и директории
8. **git commit -m "Name of commit"** - зафиксировать в коммите проиндексированные изменения (закоммитить), добавить сообщение
9. **git rm text.txt** - удалить отслеживаемый неизменённый файл и проиндексировать это изменение
10. **git log** - показать коммиты в указанной ветке
11. **git branch** - показать список веток
12. **git status** - показать состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.)
13. **git diff** - сравнить рабочую директорию и индекс (неотслеживаемые файлы ИГНОРИРУЮТСЯ)
14. **git diff HEAD** - сравнить рабочую директорию и коммит, на который указывает HEAD (неотслеживаемые файлы ИГНОРИРУЮТСЯ)
15. **git diff --staged** - сравнить индекс и коммит с HEAD
