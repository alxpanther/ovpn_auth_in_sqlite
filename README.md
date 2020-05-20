# ovpn_auth_in_sqlite
Script for storing OpenVPN users in SQLite.

# Получение справочной информации.<br />
./auth.py -h<br />
usage: auth.py [-h] {init,uadd,act,pch,inf,auth-via-file} ...<br />
<br />
<br />
positional arguments:<br />
  {init,uadd,act,pch,inf,auth-via-file}<br />
    init                Инициализация БД<br />
    uadd                Добавление пользователя<br />
    act                 Активация пользователя<br />
    pch                 Смена пароля пользователя<br />
    inf                 Информация о пользователе<br />
    auth-via-file       Авторизация OpenVPN через файл<br />
<br />
optional arguments:<br />
  -h, --help            show this help message and exit<br />
<br />
<br />
# Инициализация базы данных.<br />
./auth init<br />
Инициализация БД прошла успешно!<br />
<br />
<br />
# Добавление пользователя.<br />
./auth.py uadd myuser -a<br />
Введите пароль пользователя:<br />
Повторите пароль пользователя:<br /> 
Пользователь myuser успепшно добавлен!<br />

