## Привет!

Тефтелька - замечательный котик)

Совершенно с этим согласен

## Подключение у удалёному репозиторию

1. Создали аккаунт на Github.com
2. Создать локальный репозиторий
3. Подружить локальный и удалённый репозитории. Github при создании нового репозитория подскает как это сделать
4. Отправить (push) ваш локальный репозиторий в удалённый (на Github), при этом вам, возможно, нужно будет авторизоваться на удалённом репозитории.
5. Провести зменения с "другого компа"
6. Выкачать (pull) актуальное состояние из удалённого репозитория


## Работа с чужим репозиторием

1. Делаем (fork) нужного нам репозитория
2. Делаем git clone для нашей версии этого репозитория
3. Мы создаём ветку с предлагаемыми изменениями
4. Производим все изменения только в этой ветке
5. Отправляем эти изменения на свой аккаунт команда push
6. В окне на Github появляется возможность отправить pull request с нашими изменениями

## Доп. команды git

Команды в Git Bash консоли
clear — Очистить консоль

Навигация
pwd — Показать текущий каталог

ls - Показать файлы в данной папке, кроме скрытых

ls -f — Показать файлы в данной папке, включая и скрытые

cd c:/ — Перейти в конкретный каталог

cd - — Вернуться назад

cd .. — Выйти на 1 уровень вверх

cd ../.. — Выйти на 2 уровня вверх


Создание каталогов

mkdir — Создать папку

cd !$ — Перейти в только что созданную папку

mkdir -p {app1,app2} — Создать сразу несколько папок

mkdir -p app/{css,js} — Создать сразу несколько вложенных папок


Создание файлов

touch index.html — Создать файл index.html

touch app/{css/main.css,js/main.js,index.html} — Создать сразу несколько файлов, никаких лишних пробелов быть не должно

Удаление файлов

touch — позволяет создавать файлы

rm test — Удалить пустую папку test

rm -r test — Удалить папку test с файлами внутри неё


Перемещение файлов
mv app1/*.* app2 — Переместить все файлы из папки app1 в папку app2
