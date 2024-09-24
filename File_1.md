# Вкусно и фиг с ним 
## Основные сущности

1. Заказ
   - Номер заказа
   - Дата заказа
   - Состав заказа (список блюд)
   - Методы:
   - сделать_заказ()
   - отменить_заказ()
   - показать_сумму()

2. Блюдо
   - Название
   - Описание
   - Цена
   - Метод:
   - добавить_в_заказ()

3. Меню список
   - Список блюд
   - Методы:
   - показать_меню()
   - добавить_блюдо()
   - убрать_блюдо()

5. Клиент
   - Имя
   - Номер телефона
   - Методы:
   - сделать_заказ(Заказ)
   - оценить_заказ(Заказ, int)

6. Курьер
   - Имя
   - Номер телефона
   - Методы:
   - принять_заказ(Заказ)
   - доставить_заказ(Заказ)

7. Ресторан
   - Название
   - Адрес
   - Часы работы
   - Методы:
   - принять_заказ(Заказ)
   - подготовить_заказ(Заказ)

## Взаимодействие объектов

- Клиент создает заказ, который состоит из блюд.
- Ресторан принимает заказ, готовит его и передает курьеру.
- Курьер принимает заказ от ресторана и доставляет его клиенту.
- Клиент может оценить заказ после его получения.

## Функциональные требования

1. Клиент может:
   - Просматривать меню ресторанов
   - Создавать заказ, добавляя в него блюда
   - Отменять заказ
   - Оценивать заказ после его получения

2. Ресторан может:
   - Управлять своим меню (добавлять, удалять блюда)
   - Принимать заказы от клиентов
   - Готовить и передавать заказы курьерам

3. Курьер может:
   - Принимать заказы от ресторанов
   - Доставлять заказы клиентам

## Нефункциональные требования

1. Надежность:
   - Система должна быть доступна 24/7 с минимальным временем простоя.
   - Данные пользователей должны быть защищены от потери или несанкционированного доступа.

2. Производительность:
   - Время отклика системы при выполнении основных операций (заказ, отмена, просмотр меню) должно быть не более 2 секунд.
   - Система должна выдерживать до 1000 одновременных пользователей.

3. Удобство использования:
   - Интерфейс приложения должен быть интуитивно понятным и простым в использовании.
   - Навигация по приложению должна быть логичной и структурированной.
### UML:
![hPFD2jf058NtFiMGLN-grAqhtwCK2TKM8LemSLKA-IbseIXT5KeNVOI9JJ3KEBx2kMzKxcYQYM6aqheOa7npxpc7CqC_S1V1SkPrtdYkxmjyXSGlI1p4Xuwu_fxZ18KIEOKZ72e0SY2cyy2WCaYA8M-OiHjCQeWYA8eOm_u6n1SSQOiCwjNhneKCEOuycpR6bITFZTMAOXQ84ufxs1cgsgS](https://github.com/user-attachments/assets/8def80fa-def8-4b58-9823-032ce6fd4dc6)
![bLDDJW8n5Dxt52_iMGY2i2Fn31vW0YEI82GpPMLCO4nqGoGnhbpu4oymGP098_KANs_aAzM8jMFYB9hs-_bU-zffnJA8vEYqB_hXiIGvfAZNFP7KwKLXM_Q60q4KjEKm8jmXHuObDZhv1X-nr1ETGEanKcnsrFf2Z_MKwR5WrAG5Wsu_f18UM9jncCAhYJEXX1kisJ7XfI9aj8symXffYSu](https://github.com/user-attachments/assets/d852124d-86c5-4e94-983e-36671f8b0622)
![bL9DIiD06Dtd5BEqO2_GHUbDfAYBW8QYutuQmLNHfI0kF4BGX0PZuXNUToDVHYSECp7IG8O9x-UzxoEhQxs-qZUN5udYi-4zFKqtwqmhFA51ZGgjv37uR87x67X4WNU--nXwGILRoT698Q4TIPHRCR8ZpIGMzJlCbqkNkb3u54EVBJvuvhnNF7Sd_BI4evcLE_wSMj-grwFxheaYL8uc3sC](https://github.com/user-attachments/assets/f2a517c0-822a-452c-ba37-5ce53f8f0dfe)