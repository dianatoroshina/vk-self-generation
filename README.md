# vk-self-generation
Задача геоаналитики с генерацией train, test, features. Все датасеты были самостоятельно сгенерированы вручную.
### Зависимости, необходимые для запуска решения:
- Python
- Numpy
- Pandas
- Scikit-learn
- LightGBM
- Seaborn
- Matplotlib
- Joblib
### Запуск решения:
1. Запуск features.ipynb. Там содержится генерация признаков, их объединение, отбор самых важных признаков. Также добавление признаков о населении на основе координат местности (ссылка на данные - https://rosstat.gov.ru/compendium/document/13282). Сохранение обработанных данных.
2. Запуск train.ipynb. Обучение модели и её сохранение.
3. Запуск solution.ipynb. Там содержится генерация файла submission.csv путем загрузки обученной модели и использования её на test.csv
### Результаты:
Результаты работы представлены в файле submission.csv, а именно предсказание score объекта для test.csv
