# Research on the recommendation of mobile tariffs

We have data on customers who have already switched to "Smart" or "Ultra" mobile plan. We need to model the classification of tariff. Our model should select the most suitable tariff using the users' characteristics.

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

В нашем распоряжении данные о поведении клиентов, которые уже перешли на мобильный тариф «Смарт» или «Ультра». Нужно построить модель для задачи классификации, которая будет подбирать подходящий тариф для новых клиентов.

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