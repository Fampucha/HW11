# Домашнее задание №11
## Project for Git


### Создайте новый проект и подключите в него Git через терминал.

:white_check_mark: Создан проект "HW11"    
:white_check_mark: С помощью команды в терминале **git init (bold)** подключен Git к проекту
____

### Укажите, что в вашем проекте будут игнорироваться все файлы с расширением .sass и папки: bin, admin, config.

:white_check_mark: В файле **.gitignore (bold)** добавлены строки:
+ *.sass
+ bin/
+ admin/
+ config/
____

### Выполните следующее:

##### + добавьте все файлы в локальное хранилище;
:white_check_mark: Добавлено все файлы в статус ожидания с помощью команды в терминале **git add . (bold)**    
:black_square_button: Проверено статусы файлов с помощью команды в терминале **git status (bold)** (не обязательно)    
:white_check_mark: Добавлено все выбранные файлы в локальное хранилище с помощью команды в терминале **git commit -m "first version of project" (bold)**

##### + создайте новую ветку и перейдите в неё;
:white_check_mark: Создано новую ветку "myblog" с помощью команды в терминале **git branch myblog (bold)**    
:white_check_mark: Переход на новую ветку "myblog" с помощью команды в терминале **git checkout myblog (bold)**

##### + в новой ветке создайте папку blog с файлами: index.js, index.html;
:white_check_mark: Создано в корневой папке новую папку с названием "blog"    
:white_check_mark: В папке "blog" создано файлы index.js и index.html    
:white_check_mark: Добавлено все новые файлы в статус ожидания с помощью команды в терминале **git add . (bold)**    
:white_check_mark: Добавлено все выбранные файлы в локальное хранилище с помощью команды в терминале **git commit -m "add blog" (bold)**

##### + загрузите на удаленный репозиторий лишь основную ветку вашего проекта.
:white_check_mark: Выполнено переход на основную ветку проекта с помощью команды в терминале **git checkout master (bold)**    
:white_check_mark: На сайте [GitHub](https://github.com/) создано новый удаленный репозиторий под названием "HW11"    
:white_check_mark: С помощью команды в терминале **git remote add origin https://github.com/Fampucha/HW11.git (bold)**, проект подключен к удаленному репозиторию    
:white_check_mark: Проект загружен на удаленный репозиторий с помощью команды в терминале **git push -u origin master (bold)** 
____

### Для отправки на проверку создайте файл, в котором пропишите все команды что необходимо было бы сделать для выполнения действий задания.
:white_check_mark: Создан файл **README.md (bold)**, в котором подробно расписаны все действия для выполнения задания.
