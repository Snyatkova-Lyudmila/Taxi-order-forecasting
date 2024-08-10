# Прогнозирование заказов такси

## Описание проекта

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.

Требуется построить модель для такого предсказания (*RMSE* на тестовой выборке должно быть <= 48).

## Задачи исследования

* загрузить данные
* выполнить ресемплирование данных
* провести анализ данных
* обучить разные модели с различными гиперпараметрами (тестовая выборка = 10% от исходных данных)
* проверить модели на тестовой выборке
* сформулировать выводы

**Цель исследования** - построить модель для прогнозирования количества заказов такси на следующий час.

---
**Данные для анализа** - файл с данными *taxi.csv* (/datasets/taxi.csv)

**Описание данных**

* *num_orders* - количество заказов

**Этапы работы над проектом**

*Шаг 1.* Загрузка и изучение общей информации:
* загрузка данных
* изучение общей информации

*Шаг 2.* Ресемплирование данных

*Шаг 3.* Анализ данных

*Шаг 4.* Обучение моделей
* подготовка данных
* обучение моделей
* выводы

*Шаг 5.* Тестирование

*Шаг 6.* Общий вывод 
