# Kittygram — социальная сеть для обмена фотографиями котиков и кошечек.

![workflow](https://github.com/AleksandraStechenko/kittygram_final/actions/workflows/main.yml/badge.svg)

## Описание
Kittygram - это та самая социальная сеть, которой нам всем так не хватало.<br>
Возможности проекта: можно зарегистрироваться и авторизоваться, добавить нового котика на сайт или изменить существующего, а также просмотреть записи других пользователей. <br>
<b>Это полностью рабочий проект, который состоит из бэкенд-приложения на Django и фронтенд-приложения на React. </b>


## Используемые технологии:

* Python
* Django
* Django REST Framework
* React
* PostgreSQL
* Nginx
* Docker
* Gunicorn
* Github actions


## Как запустить проект
1. Склонируйте репозиторий:  
``` git clone git@github.com:AleksandraStechenko/kittygram_final.git```    
2. Установите и активируйте виртуальное окружение:  
``` python3 -m venv env ```  
* Если у вас Linux/macOS 
``` source env/bin/activate ```
* Если у вас windows
``` source env/scripts/activate ```
3. Установите зависимости из файла requirements.txt:
``` python3 -m pip install --upgrade pip ```
``` pip install -r requirements.txt ```
4. Примените миграции:
``` python3 manage.py migrate ```
6. Запустить проект:
``` python3 manage.py runserver ```

## Как заполнить env
- Создать .env с переменными окружения
- Пример .env.example.

Веб-приложение будет доступно по адресу:
```
http://localhost:9000/
```

### Автор проекта:

- [Александра Стеченко](https://github.com/AleksandraStechenko)