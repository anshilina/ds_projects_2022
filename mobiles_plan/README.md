# Mobile plans research

The clients of the federal mobile operator are offered two tariff plans: "Smart" and "Ultra". To adjust the advertising budget, the commercial department wants to understand which tariff is more profitable.

**Goal:** to conduct a comparison analysis of two tariffs on a small sample of customers.

There is data on 500 users: name, location, tariff they use, number of calls and messages they used in 2018.

**Task:** to analyze how customers use tariffs and conclude which tariff is better.

In this study, we will compare how users use different tariffs. Then, the hypothesis about the difference in the average revenue of the "Smart" and "Ultra" tariffs will be tested.

**"Smart" Plan**
* Monthly fee: 550 rubles
* 500 minutes, 50 messages and 15 GB of data are included
* Extra charge:
Additional minute of conversation - 3 rubles. If customers' call lasted only 1 second, fee is charged as for 1 minute.
* Additional message - 3 rubles.
* Additional 1 GB of Internet traffic - 200 rubles.

**"Ultra" Olan**
* Monthly fee: 1950 rubles
* 3000 minutes of calls, 1000 messages and 30 GB of internet traffic are included
* Extra charge: Additional minute of conversation - 1 ruble, message - 1 ruble.
* Additional 1 GB of Internet traffic: 150 rubles.

## Data description

Table `users` - information about users:
* `user_id` - unique user ID
* `first_name` - username
* `last_name` — user last name
* `age` - user age (years)
* `reg_date` — users' registration date (day, month, year)
* `churn_date` — tariff cut-off date (if the value is omitted, it means that the tariff was still valid at the time the data was uploaded)
* `city` — users' city of residence
* `tariff` — plan name

Table `calls` - information about calls:
* `id` — unique call number
* `call_date` — call date
* `duration` — call duration in minutes
* `user_id` - ID of the user who made the call

Table `messages` - information about messages:
* `id` — unique call number
* `message_date` — message date
* `user_id` - ID of the user who sent the message

Table `internet` - information about Internet sessions:
* `id` — unique session number
* `mb_used` - the amount of Internet traffic spent per session (in megabytes)
* `session_date` — internet session date
* `user_id` - user ID

Table `tariffs` - information about tariffs:
* `tariff_name` — tariff name
* `rub_monthly_fee` — monthly fee in rubles
* `minutes_included` - number of minutes included in the plan
* `messages_included` - number of messages included in the plan
* `mb_per_month_included` - the amount of Internet traffic included in the plan (in megabytes)
* `rub_per_minute` - the cost of extra minute of conversation (for example, if tariff includes 100 minutes of conversation per month, then a fee will be charged from 101 minute)
* `rub_per_message` - the cost of extra message
* `rub_per_gb` - the cost of additional gigabyte of Internet traffic (1 gigabyte = 1024 megabytes)

## Libraries

*numpy*

*pandas*

*IPython*

*matplotlib*

*seaborn*

*scipy*

# Исследование тарифов сотовой связи

Клиентам федерального оператора сотовой связи предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

**Цель:** провести предварительный анализ тарифов на небольшой выборке клиентов. 

Есть данные 500 пользователей: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018-й год. 

**Задача:** проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

В исследовании будует проведено сравнение того, как пользователи используют разные тарифы. Далее будет проверена гипотеза о разнице в средней выручке тарифов "Смарт" и "Ультра".

**Тариф «Смарт»**
* Ежемесячная плата: 550 рублей
* Включено 500 минут разговора, 50 сообщений и 15 Гб интернет-трафика
* Стоимость услуг сверх тарифного пакета:
Минута разговора — 3 рубля. Количество использованных минут и мегабайтов «Мегалайн» всегда округляет вверх. Если пользователь проговорил всего 1 секунду, в тарифе засчитывается целая минута.
* Сообщение — 3 рубля.
* 1 Гб интернет-трафика — 200 рублей.

**Тариф «Ультра»**
* Ежемесячная плата: 1950 рублей
* Включено 3000 минут разговора, 1000 сообщений и 30 Гб интернет-трафика
* Стоимость услуг сверх тарифного пакета: Минута разговора — 1 рубль. Сообщение — 1 рубль.
* 1 Гб интернет-трафика: 150 рублей.

## Описание данных

Таблица `users` — информация о пользователях:
* `user_id` — уникальный идентификатор пользователя
* `first_name` — имя пользователя
* `last_name` — фамилия пользователя
* `age` — возраст пользователя (годы)
* `reg_date` — дата подключения тарифа (день, месяц, год)
* `churn_date` — дата прекращения пользования тарифом (если значение пропущено, значит, тариф ещё действовал на момент выгрузки данных)
* `city` — город проживания пользователя
* `tarif` — название тарифного плана

Таблица `calls` — информация о звонках:
* `id` — уникальный номер звонка
* `call_date` — дата звонка
* `duration` — длительность звонка в минутах
* `user_id` — идентификатор пользователя, сделавшего звонок

Таблица `messages` — информация о сообщениях:
* `id` — уникальный номер звонка
* `message_date` — дата сообщения
* `user_id` — идентификатор пользователя, отправившего сообщение

Таблица `internet` — информация об интернет-сессиях:
* `id` — уникальный номер сессии
* `mb_used` — объём потраченного за сессию интернет-трафика (в мегабайтах)
* `session_date` — дата интернет-сессии
* `user_id` — идентификатор пользователя

Таблица `tariffs` — информация о тарифах:
* `tariff_name` — название тарифа
* `rub_monthly_fee` — ежемесячная абонентская плата в рублях
* `minutes_included` — количество минут разговора в месяц, включённых в абонентскую плату
* `messages_included` — количество сообщений в месяц, включённых в абонентскую плату
* `mb_per_month_included` — объём интернет-трафика, включённого в абонентскую плату (в мегабайтах)
* `rub_per_minute` — стоимость минуты разговора сверх тарифного пакета (например, если в тарифе 100 минут разговора в месяц, то со 101 минуты будет взиматься плата)
* `rub_per_message` — стоимость отправки сообщения сверх тарифного пакета
* `rub_per_gb` — стоимость дополнительного гигабайта интернет-трафика сверх тарифного пакета (1 гигабайт = 1024 мегабайта)

## Используемые библиотеки

*numpy*

*pandas*

*IPython*

*matplotlib*

*seaborn*

*scipy*