# LR6
Лабораторная работа №6


#### Настройка конфига командой git --global. Введены ФИО и email.

![](pictures/1.png)

![](pictures/2.png)

#### Клонирование удаленного репозитория на компьютер.

![](pictures/3.png)

#### Добавлен файл через интерфейс GitHub, подтянуты изменения в локальный репозиторий.

![](pictures/4.png)

![](pictures/5.png)

#### Переход на ветку branch1. Вывод ее истории.

![](pictures/6.png)

#### История ветки master.

![](pictures/7.png)

#### Список веток.

![](pictures/8.png)

#### Слияние веток branch1 и master. Разрешение конфликта с помощью mergetool.

![](pictures/9.png) 

#### Переход на редактор Vim, команда :diffoff.

![](pictures/11.png)

#### Результат работы в Vim. Лишнее удалено при помощи --INSERT--.

![](pictures/12.png)

#### Итоговый результат сохранен и добавлен commit.

![](pictures/13.png)

![](pictures/14.png)

#### Удалена побочная ветка branch1.

![](pictures/15.png)

#### Добавление новых файлов. Фиксация изменений в коммите.

![](pictures/16.png)

#### Откат коммитов.

![](pictures/17.png)

![](pictures/18.png)

## Создание отчета в README.md
#### Создание ветки для отчета.

![](pictures/19.png)

#### Для написания отчета использовался блокнот.

![](pictures/21.png)

#### История операций в форматированном виде (сокращённый хэш + дата + имя автора + комментарий).

![](pictures/20.png)

## Лог команд:
```
$ cd d:/'дела шаражные'/'основы программирования'/'3 семестр'/lab6
$ git clone https://github.com/Lilobeth/LR6.git
$ cd LR6
$ git pull
$ git checkout branch1
$ git log
$ git checkout master
$ git branch -l
$ git merge branch1
$ git mergetool
$ git status
$ git add .
$ git rm -f mergefile.txt.orig
$ git commit -m "merged"
$ git branch -d branch1
$ git commit -m "file 1.txt was added"
$ git commit -m "file clown.txt was added"
$ git reset --hard HEAD~1
$ git checkout -b _otchet_
$ git push origin --delete branch1
```
####