
# New York City Taxi Trip Duration

## Работа представлена в качестве решения хакатона

### Участники группы:

| Участник      |            Почта               |         Роль         |
|:--------------|:------------------------------:|:--------------------:|
| Попова Илона  |     ilona-u@mail.ru        |    Лидер проекта     |
| Рагимов Александр |    ingeloflame@gmail.com |   QA, тестирование   |
| Максимова Наталья |       Natalia-k.97@mail.ru     |   Аналитик данных    |
| Сергеев Владимир |        vvsergeev87@gmail.com    |    Data scientist    |
| Архипов Д.А.  | arkhipov.danil2015@gmail.com   | Технический писатель |

## Основные цели:
- Сформировать набор данных на основе нескольких источников информации.
- Спроектировать новые признаки с помощью Feature Engineering и выявить наиболее значимые при построении модели.
- Исследовать предоставленные данные и выявить закономерности.
- Построить несколько моделей и выбрать из них ту, которая показывает наилучший результат по заданной метрике.
- Спроектировать процесс предсказания длительности поездки для новых данных.


## Основные этапы:
1. Первичная обработка данных
2. Разведывательный анализ данных (EDA)
3. Отбор и преобразование признаков
4. Решение задачи регрессии: линейная регрессия и деревья решений
5. Решение задачи регрессии: ансамбли моделей и построение прогноза

## Описание данных:
### Данные о клиенте и таксопарке:
- id — уникальный идентификатор поездки;
- vendor_id — уникальный идентификатор поставщика услуг (таксопарка), связанного с записью поездки.

### Временные характеристики:
- pickup_datetime — дата и время, когда был включён счётчик поездки;
- dropoff_datetime — дата и время, когда счётчик был отключён.

### Географическая информация:
- pickup_longitude — долгота, на которой был включён счётчик;
- pickup_latitude — широта, на которой был включён счётчик;
- dropoff_longitude — долгота, на которой счётчик был отключён;
- dropoff_latitude — широта, на которой счётчик был отключён.

### Прочие признаки:
- passenger_count — количество пассажиров в транспортном средстве (введённое водителем значение);
- store_and_fwd_flag — флаг, который указывает, сохранилась ли запись о поездке в памяти транспортного средства перед отправкой поставщику (Y — хранить и пересылать, N — не хранить и не пересылать поездку).

### Целевой признак:
- trip_duration — продолжительность поездки в секундах.

### Дополнительные датасеты
-[Праздничные даты](https://lms.skillfactory.ru/asset-v1:Skillfactory+URFUML2023+SEP2023+type@asset+block@holiday_data.csv)

-[Файлы с данными из OSRM](https://drive.google.com/file/d/1ecWjor7Tn3HP7LEAm5a0B_wrIfdcVGwR/view?usp=sharing)

-[Информация о погодных условиях в Нью-Йорке в 2016 году](https://lms.skillfactory.ru/asset-v1:Skillfactory+URFUML2023+SEP2023+type@asset+block@weather_data.zip)

-[Тестовая выборка](https://drive.google.com/file/d/1C2N2mfONpCVrH95xHJjMcueXvvh_-XYN/view?usp=sharing)

-[Файл с данными из OSRM API для тестовой выборки](https://drive.google.com/file/d/1wCoS-yOaKFhd1h7gZ84KL9UwpSvtDoIA/view?usp=sharing)

