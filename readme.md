Памятка по использованию телеграм бота 
Подготовка к использованию бота


Бот запускаются командой из корневой папки проекта

python main.py
Общая информация.

Бот пользуется бесплатным API сайта hotels.com.
Ссылка на API: https://rapidapi.com/apidojo/api/hotels4

Для использования бота существует 4 команды:

/help
/lowprice
/highprice
/bestdeal
Также бот может реагировать на различные приветствия и прощания. К обработке текста бота добавлены 2 функции: очистка текста от различных символов, а также игнорирование орфографических ошибок.

text communication

В случае, если бот не может понять, что пишет пользователь, он ему отвечает:
dont understand
Описание работы команд.
/help
Помогает пользователю узнать об общей функциональности бота в Telegram (выводит список команд).
help command
/lowprice
Позволяет пользователю найти отели в городе, указанным пользователем, по самым дешевым ценам.
lowprice command
/highprice
Позволяет пользователю найти отели в городе, указанным пользователем, по самым высоким ценам.
highprice command
/bestdeal
Позволяет пользователю найти отели в городе, указанным пользователем, с допольнительным фильтром по минимальной и максимальной: цене, расстоянию от центра.
bestdeal command