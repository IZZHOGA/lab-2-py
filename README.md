# lab-2-py
Задание Разработать веб-форму (HTML+PHP) для запроса имени пользователя и пароля из базы данных (MySQL). Пароль состоит из цифр от 1 до 5.

Написать скрипт на языке Python, который создаёт список возможных паролей и использует brute force атаку чтобы зайти от имени пользователя

Ход работы В ходе работы была разработана веб-форма ввода логина и пароля. При отправке формы осуществляется post-запрос на страницу login.php, где в случае верного ввода логина и пароля, пользователю сообщается правильный пароль.

В части программы подбора выступает код на языке Python. Он содержит следущие функции:

-Функция создания словаря паролей (word_create)

-Функция брутфорса (brute_force)

-Функция создания графика на основе полученных данных (plt)

Запуск окружения Для запуска лабораторной среды нужно ввести команду docker-compose up, находясь в папке server.
