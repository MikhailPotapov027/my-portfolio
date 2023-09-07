# my-portfolio
## Обо мне
Привет! Меня зовут Михаил, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

## Навыки и технологии
- Инструменты анализа данных: SQL, Excel:
- Системы управления базами данных: PostgreSQL
## Проекты

<p>Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра

Что нужно было сделать:

<p>Задача №1
<p>- Нужно просчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-ти процентную маржинальность.
<p>Задача №2
<p>- Визуализировать какие пользователи, где и в каком объеме смотрят фильмы на платформе.

<p>Как решал:
<p>Определил, что является юнитом в нашей экономике.
Посчитал юнит-экономику продукта и предложил сценарий по настройке параметров для выхода на 25%-ую маржинальность.
Выбрал оптимальный вариант расчета Retention.
Собрал визуализации основных бизнес-показателей
Исследовал данные о пользователях и их поведении.

<p>Ссылка на проект:
https://docs.google.com/spreadsheets/d/1TRZJFYeCnPOuZl2OUDjmsgvIJK4p47rGzUZKXUYl5C0/edit?usp=sharing

<p>Выводы (итоги):

<p>Итог №1 Чтобы выйти на 25%-ую маржинальность необходимо увеличить стоимость подписки и Retention и уменьшить объем скидок, стоимость привлечения клиента а также постоянные затраты.
<p>Итог №2 Из визуализации можем увидеть, что самое большое кол-во подписчиков находятся в часовом поясе UTC+1, пик просмотров с 18:00 до 20:00, самое большое количество просмотров приходится на пятницу, субботу и воскресенье.

<p>Проект 2: Моделирование изменения балансов студентов

<p>Что нужно было сделать:

<p>Задача №1
<p>- Посмотрите на изменения балансов студентов (на примере топ-1000 строк), собранных из CTE.
<p>- Какие данные смущают? Какие вопросы стоит задавать дата-инженерам и владельцам таблиц?

<p>Задача №2
<p>- Создайте визуализацию (линейную диаграмму) итогового результата и какие выводы можно сделать из получившейся визуализации?

<p>Как решал: <p>
<p>Узнал, когда была первая транзакция для каждого студента.
Собрал таблицу с датами за каждый календарный день 2016 года.
Узнал, за какие даты имеет смысл собирать баланс для каждого студента.
Нашел все изменения балансов, связанные с успешными транзакциями.
Нашел баланс студентов, который сформирован только транзакциями.
Нашел изменения балансов из-за прохождения уроков.
Создал CTE для хранения кумулятивной суммы количества пройденных уроков.
Создал CTE balances с вычисленными балансами каждого студента.
И ответил на первый вопрос, как менялось общее количество уроков на балансах студентов?
Просуммировав нужные поля из CTE balances и создав визуализацию сделал выводы.

<p>Ссылка на проект
https://docs.google.com/spreadsheets/d/1YFtyCTWHtm75gCk4EREZF_iC3d4IZ21jxrYrkxZGrtk/edit?usp=sharing

<p>Выводы (итоги):

<p>Итог №1 Нашел ошибку в данных, что пользователь проходит больше уроков, чем приобрел
<p>Итог №2 Провели порядка 80% уроков которые продали, самые высокие продажи с конца октября по начала ноября, больше всего проходят уроков начиная с осени до конца декабря.
