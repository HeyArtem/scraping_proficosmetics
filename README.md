# Скрапинг ассортимента магазина "Галерея косметики"  <br/>www.proficosmetics.ru


![alt-текст](https://github.com/HeyArtem/UAI_lesson_15_tgbot_scraping/blob/master/picture_for_readme/main.png "Текст заголовка логотипа 1")



## Тех.детали: 
* _requests_
* _os_
* _BeautifulSoup_
* _json_
* _csv_
* _random_
* _time_
* _strip().  replace(). replace(),  join()_
<br/><br/>
<hr>

## Описание:
Скрипт делает запрос к сайту (я выбрал раздел шампуни), сохранит страницу, найдет блок с пагинацией и будет обращаться к каждой странице, через рандомные паузы.
<br/> Из каждой карточки товра будет собирать:
- наименование товара
- краткое описание
- стоимость
- ссылку на карточку

После этого запишет, собранную информацию:
- в json
- в csv 
<br/><br/>
<hr>

## Особенности:
Директория data создается автоматичесски, для сохранения первой страницы и собранной информации
<br/><br/>
<hr>

## Что бы запустить проект:
- создать директорию на компьютере
- открыть нужный репозиторий-Code-HTTPS-скопировать ссылку
```
$ git clone + ссылка
```
- перейти в паку с проектом

```
$ python3 -m venv venv -создать виртуальное окружение
```

```
$ source venv/bin/activate -активировать виртуальное окружение 
```

```
$ pip install -U pip setuptools 
```

```
$ pip install -r requirements.txt -установить библиотеки из requirements.txt 
```

```
$ code . -открыть проект в VS Code
```

- Возможно потребуются свежие headers (www.proficosmetics.ru)
<br/><br/>
<hr>
