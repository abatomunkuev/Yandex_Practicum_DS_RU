# Определение стоимости автомобиля 

Этот проект показывает: 
- способность писать структурированный код на Python. 
- возможность использования существующих утилит(библиотек) для обработки и анализа данных.
- навыки анализа и предварительной обработки данных
- использование моделей Машинного Обучения:
    - CatBoost
    - XGBoost
    - LightGBM

Проект включает в себя:
1. Предварительная обработка данных
2. Исследование моделей машинного обучения:
    - Подбор параметров моделей
    - Выбор лучшей моделей для решения задачи



## Данные
Предоставлены данные - исторические данные сервиса по продаже автомобилей с пробегом: технические характеристики, комплектации и цены автомобилей.

В наличии были следующие данные:
- дата скачивания анкеты из базы
- тип автомобильного кузова
- год регистрации автомобиля
- тип коробки передач
- мощность (л. с.)
- модель автомобиля
- пробег (км)
- месяц регистрации автомобиля
- тип топлива
- марка автомобиля
- была машина в ремонте или нет
- дата создания анкеты
- количество фотографий автомобиля
- почтовый индекс владельца анкеты (пользователя)
- дата последней активности пользователя
- цена

## Задача

Сервис по продаже автомобилей с пробегом разрабатывает приложение, где можно узнать рыночную стоимость своего автомобиля. Необходимо построить модель Машинного Обучения для быстрого определения стоимости автомобиля.

## Детали задачи
Заказчику важны:
- качество предсказания
- скорость предсказания
- время обучения

## Используемые библиотеки
*pandas*
*numpy*
*sklearn*
*xgboost*
*catboost*
*lightgbm*
*matplotlib*
*seaborn*
*scipy*