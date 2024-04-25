---
tags:
  - hack
  - Guide
  - wifi
---
Итак, для насыщения убогого шела «красками» есть целый ряд команд:

```bash
python3 -c 'import pty; pty.spawn("/bin/sh")'
```

`^Z` - CTRL + Z *Свернуть подключение*

```bash
stty -a # Получение колонок и строк
```

```bash
echo $TERM # Информация о оболочке
```

```bash
stty raw -echo && fg # Возврат
```

```bash
reset
```

```bash
export SHELL=bash
```

```bash
export TERM=xterm-256color
```

```bash
stty rows <num> columns <cols>
```
---

```bash
echo os.system('/bin/bash')
```

```bash
/bin/sh -i
```

```bash
perl —e 'exec "/bin/sh";'
```

```bash
perl: exec "/bin/sh";
```

```bash
ruby: exec "/bin/sh"
```

```bash
lua: os.execute('/bin/sh')
```

```bash
exec "/bin/sh"
```

```bash
:!bash
```

```bash
:set shell=/bin/bash:shell
```


