# Оценка вероятности дорожно-транспортного происшествия на дороге

[.ipynb](https://github.com/Tarakanishche/Portfolio/blob/main/Comparison%20of%20a%20text%20description%20and%20a%20photo/comparison_photo_and_request.ipynb), [HTML](https://github.com/Tarakanishche/Portfolio/blob/main/Comparison%20of%20a%20text%20description%20and%20a%20photo/comparison_photo_and_request.html)

## Описание проекта

Фотохостинги для профессиональных фотографов позволяют пользователям размещать фотографии с подробными описаниями, такими как место съемки и модель камеры. Мы планируем эксперимент с созданием поиска референсных изображений по текстовым запросам, чтобы фотографы могли найти сцены по описанию, например, "человек переходит горный перевал по металлическому мосту". 
Для демонстрационной версии нам нужно выбрать модель, способную создавать векторное представление изображений и текстов и оценивать степень их соответствия. 

Также важно учитывать юридические ограничения, особенно в отношении защиты данных о детях младше 16 лет.

## Навыки и инструменты

- python
- pandas
- numpy
- matplotlib
- scipy
- torch
- transformers
- torchvision
- `torch.nn`
- `torchvision.models.resnet18`
- `torchvision.models.ResNet18_Weights`
- `transformers.DistilBertModel`
- `transformers.DistilBertTokenizer`
- `torchvision.transforms`
- `google.colab.drive`
- `PIL.Image`
- `sklearn.model_selection.GroupShuffleSplit`
- `sklearn.preprocessing.StandardScaler`
- `from sklearn.dummy.DummyRegressor`
- `sklearn.linear_model.LinearRegression`, 
- `sklearn.linear_model.Ridge`
- `sklearn.linear_model.Lasso`
- `tensorflow.keras.models.Sequential`
- `tensorflow.keras.layers.Dense`
- `tensorflow.keras.optimizers.Adam`
- `tensorflow.keras.callbacks.EarlyStopping`
- `sklearn.metrics.mean_squared_error`
- `sklearn.metrics.mean_absolute_error`

## Общий вывод
- Выполнил выгрузку датафреймов с информацией, текстовыми описаниями и картинками из гугл-диска; 
- провёл EDA-анализ выведенных данных и ознакомился с картинками; 
- реализовал агрегированную метрику близости текста и изображения; 
- из тренировочных данных удалил запросы, которые нарушают юридические ограничения моего региона;
- векторизовал изображения с помощью архитектуры ResNet18;
- получил эмбеддинги текстовых запросов с помощью одной из модификаций модели `BERT`;
- объединил вектора изображений и текста для каждой записи;
- разделил тренировочный данные на train и validation, при это исключив попадание одного и того же изображения в обе выборки сразу;
- стандартизировал данные;
- выбрал лучшую модель на валидационных данных, после чего проверил ее результаты работы на тестовых данных; 
- сделал выводы по результатам модели и написал рекомендации для бизнеса и для улучшения качества модели.
