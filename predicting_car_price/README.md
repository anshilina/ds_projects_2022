# Predicting car price

We need to build a ML model that will predict the market value of the car. The following data is available: technical characteristics, configurations and prices of cars. Our **goal**: to choose the best model for predicting car price based on its characteristics.

We should account for:

- prediction quality (score)
- prediction time
- fitting time

*Features:*
* `DateCrawled` — date of downloading the record
* `VehicleType` — car body type
* `RegistrationYear` - year of car registration
* `Gearbox` — gear box type
* `Power` - power (hp)
* `Model` – car model
* `Kilometer` — mileage (km)
* `RegistrationMonth` — month of car registration
* `FuelType` — fuel type
* `Brand` - car brand
* `Repaired` - was the car under repair or not
* `DateCreated` — date of creation of the record
* `NumberOfPictures` - number of the car photos
* `PostalCode` — postal code of the owner
* `LastSeen` — date of last user activity


*Target:*
* `Price` — price (euro)

## Libraries

*pandas*

*numpy*

*random*

*time*

*warnings*

*sklearn*

*lightgbm*

*catboost*

*IPython*

*matplotlib*

*seaborn*

# Определение стоимости автомобилей

Нам необходимо обучить модель машинного обучения, которая будет предсказывать рыночную стоимость автомобиля. В доступе следующие данные: технические характеристики, комплектации и цены автомобилей. Наша цель: выбрать модель для предсказания стоимости авто по его характеристикам. 

Критерии заказчика:

- качество предсказания
- скорость предсказания
- время обучения

*Признаки:*
* `DateCrawled` — дата скачивания анкеты из базы 
* `VehicleType` — тип автомобильного кузова
* `RegistrationYear` — год регистрации автомобиля
* `Gearbox` — тип коробки передач
* `Power` – мощность (л. с.)
* `Model` – модель автомобиля
* `Kilometer` — пробег (км)
* `RegistrationMonth` — месяц регистрации автомобиля
* `FuelType` — тип топлива
* `Brand` – марка автомобиля
* `Repaired` — была машина в ремонте или нет 
* `DateCreated` — дата создания анкеты 
* `NumberOfPictures` — количество фотографий автомобиля 
* `PostalCode` — почтовый индекс владельца анкеты (пользователя) 
* `LastSeen` — дата последней активности пользователя 


*Целевой признак:*
* `Price` — цена (евро)

## Используемые библиотеки

*pandas*

*numpy*

*random*

*time*

*warnings*

*sklearn*

*lightgbm*

*catboost*

*IPython*

*matplotlib*

*seaborn*



