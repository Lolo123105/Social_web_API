**REST API социальной сети YaTube (Яндекс.Практикум)**
=====

**Описание проекта**
----------
Проект создан в рамках учебного курса Яндекс.Практикум.

**Стек технологий**
----------
* Python 3.9
* Django 3.2 
* Django Rest Framework
* Pytest
* Simple-JWT
* SQLite3

1. Клонировать репозиторий и перейти в него через командную строку:
```bash
git clone git@github.com:Lolo123105/api_final_yatube.git

cd api_final_yatube
```
2. Cоздать и активировать виртуальное окружение:
```bash
python3.9 -m venv venv

source venv/bin/activate
```
3. Обновить _pip_ и установить зависимости из файла ```requirements.txt```:
```bash
pip install --upgrade pip

pip install -r requirements.txt
```
4. Выполнить миграции:
```bash
cd yatube_api

python3.9 manage.py migrate
```
5. Запустить проект (в режиме сервера Django):
```bash
python3.9 manage.py runserver
```
**Документация к проекту**
----------
Документация для API после установки доступна по адресу ```/redoc/```.