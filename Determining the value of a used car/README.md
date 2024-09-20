# Определение стоимости подержанного автомобиля

[ipynb](https://github.com/Tarakanishche/Portfolio/blob/main/Determining%20the%20value%20of%20a%20used%20car/determinig_cost.ipynb), [HTML](https://github.com/Tarakanishche/Portfolio/blob/main/Determining%20the%20value%20of%20a%20used%20car/determinig_cost.html)


## Описание проекта

Требуется подготовить прототип модели машинного обучения, которая должна предсказывать стоимость продажи автомобиля на вторичном рынке в зависимости от его характеристик c платформы Kaggle (https://www.kaggle.com/competitions/used-cars-price-prediction-19ds/overview). Модель поможет более адекватно устанавливать цены на рынке подержанных авто, что приведёт к более удобному пользованию сервисом, так как уменьшиться время, которое пользователь тратит на установку более реалистичной цены, за которую покупатель будет готов заплатить. А также будет больше довольных клиентов, которые купили автомобиль не за оверпрайс. В связи с этим уменьшится число недовольных пользователей, которые могут выбрать другой маркетплейс для купли-продажи автомобилей, что опять-таки увеличит прибыльность нашего сервиса.

## Навыки и инструменты

- python
- pandas
- numpy
- matplotlib
- seaborn
- missingno
- sklearn
- `sklearn.impute.SimpleImputer`
- `sklearn.impute.KNNImputer`
- `sklearn.metrics.mean_absolute_percentage_error`
- `sklearn.preprocessing.StandardScaler`
- `sklearn.model_selection.train_test_split`
- `sklearn.linear_model.LinearRegression`
- `sklearn.tree.DecisionTreeRegressor`
- `sklearn.ensemble.RandomForestRegressor`
- `catboost.CatBoostRegressor`
- `catboost.Pool`

## Общий вывод
Выполнил анализ данных, обоснованное заполнение пропусков, получил наиболее качественную модель, выполнив проверку на валидационных данных.
Подготовил рекомендации для бизнеса и вывод по наилучшей модели, готовой к продакшену.


