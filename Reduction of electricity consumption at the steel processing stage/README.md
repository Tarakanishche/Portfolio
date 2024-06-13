# Снижение потребления электроэнергии на этапе обработки стали

[.ipynb](https://github.com/Tarakanishche/Portfolio/blob/main/Reduction%20of%20electricity%20consumption%20at%20the%20steel%20processing%20stage/temperature_control.ipynb), [HTML](https://github.com/Tarakanishche/Portfolio/blob/main/Reduction%20of%20electricity%20consumption%20at%20the%20steel%20processing%20stage/temperature_control.html)

## Описание проекта

Для оптимизации производственных расходов металлургический комбинат принял решение снизить потребление электроэнергии на стадии обработки стали. Для этого комбинат должен контролировать температуру сплава. Наша задача - создать модели, которые смогут предсказывывать эту температуру. После провести тесты на валидациионных данных и выбрать лучшую. Заказчик планирует использовать разработанную модель для имитации технологического процесса. 

## Навыки и инструменты

- python
- sqlalchemy
- pandas
- numpy
- matplotlib
- seaborn 
- datetime 
- phik
- missingno
- functools
- sklearn
- catboost 
- tensorflow
- lime
- random
- `sqlalchemy.create_engine`
- `matplotlib.pyplot`
- `datetime.datetime`
- `datetime.timedelta`
- `functools.reduce`
- `sklearn.model_selection.train_test_split`
- `sklearn.model_selection.GridSearchCV`
- `sklearn.model_selection.KFold`
- `sklearn.preprocessing.StandardScaler`
- `sklearn.dummy.DummyRegressor`
- `sklearn.linear_model.LinearRegression` 
- `sklearn.linear_model.Ridge`
- `sklearn.ensemble.RandomForestRegressor`
- `catboost.CatBoostRegressor`
- `catboost.Pool`
- `catboost.cv`
- `tensorflow.keras.models.Sequential`
- `tensorflow.keras.layers.Dense`
- `tensorflow.keras.layers.Activation`
- `tensorflow.keras.layers.LeakyReLU`
- `tensorflow.keras.layers.BatchNormalization`
- `tensorflow.keras.layers.Input`
- `tensorflow.keras.optimizers.Adam`
- `tensorflow.keras.callbacks.EarlyStopping`
- `sklearn.metrics.mean_squared_error`
- `sklearn.metrics.make_scorer`
- `sklearn.metrics.r2_score`

## Общий вывод
- Выполнил удаленное подключение к базе данных на основе PostgresSQL и c помощью запросов произвел выгрузку необходимых данных в JupyterNotebook; 
- провёл EDA-анализ всех таблиц;
- исправил аномальные значения или удалил записи с ними;
- отобрал необходимые для обучения признаки и создал дополнительные синтетические признаки для повышения качества модели;
- смерджил все таблицы по идентификатору, так чтобы не нарушался не один из производственных этапов;
- оценил распределения всех признаков;
- провёл корреляционный анализ признаков;
- определил целевую метрику для ML-моделей;
- разделил тренировочный данные на train и test для отбора лучшей модели и последующего теста на 'новых' данных;
- нормализовал данные для улучшения качества обучения моделей;
- произвел обучение моделей с помощью подборов гиперпараметров и перекрестной проверки и выбрал самую лучшую по метрике на кросс-валидации;
- сравнил лучшую модель с константной на тестовых данных;
- проанализировал важность признаков, которые модель посчитала наиболее весомыми при определении целевой метрики;
- сделал выводы по результатам модели и всей работы, а также обозначил рекомендации в технологическом процессе и сборе данных, которые смогли бы повысить качество работы модели.
