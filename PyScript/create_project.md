## Создать проект.


Шаблон python проекта для быстрого создание любых проектов.
Останавливаем хаос и приводим вещи в порядок.
Делаем приятно себе и другим.

1. Структура python проекта.
	- точка входа
	- зависимости
	- описание
	- лицензия
2. Установить шаблон.
3. Практика. (Написать код).


[Шаблон проекта](https://github.com/repen/py-project)

[Полезные команды питона](https://pythonist.ru/instrumenty-komandnoj-stroki-iz-standartnoj-biblioteki-python-3/)


#### Однострочные питон скрипты

скачивает зип архив с гитхаба

python -c "from urllib.request import urlopen as u; d=u('https://github.com/repen/py-project/archive/refs/heads/master.zip').read();import sys;sys.stdout.buffer.write(d)" > py-project.zip

#### распаковать проект командой

python -m zipfile -e py-project.zip .


#### Бонус узнать внешний ip вашего пк

python -c "from urllib.request import urlopen as u; d=u('http://eth0.me').read();print(d)"