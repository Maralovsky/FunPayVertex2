<h1 align="center">FunPay Vertex</h1>
<h4 align="center">Простой и эффективный бот для автоматизации FunPay</h4>

<h1 align="center">
    <img src="https://i.ibb.co/qDNFJGQ/Screenshot-48.png">
</h>

<h2 align="center">Перед началом настоятельно рекомендую залететь в наш <a href="https://t.me/funpayplace">Telegram чат</a> и <a href="https://dsc.gg/funpay">Discord сервер</a>. Тут и поможем чем сможем и посидеть можно.</h2>

## :clipboard: **Содержание**

- [Возможности](#robot-возможности)
  - [FunPay](#shopping_cart-funpay)
  - [Уведомления и ПУ в Telegram](#left_speech_bubble-уведомления-и-пу-в-telegram)
  - [Дополнительные возможности](#gear-дополнительные-возможности)

- [Преимущества](#1st_place_medal-преимущества)
  - [Для пользователей](#grinning-для-пользователей)
  - [Для разработчиков](#computer-для-разработчиков)

- [Установка](#arrow_down-установка)
  - [Windows](#large_blue_diamond-windows)
  - [Linux (Ubuntu)](#hotsprings-linux-ubuntu)
- [Настройка конфигов](#hammer_and_wrench-настройка-конфигов)
- [Мне нужна помощь](#question-мне-нужна-помощь)
- [Star it!](#star-star-it!)


## :robot: **Возможности**

### :shopping_cart: **FunPay**

- Автовыдача товаров.
- Автоподнятие лотов.
- Автоответ на заготовленные команды.
- Автовосстановление лотов после продажи.
- Автодеактивация лотов, если товары закончились.
- Вечный онлайн.
- Уведомления в телеграм.
- Полноценная ПУ в Telegram.

### :left_speech_bubble: **Уведомления и ПУ в Telegram**

- Возможность установки нескольких чатов для уведомлений.
- Уведомления о поднятии лотов.
- Уведомления о новых заказах.
- Уведомления о выдаче товара.
- Уведомления о новых сообщениях
- Возможность отвечать на сообщения прямо из Telegram.
- Возможность полностью настраивать автовыдачу / автоответчик и все остальные модули.
- Возможность добавлять автовыдачу для лотов, получая лоты пряма с FunPay.

### :gear: **Дополнительные возможности**

- Использование переменных в тексте для автоответа / автовыдачи.

## :1st_place_medal: **Преимущества**

### :grinning: **Для пользователей**

- **Больше**, чем наличие самого нужного функционала.
- **Оптимизация**. _20 МБ свободного места на диске, до 50 МБ ОЗУ, доступ в интернет_ - все что нужно для работы.
- Возможность установить на **любую платформу**, которую поддерживает _Python: Windows, Linux, IOS, Android_ и т.д.
- Гибкие и при этом простые конфиги, написанные в INI-формате.
- Постоянные обновления, быстрое реагирования на баги / предложения о новом функционале.
- Полное управление через Telegram.

### :computer: **Для разработчиков**

- Выбран самый простой и при этом один из самых мощных языков для такого рода приложений - _Python_.
- Полная документация кода. Все классы / методы / функции имеют док-строки, type-хинты.
- Широкое использование ООП. Почти каждый эвент / сообщение / заказ и т.д. представляют собой экземпляр соответствующего класса, а не просто набор данных в JSON.
- Сконфигурированный логгер. Никаких принтов!
- Собственный Python-пакет FunPayAPI, который никак не привязан к FunPay Vertex.

## :arrow_down: Установка

### :large_blue_diamond: Windows

1. Скачайте и установите [Python](https://www.python.org/ftp/python/3.11.0/python-3.11.0-amd64.exe).
   1. При установке поставьте галочку у `Add python.exe to PATH` на первом экране установки.
2. Скачайте FunPay Vertex.
3. Перенести папку `FunPayVertex-master` в нужное вам место.
4. Перейдите в папку `FunPayVertex-master`.
5. В адресной строке введите `cmd` и нажмите `Enter`.
6. В открывшейся командной строке введите `python setup.py`. Дождитесь окончания загрузки пакетов.
7. Закройте командную строку, настройте конфиги и запустите файл `Start.bat`.

### :hotsprings: Linux (Ubuntu)

1. Введите следующие команды для установки Python 3.11.
   1. `sudo apt update`
   2. `sudo apt install software-properties-common`
   3. `sudo add-apt-repository ppa:deadsnakes/ppa`
   4. `sudo apt update`
   5. `sudo apt install python3.11 python3.11-dev python3.11-gdbm python3.11-venv`
   6. `sudo apt install curl`
   7. `sudo apt install gcc`
   8. `curl -sS https://bootstrap.pypa.io/get-pip.py | python3.11`

2. Скачайте `git` с помощью команды `sudo apt install git`.
3. Скачайте FunPayVertex с помощью команды `git clone https://github.com/NightStrang6r/FunPayVertex`.
4. Перейдите в папку `FunPayVertex` с помощью команрды `cd FunPayVertex`.
5. Установите нужные пакеты с помощью команды `python3.11 setup.py`.
6. Настройте конфиги и запустите FunPay Vertex с помощью команды `python3.11 main.py`.

## :hammer_and_wrench: Настройка конфигов

1. Все конфиги находятся в папке `configs`
2. Все инструкции по настройке конфигов находятся внутри самих конфигов.
3. Основной конфиг со всеми переключателями: `configs/_main.cfg`
4. Конфиг автоответчика: `configs/auto_response.cfg`
5. Конфиг автовыдачи: `configs/auto_delivery.cfg`

## :star: Star it!
Если вам удобно пользоваться FunPay Vertex, не забудьте поставить :star: звезду :star: данному проекту :)
