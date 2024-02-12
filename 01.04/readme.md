ЛК 15.01
gitbash - это команды для работы с гид из терминала

![bash](https://github.com/Hottabik/6semestr/assets/113089655/b7031917-6ab5-495c-b330-3c6ce41dbfe5)

создание репозитория на компьюторе: инициализация

![1](https://github.com/Hottabik/6semestr/assets/113089655/64d71d54-65a9-4a44-8f36-2a320f053a7e)

$ git status
On branch main
указывает имя ветки
No commits yet
нет сохранений
Untracked files: - неотслеживаемые файлы 
  (use "git add <file>..." to include in what will be committed) - нужна команда добавить , чтобы зафиксировать версию
        index.html - список файлов для сохранения 
        pictures/

nothing added to commit but untracked files present (use "git add" to track) - найдены файла для добавления 
Настраиваем ползователя в git
git config --global user.name PK303-0
git config --global user.email PK303-0@gmail.com

git config --global --unset htpp.proxy
git config --global --unset htpps.proxy
git config --global --unset core.gitproxy
![3](https://github.com/Hottabik/6semestr/assets/113089655/f7386b4a-239b-410c-957a-1d8241220424)

![2](https://github.com/Hottabik/6semestr/assets/113089655/208ab0c6-cf11-42d0-b307-7322e6fb7ad8)

подтверждение 

![5](https://github.com/Hottabik/6semestr/assets/113089655/0b670c40-5a8a-4a02-8858-f7272fa2595b)

![push](https://github.com/Hottabik/6semestr/assets/113089655/4da52c50-f50c-435b-9826-7a22a6199455)

основные ошибки:
1) remote - подключение к удаленном репозиторию (показывает на какой репозиторий мы хотим сохранить данные), может быть ошибка , что неправильно указали ссылку, чтобы изменить добавить set-url
2) авторизация - github нужно передать данные пользователя (логин,пароль или токин)
3) прокси сервер - проверям включен или нет
лк 3
если есть папка .git то команду git init
команда config настраиваются на пк (1 раз)
git remote используется один раз

Пароли :
qwerty - debian
12345678 - red os

![изображение](https://github.com/Hottabik/6semestr/assets/113089655/7c4fc59d-369f-48c9-aee7-5bce4042e30e)

![изображение](https://github.com/Hottabik/6semestr/assets/113089655/a9c805ff-ee42-420e-9e43-fe7028971dd1)

05.02 - Работа с файлами
1) Создание
2) Перемещение
3) Редактировани
4) Удаление
Обычный файл (Regular file)
1) touch churka.txt
2) mv churka.txt /home/stud
3) nano /home/stud/churka.txt ; cat  /home/stud/churka.txt
4) rm  /home/stud/churka.txt
   
![image](https://github.com/Hottabik/6semestr/assets/113089655/945d2fe0-4784-4de9-9abe-ae114f47e2ff)

Папка (DIrectory)
1) mkdir ussr
2) mv  /home/stud/ussr /home/stud/reich
3) ls /home/stud/reich
4) rm -r  /home/stud/reich

![image](https://github.com/Hottabik/6semestr/assets/113089655/c8be093a-37a2-4f48-84ad-94d12ab7817a)

жесткая ссылка:
ln London.txt Manch.txt

12.02.24
Устройства:
1. Символьные (мышка клавиатура)
2. Блочные (Флешки)
   ![image](https://github.com/Hottabik/6semestr/assets/113089655/5343dd85-e6d1-452b-b6e7-0e4cf3fe9427)
mknod blockf b 5 100
ls -la
nano blockf
rm blockf
ls -la
![image](https://github.com/Hottabik/6semestr/assets/113089655/729bb147-4503-48f0-b1c4-33a5a182b253)
Файлам присваивается уникальный номер (инод), посмотреть командой i1
Жесткие ссылки имеют тот же номер , что и исходный файл и это можно использовать , чтобы найти все жесткие ссылки.
