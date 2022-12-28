# Bank customers attrition analysis 

## Data description

There are loss of clients in "Beta Bank". According to bank data, it is cheaper to keep current customers than to attract new ones. Therefore, our **goal** is to predict whether the client will leave the bank in the near future or not. Using the data on customers we will classify them on those who will leave and will not.

We have to fit classification model and get at least 0.59 of the F1-score. In addition, we will check AUC-ROC.

Features:

* RowNumber - row index in the data
* CustomerId - unique customer identifier
* Surname - surname
* CreditScore - credit score
* Geography - country of residence
* Gender - gender
* Age - age
* Tenure - how many years a person has been a bank client
* Balance - account balance
* NumOfProducts - the number of bank products used by the client
* HasCrCard - whether customer has a credit card
* IsActiveMember - whether client is an active member
* EstimatedSalary - client's salary

Target:

* Exited - binary variable, takes 1 if client left.

Data access: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Libraries

*pandas*

*random*

*numpy*

*sklearn*

*imblearn*

*matplotlib*

*seaborn*

# Прогнозирование оттока клиентов из банка

## Описание данных

Из банка каждый месяц стали уходить клиенты. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Поэтому наша **цель**: спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Мы будем решать задачу классификации.

В доступе исторические данные о поведении клиентов и расторжении договоров с банком. Необходимо построить предсказательную модель с предельно большим значением F1-меры (не менее 0.59). В качестве дополнительной проверки измеряется AUC-ROC. 

Ниже представлены неизвестные переменные:

* RowNumber — индекс строки в данных
* CustomerId — уникальный идентификатор клиента
* Surname — фамилия
* CreditScore — кредитный рейтинг
* Geography — страна проживания
* Gender — пол
* Age — возраст
* Tenure — сколько лет человек является клиентом банка
* Balance — баланс на счёте
* NumOfProducts — количество продуктов банка, используемых клиентом
* HasCrCard — наличие кредитной карты
* IsActiveMember — активность клиента
* EstimatedSalary — предполагаемая зарплата

Целевой признак:

* Exited — факт ухода клиента.

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Использованные библиотеки

*pandas*

*random*

*numpy*

*sklearn*

*imblearn*

*matplotlib*

*seaborn*