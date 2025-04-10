# api_final
api final
# api_final_yatube

Проект представляет собой REST API для социальной сети Yatube. С помощью него можно работать с публикациями, комментариями, подписками и сообществами. Аутентификация осуществляется через JWT-токены.

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```bash
git clone https://github.com/zumassh/api_final_yatube.git
cd api_final_yatube
```

Создать и активировать виртуальное окружение:

```bash
python -m venv env
```

Для Windows:

```bash
env\Scripts\activate
```

Для Linux/macOS:

```bash
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Выполнить миграции:

```bash
python manage.py migrate
```

Запустить проект:

```bash
python manage.py runserver
```

## Документация API

Документация доступна по адресу:

```
http://localhost:8000/redoc/
```