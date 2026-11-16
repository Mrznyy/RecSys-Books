# RecSys Books

Рекомендательная система для книг на датасете Goodreads.

## Структура

├── data/  
│ ├── books.csv    
│ ├── ratings.csv  
│ ├── tags.csv  
│ └── book_tags.csv  
└── RecSys_Books.ipynb  

## Данные

Положите четыре CSV-файла в папку `data/` рядом с ноутбуком. Ожидаемые колонки:

- `ratings.csv` 
- `books.csv` 
- `tags.csv` 
- `book_tags.csv` 

## Запуск

Откройте `RecSys_Books.ipynb` в Jupyter предварительно скачав папку data с датасетами и выполните ячейки по порядку. 

## Содержание ноутбука

1. EDA: распределение оценок, активность пользователей и книг.
2. Baseline-модели: глобальное среднее, средняя оценка пользователя.
3. Item-Based CF.
4. Матричные разложения (SVD через `surprise`).
5. Оценка качества: RMSE, Precision@K, Recall@K, nDCG@K.
6. Гибридный подход против холодного старта.

