# G4.10 Docker
```
Запустить контейнеры:
docker-compose up --build
```
```
Перейти по адресу:
http://localhost/
```
```
Ввести учетные данные для входа в админ панель:
логин: admin
пароль: admin
```

```
Если у вас система Windows и не получается запустить проект, то необходимо изменить настройки git

>git config --global core.autocrlf false

т.к. в контейнерах среда linux, из-за внесенных изменении под windows, скрипты в контейнерах не смогут правильно работать с crlf разметкой.
```
