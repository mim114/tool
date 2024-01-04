git config --global user.name "naem"
git config --global user.email "jfj@kdkd"
git config --global core.editor vim
git config --global init.defaultBranch main
git config -l -------------> просмотр конфигурационного файла.

git -----------------------> часто используемые команды
git -v --------------------> Версия git
git init ------------------> Инециализировать новый репозиторий.
git clone http:// newname -> скопировать существующий репозиторий.
git pull ------------------> скачать из github обновления
git push origin main ------> отправить в github
cat > .gitignore \n regx --> Какие файлы игнорировать
git add -------------------> добавить в отслеживаемые.
git commit -m "text" ------> фиксация репозитория.
git status -s -------------> текущее состояние репозитория.
git log -------------------> история фиксаций.
git show [hash] -----------> подробно о последней фиксации.
git diff hash1 hash2 ------> сравнить две фиксации.
git diff --staged ---------> Разница между фиксацием и добавлением
git branch name -----------> Создать новую ветку.
git branch -m name --------> Переименовать ветку.
git branch ----------------> Список веток.
git branch -f name name ---> Передвинуть ветку.
git checkout name ---------> Перейти в ветку name.
git checkout name^/~5 -----> Перейти к родительскому commit.
git checkout -b name ------> Создать и переключится на новую ветку.
git merge name ------------> Принять в текущюю ветку ветку name.
git rebase name -----------> Перенести текущюю ветку в ветку name.
git reset name^ -----------> Локальная перезапись ветки.
git revert name -----------> Глобальная перезапись ветки.

working directory
staging area
repository
