# Инструкция для работы с Git и удалёнными репозиториями
## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)
## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*.

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть _**ДОБАВЛЕНЫ**_ и сообщение к коммиту писать _**ОБЯЗАТЕЛЬНО**_.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*.

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием.

## Работа с изображениями

Чтобы вставить изображение в текст необходимо сделать следующее:

### Картинки
![Картинка](GitIcon.png)

### Gif-Изображения
![Gifka](Gitgif.gif)

### Картинки через ссылки
![Picture](https://www.freecodecamp.org/news/content/images/2022/07/git-github.png)

## Добавление ссылок
Для добавления ссылок, используйте следующую форму:
"*Текст объясняющий куда ведёт ссылка [clickbait](ссылка.)* (без точки)

Выглядит это так:

В качестве основы данной инструкции был использован следующий документ [https://github.com/oleggolen/Seminar-13-12-2021#инструкция-для-работы-с-git-и-удалёнными-репозиториями](https://github.com/oleggolen/Seminar-13-12-2021#инструкция-для-работы-с-git-и-удалёнными-репозиториями)

## Как оформлять цитаты

Для оформления блока цитаты необходимо использовать символ **>** в начале текста, без пробела.

>Это блок цитирования. Обычно он отображается с отступом и имеет другой цвет фона.

## Как оформлять таблицы 

Использование вертикальных линий и строк является самым простым способом создания таблиц в Markdown. Чтобы создать стандартную таблицу с заголовком, вставьте пунктирную линию после первой строки.

|This is   |a simple   |table header|
|----------|-----------|------------|
|table     |data       |here        |
|it doesn't|actually   |have to line up nicely!|

Можно выровнять столбцы с помощью двоеточий:

| Fun                  | With                 | Tables          |
| :------------------- | -------------------: |:---------------:|
| left-aligned column  | right-aligned column | centered column |
| $100                 | $100                 | $100            |
| $10                  | $10                  | $10             |
| $1                   | $1                   | $1              |

## Комментарии

Документация поддерживает комментарии HTML, если необходимо закомментировать разделы статьи
< !--- Here's my comment --- >

<!--- Here's my comment --->

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками *. Например, *вот так*.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**). Например, **вот так**

 Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки 
Чтобы добавить нумерованные списки, необходимо пункты выделить звездочкой (*) или знаком +. Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, можно пункты просто пронумеровать, вот так:
1. Первый пункт.
2. Второй пункт.

## Ветки в Git
### Создание ветки
Для создания ветки используй команду *git branch*. В терминале необходимо ввести следующее: *git branch <название новой ветки>*

### Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*

### Удаление веток
Для удаления ветки ввести команду *"git branch -d 'name branch'"*

# Заключение
Не останавливайтесь на достигнутом! Здесь указаны лишь некоторые основные возможности разметки Markdown. Более подробную информацию можно найти тут: [https://learn.microsoft.com/ru-ru/contribute/markdown-reference](https://learn.microsoft.com/ru-ru/contribute/markdown-reference)