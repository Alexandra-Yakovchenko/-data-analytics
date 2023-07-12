# Обо мне
Привет! Меня зовут Александра, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

# Навыки и технологии
- Инструменты анализа данных: SQL, Excel
- Языки программирования и библиотеки: Python
- Системы управления базами данных: MySQL, PostgreSQL
- Средства визуализации данных: А/Б есты


# Проекты
### Проект 1: Калькулятор юнит-экономики онлайн-школы

Что нужно было сделать:

**Задача №1** *Настроить в калькуляторе учет корректировок планов маркетинга.*   
**Задача №2** *Пересчитать план найма преподавателей.*   
**Как решала:** Для решения поставленных задач настроила динамический расчет количества студентов за период 05.21-04.22 с поправкой на коэффициент. Просчитала сценарий, при котором планы маркетинга будут увеличены на 12% без изменений остальных показателей.
Построила калькулятор Найма преподавателей и добавила в него возможность изменять входных параметры: Пропускную способность и Retention - с помощью дополнительного столбца с процентными изменениями.

**Ссылка на проект** [Проект1](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12009996/1_.-.-.xlsx)

**Выводы (итоги):**

Итог №1 просчитан сценарий, при котором планы маркетинга будут увеличены на 12%.  
Итог №2 составлен план найма с ограничением не более 70 преподавателей в месяц.   

### Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра

Что нужно было сделать:

**Задача №1** *Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность.*  
**Задача №2** *Собрать наглядную визуализацию.*  
**Как решала:** Определа юнит в данной экономике. Посчитала юнит-экономику продукта и предложила сценарий по настройке параметров для выхода на 25%-ную маржинальность. Расчитала Retention. Собрала визуализацию основных бизнес-показателей. Провела исследование данных о пользователях и их поведении.

**Ссылка на проект** [Проект2_ Таблицы_с_данными_2часть.xlsx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12023089/2_._._._2.xlsx)  
[Проект2_ Таблицы_с_данными.xlsx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12023088/2_._._.xlsx)  
[Проект2_ Калькулятор юнит-экономики онлайн-кинотеатра.xlsx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12023087/2_.-.-.xlsx)  


**Выводы (итоги):**

Итог №1 Далеко не весь контент, который представлен в онлайн-кинотеатре интересен зрителям. Согласно графикам, половину всех просмотров покрывает 73 фильма из 140568 размещенных на платформе.  
Итог №2 Прослеживается прямая зависимость между затратами на маркетинг и количеством новых пользователей. Что привело к высокому CAC на юнит 139%. И соответственно отрицательной маржинальности.   
Итог №3 Выйти на прибыль мы можем за счет захвата бОльшей доли рынка. Для этого стоит сделать акцент в маркетинге на рекламирование топ фильмов из тех 70, которые составляют половину от количества просмотров. Учитывать спрос на контент, который просматривают в выходные. Увеличение цены на подписку.  И предоставить скидки для старых пользователей для увеличения Retention.   


### Проект 3**: Когортный анализ онлайн-кинотеатра с помощью SQL

Что нужно было сделать:

**Задача №1** *Найти как ведут себя клиенты, пришедшие от партнеров. Определить эффективность каналов привлечения клиентов, используемых в течение рассматриваемого периода.*    
**Задача №2** *Визуализировать винтажные доходимости с учетом скорости падения интереса клиентов в разбивке по партнерам.*   
**Как решала:** Проранжировала покупки во всей таблице, чтобы определить какой по счету является данная покупка в рамках всех покупок клиента. Построила распределение количества первых покупок клиента по полям флагам бесплатная/платная подписка, а также по партнерам. 
Скачала результаты в Excel. Построила гистограмму с распределением количества покупок, добавила к графику срез, на котором можно выбрать, на каких по счету покупках в рамках клиента построена гистограмма.  
Дополнила код таким образом, чтобы получились винтажные доходимости для каждого партнера (процент клиентов, которые дошли до второй покупки, до третьей покупки и т.д.). Вывела полученные результаты в Excel и нарисовала график, на котором каждая линия показывает своего партнера.

