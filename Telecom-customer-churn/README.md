# Прогноз количества заказов для сервиса такси

[ipynb](https://github.com/EktTitova/Projects/blob/main/Taxi-time-forecast/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82_%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5_%D1%80%D1%8F%D0%B4%D1%8B.ipynb)

## Описание проекта

Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**GridSearchCV**
- sklearn.linear_model.**LinearRegression**
- **LGBMRegressor**
- **matplotlib**

## 

## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование двух типов моделей, выбран градиентный бустинг.
