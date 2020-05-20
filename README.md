# ovpn_auth_in_sqlite
Script for storing OpenVPN users in SQLite.

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

./auth init
Инициализация БД прошла успешно!

./auth.py uadd myuser -a  
Введите пароль пользователя: 
Повторите пароль пользователя: 
Пользователь myuser успепшно добавлен!

