# Api_final
## Описание проекта:
API для социальной сети YATUBE, позволяющий публиковать посты, создавать комментарии, вступать в группы, а также подписываться на других авторов.

## СТЕК технологий:
* Python == 3.10.12
* Django == 3.2.16
* Django Rest Framework == 3.12.4
* Djangorestframework-simplejwt == 4.7.2

## Описание возможностей:
- Реализован CRUD для публикаций и комментариев к публикациям.
- Можно подписываться на интересующего автора поста, а также отслеживать список подписок.
- Кроме того, было реализовано получение, обновление и проверка JWT-авторизации.

## Документация API:
Документация проекта представлена в формате Redoc и после запуска проекта будет доступна по адресу `http://127.0.0.1:8000/redoc/`.

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```sh
git clone git@github.com:FeodorPyth/api_final_yatube.git
```

```sh
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```sh
python3 -m venv env
```

```sh
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```sh
python3 -m pip install --upgrade pip
```

```sh
pip install -r requirements.txt
```

Выполнить миграции:

```sh
python3 manage.py migrate
```

Запустить проект:

```sh
python3 manage.py runserver
```

## Автор:
[FeodorPyth](https://github.com/FeodorPyth)
