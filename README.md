# Heart Disease Prediction

Этот проект включает в себя сравнение различных классификационных моделей для предсказания сердечно-сосудистых заболеваний на основе набора данных. В качестве моделей используются дерево решений, бэггинг и случайный лес.

## Описание

Цель проекта — провести анализ и оценку нескольких машинных моделей для классификации пациентов с сердечно-сосудистыми заболеваниями. В рамках этого проекта были использованы следующие шаги:

1. Загрузка и подготовка данных.
2. Обучение и оценка нескольких классификационных моделей: дерева решений, бэггинга и случайного леса.
3. Сравнение моделей с использованием метрик качества (точность, точность предсказания, полнота, F1-меры).
4. Визуализация результатов.
5. Построение ROC-кривой для лучшей модели (случайного леса).

## Датасет

Датасет используется для классификации сердечно-сосудистых заболеваний и был взят с [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

- **Источник**: [Heart Disease Dataset на Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Датасет содержит информацию о пациентах, включая такие признаки, как возраст, пол, уровень холестерина и другие, и предназначен для предсказания наличия или отсутствия сердечно-сосудистых заболеваний.

## Структура данных

1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

Для запуска этого проекта необходимо установить следующие библиотеки:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
