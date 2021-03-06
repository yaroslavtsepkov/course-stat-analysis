# Статистическое исследование данных abalone

## Результаты кореляционного анализа

**Диаграмма рассеивания случаных велечин**
![Диаграмма рассеивания случаных велечин](data/multinoraml-dist-scatterplot.svg)

- corr coeff: 0.9494664679963203

- real correlation: 0.9486832980505138

- diff: 0.0007831699458065167

- p-value: 0.0

**Диаграмма рассеивания длины морского ушка и диаметра**
![Диаграмма рассеивания длины морского ушка и диаметра](data/abalone-scatterplot.svg)

- corr coeff: 0.9868115846024836

- p-value: 0.0

## Результаты регрессионого анализа

**Диаграмма рассеивания и регрессионая модель случаных велечин**

![Диаграмма рассеивания и регрессионая модель случаных велечин](data/lineregressongendata.svg)

- slope: 2.0243767054704427

- intercept: -2.0185443865482906

- R_square: 0.25533339703923374

- p_value: 0.0

- std_err: 0.03457497636019418

**Диаграмма рассеивания и регрессионая модель длины и диаметра морского ушка**

![Диаграмма рассеивания и регрессионая модель морского ушка от диаметра](data/abalone-regression-model.svg)

- slope: 1.194168049239271

- intercept: 0.03691333759877169

- R_square: 0.973797103505684

- p_value: 0.0

- std_err: 0.00303163993093564

## Результаты кластерного анализа

**Диаграмма рассеивания случаных величин**

![Диаграмма рассеивания случаных величин](data/gendatascatterplot-03.svg)

**Кластеры и центры кластеров**

![Класстеры и центры кластеров](data/gendataclusters-03.svg)

**Диаграмма рассеивания по характеристи Sex данных морских ушек**

![Диаграмма рассеивания по характеристи Sex данных морских ушек](data/abalonebysex.svg)

**Кластеры и центры кластеров**

![Класстеры и центры кластеров](data/clusterabalonebysex.svg)

## Применение метода классификации KNN
**Трехмерная диаграма рассеивания для смоделированных данных** 
Разными цветами изображены разные классы
![Диаграмма](data/3dscatter-normal.svg)
accuracy score: 0.52

**Трехмерная диаграма рассеивания для abalone данных** 
![Диаграмма](data/3dscatter-abalone.svg)
accuracy score: 0.5126854954523695