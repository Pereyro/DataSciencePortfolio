# Предсказание коэффициента восстановление золота из руды

[тетрадь проекта](https://github.com/Pereyro/DataSciencePortfolio/blob/master/GoldRecovery/gold_recovery_notebook.ipynb)


## Описание проекта


Восстановление золота из руды

Необходимо подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды, используя данные с параметрами добычи и очистки.

Модель должна помочь оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Стек и инструменты
- Pandas
- Numpy
- Matplotlib
- Seaborn
- sklearn.linear_model.LinearRegression
- sklearn.linear_model.Lasso
- sklearn.ensembleRandomForestRegressor
- sklearn.model_selection.train_test_split
- sklearn.model_selection.cross_val_score
- sklearn.preprocessing.StandardScaler
- sklearn.metrics.mean_squared_error
- sklearn.metrics.mean_absolute_error
- sklearn.metrics.make_scorer



## Вывод по проекту
Обучил модель для предсказания коэффициента восстановления золота из золотосодержащей руды на стадиях грубой и тонкой очистки.
Использовал следующие модели библиотеки SciKit-learn:
  - Random Forest
  - Lasso
  - Модель линейной регрессии
По результатам лучшей оказалась модель RandomForestRegressor
