git config --global user.name "naem"
git config --global user.email "jfj@kdkd"
git config --global core.editor vim
git config --global init.defaultBranch main
git config --global push.default simple -> реакция на ошибку
git config -l -------------> просмотр конфигурационного файла.

git -----------------------> часто используемые команды
git -v --------------------> версия git
git init ------------------> инециализировать новый репозиторий.
git clone http:// newname -> скопировать существующий репозиторий.
git pull ------------------> скачать из github обновления
git push ------------------> отправить в github
cat > .gitignore \n regx --> Какие файлы игнорировать
git add -------------------> добавить в отслеживаемые.
git restore name ----------> отменить изменения в рабочем каталоге
git commit ----------------> фиксация репозитория.
git rm name ---------------> удалить из индекса
git vm name name ----------> переименовать в индексе
git status ----------------> текущее состояние репозитория.
git log -------------------> история фиксаций.
git diff ------------------> разница между индексом и раб. каталогом
git show ------------------> подробно о последней фиксации.
git branch ----------------> Список веток.
git switch name -----------> перейти на веку name
git checkout name ---------> Перейти к коммит name.
git merge name ------------> Принять в текущюю ветку ветку name.
git rebase name -----------> Перенести текущюю ветку в ветку name.
git reset name ------------> перенос ветки(ссылки) на другой комит --hard
git revert name -----------> перевернуть значение комита и создать новый
git cat-file -p <hash> ----> просмотр содержимого git-object
git remote -v -------------> список связанных удалённых репозиториев

HEAD~3 --------------------> шаблон для третего комита от последнего
HEAD^2 --------------------> шаблон для родителя №2
