
Autor: [Artur D. Nasyrov](https://github.com/Arturawesome)

Laboratory: [Bauman Digital Soft Matter laboratory, BMSTU](http://teratech.ru/en)

Operating System: Manjaro Linux KDE Plasma Version: 5.22.5. 

Processors: 8 × Intel® Core™ i7-9700KF CPU @ 3.60GHz
---
При перезагрузке, LINUX может не увидеть HDD.

# SOLVE

1) узнать имя раздела
```shell
[~$] lsblk
```
2) Установить приложение *ntfs-3g*. И ее запуск
```shell
[~$] sudo pacman -S ntfs-3g
[~$] sudo ntfsfix /dev/disk_name
```
GOOD-LUCK
