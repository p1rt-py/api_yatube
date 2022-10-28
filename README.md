API для социальной сети YaTube - https://github.com/p1rt-py/hw05_final.

Yatube - Это социальная сеть для блогеров. В которой реализована
авторизация на Django, работа с Базами Данных, создание индивидуальных страниц
пользователей. Создание постов, их оценка и возможность добавить комментарии.

Позволяет делать запросы к моделям проекта: Посты, Группы, Комментарии, Подписки.
Поддерживает методы GET, POST, PUT, PATCH, DELETE
Предоставляет данные в формате JSON

### Технологии:
- Python 3.8
- Django REST Framework 3.12.4
- Django 2.2.16
- Djangorestframework-simplejwt 4.7.2
- Pillow 8.3.1


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/p1rt-py/api_yatube
```

```
cd api_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source venv/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
