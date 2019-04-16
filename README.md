# Тестовое задание для стажера в юнит core-services

Необходимо сделать приложение на PHP|Golang, парсящее сайт Авито.
Приложение может быть в виде CLI или HTTP-микросервиса
Запускаться должно в Docker образе

## Задание

1. Получить список существующих локаций Авито (Города, Области, которые можно выбрать в фильтре)
2. Распарсить дерево категорий, существующих на Авито. (можно выбрать в фильтре вверху страницы https://www.avito.ru/rossiya)
3. Посчитать количество объявлений в каждой категории в городе Москва

## Результат

В качестве результата хочется увидеть json-файлы:
locationsTree.json, categories.json, categoriesMoscow.json

## Дополнительные опции:

Их выполнение абсолютно опционально, но дает плюсек в карму.

1. Добавьте возможность в один запрос получить статистику в разрезе категорий по любому городу (город вводится параметром)
2. Добавьте возможность отображать статистику по городу в удобном для человека виде

Если будут вопросы: Можете задать их в issues или в telegramm @shaman_s_bubnom