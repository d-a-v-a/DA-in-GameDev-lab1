# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #3 выполнил:
- Дубровский Давид Русланович
- РИ-210912
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Подготовить среду разработки и научиться ей управлять

## Задание 1 
Реализовать систему машинного обучения в связке Python – Unity.

Создаем проект в Unity, добавляем туда MLAgent. Добавляем необходимые объекты. Сфере добавляем и настраиваем C# скрипт и компоненты Rigidbody, Decision Requester, Behavior Parameters:

![1](https://user-images.githubusercontent.com/92369801/198334145-45b7425e-ba9a-4d32-82c4-283e6decbf6a.jpg)

![2](https://user-images.githubusercontent.com/92369801/198334201-e601d67f-9f63-46a2-a4b2-0ec49ed0379e.jpg)

В корень проекта добавляем файл конфигурации .yaml нашей нейронной сети:

![3](https://user-images.githubusercontent.com/92369801/198334258-b81ad670-49dc-4afa-aa39-37b82ac55c7c.jpg)

Запускаем Anaconda Promt, создаем, активируем и запускаем MLAgent:

![4](https://user-images.githubusercontent.com/92369801/198334291-828781cb-3bdc-4fd7-b13b-9fcccaa9ea5b.png)

Вернувшись в Unity-проект, проверяем работу ML-агента. Затем запускаем обучение на большем количестве копий модели.

копируем готовую модель в ассеты и переносим в Behavior Parameters:

![5](https://user-images.githubusercontent.com/92369801/198334312-67eb898d-485f-422f-9e18-a1f46b2c6be0.jpg)

Теперь можем проверить работу обученной модели, удобнее на одной копии.

![6](https://user-images.githubusercontent.com/92369801/198334323-2723cb11-e728-46b2-b02f-f169181847db.jpg)

По итогу обучения: шар самостоятельно двигаеься к каждому новому кубу. При этом шар не падает с платформы.


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
