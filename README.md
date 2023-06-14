# Поквитаемся с иви

Мы решили парсить данные с российской видиотеки Иви (интересный факт: теперь Иви пишется по-русски (ранее ivi))

Ссылка на сайт:
[ИВИ](https://www.ivi.tv/movies/all?ysclid=lh3kbxx7q6794249776)

## Описание проекта

Наш проект включает в себя следующие компоненты:

- **Сбор данных**: 
В папке [parsing](https://github.com/Alinaereo/Project-AA/tree/main/parsing) вы можете найти следующие файлы:
  - код для выполнения парсинга данных.
  - [project2.csv](https://github.com/Alinaereo/Project-AA/blob/main/parsing/project2.csv): Файл с данными, полученными в результате парсинга сайта иви. 

- **EDA**: Эта папка содержит файлы и скрипты, относящиеся к анализу данных.
  - `eda.ipynb`: Jupyter Notebook с проведением EDA. Провели предварительную обработку, визуализацию и добавили новые признаки
  - : файл с обработкой и новыми признаками для дальнешей работы

- **Гипотезы**: 
- :тестируем наши гипотезы о собранных данных

- **Машинное обучение**: 
- :обучаем модели предсказывать рейтинг и выявляем оптимальные метрики
Возможность предсказывать рейтинг поможет как создателям (анализировать предпочтения зрителей и заранее определить успех проекта), так и зрителям (стоит ли идти на премьеру того или иного фильма)

## Авторы

- Глушенкова Алина Павловна
- Золотникова Ангелика Алексеевна

