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
