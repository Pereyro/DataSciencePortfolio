# Прогнозирование оттока клиентов телеком компании

[тетрадь проекта](https://github.com/Pereyro/DataSciencePortfolio/blob/master/CustomerChurnModel/customer_churn_model_notebook.ipynb)


## Описание проекта

Необходимо научиться прогнозировать отток клиентов оператора связи. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. На основании этих данных необходимо обучить несколько моделей и выбрать лучшую.

## Стек и инструменты
- Pandas
- Numpy
- Matplotlib
- Seaborn
- catboost
- sklearn.pipeline.Pipeline
- sklearn.compose.ColumnTransformer
- sklearn.preprocessing.OneHotEncoder
- sklearn.preprocessing.StandardScaler
- sklearn.model_selection.train_test_split
- sklearn.model_selection.cross_val_score
- sklearn.model_selection.GridSearchCV
- sklearn.metrics.roc_curve
- sklearn.metrics.roc_auc_score
- sklearn.metrics.confusion_matrix
- phik.phik_matrix
- phik.report.plot_correlation_matrix



## Вывод по проекту
Спрогнозировал отток клиентов для оператора связи.
В проекте использовал модели CatBoostClassifier и линейная регрессия из библиотеки scikit-learn.
Проанализировал признаки на дисбалланс и мультиколлениарность
Произвел анализ важности признаков и рассчитал матрицу ошибок
Добился значения целевой метрики AUC-ROC на тестовой выборке = 0.86
