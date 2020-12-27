# linux1

## Задание  
Надо было сделать dracut-модуль, который при запуске системы выводил что-нибудь в консоль

## Выполнение
1. Переходим в папку с модулями: `cd /usr/lib/dracut/modules.d`
2. Создаем папку с нашим модулем: `mkdir 01dracut_lab1`
3. Переходим в нее `cd 01dracut_lab1`
4. Копируем в папку файлы *dracut_lab1.sh* и *dracut_lab1.sh* из репозитория: `cp путь_до_файла .`
5. Собираем модуль: `sudo dracut -f`
6. Перезагружаем систему: `sudo reboot`
7. При загрузке системы нажимаем *е* и убираем *ro quiet*
8. Нажимаем F10  
![](https://sun9-68.userapi.com/impg/A6iUIc6YRYTpST47tc79vjj9joaw7fHqeGEeHQ/6-i0OSaDVvQ.jpg?size=556x277&quality=96&proxy=1&sign=8519896091f68a1eb61f3473a530e15b&type=album)
