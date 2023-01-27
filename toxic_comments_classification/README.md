# Toxic comments classification for online store

## Data description

Online store is launching a new service: now users can edit and add product descriptions like in wikipedia. That is, clients propose their edits and comment on others' messages. Store needs a tool that will detect toxic comments and submit them for moderation.

Our **goal**: to fit ML models to classify comments as positive or negative (toxic). We have a dataset with where comments were labeled as toxic or not.

Let's build a model with the resulting quality metric *F1* not less than 0.75.

**Features**

The *text* column contains the text of the comment, and *toxic* is the target (1 – comment is toxic, 0 - it is not).

## Libraries

*pandas*

*numpy*

*re*

*nltk*

*spacy*

*sklearn*

*lightgbm*

*catboost*

*xgboost*

*time*

*IPython*

*pprint*

*matplotlib*

*seaborn*

# Классификация токсичных комментариев для интернет-магазина

## Описание данных

Интернет-магазин запускает новый сервис: теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

Наша **задача**: обучите модель классифицировать комментарии на позитивные и негативные. У нас есть набор данных с разметкой о токсичности правок.

Построим модель со значением метрики качества *F1* не меньше 0.75. 

**Признаки*

Столбец *text* содержит текст комментария, а *toxic* — целевой признак.

## Используемые библиотеки

*pandas*

*numpy*

*re*

*nltk*

*spacy*

*sklearn*

*lightgbm*

*catboost*

*xgboost*

*time*

*IPython*

*pprint*

*matplotlib*

*seaborn*