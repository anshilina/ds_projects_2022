# Exploring sales advertising in the housing market in St. Petersburg 

In this project, data provided by the Yandex.Realty service is studied. There are ads of apartments for sale in St. Petersburg and neighboring settlements over several years. **The purpose** is to determine the market value of real estate objects. We need to establish parameters that will be used in automated system that monitors outliers and fraudulent activity. The project will solve the following **tasks**:

- To preprocess data: identify and drop duplicates; study and fill in the missing values; change the data type if necessary; drop outliers
- To add new variables needed to build an automated system
- To explore and analyze data, visualize results
- To determine the speed of sales
- To identify factors affecting the total cost of apartments
- To identify the locations with the highest and lowest cost per meter squared
- To determine relationship between price and distance from city center (in St. Petersburg)

There are two types of data available. The first one is the data provided by users (apartments owners or agents) when posting an ad. The second one (for example, distance from the city center, airport, nearest parks and pounds) was automatically collected using maps. More detailed description of the variables is provided in the section **Data description**.

## Data description

* `airports_nearest` - distance to the nearest airport in meters (m)
* `balcony` - number of balconies
* `ceiling_height ` - ceiling height (m)
* `cityCenters_nearest` — distance to the city center (m)
* `days_exposition` - how many days ago the ad was published (from publication to removal)
* `first_day_exposition` — publication date
* `floor` — floor
* `floors_total ` - total floors in the house
* `is_apartment ` - apartments (boolean)
* `kitchen_area ` - kitchen area in meters squared (m²)
* `last_price ` - price at the time of removal from publication
* `living_area ` - living area in meters squared (m²)
* `locality_name ` - the name of the locality
* `open_plan ` - open plan (boolean type)
* `parks_around 3000` - the number of parks within a 3 km radius
* `parks_nearest ` - distance to the nearest park (m)
* `ponds_around 3000` - the number of ponds within a radius of 3 km
* `ponds_nearest ` - distance to the nearest body of water (m)
* `rooms` - number of rooms
* `studio` - studio apartment (boolean)
* `total_area ` is the total area of the apartment in meters squared (m²)
* `total_images ` - the number of photos of the apartment in the ad

## Libraries

*re*

*pandas*

*numpy*

*statistics*

*seaborn*

*IPython*

*matplotlib*

#  Исследование объявлений о продаже квартир

В проекте исследуются данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. **Цель исследования** – определение рыночной стоимости объектов недвижимости. В рамках данного проекта необходимо установить параметры, которые позволят построить автоматизированную систему, отслеживающую аномалии и мошенническую деятельность. В проекте будут решены следующие **задачи**:

- Предобработать данные сервиса: выявить и удалить дубликаты; исследовать и заполнить пропуски; изменить тип данных при необходимости; устранить редкие и выбивающиеся значения;
- Добавить новые переменные, необходимые для построения автоматизированной системы;
- Исследовать и проанализировать данные, визуализировать результаты;
- Определить скорость продажи квартир;
- Выявить факторы, влияющие на общую стоимость квартир;
- Определить населенные пункты с самой высокой и самой низкой стоимостью квадратного метра;
- Определить среднюю стоимость каждого км от центра (в Санкт-Петербурге).

В массиве данных доступны два вида данных. Ряд из них был внесен пользователями при размещении объявления. Оставшиеся данные (например, расстояние до центра, аэропорта, ближайшего парка и водоёма) были получены автоматически на основе картографических данных. Более подробное описание переменных представлено в разделе **Описание данных**.

## Описание данных

* `airports_nearest` — расстояние до ближайшего аэропорта в метрах (м)
* `balcony` — число балконов
* `ceiling_height` — высота потолков (м)
* `cityCenters_nearest` — расстояние до центра города (м)
* `days_exposition` — сколько дней было размещено объявление (от публикации до снятия)
* `first_day_exposition` — дата публикации
* `floor` — этаж
* `floors_total` — всего этажей в доме
* `is_apartment` — апартаменты (булев тип)
* `kitchen_area` — площадь кухни в квадратных метрах (м²)
* `last_price` — цена на момент снятия с публикации
* `living_area` — жилая площадь в квадратных метрах (м²)
* `locality_name` — название населённого пункта
* `open_plan` — свободная планировка (булев тип)
* `parks_around3000` — число парков в радиусе 3 км
* `parks_nearest` — расстояние до ближайшего парка (м)
* `ponds_around3000` — число водоёмов в радиусе 3 км
* `ponds_nearest` — расстояние до ближайшего водоёма (м)
* `rooms` — число комнат
* `studio` — квартира-студия (булев тип)
* `total_area` — общая площадь квартиры в квадратных метрах (м²)
* `total_images` — число фотографий квартиры в объявлении

## Используемые библиотеки

*re*

*pandas*

*numpy*

*statistics*

*seaborn*

*IPython*

*matplotlib*
