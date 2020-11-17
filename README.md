# Game

## История

### Предыстория
2320 год. Люди, вошли в сильный симбиоз с роботами. Выращивали детей до 12 
лет, как и раньше, а потом начинали делать операции по замене частей тела. 
В 18 лет всё, что осталось от человека, а это мозг и нервная система, 
были перемещены в экзоскелет. Были две компании, которые занимались 
межпланетными перевозками: SpaceJ и Carpus. Уже регулярными рейсами компании 
SpaceJ можно было попасть на 2 планеты, это Марс и Венера. В то время 
как компания Carpus перевозила только на Венеру. Перевозки осуществлялись
благодаря, многоуровневым туннелям между этими планетами. Каждая компания имела свои 
туннели. По туннелям ездили поезда. У влиятельных людей были личные космолёты.

Из-за большого количества роботов необходимо было много энергии. 
Большую часть энергии получали с помощью солнечных батарей, установленных 
на Меркурии. Меркурий, Венеру и Землю связывал туннель, по которому и переходила 
энергия. Этот туннель и батареи принадлежали компании SpaceJ. 

### Происшествие
Компания SpaceJ, владелец которой Беккет, развивалась мирно и быстро. А 
Carpus, владелец которой Шик, была недовольна, что SpaceJ абсолютный лидер 
среди компаний. По этому Carpus решила насолить своему конкуренту. 
Владелец Carpus на своём личном космолёте полетел к туннелю, который связывал 
Меркурий и Венеру. Он летел пару часов, а когда прибыл к середине, разорвал 
туннель своей пушкой и улетел. Из-за прерывания потока энергии с Меркурия, 
уже через 10 минут не было энергии на Венере, а через 25 минут и на Земле, 
а через 40 минут на Марсе. Поезда остановились. На ремонт туннеля уйдёт 
несколько дней. Освещения нет, невозможно заметить Шика. За такой проступок 
Шика надо осудить. 

### Миссия
Ваша миссия найти и захватить Шика, по возможности живым, и привести в земной 
суд. 

___

### Планетные истории
1. Меркурий
...
2. Венера
...
3. Земля
...
4. Марс
...
5. Юпитер
...
6. Сатурн
...
7. Уран
...
8. Нептун
...

## Вся логика

### Объекты
- Планеты
- Снаряжение(Kit)
- Жизни
- Деньги
- Боссы
- Космические тела
- История

#### Планеты
- Mercury
- Venus
- Earth
- Mars
- Jupiter
- Saturn
- Uranus
- Neptune

#### Снаряжение
##### Космолёты
- Стандарт
    - Цена: 0 J
    - Место только для одной пушки
- Ловкость
    - Цена: 200 J
    - Место только для одной пушки
    - Поворачивает быстрее в 2 раза чем _стандарт_
- Громадина
    - Цена: 400 J
    - Место только для двух пушек
- Элита
    - Цена: 800 J
    - Место только для двух пушек
    - Поворачивает быстрее в 2 раза чем _стандарт_

##### Пушки
- Стандарт
    - Цена: 0 J
    - Урон: 10
    - Скорострельность: 1/сек.
- Ловкость
    - Цена: 350 J
    - Урон: 10
    - Скорострельность: 2/сек.
- Громадина
    - Цена: 300 J
    - Урон: 20
    - Скорострельность: 1/сек.
- Элита
    - Цена: 750 J
    - Урон: 20
    - Скорострельность: 2/сек.
    

#### Жизни
На всю игру даётся три жизни. Жизни отображаются снизу слева, во время 
прохождений уровней. Они используются, по одной, когда космолёт врезается 
в космические тела или получает достаточно урона от вражеских снарядов. 
Восстановление космолёта происходит на месте его уничтожения.

#### Деньги ( J )
Деньги понадобятся для покупки усовершенствованного ___снаряжения___. 
Деньги можно получить:
- Награда за прохождение уровня
- Награда за уничтожение босса
- Собрав из разрушенного метеороида
> Чтобы собрать с метеороида надо в начале разрушить его используя пушку, а
> потом, если выпали деньги, собрать их, коснувшись космолётом до иконки 
> денег.

#### Боссы
##### "Телохранитель Шика"("Shick's bodyguard")
Телохранитель будет на 5 уровне(Юпитер). Он шириной в треть экрана. При 
встрече ты останавливаешься и начинаешь поединок. Телохранитель будет 
стрелять в тебя. Твоя задача наносить ему урон и уклонятся от оставшихся 
___космических тел___ и его снарядов.
- единиц прочности: 1000.
- награда за убийство: 100 J.
##### "Шик"("Shick")
Шик будет на 8 уровне(Нептун). Он чуть больше тебя. При встрече ты 
начинаешь догонять его, а он убегать, в это время ___космические тела___ 
продолжают появляться. Твоя задача наносить ему урон и уклонятся от 
___космических тел___.
- единиц прочности: 500.
- награда за убийство: Медаль героя планеты Земля.

#### Космические тела
Космические тела будут встречаться во время прохождения уровней. Их следует 
облетать или разрушать нанесениями ударов снарядами из пушки. Урон пушки 
равен количеству единиц прочности, которые будут отняты за попадание снаряда
в цель.
- Метеороид(Meteoroid)
    - Малый
        - единиц прочности: 10/20.
        - шанс выпадения денег: 80%.
        - шанс появления: 80%.
    - Средний
        - единиц прочности: 30.
        - шанс выпадения денег: 70%.
        - шанс появления: 70%.
    - Большой
        - единиц прочности: 40/50.
        - шанс выпадения денег: 50%.
        - шанс появления: 50%.
