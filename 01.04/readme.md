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
