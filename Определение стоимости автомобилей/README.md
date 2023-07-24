# Определение стоимости автомобилей


[ipynb](https://clck.ru/355oNk)

## Описание проекта

Требуется предсказать рыночную стоимость автомобиля используя исторические данные сервиса по продаже авто: технические характеристики, комплектации и цены автомобилей.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- **re**
- **scipy**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.compose.**make_column_transformer**
- sklearn.metrics.**mean_squared_error**
- sklearn.preprocessing.**StandardScaler**
- sklearn. preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.neighbors.**KNeighborsRegressor**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**
- **matplotlib**

## 

## Общий вывод

Проведено исследование признаков, выявлены и удалены аномалии. Проведено исследование трёх типов моделей, выбрана CatBoostRegressor.
