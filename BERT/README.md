# Описание проекта

Этот проект представляет собой реализацию модели классификации текста с использованием предварительно обученной модели BERT. Код написан на языке программирования Python и использует библиотеки PyTorch, Transformers и другие.

## Структура проекта


- `BERT/`: Папка с кодом проекта.
  - `DZ_BERT.ipynb`: Jupyter Notebook с кодом проекта.
  - `data/`: Папка для хранения данных.

## Инструкции по запуску

1. Убедитесь, что у вас установлены все необходимые библиотеки.
2. Откройте `DZ_Bert.ipynb` в Jupyter Notebook или другой среде разработки.
3. Запустите код ячейка за ячейкой, следуя комментариям и инструкциям в ноутбуке.

## Обучение модели

1. Модель обучается на данных, предварительно обработанных и токенизированных с использованием BERT.
2. Во время обучения выводятся результаты, включая потери и точность.

## Оценка модели

1. После обучения модели выполняется оценка на валидационном наборе данных.
2. Выводятся результаты, такие как AUC-ROC и точность.
