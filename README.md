# Analysis of game users activity
Анализ активности игроков в компьютерной игре.

## Цель
Реализовать функцию для расчета Retention rate игроков от дня регистрации. Обработать результаты АВ-теста. Предложить метрики для оценки результатов последнего прошедшего тематического события в игре.

## Библиотеки
pandas, seaborn, matplotlib, numpy, scipy, json, urllib

## Краткое описание данных
problem1-reg_data.csv — таблица с айди и датой регистрации пользователя в UTC

problem1-auth_data.csv —  таблица с айди и датой аутентификации пользователя в UTC

Проект_1_Задание_2.csv —  таблица результатов АВ-теста

## Результаты
### Реализована функция для расчета Retention rate.

Функция на вход принимает два DataFrame, первый - время регистрации пользователя, второй - время аутентификации.
Возвращает DataFrame с Retention rate.

### Проанализированы результаты АВ-теста
Данные были загружены с помощью Яндекс-API.
В результате было выявлено что конверсия в покупку была лучше у контрольной группы, но больший доход принесла тестовая группа.
Также были высказаны сомнения в корректности проведенного эксперимента.

### Предложены метрики для оценки результатов последнего прошедшего тематического события в игре.
Наилучшеми метриками будут являться:
1. Отношение времени затраченного игроком в тематическом событии к общему времени проведенному в  игре.
2. Среднее количество уровней пройденных игроками.
3. Отношение игроков прошедших 50% всеX уровней события ко всем игрокам которые пробовали событие.


