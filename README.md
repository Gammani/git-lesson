1. git status
2. git add [files] - добавляет файлы в stage
3. git commit -m "comment"
4. git log / git log --oneline - показывает информацию о коммитах
5. git push [rep_link] [branch_name] 
6. git remote -v - ссылка на репозиторий
7. git branch - ссылка на ветку
8. git push origin master
9. git reset - удаляет из stage
10. git reset --hard - возвращает все изменения и очищает git status
11. git diff / git diff [files] - показывает изменения 

Ветки 
1. git branch [name] - создать ветку
2. git checkout [name] - переключиться на ветку
3. pull [rep_link] [branch_name]
4. git branch -d [branch_name] - удалить ветку

Слияние веток
1. git checkout master
2. git merge [name_branch_which_in_the_current]