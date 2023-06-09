# Инструкция для работы с markdown

**Git** — это набор консольных утилит, которые отслеживают и фиксируют изменения в файлах (чаще всего речь идет об исходном коде программ, но вы можете использовать его для любых файлов на ваш вкус). Изначально Git был создан Линусом Торвальдсом при разработке ядра Linux. Однако инструмент так понравился разработчикам, что в последствии, он получил широкое распространение и его стали использовать в других проектах. С его помощью вы можете сравнивать, анализировать, редактировать, сливать изменения и возвращаться назад к последнему сохранению. Этот процесс называется контролем версий.

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания. Например, *вот так* или _вот так_.

Чтобы обрамить текст полужирным необходимо обрамить его двойными звездочками (**) двойным знаком нижнего подчеркивания. 
Например, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того чтобы мы могли совмещать оба способа.
Например, _текст может быть выделен курсивом и при этом быть **полужирным**_

## Работа с изображениями

Чтобы вставить изображение в текст достаточно написать следующее:
![привет, это медали](%D0%BC%D0%B5%D0%B4%D0%B0%D0%BB%D0%B8.jpg)

## Списки
Чтобы добавить ненумерование списки необходимо пункты выделить (*) или (+). Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки необходимо просто пронумеровать. Напрмер, вот так:
1. Первый пункт
2. Второй пункт

## Работа с удаленными репозиториями

Для работы с удаленными репозиториями необходимо выполнить несколько действий, а именно:
 1. Создать аккаунт на GitHub.com.
 2. Создать локальный репозиторий.
 3. "Подружить" ваш локальный и удаленный репозитории. Github при создании нового репозитория подскажет как это сделать.
 4. Отправить (push) ваш локальный репозиторий в удаленный (на Github), при этом вам, возможно, нужно будет авторизоваться на удаленном репозитории.
 5. Провести изменения "с другого компьютера".
 6. Выкачать (pull) актуальное состояние из удаленного репозитория.

 ## Команды

 * git clone - эта команда позволяет склонировать внешний репозиторий на ваш ПК.
 
 * git pull - эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией.

 * git push - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий.

 ## Работа с каким-либо закрытым проектом на Github

 1. Делаем fork интересующего нас репозитория.
 2. Мы делаем git clone для нашей версии этого репозитория.
 3. Мы создаем отдельную ветку с предлагаемыми изменениями.
 4. Производим все изменения только в этой ветке.
 5. Отправляем эти изменения на свой аккаунт (push).
 6. В окне на Github появляется возможность отправить pull request.