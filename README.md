## Описание проекта Yatube:
Yatube — это платформа для блогов. Блог-сервис предполагает возможность зарегистрироваться, создать, отредактировать или удалить собственный пост, прокомментировать пост другого автора и подписаться на него.

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

`git clone git@github.com:ValentinSmir/api_final_yatube.git`

Cоздать и активировать виртуальное окружение:

`python -m venv venv`

`source venv/Scripts/activate`

Установить зависимости из файла requirements.txt:

`pip install -r requirements.txt`

Выполнить миграции:

`python manage.py migrate`

Запустить проект:

`python manage.py runserver`

## Примеры запросов:

Получение списка постов:

`GET /v1/posts/`

Создание нового поста:

`POST /v1/posts/`

`{`
`"text": "string",`
`"image": "string",`
`"group": 0`
`}`

Получение комментариев к посту:

`GET /v1/posts/1/comments/`

## Использованные технологии:
Работал с JWT-токеном при помощи библиотеки Djoser

## Информация об авторе:
Валентин Смирнов. Студент Яндекс Практикума.