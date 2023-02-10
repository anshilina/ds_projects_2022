# Research on the recommendation of mobile tariffs

We have data on customers and their mobile plan. We will build ML model to classify tariff using customers' data.

**Goal:** Select the model with the highest *accuracy* (0.75).

Features:

* calls - number of calls
* minutes — total duration of calls in minutes
* messages - number of sms messages
* mb_used - Internet traffic used in Mb

Dependent variable:

* is_ultra - user's mobile plan ("Ultra" - 1, "Smart" - 0)

## Libraries

*pandas*

*IPython*

*seaborn*

*matplotlib*

*sklearn*

# Рекомендация тарифов сотовой связи

В нашем распоряжении данные о клиентах мобильных тарифов. Нужно построить модель для задачи классификации, которая будет подбирать подходящий тариф для новых клиентов.

**Цель:** постройте модель с максимально большим значением *accuracy* (0.75).

Признаки:

* сalls — количество звонков
* minutes — суммарная длительность звонков в минутах
* messages — количество sms-сообщений
* mb_used — израсходованный интернет-трафик в Мб

Зависимая переменная:

* is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0)

## Используемые библиотеки

*pandas*

*IPython*

*seaborn*

*matplotlib*

*sklearn*