# Проект: «Восстановление золота из руды»
В нашем распоряжении сырые данные золотодобывающей компании. Необходимо подготовить прототип модели машинного обучения. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды, что в итоге поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

**Цели:**

1. Подготовить данные;
2. Провести исследовательский анализ данных;
3. Построить и обучить модель.

**Выводы:**


Для достижения поставленной цели было изучено и смоделировано три алгоритма регрессии:

- RandomForestRegressor;
- KNeighborsRegressor;
- LinearRegression.

В качестве метрики оценки производительности алгоритма была введена метрика *sMAPE* — «симметричное среднее абсолютное процентное отклонение». По смыслу она схожа с *MAE*, однако выражается не в абсолютных величинах, а в относительных. Также она способна одинаково учитывать масштаб и целевого признака, и предсказания.

В результате проведенного исследования лучшие результаты *sMAPE*, 7.854, показала модель *RandomForestRegressor*.
