Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

https://github.com/boreesych/kittygram_backend.git
cd kittygram_backend
Cоздать и активировать виртуальное окружение:

python -m venv env
source env/bin/activate
python -m pip install --upgrade pip
Установить зависимости из файла requirements.txt:

pip install -r requirements.txt
Выполнить миграции:

python manage.py migrate
Запустить проект:

python manage.py runserver