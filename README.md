# Прикладные системы и фреймворки искусственного интеллекта

| Фамилия Имя     |      Группа |
|:----------------|------------:|
| Федоров Алексей | М8О-409Б-22 |


## Данные
1. Классификация: [COVID-19 Dataset](https://www.kaggle.com/datasets/meirnizri/covid19-dataset)
2. Регрессия: [Medical Insurance Cost Prediction](https://www.kaggle.com/datasets/rahulvyasm/medical-insurance-cost-prediction)

Скачанные датасеты расположены в папке [datasets](datasets).

## Лабораторные работы
Выполненные работы расположены в папке [notebooks](notebooks).

## Лучшие метрики

### Классификация
| ЛР | Accuracy               | Precision              | Recall                                  | F1                                      | ROC AUC                         |
|----|------------------------|------------------------|-----------------------------------------|-----------------------------------------|---------------------------------|
| 1  | 0.9425 (custom_knn)    | 0.6765 (custom_knn)    | 0.4572 (tuned_knn)                      | 0.5296 (baseline_knn)                   | 0.9119 (custom_knn)             |
| 2  | 0.9442 (custom_logreg) | 0.6701 (custom_logreg) | 0.8954 (baseline_logreg / tuned_logreg) | 0.5562 (baseline_logreg / tuned_logreg) | 0.9575 (custom_logreg)          |
| 3  | 0.9380 (custom_tree)   | 0.5911 (custom_tree)   | 0.8980 (tuned_tree)                     | 0.5353 (tuned_tree)                     | 0.9266 (tuned_tree)             |
| 4  | 0.9349 (baseline_rf)   | 0.5554 (baseline_rf)   | 0.8124 (tuned_rf)                       | 0.5951 (tuned_rf)                       | 0.9572 (custom_rf)              |
| 5  | 0.9488 (baseline_gb)   | 0.7949 (custom_gb)     | 0.5013 (tuned_gb)                       | 0.5853 (tuned_gb)                       | 0.9619 (baseline_gb / tuned_gb) |

### Регрессия
| ЛР | MAE                     | RMSE                        | R2                                                   |
|----|-------------------------|-----------------------------|------------------------------------------------------|
| 1  | 784.4997 (tuned_knn)    | 3125.5939 (tuned_knn)       | 0.9363 (tuned_knn)                                   |
| 2  | 4160.2467 (tuned_reg)   | 6319.2717 (baseline_linreg) | 0.7398 (baseline_linreg / tuned_reg / custom_linreg) |
| 3  | 583.6016 (tuned_tree)   | 2787.6640 (baseline_tree)   | 0.9494 (baseline_tree)                               |
| 4  | 1299.5759 (baseline_rf) | 2745.0525 (tuned_rf)        | 0.9509 (tuned_rf)                                    |
| 5  | 1449.1698 (tuned_gb)    | 2895.1825 (tuned_gb)        | 0.9454 (tuned_gb)                                    |


## Мемы
(а почему бы и да)\
<img src="images/3.jpg" width="500px">
<img src="images/4.jpg" width="500px">
<img src="images/2.jpg" width="500px">
<img src="images/1.jpg" width="500px">