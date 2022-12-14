Набор данных содержит почасовой и ежедневный подсчет проката велосипедов в период с 2011 по 2012 год в системе проката велосипедов Capital в Вашингтоне, округ Колумбия, с соответствующей информацией о погоде и сезоне.

**Задание**:
Вы должны предсказать oбщее количество арендованных велосипедов (сount) в течение каждого часа, охваченного тестовым набором, используя только информацию, доступную до периода аренды.

**В результате**:

1) Из трёх вариантов моделей (RandomForestRegressor, DecisionTreeRegressor и LinearRegressor) отобрана наиболее оптимальная - RandomForestRegressor с {'max_depth': 25, 'n_estimators': 800}

2) Полученные усреднённые (после кросс-валидации) метрики ошибок :

*MAE*: 62.9

*RMSE*: 88.8

3) Полученную модель можно использовать для прогнозов выручки компании (используя соответствующую погрешность), анализу недостающих единиц велосипедов на точках (неудовлетворенность спроса), а также для разработки раздела приложения, сообщающего пользователям в каких точках ожидается нехватка велосипедов (чтобы пользователи могли спланировать свой маршрут заранее).

4) Получены предсказания кол-ва арендованных велосипедов для тестовой выборки.
