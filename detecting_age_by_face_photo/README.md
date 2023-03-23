# Detecting age by face photo

## Problem statement

Photographs of people's faces and data on their real age are available. Our **goal**: to detect the age by the photo. 

In this project, we need to solve the regression problem. Target quality metric: MSE (< 7).

## Stages of the project

1. Exploratory data analysis: after loading data we will estimate the sample size and distribution of the dependent variable (age). I addition, we will study some of the available photographs.
2. Building and training a model: we will build a neural network that will predict a person's age by face photo. We employ ResNet-50 as the backbone network. Activation function is RELU (to avoid negative values for age predictions). The loss function is the mean square error (MSE), quality of predictions is measured using mean absolute error (MAE).

## Libraries

*pandas*

*numpy*

*tensorflow*

*matplotlib*

*seaborn*

*IPython*

*PIL*

# Определение возраста по фотографии

## Постановка задачи

Нам доступны фотографии людей и данные о их реальном возрасте. Наша **задача**: определить возраст по фотографии. 

В данном проекте мы решаем проблему регрессии. Целевая метрика качества: MSE (< 7).

## Этапы реализации проекта

1. Исследовательский анализ данных: после загрузки массива мы оценим размер выборки, распределение зависимой переменной (возраст), а также посмотрим на несколько фотографий из тех, что нам доступны
2. Создание и обучение модели: мы создадим нейронную сеть, которая будет предсказывать возраст человека по фотографии. Основой нейронной сети будет ResNet50. В качестве функции активации мы будем использовать функцию RELU (так мы точно не получим отрицательные значения возраста). Функция потерь в данной задаче – среднеквадратичная ошибка (MSE), качество замеряем на средней абсолютной ошибке (MAE).

## Используемые библиотеки

*pandas*

*numpy*

*tensorflow*

*matplotlib*

*seaborn*

*IPython*

*PIL*