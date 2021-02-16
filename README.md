# DS
## [Face mask detection](https://github.com/SemyonPolytechnic/DS/tree/main/Face%20mask%20detection)
- [1. Data Preprocessing](https://github.com/SemyonPolytechnic/DS/blob/main/Face%20mask%20detection/1.%20Data%20Preprocessing.ipynb)
На данном этапе из датасета [face-mask-detection](https://www.kaggle.com/andrewmvd/face-mask-detection) были вырезаны все ограничивающие области лиц, из которых был сформирован новый датасет, на котором на следующем шаге обучалась и тестировалась модель. Исходный набор данных содержал 3 класса, но в связи с тем, что данных о неправильном ношении маски было недостаточно, было принято решение свести задачу к бинарной классификации с классами "с маской" и "без маски".
- [2. Face mask classifier](https://github.com/SemyonPolytechnic/DS/blob/main/Face%20mask%20detection/2.%20Train%20and%20validation.ipynb)
  На данном этапе была обучена нейронная сеть на основе архитектуры ResNet50 и удалось добиться качества 0.93 по метрике F1-score (precision = 0.88, recall = 1.0) на тестовой выборке.
  
 ![Результаты](https://github.com/SemyonPolytechnic/DS/blob/main/Face%20mask%20detection/result.png)
