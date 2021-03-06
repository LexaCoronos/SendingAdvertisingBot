# ~ Telegram Bot «Sending Advertising Bot» ~

![screen1](https://github.com/LexaCoronos/SendingAdvertisingBot/blob/master/img/LogoSA.png)

**Краткое описание:** Telegram бот для организации автоматических рассылок постов в группы с системой платных подписок с интегрируемой интернет-кассой и приёмом онлайн платежей.  Интегрируемая касса **WayForPay**.

**Категория:** Разработка ботов.

**Ссылка:** http://t.me/SendingAdvertisingBot

-----------------------------------

🔻 **Возможности:**

✅ Создание рассылок информационного или рекламного характера в группах.

✅ Поддержка рассылок в группах и каналах.

✅ Подтверждение админ прав в группе, перед организацией рассылки.

✅ Вариативность возможностей при создании с постов.

✅ Управление вашими рассылками и редактирование их параметров.

✅ Система платных подписок в боте для осуществления рассылок.

✅ Админ панель для управления.

✅ Система блокировок пользователей.

✅ Система прав пользователей.

✅ Возможность получения пробного периода с двумя слотами для рассылок на 5 дней.

-----------------------------------

🔻 **Описание работы:**

-----------------------------------

🔹 Создание рассылок по следующим шагам:

   - Выбор группы/канала для рассылки (обязательное условие быть админом в данной группе, бот это проверяет каждый раз)

   - Текст поста (возможен HTML стиль размети текста)
	
   - Прикрепление к посту: изображение, видео
	
   - Указание кнопок-ссылок с названием под постом
	
   - Ввод начала старта рассылки
	
   - Ввод времени окончания рассылки
	
   - Ввод периодичности рассылки в формате: 1d, 2h или 15m
	
   - Указание дополнительных параметров рассылки
	
   - Предворительный просмотр вида поста и параметров рассылки
	
   - Подтверждение и запуск данной рассылки
	
-----------------------------------

🔹 Дополнительные возможности с постами реализованы в виде переключателей true/false:

   - Автоудаление постов при циклической рассылке
   
   - Превью ссылок в посте
   
   - Удаление постов по окончинии рассылки
	
-----------------------------------

🔹 Вид поста рассылки в группе:
![screen1](https://github.com/LexaCoronos/SendingAdvertisingBot/blob/master/img/postinchat.png)

-----------------------------------

🔹 Управление вашими рассылками и редактирование их параметров
![screen1](https://github.com/LexaCoronos/SendingAdvertisingBot/blob/master/img/controlSending.png)

-----------------------------------

🔹 Админ панель для управления с возможностями:

   - Удаление любой рассылки
   
   - Выдача подписки пользователю
   
   - Снятие подписки у пользователя
   
   - Список подписчиков
   
   - Назначить, снять админа
   
   - Список администрации
   
   - Забанить, разбанить пользователя
   
   - Чёрный список
![screen1](https://github.com/LexaCoronos/SendingAdvertisingBot/blob/master/img/adminpanel.png)

-----------------------------------

🔹 Система платных подписок в боте для осуществления рассылок реализована по принципу выдачи купленного количества слотов на определённый период в зависимости от выбранного абонемента.
![screen1](https://github.com/LexaCoronos/SendingAdvertisingBot/blob/master/img/ordering.png)
![screen1](https://github.com/LexaCoronos/SendingAdvertisingBot/blob/master/img/paying.png)

-----------------------------------

🔹 Интеграция с кассой проводилась через **WayForPay API** кассы. Вся платёжная система, генератор и обработчик платежей написаны вручную и заточены под данную целевую задачу.
![screen9](https://github.com/LexaCoronos/SendingAdvertisingBot/blob/master/img/WayForPay.png)
