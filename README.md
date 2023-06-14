# Поквитаемся с иви

Мы решили парсить данные с российской видиотеки Иви \
(интересный факт: теперь Иви пишется по-русски (ранее ivi))

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
  - [EDA](https://github.com/Alinaereo/Project-AA/blob/main/EDA/EDA.ipynb): Jupyter Notebook с проведением EDA. Провели предварительную обработку, визуализацию и добавили новые признаки
  - [EDA](https://github.com/Alinaereo/Project-AA/blob/main/EDA/EDA.html): файл с кодом в формате html
  - [project_dropped](https://github.com/Alinaereo/Project-AA/blob/main/EDA/project_dropped.csv) - файл с обработанными данными
  - [project_new_feature_year_class](https://github.com/Alinaereo/Project-AA/blob/main/EDA/project_new_feature_year_class.csv): файл с новыми признаками (использовать для машинного обучения и тестирования гипотез)

**Гипотезы**: 
- [hypotheses](https://github.com/Alinaereo/Project-AA/blob/main/hypotheses/hypotheses.ipynb): тестируем наши гипотезы о собранных данных
- [hypotheses](https://github.com/Alinaereo/Project-AA/blob/main/hypotheses/hypotheses.html): файл кода в формате html

**Машинное обучение**: 

В папке [ML](https://github.com/Alinaereo/Project-AA/tree/main/ML) содержатся файлы по машинному обучению:
- [machine_learning](https://github.com/Alinaereo/Project-AA/blob/main/ML/machine_learning.ipynb): обучаем модели предсказывать рейтинг и выявляем оптимальные метрики.
- [machine_learning.html](https://github.com/Alinaereo/Project-AA/blob/main/ML/machine_learning.html) - файл кода c машиннsv обучением в формате html

machine_learning

Возможность предсказывать рейтинг поможет как создателям (анализировать предпочтения зрителей и заранее определить успех проекта), так и зрителям (определять стоит ли идти на премьеру того или иного фильма)

## Авторы

- Глушенкова Алина Павловна
- Золотникова Ангелика Алексеевна

