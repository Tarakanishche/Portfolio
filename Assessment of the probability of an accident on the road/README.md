# Оценка вероятности дорожно-транспортного происшествия на дороге

[.ipynb](https://github.com/Tarakanishche/Portfolio/blob/main/Assessment%20of%20the%20probability%20of%20an%20accident%20on%20the%20road/accident_analysis.ipynb), [HTML](https://github.com/Tarakanishche/Portfolio/blob/main/Assessment%20of%20the%20probability%20of%20an%20accident%20on%20the%20road/accident_analysis.html)

## Описание проекта

Требуется создание системы, которая сможет предсказывать шансы на аварию по маршруту, который выберет водитель. Эта система будет оценивать риск повреждения автомобиля в дороге. Когда водитель возьмет машину в пользование и укажет куда едет, наша задача — дать ему знать о риске. Если опасность высока, покажем предупреждение и посоветуем, как лучше поехать.

Сейчас идея находится в стадии обсуждения. Нет ни готового плана, как это всё будет работать, ни чего-то похожего на рынке. Сначала нам нужно выяснить, реально ли прогнозировать аварии, анализируя прошлые данные о происшествиях в конкретной местности.

## Навыки и инструменты

- python
- pandas
- numpy
- matplotlib
- seaborn
- missingno
- phik
- copy
- sklearn
- `sqlalchemy.create_engine`
- `sklearn.impute.SimpleImputer`
- `sklearn.metrics.f1_score`
- `sklearn.metrics.precision_recall_curve`
- `sklearn.preprocessing.StandardScaler`
- `sklearn.preprocessing.OneHotEncoder`
- `sklearn.preprocessing.OrdinalEncoder`
- `category_encoders.leave_one_out.LeaveOneOutEncoder`
- `sklearn.model_selection.train_test_split`, 
- `sklearn.model_selection.GridSearchCV`
- `sklearn.model_selection.KFold`
- `sklearn.compose.ColumnTransformer`
- `sklearn.pipeline.Pipeline`
- `sklearn.linear_model.LogisticRegression`
- `sklearn.linear_model.RidgeClassifier`
- `sklearn.ensemble.RandomForestClassifier`
- `catboost.RandomForestClassifier`
- `catboost.Pool`
- `catboost.cv`

## Общий вывод
- Выполнил выгрузку датафреймов из БД; 
- провёл анализ выведенных данных; 
- написал аналитические задачи для своих коллег; 
- подготовил данные;
- с помощью подбора гиперпараметров и определения порога классификации определил лучшую модель на тестовых данных, готовую к использованию в продакшене; 
- сделал выводы по результатам модели и написал рекомендации для бизнеса и для улучшения качества модели.

