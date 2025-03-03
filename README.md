# django-dvertising-site

### Сайт на Django для рекламы 

## Стек
* Python 3.13+
* Django>=5.1.6
* python-dotenv

## Функционал
Данный сайт сделан для рекламы.

## Развертывание
* Клонируйте репозиторий - `git clone https://github.com/semenkulikov/django-avertising-site.git`
* Создайте и активируйте виртуальное окружение
* Установите необходимые зависимости командой `pip install -r requirements.txt`
* Заполните поля в файле .env.template, переименуйте его в .env
* Создайте базу данных - `python manage.py migrate`
* Примените миграции - `python manage.py makemigrations`
* Запустите сайт командой `python manage.py runserver`
* Для запуска на сервере проделайте вышеперечисленные шаги, вместо последнего создайте службу для запуска сайта и настройте ее соответственно.

