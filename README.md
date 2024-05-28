# Стартап, продающий продукты питания
Нам предстоит разобрать поведение пользователя в мобильном приложении. А именно, как и сколько пользователей доходят до покупки, исследовать результаты A/A/B-эксперимента, в котором рассматривается вопрос о смене шрифтов во всем приложении.
## Описание данных
Каждая запись в логе — это действие пользователя, или событие. 
* EventName — название события;
* DeviceIDHash — уникальный идентификатор пользователя;
* EventTimestamp — время события;
* ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.
