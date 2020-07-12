# VK Tinder

С помощью данного скрипта можно находить новых людей в VK.

На вход программа принимает токен для доступа к VK (если токена нет, есть возможность его получить с помощью данного скрипта) и параметры для поиска (страна, город, пол, диапазон возраста).

На выходе пользователь получает json-файл со списком из 10 пользователей, у каждого из которых есть ссылки на 3 фотографии профиля с наибольшим количеством лайков (в выборку попадают только пользователи с загруженными фотографиями профиля; при меньшем количестве фотографий будут предоставлены ссылки на них).
Полученные данные хранятся в базе данных Mongo, есть возможность при желании "пролистать" на следующие 10 результатов поиска и далее, при наличии.

Код выполнен с использованием VK API и библиотек:
- requests;
- time;
- json;
- alive_progress;
- urllib.parse;
- pymongo.

Код соответствует PEP8.