**Ссылка на проект:** [Проект3_Покупки с проставленными рангами.xlsx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12022923/3_.xlsx)  
[Проект3_Когортный анализ онлайн-кинотеатра.xlsx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12022922/3_.-.xlsx)  
[Проект3_SQL_запрос.docx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12022921/3_SQL_.docx)  



**Выводы (итоги):**

Итог №1 Больше всего покупок пришло с "органической покупки", через первые бесплатные уроки. На стакнутом барчарте, это можно отследить наглядко (вложение 1)  
Итог №2 Анализ партнеров показал, что Тинькофф показал хорошую доходимость, а Альфа-банк показал плохую дохоимость.   


### Проект 4: Построение витрины для модели машинного обучения в банке

Что нужно было сделать:  


**задача №1**  *Составить витрину модели по запросу специалистов по машинному обучению.*     
**Как решала:** Написала скрипт, основываясь на таблице с клиентами, со следующими полями:  
-	внутренний идентификатор клиента,
-	название города,
-	числовой признак, который принимает значение 1 для мужчин и 0 для женщин,
-	иозраст,
-	числовая переменная, которая показывает, в первый ли раз клиент обратился к нам за кредитом, 
-	числовой признак, который принимает значение 1 при наличии мобильного телефона и 0 при его отсутствии,
-	числовая переменная, которая показывает, активен ли клиент, 
-	номер клиентского сегмента,
-	размер выданного кредита,
-	дата выдачи кредита,
-	тип выданного кредита,
-	суммарный объем кредитов, выданных в этом городе,
-	доля данного кредита среди всех кредитов, выданных в этом городе,
-	суммарный объем кредитов, выданных в рамках указанного типа кредита,
-	доля данного кредита среди всех кредитов, выданных в рамках указанного типа кредита,
-	суммарный объем кредитов, выданных в рамках указанного типа кредита и города,
-	доля данного кредита среди всех кредитов, выданных в рамках указанного типа кредита и города,
-	количество кредитов, выданных в этом городе,
-	количество кредитов, выданных в рамках указанного типа кредита,
-	количество кредитов, выданных в рамках указанного типа кредита и города.

**Ссылка на проект:** [Проект4_SQL_запрос.docx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12022939/4_SQL_.docx)  


**Выводы (итоги):**

Итог №1 Готовая витрина по запросу


### Проект 5: Моделирование изменения балансов студентов.

Что нужно было сделать: Смоделировать изменение балансов студентов.

**Задача №1** *Узнать количество уроков на балансе всех учеников за каждый календарный день.*  
**Задача №2** *Отследить изменения под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков)*  
**Задача №3** *Создать визуализацию (линейную диаграмму) итогового результата. Сделать выводы из получившейся визуализации.*  
**Как решала:** Узнала, когда была первая транзакция для каждого студента. Собрала таблицу с датами за каждый календарный день рассматриваемого года. Узнала, за какие даты имеет смысл собирать баланс для каждого студента.   
Нашла:  
- все изменения балансов, связанные с успешными транзакциями.   
- баланс студентов, который сформирован только транзакциями.   
- изменения балансов из-за прохождения уроков.   
Определила кумулятивную сумму количества пройденных уроков. Создала таблицу с вычисленными балансами каждого студента. Выбрала топ-1000 строк из этой таблицы для анализа изменения балансов студентов. Создала визуализацию (линейную диаграмму) итогового результата.

**Ссылка на проект:** [Проект5_Моделирование изменения балансов студентов.xlsx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12022943/5_.xlsx)  
[Проект5_SQL_запрос.docx](https://github.com/Alexandra-Yakovchenko/-data-analytics/files/12022942/5_SQL_.docx)


**Выводы (итоги):**

Итог №1 Появились вопросы к дата-инженерам и владельцам таблицы payments.  
Итог №2 На графиках видно, что по нарастающей увеличиваются покупки и прохождения уроков студентами. Что соответсвует нормальным требованиям данного процесса.
Есть стабильность: спроса в покупке уроков, использования услуг компании, в процессе между покупками и прохождением уроков.   



# Контактная информация
Email: <syakovchenko9@yandex.ru>  
Конт.телефон 89644349176  
