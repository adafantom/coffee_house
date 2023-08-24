# Ближайшие Кофейни Москвы

Программа отрисовывает карту Москвы с геопозицией пользователя и показывает ближайшие пять кофеен.

## Среда
### Требования
Python3 уже должен быть установлен. Используйте pip(или pip3, если есть конфликт с Python2) для установки зависимостей

Должна быть установлены библиотеки

```bush
pip install json
pip install requests
pip install geopy 
pip install folium
pip install flask
```

## Запуск
Запуск в Linux(Python 3) или Windows:

```bush
$ python main.py
```

Для получения API используется [Yandex geocoder API](https://dvmn.org/encyclopedia/api-docs/yandex-geocoder-api/)


Программа запрашивает местоположение пользователя и открывает для него карту с метками


## Цели проекта
Этот код был написан в образовательных целях как часть онлайн-курса для python-разработчиков на [Devman](dvmn.org)
