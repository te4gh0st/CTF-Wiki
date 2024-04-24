---
tags:
  - commans
---

```bash
ssh2john id_rsa > id_rsa.hash # Получение хеша пароля из private rss key

john id_rsa.hash --wordlist=/usr/share/wordlists/rockyou.txt # брутфорс
```