#  Predicting number of taxi orders

## Data description

Taxi service company provided historical data on taxi orders at airports in 2018. In order to attract more drivers during the peak period, we must **predict the number of taxi orders for the next hour**. We need to select the best ML model for this purpose.

The *RMSE* score on the test sample should not exceed 48.

Steps:

1. Load the data and resample it by one hour.
2. Analyze the data.
3. Get test sample that is 10% of the original data.
4. Fit different models with different hyperparameters.
5. Check the best model on the test sample and draw conclusions.

The number of orders is in the `num_orders` column.

## Libraries

*pandas*

*numpy*

*statsmodels*

*sklearn*

*time*

*IPython*

*pprint*

*matplotlib*

*seaborn*

#  Прогнозирование заказов такси

## Описание данных

Компания, предоставляющая сервис такси, направила исторические данные о заказах такси в аэропортах за 2018 год. Чтобы привлекать больше водителей в период пиковой нагрузки, мы должны **спрогнозировать количество заказов такси на следующий час**. Нам необходимо построить модель для такого предсказания.

Значение метрики *RMSE* на тестовой выборке должно быть не больше 48.

Шаги исследования:

1. Загрузить данные и выполнить их ресемплирование по одному часу.
2. Проанализировать данные.
3. Сделать тестовую выборку размером 10% от исходных данных.
4. Обучить разные модели с различными гиперпараметрами.
5. Проверить данные на тестовой выборке и сделать выводы.


Количество заказов находится в столбце `num_orders`.

## Используемые библиотеки

*pandas*

*numpy*

*statsmodels*

*sklearn*

*time*

*IPython*

*pprint*

*matplotlib*

*seaborn*