# Инструкция по работе с Git

## Что такое Git?
Git - одна из реализаций распределенных систем контроля версий, позволяющая организовать версионность, как локально, так и на удаленном сервере. Самая популярная платформа, реализующая *Git*, - [GitHub](https://github/com)


## Подготовка репозитория
Для создания в папке репозитория необходимо открыть эту папку в терминале и написать команду *git init*, после чего в этой папке создаться скрытая папка *.git*, и таким образом папка станет репозиторием

## Создание коммитов

### Отправка коммита

### Создание фиксации
Для создания фиксации оиспользуется команда *git commit*. Для этого в терминале с папкой-репозиторием необходимо написать команду *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**.


## Создание "сохранения"

### Добавление файлов к "сохранению"
Для того, чтобы добавить файл к "сохранению", нкобходимо использовать команду *git add*. В терминале с открытой папкой-репозиторием необходимо написать *git add <название файла>*, и этот файл добавится к "сохранению"

### Просмотр состояния репозитория
Для просмотра состояния репозитория используется команда *git status*. В терминале с открытой папкой репозитория необходимо написать команду *git status*. В результате можно увидеть следующие выводы:
1. On branch *** noting to commit - нет активных изменений
2. Untracked file - файлы, не отслеживаемые системой контроля версий
...


## Перемещение между "сохранениями"

## Журнал изменений
Для просмотра историй изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием, необходимо написать *git log*, и Вы увидите список всех коммитов в этой ветке с описанием: имени, электронной почты, сообщением к коммиту и номер коммита.

## Перемещение между "сохранениями"
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout* <номер коммита>*. Номер коммита берется из журнала изменения ветки.
## Ветки в git

## Слияние веток и решение конфликтов

## Удаление веток