# Шпаргалка по GIT

## Выделение текста

1. Инициировать git репозиторий:

   ```
   git init
   ```
2. Как задать имя пользователя и адрес электронной почты:

   ```
   git config --global user.name "Tara Routray"

   git config --global user.email "dev@tararoutray.com"
   ```
3. Добавление отдельных файлов или всех файлов в область подготовленных файлов:

   ```
   git add tets.txt

   git add. 
   ```
4. Проверка статуса репозитория:

   ```
   git status
   ```
5. Внесение изменений однострочным сообщением или через редактор:

   ```
   git commit -m "text"
   ```
6. Просмотр истории коммитов с изменениями:

   ```
   git log -p
   ```
7. Внесение изменений однострочным сообщением или через редактор:

   ```
   git diff test.txt
   ```
8. Переименование файлов:

   ```
    git mv dir1/somefile.js dir2
   ```
9. Отмена подготовленных и неподготовленных изменений:

   ```
   git checkout somefile.js
   ```
10. Изменение последнего коммита:

    ```
    git commit --amend -m "Updated message for the previous commit"
    ```
11. Откат последнего коммита:

    ```
    git rever HEAD
    ```
12. Откат заданного коммита:

    ```
    git rever test
    ```
13. Создание новой ветки и переход в неё (параметр -b для автоматического перехода в новую ветку):

    ```
    git branch new_brance_name
    ```
14. Просмотр списка веток:

    ```
    git brance

    gitbrance -a
    ```
15. Удаление ветки:

    ```
    git brance -d existing_branch_name
    ```
16. Удаление ветки в удаленном репозитории:

    ```
    git push origin --delete existing_branch_name
    ```
17. Слияние двух веток:

    ```
    git merge existing_branch_name
    ```
18. Добавление удаленного репозитория:

    ```
    git remote add awesomeapp https://github.com/someurl
    ```
19. Отправка изменение в удаленный репозиторий:

    ```
    git push origin master
    ```
20. Получение изменения из удаленного репозитория:

    ```
    git pull
    ```
21. Отправка новой ветки в удаленный репозиторий:

    ```
    git push -u origin new_branche
    ```
22. Удаление удаленной ветки:

    ```
    git push --delete origin existing_branch
    ```
