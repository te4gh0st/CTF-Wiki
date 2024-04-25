---
tags:
  - commans
---
#### PORT
```bash
ss -lntup # Просмотр открытх портов
```

#### TERM
```bash
export TERM=screen
```

#### MYSQL
```bash
mysql -u <user> -p
```

> `show databases;`
> `show tables;`\
> `use <db_name>`
> 

#### Получение текущего пользователя
```bash
whoami
echo $USER
```

#### Выполнение от имении администратора
Команда `sudo -l` используется для просмотра списка разрешенных (или запрещенных) пользователю команд, которые можно выполнять с помощью `sudo` (поднятие привилегий).

#### SQL inject

```sql

admin' or 1=1 -- -
admin' or 1=1#

```

#### Получение пользователей системы с авторизацией
```bash
grep /etc/passwd "sh" 
```

