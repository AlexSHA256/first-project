# Основы Git и GitHub
---
## Установка Git 
```bash
$ brew install git 
$ git version 
```

### Работа с файлом .gitconfig
```bash
$ git config --global user.name "Sasha"
$ git config --global user.email user@yandex.ru
$ cat ~/.gitconfig или $ git config --list
```


## Инициализируем репозиторий 
** Создание репозитория **
```bash
$ mkdir first-project
$ cd first-project 
$ git init
```

** Как "Разгитить" папку **
```bash
$ cd first-project
$ rm -rf .git 
```
По сути, мы просто удаляем скрытую папку, содержащую системную информацию 

** Проверим состояние репозитория **
```bash
$ git status
```

