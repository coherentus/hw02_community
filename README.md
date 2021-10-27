# Яндекс.Практикум

# курс Python-разработчик

## студент  Ковылин Василий

## Учебный проект sprint_3  Знакомство с фреймворком Django.

***

Шаблоны и структура проекта заданы.

Задание проекта:

* Создано и зарегистрировано приложение Posts.
 
* Подключена база данных.
 
* Десять последних записей выводятся на главную страницу.

* В админ-зоне доступно управление объектами модели Post: можно публиковать новые записи или редактировать/удалять существующие.

* Пользователь может перейти на страницу любого сообщества, где отображаются десять последних публикаций из этой группы.

***

Разворачивание проекта:

Клонировать репозиторий и перейти в его папку в командной строке:

```
git clone https://github.com/coherentus/hw02_community
```

```
cd https://github.com/coherentus/hw02_community
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

Для *nix-систем и MacOS:

```
source venv/bin/activate
```

Для windows-систем:

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip

pip install -r requirements.txt
```

Выполнить миграции:

```
cd yatube_api
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

Создать суперпользователя Django:

```
python3 manage.py createsuperuser
```

Сам проект и админ-панель по адресам:

```
http://127.0.0.1:8000

http://127.0.0.1:8000/admin
```

***
