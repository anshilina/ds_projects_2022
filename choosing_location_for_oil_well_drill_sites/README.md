# Choosing region for oil well drill site

Oil company needs to decide where to drill a new well. We have to chose the best region.

There is data on oil samples in three regions: 10,000 observations in each region, where the quality of oil and the volume of its reserves were measured. To choose region, where mining will be the most profitable, we will use ML models. Profit and risks will be analyzed using *bootstrap sampling*.

## Libraries

*pandas*

*numpy*

*sklearn*

*IPython*

*matplotlib*

*seaborn*

# Выбор локации для скважины


Нефтяной компании необходимо решить, где бурить новую скважину. Есть данные по пробам нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Для принятия решения, какой регион выбрать, где добыча принесёт наибольшую прибыль, будет построена модель машинного обучения. Возможная прибыль и риски будут проанализированы техникой *Bootstrap.*

В проекте были реализованы следующие шаги для выбора локации:

- В избранном регионе были найдены месторождения, для каждого было определено значения признаков
- Была построена модель и оценен объём запасов
- Было выбрано месторождение с самым высокими оценками значений. Были учтены бюджет компании и стоимость разработки одной скважины
- Прибыль рассчитывалась как суммарная прибыль отобранных месторождений

# Используемые библиотеки

*pandas*

*numpy*

*sklearn*

*IPython*

*matplotlib*

*seaborn*