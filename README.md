Постапокалиптический скроллер
============================

### [Demo (Firefox, Opera or Internet Explorer.)](http://kell18.github.io/some-projects/PostapocalipticScroller.html)

###TODO

#####По графике:
1. __Доделать мертвяка №1 (подумать над анимацией смерти, улучшить ходьбу и уменьшить BB)__

> **Сделано**
+ Сделать один качественный спрайт зомбака и отдельно картинки его конечностей 
+ Задизайнить первый уровень
+ Найти звуки для игры

#####По механике:
1. Доделать UI
2. Заменить инстанциирование пулами объектов (todo в коде)
3. Переделать выстрелы
	
> **Сделано**
+ Определить силу и направление столкновения 
+ Сделать разлёт частей
+ Добавить машине способность вращаться в воздухе
+ Сделать звуки двигателя и окружения
+ Сдлеать пушку
+ Ускорить машину
+ Доделать распространение частиц из под колёс

	
<br />

###Тематика игры
Решили сделать нечто похожее на [Earn to Die](https://play.google.com/store/apps/details?id=com.notdoppler.earntodie) или [Zombie Road Trip](https://play.google.com/store/apps/details?id=com.noodlecake.zombieroadtrip)

<br />


###Работа с Unity
+ [Unity2D](https://unity3d.com/ru/learn/tutorials/modules/beginner/2d/2d-overview)
+ [Unity3D и 3D Max](http://www.youtube.com/user/4GameFree)

<br />

###3D Модели
+ [Как можно просто наделать моделек зданий](http://www.youtube.com/watch?v=A8e1zHEgdI8)

<br />


###Работа с репой
#####Получение последней версии с github
1. Получаем изменения из удалённой репы: `git fetch origin` 
2. Применяем эти изменения к своей репе: `git pull`
3. Если при `git pull` были конфликты (в консоли будут строки с пометкой `CONFLICT in: имя файла`) то нужно разрешить конфликты: либо с помощью доп утилит, например kdiff3 (подробности по установке в google) коммандой `git mergetool`; либо вручную: зайти в них, найти строки со следующими символами: `<<<<< HEAD`, `=====`, `>>>>>`. Всё что после `<<<<< HEAD` и до `=====` это из удалённой репы, а всё что после `=====` и до `>>>>>` это ваши изменения. Нужно удалить эти закорючки (`<<<<< HEAD` и пр.) и оставить только нужные строки. *Только подумайте что удалять - не затрите изменения других людей (возможно оставить два варианта)*. И после ввести команду `git merge origin`

#####Коммит локальных изменений на github
1. Добавляем (индексируем) файлы которые мы изменяли: `git add .`
2. Коммитим изменения локально: `git commit -m "Сообщение коммита"`
*Сообщение коммита заменить на сообщение о том, что закомитили (кратко и понятно)*
3. [Получаем последнюю версию с github ](https://github.com/bk0606/PostapocalypticScroller#%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D1%81%D0%BB%D0%B5%D0%B4%D0%BD%D0%B5%D0%B9-%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D0%B8-%D1%81-github)
4. Проверяем что всё работает *(как минимум должна запускаться игра)*
5. Пушим файлы на github: `git push`

#####Клонирование репозитория на комп
1. В командной строке в том месте где хотим разместить проект                              
`git clone https://github.com/bk0606/PostapocalypticScroller.git`
2. Обязательно проверьте чтобы в локальном проекте был файл .gitignore (если его там нет - создать ручками и содержание вставить из файла на github.com)

<br />

