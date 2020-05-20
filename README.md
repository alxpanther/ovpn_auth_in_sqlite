# ovpn_auth_in_sqlite
Script for storing OpenVPN users in SQLite.

# Получение справочной информации.
```python
./auth.py -h
usage: auth.py [-h] {init,uadd,act,pch,inf,auth-via-file} ...

positional arguments:
  {init,uadd,act,pch,inf,auth-via-file}
    init                Инициализация БД
    uadd                Добавление пользователя
    act                 Активация пользователя
    pch                 Смена пароля пользователя
    inf                 Информация о пользователе
    auth-via-file       Авторизация OpenVPN через файл

optional arguments:
  -h, --help            show this help message and exit
```

# Инициализация базы данных.
```python
./auth init
Инициализация БД прошла успешно!
```

# Добавление пользователя.
```python
./auth.py uadd myuser -a<br />
Введите пароль пользователя:<br />
Повторите пароль пользователя:<br /> 
Пользователь myuser успепшно добавлен!<br />
```
