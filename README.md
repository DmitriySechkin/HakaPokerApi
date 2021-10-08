Используем докер для запуска Redis

$ docker run -p 6379:6379 -d redis:2.8


## Скачивание и установка зависимостей python
1. git clone _url_ _target directory_  - клонирование проекта с гитхаб
2. python -m venv venv  - установка окружения
3. cd venv/Scripts/activate.bat - активация оружения
4. переодим в папку проекта
6. pip install -r requirements.txt  - установка зависимостей python
7. python manage.py makemigrations - создание миграций для базы данных
8. python manage.py migrate - создание таблиц в базе данных
9. python manage.py runserver - запуск проекта на локал хосте http://127.0.0.1:8000 
10. api url - http://127.0.0.1:8000/v1/rooms/

