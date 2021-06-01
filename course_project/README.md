Итоговый проект (пример) курса "Машинное обучение в бизнесе"

Стек:

ML: sklearn, pandas, numpy API: flask Данные: с kaggle - https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

Задача: Прогнозируйте дождь на следующий день, обучив модели классификации на целевой переменной RainTomorrow .Бинарная классификация

Используемые признаки:
'MinTemp',
'MaxTemp',
'Rainfall', 
'Evaporation'
'WindGustSpeed'
'WindSpeed9am',
'WindSpeed3pm',
'Humidity9am',
'Humidity3pm',
'Pressure9am',
'Pressure3pm',
'Cloud9am',
'Cloud3pm',
'Temp9am',
'Temp3pm',
'Location', 
'WindGustDir',
'WindDir9am',
'WindDir3pm',
'RainToday',
'RainTomorrow'

Модель: XGBClassifier

### Клонируем репозиторий и создаем образ

папка //app/models/ содержит:
1) weather_forecast.ipynb - иследовательский файл. Подбор модели
2) Pyplene_class.ipynb - пайплан проекта. 
3) pipeline.dill  - сохраненная модель предобработки данных

папка //app/ содержит:
1) run_server.ipynb - Запуск сервера для обработки запросов flask
2) Запросы к серверу.ipynb - собсвеено пример запросов.
3) x_test.csv и y_test.csv. Примеры данных для запроса.
