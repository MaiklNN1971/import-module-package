Домашнее задание к лекции 1.«Import. Module. Package»

    Разработать структуру программы "Бухгалтерия".

    main.py;
    директория application:
    -- salary.py;
    -- директория db:
    --- people.py;
    main.py - основной модуль для запуска программы.
    В модуле salary.py функция calculate_salary.
    В модуле people.py функция get_employees.

    Импортировать функции в модуль main.py и вызывать эти функции в конструкции.

if __name__ == '__main__':

Сами функции реализовать не надо. Достаточно добавить туда какой-либо вывод.

    Познакомиться с модулем datetime. При вызове функций модуля main.py выводить текущую дату.

*4. Создать рядом с файлом main.py модуль dirty_main.py и импортировать все функции с помощью конструкции (необязательное задание)

from package import *

Домашнее задание сдается ссылкой на репозиторий BitBucket или GitHub

Не сможем проверить или помочь, если вы пришлете:

    архивы;
    скриншоты кода;
    теоретический рассказ о возникших проблемах.

