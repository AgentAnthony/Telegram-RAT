# :fire: Telegram-RAT:
Управляйте компьютером с помощью телеграмма!

# :page_facing_up: Установка:
Для работоспособности скрипта установите Python 3.8 и следующие библиотеки
* `pip3 install pytelegrambotapi`
* `pip3 install opencv-python`
* `pip3 install cryptography`
* `pip3 install comtypes`
* `pip3 install pywin32`
* `pip3 install pyaudio`
* `pip3 install pillow`
* `pip3 install pycaw`

* Если есть ошибка с pyaudio, скачайте [отсюда](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)
  * Перейдите в директорию с whl-файлом и впишите в консоль `pip3 install pyaudio.x.x.x.whl`
* Создаём бота в телеграме у `@BotFather`, после чего находим его API
 <img src="https://i.imgur.com/3eWSJtZ.png">
* Теперь вам нужно получить Telegram-ID. Для этого перейдите к `@my_id_bot` и сохраните ваш идентификатор.
 <img src="https://i.imgur.com/TIoauMO.png">
* Теперь впишите скопированный токен и айди в скрипт RAT.py
 <img src="https://i.imgur.com/1T56OZL.png">
* Теперь нажмите CTRL + S, чтобы сохранить изменения.                                                      
* Чтобы скомпилировать скрипт, воспользуйтесь pyinstaller'ом (`pip install pyinstaller`)
  * Теперь откройте CMD в директории со скриптом и впишите `pyinstaller --onefile --noconsole RAT.py` и подождите.
  * Скомпилированный `.exe` файл будет в находиться в папке «dist». И при запуске будет отправлять вам подобное сообщение.
 <img src="https://i.imgur.com/CuRuUjn.png">


# :rose: Функции:
* АнтиБот (ВТ)
* Обнаружение антивирусного ПО
* Узнать версию OS
* Узнать IP жертвы
* Скриншот экрана
* Фото с вебки
* Видео с вебки
* Запись микрофона
* Управление питанием
   * Выключение
   * Перезагрузка
   * Синий экран смерти
* Автозагрузка
   * Сохранить в автозагрузку
     * Изменение даты и имени файла
   * Самоудаление
* Файловый менеджер
   * Просмотр текущей директории
   * Просмотр содержимого
   * Удаление файлов
      * Удаление всех файлов
   * Загрузить файл
   * Скачать файл
   * Запустить файл
      * Запустить от им. админа
* Диспетчер задач
  * Получить список процессов
  * Остановить процесс
     * Остановить все процессы
     * Отключить диспетчер задач
* Вывести сообщение на экран
* Озвучить сообщение
* Открыть ссылку
* Установить обои
* Запустить программу
  * Запустить один раз
  * Запустить много раз
* Стиллер паролей
* Буфер обмена
  * Просмотр буфера обмена
  * Редактирование буфера обмена

# Скриншоты
<p align="center">
    <img src="https://i.imgur.com/CzJ3u2t.png" Telegram-RAT">
</p>

# Кнопки навигации
<p align="center">
    <img src="https://i.imgur.com/LMsVw3L.png" Telegram-RAT">
</p>





# Версии
`RAT v1`
* Расшифровка паролей
* Информация о системе
* Скрин рабочего стола
* Отправка в телеграмм

`RAT v2`
* Управление через бота
* Фото с вебки
* Видео с вебки
* Запись микрофона
* Выключение компьютера
* Самоудаление

`RAT v3`
* Переход на кнопки
* Добавлен BSoD

`RAT v5`
* Новый интерфейс
* Оптимизация кода
* Исправлен баг с перевернутым видео
* Добавлен файловый менеджер
* Добавлен контроль над процессами
* Добавлен вывод сообщения на экран
* Добавлено открытие URL-ссылки
* Добавлен запуск любой программы
* Добавлен вывод айпи пользователя
* Улучшеное добавление в автозагрузку

`RAT v5.1`
* Улучшенное добавление в автозагрузку
* Исправлен баг с выводом имени файла

`RAT v5.3`
* Теперь можно скачивать фотографии
* Поправил функцию самоудаления
* Исправил ошибки в словах
* Исправлен баг с PWD

`RAT v6`
* Теперь можно скачивать папки
* Убрал ненужные модули
* Удалил стиллер паролей

`RAT v7`
* Просмотр метаданных файла/папки
* Улучшена функция самоудаления
* Улучшена функция скачивания
* Загрузка файлов на компьютер 
* Возможность установки обоев
* Просмотр активного окна
* Озвучивание текста

`RAT v8`
* Обновил интерфейс
* Добавлен переворот экрана
* Добавлена блокировка мыши
* Улучшены некоторые функции
* Бот теперь может быть публичным

`RAT v8.5`
* Улучшенное добавление в автозагрузку
* Удалил переворот экрана
* Удалил блокировку мыши
* Обновил интерфейс

`RAT v9.0`
* Добавлена остановка всех процессов
* Добавлено определение антивируса
* Обновил интерфейс

`RAT v10`
* Улучшенное добавление в автозагрузку
* Добавлено изменение даты и имени файла
* Добавлено отключение Taskmgr

`RAT v11`
* Добавлены потоки

`RAT v12`
* Добавлен стиллер паролей
* Добавлен вывод процессов

`RAT v13`
* Добавлены коментарии к коду
* Добавлено воспроизведение аудио

`RAT v14`
* Добавлен АнтиБот (ВТ)
* Добавлен буфер обмена
* Добавлено удаление всех файлов
* Добавлен запуск от им. админа
