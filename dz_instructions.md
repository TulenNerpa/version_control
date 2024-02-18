# Подсказки по Git
## Команды инициализации
### Назначение имени
```sh 
config --global user.name "Name Surname"
config --local user.name "Name Surname"
```
### Назначение почты
```sh
config --global user.email "Почта"
config --local user.email "Почта"
```
## Работа с директорией
### Создание директории
```sh
mkdir
```
### Показать текущую директорию
```sh
pwd
```
### Показание файлов в директории
```sh
ls
```
### Удаление изменений
```sh
git restore
```
## Создание репозитория:
```sh
git init
```
### Добавление изменений
```sh
gitt add
```
### Проверка репозитория
```sh
git status
```
## Создание файла
```sh
touch name_file
```
## Смена директории
### Смена дирекции
```sh
cd
```
### Смена папки/диска
```sh
cd/d/
```
### Вернуться на папку назад
```sh
cd..
```
### перейти в новый файл
```sh
cd file
```
## Добавление коммита
```sh
git commit -m "Message"
```
## Проверка логов
```sh
git log
git log --oneline
```
## Удаление хеша
```sh
git checkout 
```
## Возвращение хеша
```sh
git checkout master
```

Команда смены директории
```sh
cd c:\folder_name
```


Листинг текущей директории
```sh
dir
```

Удаление файла в Windows
```sh
del <filename>
```
## Изменение хеша
### Временное удаление коммита
```sh
checkout хеш
```
### Возвращение к последним изменениям
```sh
git checkout master
```
### Изменение в сохраненном, но не коммиченном файле
```sh
git diff
```
### Разница между хешами
```sh
git dif хеш хеш
```
### Отображение всех веток
```sh
git branch
```

### Перемещение по веткам
```sh
git checkout <branch_name>
```