# tmdb_api
# Упражнение на чтение кода. Фильмы с TMDB
#### Данны проект представляет собой следующее:
# папка gitignore 
### содержит, то, что git не должен принимать вовнимание.
# папка LICENSE
### описывает принципы распространения и пользования програмным кодом
# find_similar
### Здесь происходит общение  пользователя с программой. У пользователя запрашивается адрес сайта, который выступит базой данных фильма, а также название самого фильма. Далее запускается функция которая ищет фильм на предложенном сайте, который выступает хранилищем. Если фильма нет, то программа закроется. Если же фильм есть, то запускается другая функция, где происходит предложение похожего фильма. При этом используются 4-е критерия похожести.  
# hello_api_TMDB
### Начальный файл, где проверяется Ключ апи пользователя.
# make_own_db
### Здесь идет создание базы данных из тысячи фильмов. Фильмы помещаються в словарь. Который потом сохраняется в формате json
# own_db_helpers
### Происходит чтение файла записанного предыдущей функцией. О фильмах по-очереди выводиться информация о фильмах.
# requirements
### Файлик о хранимой версии "requests"
# search_in_db
### ИСпользуя сформированную фазу данных пользователю выдается запрошенный фильм, если таковой имеется. Программа запрашивает путь к базе данных и часть названия фильма. 
# tmdb_helpers
### Здесь содержатся функции к которым обращаються другие разделы программы
### Запрос у пользователя ключа в методе get_user_api_key()
### Проверка ключа на правильность и возврат ответа make_tmdb_api_request(), load_json_data_from_url
### Предварительно идет подключение необходимых библиотек

