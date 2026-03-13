# Лабораторная работа №2

## Доступ к атрибутам и защита модели

## Структура проекта
Laba2_task
 <pre>
 ├── src/ # 
 │ ├── init.py # Инициализация 
 │ ├── Task.py # Модель задачи в виде dataclass
 │ ├── TaskSource.py # Протокол источника задач
 │ ├── FileTaskSource.py # Источник задач из файла
 │ ├── GeneratorTaskSource.py # Генератор задач
 │ ├── APITaskSource.py # API-заглушка
 │ ├── descriptors.py #Дескрипторы
 │ ├── exceptions.py # Исключения
 │ └── main.py # точка входа в программу
 │
 ├── tests/ # Тесты
 │ ├── init.py # Инициализация тестов
 │ ├── test.py # Тесты 
 ├── .gitignore 
 ├── .pre-commit-config.yaml
 ├── pyproject.toml
 ├── README.md
 ├── requirements.txt
 ├── tasks.json 
 └── uv.lock
  </pre>
## Все вроде сделано,а именно ДатаДескрипторы НонДатаДескриптор, использование property,предотвращение некорректных состояний объекта
## Тесты 86%
<img width="734" height="218" alt="image" src="https://github.com/user-attachments/assets/45035110-024f-4272-a2be-7789f015dbe8" />

## Установка 
 ```bash
 $ python -m venv venv
 $ source venv/bin/activate
 
 $ pip install requirements.txt
 $ python -m src.main
```
