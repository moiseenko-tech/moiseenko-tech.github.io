+++
date = '2025-03-29T10:59:32+02:00'
draft = false
title = 'Гиперфокус — дар или проклятье?'
+++
## Что такое гиперфокус

В состоянии гиперфокуса я залипал в задачу так, что мир вокруг просто переставал существовать. Я часами писал код, не замечая голода, усталости и даже того, что наступил новый день. Звучит безумно соблазнительно, правда?

Но гиперфокус — не суперсила по желанию. У кого-то он отсутствует в принципе. У остальных, включая меня, включается произвольно. Есть люди, которые пытаются более-менее успешно управлять наступлением гиперфокуса, создавая благоприятные условия, но в целом его не включишь, нажав волшебную кнопку.

Да и нужно ли его включать? Для себя сделал однозначный вывод, что в разрезе программирования гиперфокус — это не суперсила. Скорее наоборот. Да, я могу уйти в код с головой, но это вовсе не значит, что в итоге получится что-то хорошее.

## Проблемы

Когда я впадал в гиперфокус, то работал в одиночку. Без общения с коллегами, без обмена идеями и опытом, без неудобных вопросов очень легко было пойти в неверном направлении, причём на огромной скорости. И я много раз в эту ловушку попадал. Часто было так, что на следующий день, или через несколько дней я выбраковывал всё то, что написал ранее. Это здорово снижало среднюю скорость разработки.

> Мне очень нравится такая аналогия: когда я в состоянии гиперфокуса, то я — космический путешественник, который летит на космическом корабле с гипердвигателем 🚀. Часто я ошибаюсь с курсом и после прыжка понимаю, что нахожусь вообще не там, где надо. Ценное топливо потрачено и надо выбирать — проложить новый курс из текущей точки, что может быть сложно, или вернуться туда, где был и попробовать снова.

Вторая проблема — огромные куски кода на ревью. Гиперфокус непрогнозируем. Сегодня я его поймал — окей, но когда будет следующий раз — да чёрт его знает. Поэтому возникало естественное желание воспользоваться моментом на полную катушку. Ждать коллег, отдавая небольшие, но логически завершённые части — нет, спасибо. В гиперфокусе я не хотел простаивать — пока код пишется, я писал.

Закономерный итог этого — абсолютно нечитаемые портянки мердж-реквестов на тысячи строк кода, недовольные коллеги и мучительный для них разбор мердж-реквестов. Бывало так, что мне прямым текстом говорили, что проревьювить качественно такой объём невозможно. То есть страдало качество.

Ещё одной важной проблемой является потеря контекста. В состоянии гиперфокуса я так сосредотачивался на реализации, что переставал видеть картину в целом: забывал о бизнес-требованиях, или о пользовательских сценариях. В итоге заложенная бомба могла оказаться такой мощной, что проще было выбраковать код и написать заново, нежели отрефакторить.

## Решение

Есть несколько подходов для того, чтобы решить проблему гиперфокуса.

Например, очень известная техника Pomodoro 🍅. Она подразумевает работу определёнными интервалами с обязательными перерывами между ними. Для меня это абсолютно нерабочий вариант. Вообще, регулярно ставить таймер если у тебя СДВГ — это уже небольшой подвиг.

Я считаю, что назначенные врачом психостимуляторы могут помочь. Гиперфокус сам по себе недостаточно изучен, но моё мини-исследование показывает, что есть разумные объяснения этому эффекту. СДВГ — это не дефицит внимания, а нарушение в его распределении: либо рассеянность, либо «залипание». Вероятно, причина в дисфункции дофаминовой системы, которая отвечает за мотивацию и контроль. Стимуляторы помогают регулировать этот процесс, поэтому гиперфокус не исчезает, но становится более управляемым, а переключаться между задачами — легче.

Мой любимый способ контроля гиперфокуса — парное программирование. Об этой инженерной практике я ещё напишу отдельно, но в контексте гиперфокуса для меня это идеальный вариант. По сути, я передаю контроль коллеге: он может вовремя притормозить, если я увлекусь или подкорректировать направление. А если наоборот — я рассеян, то помогает сосредоточиться. Ещё один плюс: работая в паре, я физически не могу погружаться в код сутками, ведь мой рабочий ритм синхронизирован с партнёром.

## Резюме

* Гиперфокус оказался не суперсилой, а палкой о двух концах. Он позволял мне глубоко погружаться в работу, но без контроля приводил к потере времени, неверным решениям и хаосу в коде. В одиночку я легко мог уйти не туда, перегрузить коллег огромными мердж-реквестами и потерять общий контекст задачи.
* Решения есть, но далеко не все рабочие. Pomodoro мне вообще не зашёл, а вот медикаментозная терапия помогла сделать гиперфокус управляемым. Стимуляторы не убрали его, но дали больше контроля и гибкости. Ещё одним мощным инструментом стало парное программирование — с ним стало легче держать баланс, вовремя останавливаться и сохранять адекватный ритм работы.
* Гиперфокус можно направить в нужное русло, но с ним нужно быть очень осторожным.