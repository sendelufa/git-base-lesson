# Базовые команды Git

## Конфигурация

После установки git необходимо обязательно указать автор коммитов:

- `git config --global user.name "SkStudent"` - установить имя автора новых коммитов.
- `git config --global user.email my@email.ru` - установить email автора новых коммитов.

- `git config user.name` - прочитать имя автора коммитов
- `git config user.email` - прочитать email автора коммитов

## Репозиторий

- `git init` - создание пустого репозитория в текущей директории.
- `git clone <url>` - скачать репозиторий, будет создана директория с названием удаленного репозитория.
- `git status` - вывести информацию о состоянии локального репозитория.
- `git log` - вывести историю коммитов, если история длинная можно стрелками перемещаться, для выхода нажмите Q.
- `git log --oneline --graph` - более красивое отображение веток и коммитов с помощью псевдографики и
с кратким выводом информации о коммите.

## Коммиты

- `git add <path>/<filename>` - добавить файл в Staged, подготовить к коммиту.
- `git add .` - добавить все доступные файлы в Staged.
- `git commit -m "first commit"` - создать коммит из добавленного в Staged с комментарием "first commit"
- `git commit` - создать коммит из добавленного в Staged, для написания откроется стандартный редактор.
Удобнее использовать параметр -m и текст комментария.
- `git pull` - прочитать и получить новые коммиты из удаленного репозитория.
- `git push` - отправить в удаленный репозиторий новый коммиты.

