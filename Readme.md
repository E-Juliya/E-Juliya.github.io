# команды MARKDOWN

## посмотреть версию GIT

```git_version```
- где _ это пробел

## начать работу в выбронной папке

```git init```

## посмотреть что думает о нашей папке git

```git status```

## команда которая делает файл отслеживаемым

```git add```
- так же надо указать название самого файла (можно нажать первые буквы и TAB - добавит остальное самостоятельно)

## после всех изменений надо их зафиксировать

```git commit``` 
- обязательно надо добавить комментарий -m  и в двойных ковычках "указать комментарий, что добавили"  
двойные ковычки -m "комментарий" -- **обязательно**!!!

## чтобы посмотреть все изменения которые мы сделали

```git log```
- так же команда ```git log --oneline``` покажет все изменения списком

## чтобы перейти к нужному нам сохранению - фиксациии (commit)

```git chekout```
- при добавлениее в git chekout - достаточно вставить 4 первых символа с ссылки которую нас приидоставит в журнале GIT


## чтобы посмотреть разницу между состояниями файлов

```git diff```
- diff от слова difference - разница

так же GIT может попросить добавить ваше имя и почту
вам потребуется команда:

```git config --global user.email```
- пишем актуальную почту и enter

```git config --global user.naim```
- пишем актуальное имя

```git clone ссылка```
- копирует репозиторий который мы скопировали в  GitHab

```cd имя репозитория в котором работаем```
- меняем репозиторий для работы

```git pull```
- позволяет скачать с GitHub репозиторий (могут быть конфликты обратить внимание)

```git push```
- отправляем все что сделали на GitHab в папку в которой делали изменения (должен быть авторизован)

# Что поможет для печати в GIT

*курсив*

**полужирный**

списки ненумерованные
* список 1
* список 2
- где ставим *_ команда звездочка и пробел

спивски номерованные

1. список 1
2. список 2
- где ставим 1. цыфру и точку

Важно знать!!!

- что при печати если при в вода текста нажать один раз enter, то текст при выводе не экран будет продолжаться в той же строке

 - если после печати текста нажимаем 2 раза enter, то при выводе на экран, текст переходит на другой абзац


Паршин Дмитрий.
