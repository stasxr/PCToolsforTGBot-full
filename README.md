# PC Tools Bot
Это скрипт на Python, созданный для упрощенного и защищенного управления вашим компьютером через Telegram бота. Скрипт позволяет делать скриншоты экрана, управлять мышкой, управлять файлами и процессами, выполнять команды в командной строке, выключать или перезагружать компьютер, а также загружать и скачивать файлы на компьютер.

Для использования скрипта необходимо скомпилировать его и указать внутри скрипта API телеграм бота и свой Telegram ID. Это обеспечит защиту вашего компьютера от нежелательного доступа и оповестит вас, если кто-то другой попытается управлять вашим компьютером через бота.
## Скриншоты
 Сообщение о первом запуске на компьютере
 
 ![image](https://user-images.githubusercontent.com/94005290/222238712-ac71ba15-fce4-4f19-842f-bcab27863a22.png)
 
 Главное меню
 
 ![image](https://user-images.githubusercontent.com/94005290/222238806-1864b233-54f4-465f-bda2-7cb4088d870b.png)
 
 Меню "Файлы и процессы"
 
 ![image](https://user-images.githubusercontent.com/94005290/221945630-1218868b-cac1-4125-b727-7fa2803d3f4d.png)
 
 Меню "Дополнительно"
 
 ![image](https://user-images.githubusercontent.com/94005290/221945697-d5de8b96-005d-4f29-9a0d-33ad80fc41e6.png)
 
 Меню "Управление мышкой"
 
 ![image](https://user-images.githubusercontent.com/94005290/221945316-bf336357-64fe-41ac-ad0a-8a995db22dc0.png)
## Функции бота
 📷Быстрый скриншот - отправляет скриншот экрана<br/>
 🖼Полный скриншот - отправляет скриншот экрана без сжатия<br/>
 📹Фото вебкамеры - отправляет фотографию с вебкамеры<br/>
 🖱Управление мышкой - переходит меню управления мышкой<br/>
 📂Файлы и процессы - переходит в меню с управлением файлов и процессов<br/>
 ❇️Дополнительно - переходит в меню с доп. функциями<br/>
 📩Отправка уведомления - пришлет на ПК окно с сообщением(msgbox)<br/>
 ⏪Назад⏪ - возвращает в главное меню<br/><br/>

 
 🔗Перейти по ссылке - переходит по указанной ссылке(важно указать "http://" или "https://" для открытия ссылки в стандартном браузере, а не IE)<br/>
 ✅Выполнить команду - выполняет в cmd любую указанную команду<br/>
 ⛔️Выключить компьютер - моментально выключает компьютер<br/>
 ♻️Перезагрузить компьютер - моментально перезагружает компьютер<br/>
 🖥О компьютере - показыввает имя пользователя, ip, операционную систему и процессор<br/><br/>

 
 ❌Замочить процесс - завершает любой процесс<br/>
 ✔️Запустить - открывает любые файлы(в том числе и exe)<br/>
 ⬇️Скачать файл - скачивает указанный файл с вашего компьютера<br/>
 ⬆️Загрузить файл - загружает файл на ваш компьютер<br/>
 🔗Загрузить по ссылке - загружает файл на ваш компьютер по прямой ссылке<br/><br/>

## Установка и запуск
*1)* Перейдите в телеграм и напишите @BotFather (t.me/BotFather)<br/>
*2)* Напишите команду /newbot в @BotFather<br/>
*3)* Напишите любое имя бота(пример: PC Tools) <br/>
*4)* Напишите логин бота с окончанием на слово bot, советую писать рандомные символы(пример: nr9dsn6lsh_bot)<br/>
*5)* Вы получите сообщение примера:<br/>
  *"Use this token to access the HTTP API:*<br/>
    *1234567:ASDFGHJKLQWERTY*<br/>
    *Keep your token secure and store it safely, it can be used by anyone to control your bot.*<br/>
    *For a description of the Bot API, see this page: https://core.telegram.org/bots/api"*<br/>
*6)* Нам необходимо скопировать API(1234567:ASDFGHJKLQWERTY)<br/>
*7)* Переходим в созданного бота в телеграмме по ссылке из сообщения и нажимаем запустить<br/>
*8)* Скачиваем с репозитория скрипт бота(PCToolsBot.py) и фaйл(install.txt)<br/>
*9)* Переходим на офф. сайт https://www.python.org/downloads/ и скачиваем установщик python<br/>
*10)* Открываем установщик и устанавливаем обязательно поставив галочку на пункте add python to path<br/>
*11)* Запускаем cmd(Win + R и вписываем cmd) <br/>
*12)* Пишем в cmd pip install -r путь до файла install.txt (пример: pip install -r C:\download\install.txt)<br/>
*13)* Открываем через любой текстовый редактор PCToolsBot.py<br/>
*14)* Вписываем в поле bot_token API бота который мы скопировали<br/>
*15)* Вписываем в поле my_id ваш TELEGRAM ID(Можно у знать у бота @userinfobot (t.me/userinfobot))<br/>
*16)* Сохраняем файл и переходим обратно в консоль<br/>
*17)* пишем cd путь директории где лежит файл PCToolsBot.py (cd C:\download)<br/>
*18)* Пишем в консоли pyinstaller -w -F PCToolsBot.py<br/>
*19)* Перемещаем из папки dist exe-шник в удобну нам папку, создаем ярлык exe-шника<br/>
*20)* Кидаем ярлык в папку автозагрузки C:\Users\Имя_Пользователя\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup<br/>

## Разработчик
- Телеграм канал: [@devFRAME](https://t.me/+5SHcAW68EoZjN2Vi) 
- Старый телеграм канал: [FRAMEDEV](https://t.me/+VHwM4LtIRvXJIqol)

## Поддержать
- CloudTips(Карта): https://pay.cloudtips.ru/p/105e5b0a
- XMR: ```8AsjFH383uoCE5PNn1dhYzi3dkUfw6Cjs888Y5NTSCz918eszCApp6bZWiphfkBgswYSsayDxr9zmJpfywe9N6wS2ffSEam```
