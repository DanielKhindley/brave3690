#Подсказка по GIT

Создание репозитория:
```sh
git init
```
Добавить файл к текущему коммиту:
```sh
git add
```
Добавление коммита:
```sh
git commit -m "message"
```
Истории изменений:
```sh
git log
```
Просмотр краткой истории изменения файлов:
```sh
git log --oneline
```
Команда для переключения по веткам:
```sh
git checkout <branch_name>
```
Отображение всех веток:
```sh
git branch
```
Создание новой ветки:
```sh
git branch branch_name
```
Команда для слияния веток:
```sh
git merge branch_name
```
Команда для удаления слитой ветки:
```sh
git branch -d branch_name
```
Команда для удаления неслитой ветки:
```sh
git branch -D branch_name
```
Команда для одновременного добавления и коммита:
```sh
git commit -am "commit_text"
```