# Определение уровеня сложности языка фильма по субтитрам

## Описание проекта
Требуется определить уровень английского языка в фильме на языке оригинала для того, чтобы студент мог выбрать фильм, который подходит ему по уровню сложности.

## Навыки и инструменты
- python
- pandas
- numpy
- sklearn.model_selection.train_test_split
- sklearn.model_selection.GridSearchCV
- sklearn.feature_extraction.text.TfidfVectorizer
- sklearn.linear_model.LinearRegression
- sklearn.ensemble.RandomForestClassifier, GradientBoostingClassifier
- sklearn.tree.DecisionTreeRegressor
- catboost.CatBoostClassifier
- LGBMClassifier

## Общий вывод
Обработала исходные данные и собрала в один Датафрейм, обработала субтитры, провела лематизацию. 
Исследовала четыре модели, выбрала LogisticRegression.
