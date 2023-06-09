# [Домашнее задание седьмого занятия](https://youtu.be/FfMrFOwbz5k)

Если не получается решить ДЗ, попробуйте пересмотреть видео, поискать информацию в интернете или попросите помощь в [чатике](https://t.me/ablazhievski).

**Примеры решения задач доступны по ссылке (котлин-файл с кодом): [тык](https://github.com/TomNotArtem/myCourseKotlinRu/blob/main/Lesson_7/tasks_for_lesson_7.kt)**

> Чтобы  помочь  вам  понять  логические  операторы, представьте  себе
> разговор  между  ребенком и  его  матерью. Он  хочет  поиграть  на
> компьютере, поэтому  спрашивает  маму, а  она  говорит: «Ты  можешь
> поиграть на  компьютере, но  только  если  сделаешь домашнее  задание
> **И**  уберёшься  в  комнате».  В  программировании  вы  можете  выразить
> это  условие, используя  оператор  **и** ( **&&** ) между  логическими
> значениями. Либо логические **или**(**||**), если мама назвала
> условие: "Ты  можешь  поиграть на компьютере, если сделаешь домашнее
> задание  **ИЛИ** уберёшься в  комнате."

## Задание 1. Странная касса

Представьте, что вы разрабатываете программы для кассы самообслуживания. Предположим, что есть такой товар, который нельзя продавать до 18 лет. Напишите программу, которая будет проверять возраст клиента и, если ему меньше 18 лет запрещает продажу этого товара.

1. Создайте константу с именем `age` и задайте для нее любой возраст.

2. Создайте константу с именем `minAge` и задайте ей значение 18.

3. Затем создайте константу с именем `isAccessible` 
4. Используя операторы сравнения, определите можно ли продать клиенту товар и запишите результат проверки в константу `isAccessible`

5. В результате должно быть записано "true" или "false" в константу `isAccessible`.

6. Выведите содержимое этой константы в консоль.

## Задание 2. Еще более странная касса

Вы решили не останавливаться и ввести проверку не только минимального возраста, а также и максимального, после которого товар больше не продается.

1. Создайте константу `maxAge` и укажите возраст, до которого(включительно) продается товар.

2. Используя операторы сравнения, проверьте находится ли значение переменной `age` в промежутке от минимального до максимального возраста.

3. В результате должно быть записано "true" или "false" в константу `isAccessible`.

4. Выведите содержимое этой константы в консоль.

## Задание 3. Ну мы так вообще разоримся...

Добавим еще проверку. По мимо проверки возраста, необходимо, чтобы время покупки товара находилось в промежутке с 8 утра до 23 часов. Дополните код предыдущей задачи.

1. Создайте переменную с именем `time` и установите значение 22

2. Используя логические операторы добавьте дополнительную проверку. По мимо проверки возраста, необходимо чтобы еще И время было в определенном промежутке. Только в таком случае в константу `isAccessible` должен быть записан "true".

3. Выведите содержимое этой константы в консоль.

## Задание 4. Ну хоть что-то светлое

Добавьте еще одну проверку в условие. Сделайте так, чтобы если эта проверка выполнялась, то товар продавался не смотря на то какой был результат предыдущих проверок.

1. Создайте константу `isLucky` типа `Boolean` и установите значение `true`

2. Доработайте условие таким образом, чтобы при значении `isLucky` `true` товар продавался в любой случае, не зависимо от результата проверки предыдущих условий.

3. И при значении `isLucky` `false` никак не влиял на результат.