- Астероид(Asteroid)
    - Малый
        - единиц прочности: 60/70.
        - шанс выпадения денег: 40%.
        - шанс появления: 40%.
    - Средний
        - единиц прочности: 80.
        - шанс выпадения денег: 30%.
        - шанс появления: 30%.
    - Большой
        - единиц прочности: 90/100.
        - шанс выпадения денег: 10%.
        - шанс появления: 10%.
> Денег выпадает столько, сколько прочности было у разрушенного космического 
> тела.

#### История
Делится на разделы:
- Предыстория
- Происшествие
- Миссия
- По-уровневое продолжение истории(__Планетные истории__).

### Этапы(Stages)

#### Открытый kit
На этом этапе предоставляется информация о ___снаряжении___ и возможности: 
- Купить новое ___снаряжение___.
- Поменять используемое ___снаряжение___ на купленное.

#### Предыстория
На этом этапе показывается текст раздела __Предыстория__.

И кнопка "Продолжить".

#### Происшествие
На этом этапе показывается текст раздела __Происшествие__.

И кнопка "Продолжить".

#### Миссия
На этом этапе показывается текст раздела __Миссия__.

И кнопка "Продолжить".

#### Изменение языка
Можно вернуться назад, нажав кнопку "Отмена".

На этом этапе, нажав на блок языка, можно выбрать из списка языков:
- Русский
- Английский
- Немецкий

Затем можно будет изменить интерфейс на выбранный язык, нажав на кнопку "Изменить".

#### Подтверждение выхода
На этом этапе показывается текст: Вы уверены, что хотите выйти из приложения?.

Можно выйти из приложения, нажав на кнопку "Выход".

Можно вернуться назад, нажав на кнопку "Отмена".

#### Подтверждение о покупке
На этом этапе показывается текст: Вы уверены, что хотите купить такое-то снаряжение
за столько-то денег?.

Можно купить снаряжение, нажав на кнопку "Купить".

Можно вернуться назад, нажав на кнопку "Отмена".

#### Стартовая страница
Можно начать новую игру, нажав на кнопку "Новая игра".

Можно продолжить прошлую игру, нажав на кнопку "Продолжить игру".

Можно изменить язык интерфейса, нажав на кнопку "Язык".

Можно выйти из приложения, нажав на кнопку "Выход".

#### Главное меню
На этой странице изображена информация об объектах:
- Планеты
> Все планеты в ряд, нажимая на планету переходишь в этот уровень, если он 
 открыт для прохождения.
- Жизни
- Деньги

Можно получить информацию о снаряжении, нажав на кнопку "Kit".

Можно вернуться назад, нажав на кнопку "Back".

#### Конец уровня
Выводится: 
- Текст - Номер уровня и название планеты
- Текст - История для этой планеты
- Число - Собранные деньги 
- Число - Награда за прохождение уровня
> Количество денег подсчитывается по формуле:
~~~
Номер уровня * 5 = количество денег (J)
~~~
- Число - Сумма полученных денег за этот уровень

Если на этом уровне был босс, то дополнительно выводится:
- Текст - Имя босса
- Число - Деньги полученные за его уничтожение

Можно вернутся к главному меню, нажав кнопку "Дальше".

#### Die(Смерть)
На этом этапе показывается текст: "Вы потратили все жизни. Придётся начать сначала.
Надеюсь в следующий раз у вас получится".

Можно вернутся на стартовую страницу, нажав кнопку "Дальше".

#### Прохождение уровня
Чтобы уровень посчитался пройденным необходимо долететь до конца. Конец 
уровня наступает, когда время уровня заканчивается.
> Время прохождения уровня указано в файле этого уровня(планеты).

От игрока приходят данные об управлении космолётом(левая и правая кнопки).

Во время прохождения этого этапа будут игрок будет взаимодействовать с объектами:
- Планеты
- Снаряжение
- Жизни
- Деньги
- Боссы
- Космические тела

Методы объектов, которые могут быть задействованы:
- Планеты
    - getBackground() : file(img)
    - getBoss() : bool
    - getLevelAward() : int
- Снаряжение
    - getUsedSpaceship() : file(img)
- Жизни
    - getRemainingLives() : int
    - minusLife() : void
- Деньги
    - addSession(Session $session) : void
- Session
    - setLevelAward(int $award) : void
    - addMeteoroidMoney(int $money) : void
    - addAsteroidMoney(int $money) : void
    - addBossMoney(int $money) : void
- Боссы
    - appear() : void
    - minusStrength(int $strength) : void
- Космические тела
    - getView() : file(img)
    - crush() : int
    
Внешние функции
- moveTopToBottom(object $object) : void
> Двигает полученный объект сверху в низ, пока он не исчезнет с области видимости.
- moveToRight(object $object) : void
> Передвигает объект на минимальное расстояние в право.
- moveToLeft(object $object) : void
> Передвигает объект на минимальное расстояние в лево.

Во время прохождения ты:
- Управляешь ___космолётом___
    - Поворачивать его левее.
    - Поворачивать его правее.
- Уворачиваешься от ___космических тел___
- Уничтожаешь ___космические тела___
- Собираешь ___деньги___
- Уворачиваешься от атак ___босса___
- Уничтожаешь ___босса___
