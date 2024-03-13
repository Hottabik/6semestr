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

https://docs.google.com/document/d/1z27O5xLblWKjIxcXRZnbd1smm-oYa8bt/edit#heading=h.djklet2cwec6

![изображение](https://github.com/Hottabik/6semestr/assets/113089655/10c50f65-15a9-4c5c-b382-a2d424a446a9)
![изображение](https://github.com/Hottabik/6semestr/assets/113089655/add49044-8057-4938-b5c1-be4bfa3e94aa)
![изображение](https://github.com/Hottabik/6semestr/assets/113089655/2878700e-880c-4d16-ba54-e0d3f91fe883)
![image](https://github.com/Hottabik/6semestr/assets/113089655/6d23a08c-82eb-4b34-863f-e44d0c704e8b)
![image](https://github.com/Hottabik/6semestr/assets/113089655/2d5a439e-3384-4e5c-91ff-ee2336c5245e)
![image](https://github.com/Hottabik/6semestr/assets/113089655/af5c5705-47b9-40d2-aa5c-46c4b3b112f5)
![image](https://github.com/Hottabik/6semestr/assets/113089655/2e376d05-1e95-4e2f-a78a-e9c69826aeca)
![image](https://github.com/Hottabik/6semestr/assets/113089655/af6b30ab-4543-4b4f-a1e2-40766bbae5d0)
![image](https://github.com/Hottabik/6semestr/assets/113089655/cd3330d1-d268-4001-b6af-bcd6b5b255da)
![image](https://github.com/Hottabik/6semestr/assets/113089655/1e515794-86b9-4c3c-a439-e90ea74913be)
![image](https://github.com/Hottabik/6semestr/assets/113089655/14238dd8-5d6d-4d95-840d-c84a0dcdc5eb)


ЛК 19.02
![image](https://github.com/Hottabik/6semestr/assets/113089655/2a14b0d2-b54c-4c41-b6a7-b34f5e194eea)
Имя пользователя:
Место под пароль в файле пароля 
1000:1000
номер пользователя:Номер группы
stud:x:1000:1000:Student,,,:/home/stud:/bin/bash
/bin/bash/ - Терминал пользователя.
![image](https://github.com/Hottabik/6semestr/assets/113089655/5f9d8a3f-b48d-4b75-95f5-1e700b2a735a)
![image](https://github.com/Hottabik/6semestr/assets/113089655/635b8e7c-155c-4b93-bbca-8f716ecdb575)
![image](https://github.com/Hottabik/6semestr/assets/113089655/4b9126ac-0d64-4445-8b68-63d437d8fd0b)
![image](https://github.com/Hottabik/6semestr/assets/113089655/8b25a89c-2ae2-4568-8006-70653b05c6ce)
![image](https://github.com/Hottabik/6semestr/assets/113089655/16695f01-64c5-47ea-b6a7-07c48b8a315f)
![image](https://github.com/Hottabik/6semestr/assets/113089655/839c8072-7fb2-49a9-9358-714c5fa26345)
![image](https://github.com/Hottabik/6semestr/assets/113089655/a53d36cb-e388-40b7-851a-7f6993bb5995)


#Red os
![image](https://github.com/Hottabik/6semestr/assets/113089655/a619335c-b8ad-476d-a3b2-34fd7ef6bf25)
![image](https://github.com/Hottabik/6semestr/assets/113089655/48f708a9-49ed-429b-84e1-08ea2a758b57)
![image](https://github.com/Hottabik/6semestr/assets/113089655/d86fc13e-b508-4364-b634-d52e59501690)
![image](https://github.com/Hottabik/6semestr/assets/113089655/b2c36d57-7701-41d0-a3b5-336ab2da3e54)
![image](https://github.com/Hottabik/6semestr/assets/113089655/a790cbd8-1d23-4412-aa31-fbf1fbcd7d16)
![image](https://github.com/Hottabik/6semestr/assets/113089655/9d9cce5f-5d4b-4129-a18c-4708aea41383)

4 Тема
![image](https://github.com/Hottabik/6semestr/assets/113089655/c4bcb330-ce92-48c3-a7c9-411123fe0235)
![image](https://github.com/Hottabik/6semestr/assets/113089655/6aab8f2a-d8f2-4d9b-93c5-a86862436589)
![image](https://github.com/Hottabik/6semestr/assets/113089655/226572bf-d485-4bd0-9cc1-ca86ee9a87cb)
![image](https://github.com/Hottabik/6semestr/assets/113089655/0ebb9dbb-11d6-40bd-b589-06e03ab30402)
Red os
![image](https://github.com/Hottabik/6semestr/assets/113089655/427d7f64-c9f3-405d-8f77-b9fbf843b3c4)
![image](https://github.com/Hottabik/6semestr/assets/113089655/9483b168-2651-41f3-b193-4edcf30968f3)
![image](https://github.com/Hottabik/6semestr/assets/113089655/81bc43fb-2dd3-4204-92c3-ed6ffc7588d9)
![image](https://github.com/Hottabik/6semestr/assets/113089655/557cff72-d552-42bc-aca4-374f2d530641)
5 тема 
Атрибуты процесса:
1) Pid - уникальный индефикатор
2) Адресация областей памяти
3) fd - открытые файловые дискрипторы
4) обработчики сигналов процесса
5) код выхода
6) рабочий каталог
![image](https://github.com/Hottabik/6semestr/assets/113089655/cbabab8f-3c4b-42ab-b121-8721c5292e61)
первый процесс это инит
![image](https://github.com/Hottabik/6semestr/assets/113089655/0d2755d1-c7a2-4c42-8482-328797898714)
смерть процесса
exit или kill - завершение процесса.
зомбак не может поключится
остановили дочерний процесс
остановили родительский процесс - дочерний или зомби или найдет другой дочерний
ready - процесс готов к работе или в очереди.
Сигналы:
способы оповестить о прекращении
![image](https://github.com/Hottabik/6semestr/assets/113089655/f49697c9-32a3-4be4-83bd-7c064003f312)
прерывание:
аппаратные - все проблемы с устройством
программные - все что с программмами
планировщик процессов:
вытесняющая(планировщик сам) и кооперативная(пк сам выбирает) многозадачность

![image](https://github.com/Hottabik/6semestr/assets/113089655/222a3f08-0603-4f67-b27e-ed755bfc3c27)
![image](https://github.com/Hottabik/6semestr/assets/113089655/f75b812b-e76b-4af0-8c18-24838684686f)
![image](https://github.com/Hottabik/6semestr/assets/113089655/b013c38b-6065-44f7-9ba3-019f31a7dbbb)
![image](https://github.com/Hottabik/6semestr/assets/113089655/de7ebb76-f8a2-43bc-9fb8-162cc393e1ed)
![image](https://github.com/Hottabik/6semestr/assets/113089655/8f31bfd9-5b38-452c-8b99-a9a4b08ca998)
![image](https://github.com/Hottabik/6semestr/assets/113089655/cbe04e1d-c53f-48c6-bf04-3dd4e005c0a6)
![image](https://github.com/Hottabik/6semestr/assets/113089655/15db55cb-35b0-4a43-824b-5c222f27f71c)


