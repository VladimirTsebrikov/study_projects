Задачей проекта было построение модели для определения стоимости подержанного автомобиля по табличным данным, содержащим его характеристики. При этом, помимо качества предсказания (RMSE не ниже 2500), важны также скорость предсказания и время обучения модели.

При работе над проектом была проведена предобработка данных (удаление дубликатов, выбросов, заполнение пропусков).  Обучались модели `LGBMRegressor`, `CatBoostRegressor` и `RandomForestRegressor`, из которых `LGBMRegressor` показал наилучший результат по совокупности характеристик точности (RMSE=1569), скорости обучения и предсказания.

Использованные библиотеки: `pandas`, `sklearn`, `lightgbm`, `catboost`, `time`
