---
tags:
  - Linux
  - terminal
  - commans
  - wifi
  - tutorial
created: 2024-04-24T21:44:00
---

```bash
rar a file1.rar file1 file2 dir1
```
Создать rar архив file1.rar, заархивировав файлы: file1, file2 и директорию: dir1

```bash
gzip -9 file1
```
Поместить файл file1 в архив gzip с максимальной степенью сжатия

```bash 
rar a file1.rar test_file
```
Упаковать в rar архив file1.rar файл test_file

```bash
rar x file.rar
```
Разархивировать rar архив file.rar

```bash
bzip2 file1
```
Сжимает файл file1

```bash 
bunzip2 file1.bz2
```
Разжимает файл file1.bz2

```bash
gzip file1
```
Сжимает файл file1

```bash
gunzip file1.gz
```
Разжимает файл file1.gz

```bash
tar -cvf archive.tar file
```
Упаковать в tar-архив archive.tar файл file

```bash
tar -tf archive.tar
```
Вывести содержимое tar архива

```bash
tar -xvf archive.tar -C /tmp
```
Распаковать архив в /tmp

```bash
tar -cvfz archive.tar.gz dir1
```
Создать tar архив и сжать его с помощью программы gzip

```bash
zip file1.zip file1
```
Создать сжатый zip-архив

```bash
unrar x file1.rar
```
Распаковать rar-архив
