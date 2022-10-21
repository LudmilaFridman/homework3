# Инструкция для работы с Git и удалёнными репозиториями
![Logo](markdown.png)

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создания репозитория необходимо выполнить команду *git init*  в папке с репозиторием, и у Вас создатся репозиторий (появится скрытая папка .git).

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add <имя файла>*.

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория, используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите, были ли измения в файлах или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение), необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ***, и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*.

## Журнал изменений
Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием.

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом: в папке с репозиторием: *git branch <название новой ветки>*.

## Слияние веток

Для того, чтобы добавить ветку в текущую ветку, используется команда *git merge <name branch>*.

## Удаление веток
Для удаления ветки - ввести команду "git branch -d 'name branch'".

## Working with remote repositories
*git remote*
To connect a local repository with a remote repository. A remote repository can have a name set to avoid having to remember the URL of the repository.

*git clone*
To create a local working copy of an existing remote repository, use git clone to copy and download the repository to a computer. Cloning is the equivalent of git init when working with a remote repository. Git will create a directory locally with all files and repository history.

*git pull*
To get the latest version of a repository run git pull. This pulls the changes from the remote repository to the local computer.

*git push*
Sends local commits to the remote repository. git push requires two parameters: the remote repository and the branch that the push is for.
