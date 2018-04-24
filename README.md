# Оптимизация контейнеров

## Установка
* Установить системные зависимости
  ## With pip (recomended)

  `pip install pipenv`

  ## With brew

  `brew install pipenv`


  ## Ubuntu

  ```
  apt update
  apt install redis-server
  ```

  ## MacOS

  ```
  brew install redis
  ```
* Установить python зависимости: `pipenv install`

## Запуск

### Подготовка
* Удостовериться, что redis-server запущен: `service redis start`
* Запустить виртуальное окружение: `pipenv shell`

### Обучение
Для старта выполнить: `python train.py`  
Все данные о состоянии симуляции отправляются в redis (в JSON формате)

### Frontend
Запуск frontend'a: `cd frontend && python app.py`  
Frontend запустится на localhost:5000
