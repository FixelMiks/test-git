Основы Git и GitHub
1. git status - отображает изменения в локальном репозитории
2. git add [files] - добавляет файлы в stage
3. git commit -m "comment" - добавление коммита
4. git remote -v - отображение ссылки на репозиторий
5. git push [rep_link] [branch_name] - отправить наши изменения на удалённый репозиторий
6. git log / git log --oneline - вывод информации о наших коммитах
7. git pull [rep_link] [branch_name] - загружает последний коммит указанной ветки на локальный репозиторий
8. git clone [rep_link] - клонирование указанного репозитория

Удаление / откат локальных изменений
1. git reset [files] - удаляет файл из состояния stage
2. git reset --hard - удаляет все изменения, которые мы проделали до последнего коммита
3. git diff [files] / git diff - показывает изменения в определённом файле / во всём проекте

Работа с ветками
1. git branch - показывает все ветки в репозитории
2. git branch [branch_name] - создаёт новую ветку
3. git checkout [branch_name] - переключается на указанную ветку
4. git branch -d [branch_name] - удаление указанной ветки (локально)

Слияние веток
1. git checkout [main_branch_name] - переключиться на главную ветку, в которую мы хотим внести изменения из другой ветки
2. git merge [branch_name] - добавляет изменения из указанной ветки в текущую (где мы находимся)
3. git push [rep_link] [branch_name] - добавление изменений на GitHub
4. хорошей практикой считается удаление ветки после мёрджа

Доп. информация
1. .gitignore - файл, в котором можно перечислить папки/файлы, которые будут игнорироваться git'ом, такие как build, node_modules, .env и т.п.
