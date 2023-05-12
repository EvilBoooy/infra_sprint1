### Описание проекта:

Проект Kittygram создан для того, чтобы хозяева могли делиться своими котиками.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/EvilBoooy/infra_sprint1.git
```

```
cd infra_sprint1
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
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

### Примеры запросов:

Главная страница с котиками:

'
https://infra.servebeer.com/
'

Добавить котика:

'
https://infra.servebeer.com/cats/add
'

Посмотреть конкретного котика:

'
https://infra.servebeer.com/cats/{cat_id}
'

Редактирование поста о котике:

'
https://infra.servebeer.com/cats/edit
'
