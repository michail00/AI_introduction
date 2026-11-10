[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michail00/AI_introduction/blob/main/lab1/notebooks/lab1.ipynb)


Таблица пункта 9:

| | VS Code | Colab |
|---|---|---|
| Версия Python |3.12.14 |3.13.18 |
| Версия pandas |3.1.1 |2.2.3 |
| Где хранятся файлы |Локально |На удаленном сервере |
| Что потребовалось для запуска |Пришлось установить все локально: VS Code, Python, окружения и библиотеки |Браузер, стабильное интернет соединение, аккаунт google, подключение к среде выполнения|


# Практическое занятие 1. Рабочее окружение

Автор: Подольский Михаил Александрович, группа 251-952

## Структура папки lab1

Папка data содержит данные, папка notebooks – ноутбук lab1.ipynb, файл requirements.txt – список библиотек.

## Запуск на локальном компьютере

В папке lab1:

1. Создать окружение: python -m venv .venv
2. Включить окружение: .venv\Scripts\activate (macOS и Linux: source .venv/bin/activate)
3. Установить библиотеки: pip install -r requirements.txt
4. Открыть notebooks/lab1.ipynb в VS Code и выбрать ядро .venv