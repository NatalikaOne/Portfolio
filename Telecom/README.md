# Прогнозирование оттока клиентов телеком компании
## Описание проекта
Оператор связи хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, оператору нужна модель, которая будет предсказывать, разорвёт ли абонент договор. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и услугах.

Задача — обучить модель для прогноза оттока клиентов.

## Навыки и инструменты
python
pandas
numpy
statsmodels.tsa.seasonal.seasonal_decompose
sklearn.model_selection.TimeSeriesSplit
sklearn.model_selection.GridSearchCV
sklearn.metrics.mean_squared_error
sklearn.metrics.make_scorer
sklearn.linear_model.LinearRegression
sklearn.ensemble.RandomForestRegressor
sklearn.tree.DecisionTreeRegressor
catboost.CatBoostRegressor
lightgbm
matplotlib

## Общий вывод
Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование трёх типов моделей, выбрана линейная регрессия.
