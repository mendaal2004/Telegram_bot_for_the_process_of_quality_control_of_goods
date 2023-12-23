# Процесс контроля качества товаров

## Описание проекта

Проект "Процесс контроля качества товаров" создан для автоматизации процесса оформления отчета о товаре с использованием телеграм-бота.
Основная цель проекта - упростить и ускорить процесс контроля качества товаров путем создания эффективного инструмента для сбора информации о товарах, их проверки и формирования отчетов.

 Основные характеристики проекта включают:
* Генерация отчетов на основе введенных данных (дата, должность, номер товара, состояние товара)
* Визуализация работы в BPMN диаграмме.

## Установка и запуск проекта на локальной машине
1. Выберите место расположения проекта:\
```
git clone https://github.com/mendaal2004/Telegram_bot_for_the_process_of_quality_control_of_goods.git
```
2. В текстовом редакторе установите библиотеку telebot:\
```
pip install telebot
```
3. Откройте в ветке release коммит the_final_code. Скопируйте код и создайте файл TgBot.py.
4. Запустите код. Бота можно найти в телеграме @quality_control_of_goods_bot или по ссылке: https://t.me/quality_control_of_goods_bot
5. Откройте в ветке release коммит dashboard. Скопируйте код и создайте файл Dashboard.py.
6. Запустите код. Дашборд будет доступен по ссылке: <http://127.0.0.1:8050/>

## Использование проекта
Для начала работы с ботом в меню предоставлены команды /start и /help.
* /start - начать диалог с ботом.

![start](https://github.com/mendaal2004/Telegram_bot_for_the_process_of_quality_control_of_goods/assets/134377794/d72f4b2e-77e3-453c-a214-59e9c8f4d327)

* /help - возможности бота. То есть, бот предоставит Вам выбор команд.

![help](https://github.com/mendaal2004/Telegram_bot_for_the_process_of_quality_control_of_goods/assets/134377794/17caeded-96f2-4508-8cc4-a63eb8ab7b8f)
  
  * Диаграмма BPMN\
    
Если Вы нажмете на эту кнопку, то бот выдаст информацию по диаграмме BPMN, объяснит принцип работы и предоставит изображение.

![BPMN_diagram](https://github.com/mendaal2004/Telegram_bot_for_the_process_of_quality_control_of_goods/assets/134377794/e188d12e-30d4-4b4b-932d-d853431bc8fb)
  
  * Дашборд\
    
Если Вы нажмете на эту кнопку, то бот выдаст информацию по дашборду, объяснит принцип работы и  предоставит ссылку на код на GitHub

![dashboard](https://github.com/mendaal2004/Telegram_bot_for_the_process_of_quality_control_of_goods/assets/134377794/97b100d4-974a-401f-8936-43e9f2d3f365)
    
  * Оформить отчет\
    
Если Вы нажмете на эту кнопку, то бот попросит Вас ввести данные (дата, должность, номер товара, состояние товара) и сформирует отчет о товаре.

![issue_a_report](https://github.com/mendaal2004/Telegram_bot_for_the_process_of_quality_control_of_goods/assets/134377794/4f1eec1f-3180-468e-87e6-e780c2138e21)

  * Помощь\
    
Если Вы нажмете на эту кнопку, то бот выдаст информацию о возможностях бота.

![help_with_the_bot](https://github.com/mendaal2004/Telegram_bot_for_the_process_of_quality_control_of_goods/assets/134377794/f17648ac-94ec-4b8c-b583-27a2a89ab856)

## Ссылки
* Профиль GitHub: <https://github.com/mendaal2004>
* Проект Dashboard: <https://github.com/mendaal2004/Analysis_of_sunset_and_sunrise_time_data.git>
* BPMN диаграмма: <https://lucid.app/lucidchart/60176f7c-3893-4d3f-b003-5b96004695a1/view?invitationId=inv_372dc1fa-8bb5-419a-82bf-dc5a342b1e95&page=0_0#>
