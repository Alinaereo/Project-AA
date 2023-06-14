# Поквитаемся с иви

Мы решили парсить данные с российской видиотеки Иви (интересный факт: теперь Иви пишется по-русски (ранее ivi))

Ссылка на сайт:
[ИВИ](https://www.ivi.tv/movies/all?ysclid=lh3kbxx7q6794249776)

## Описание проекта

Наш проект включает в себя следующие компоненты:

**Сбор данных**: 

В папке [parsing](https://github.com/Alinaereo/Project-AA/tree/main/parsing) вы можете найти следующие файлы:
  - [parsing](https://github.com/Alinaereo/Project-AA/blob/main/parsing/parsing.ipynb) код для выполнения парсинга данных. 
  - [project2](https://github.com/Alinaereo/Project-AA/blob/main/parsing/project2.csv): Файл с данными, полученными в результате парсинга сайта иви. (использовать для EDA)
  - [parsing.html](https://github.com/Alinaereo/Project-AA/blob/main/parsing/parsing.html) - файл с кодом для парсинга в формате html
  

**Анализ данных**: 

Папка [EDA]() содержит файлы, относящиеся к работе с данными:
  - `eda.ipynb`: Jupyter Notebook с проведением EDA. Провели предварительную обработку, визуализацию и добавили новые признаки
  - [project_dropped](https://github.com/Alinaereo/Project-AA/blob/main/EDA/project_dropped.csv) - файл с обработанными данными
  - [project_new_feature_year_class](https://github.com/Alinaereo/Project-AA/blob/main/EDA/project_new_feature_year_class.csv): файл с новыми признаком (использовать для машинного обучения и тестирования гипотез)

**Гипотезы**: 
- :тестируем наши гипотезы о собранных данных

**Машинное обучение**: 
- :обучаем модели предсказывать рейтинг и выявляем оптимальные метрики.

Возможность предсказывать рейтинг поможет как создателям (анализировать предпочтения зрителей и заранее определить успех проекта), так и зрителям (стоит ли идти на премьеру того или иного фильма)

## Авторы

- Глушенкова Алина Павловна
- Золотникова Ангелика Алексеевна

