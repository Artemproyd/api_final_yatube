# API социальной сети "Yatube"

Описание проекта
----------
Разработан API для проекта социальной сети. Реализована возможность добавления, 
удаления и изменения постов и комментариев. Настроена пагинация, пермишены.
### **Использованные технологии**

| программа                     | версия |
|-------------------------------|--------|
| Django                        | 3.2.16 |
| pytest                        | 6.2.4  |
| pytest-pythonpath             | 0.7.3  |
| pytest-django                 | 4.4.0  |
| djangorestframework           | 3.12.4 |
| djangorestframework-simplejwt | 4.7.2  |
| Pillow                        | 8.3.1  |
| PyJWT                         | 2.1.0  |
| requests                      | 2.26.0 |
| djoser                        | 2.1.0  |


### **Запускаем проект в dev режиме на OC Linux**
Клонировать репозиторий с GitHub
```
git clone git@github.com:boginskiy/api-Yatube.git
```

Установить виртуальное окружение venv
```
python3 -m venv venv
```

Aктивировать виртуальное окружение venv
```
source venv/bin/activate
```

Обновить менеджер пакетов pip
```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt
```
pip install -r requirements.txt
```

Выполнить миграции
```
python3 manage.py migrate
```

Запустить проект
```
python3 manage.py runserver
```

### **Автор**
[Пройдаков_Артём](https://github.com/Artemproyd)