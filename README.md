# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил:
- Дубровский Давид Русланович
- РИ-210912
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

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
Узнать что такое перцептрон и понять принципы его работы
## Задание 1 
В программе Unity реализовать перцептрон, который умеет проводить вычисления OR, AND, NAND, XOR

1) Внес в пустой GameObject код прецептрона и указал нужные значения для вычисления OR

![1](https://user-images.githubusercontent.com/92369801/205012686-488d04de-2534-42b8-a052-482bb0f00066.jpg)

2) Подобрал значение массива ts, с помощью метода Train, чтобы гарантированно научить прецептрон вычислять OR

![3](https://user-images.githubusercontent.com/92369801/205013428-1a3ea0e5-b7d6-4651-9e07-202ed91dc035.jpg)

![2](https://user-images.githubusercontent.com/92369801/205013453-cb759104-5bca-4233-b024-19398d055922.jpg)

Прецептрон может работать с вычислением OR, примерно 5 эпох ему достаточно

3) Внес в пустой GameObject код прецептрона и указал нужные значения для вычисления AND

![and1](https://user-images.githubusercontent.com/92369801/205014861-b371f19a-4692-4055-be68-5ef32762eac3.jpg)

Примерное количество эпох для обичения 8
![and2](https://user-images.githubusercontent.com/92369801/205015083-16b4753f-836b-4c82-aa4a-f27bc94eb9d7.jpg)

4) Внес в пустой GameObject код прецептрона и указал нужные значения для вычисления NAND

![nand1](https://user-images.githubusercontent.com/92369801/205017083-45140c7f-4548-43be-bebb-7e9761766f27.jpg)

Примерное количество эпох для обичения 8

![nand2](https://user-images.githubusercontent.com/92369801/205017350-2115e667-adf9-4041-afbf-1f8c653134e4.jpg)

5)  Внес в пустой GameObject код прецептрона и указал нужные значения для вычисления XOR

![xor1](https://user-images.githubusercontent.com/92369801/205018918-dcb437f4-5b71-4e3e-ab14-f566b8e63b7b.jpg)

Прецептрон не может считать значение XOR, поскольку линейный классификатор может делить плоскость только прямыми линиями, а при вычислении XOR два сигнала на входе имеют разные значения

![xor2](https://user-images.githubusercontent.com/92369801/205020162-aaa2efbc-b780-4364-866a-d4e636d25dc0.jpg)

## Задание 2
### Построить графики зависимости количество эпох от ошибки обучения. Указать от чего зависит необходимое количество эпох обучения

![graf](https://user-images.githubusercontent.com/92369801/205034815-d9cbeeb7-5b57-491e-925b-93cd57a265e8.jpg)

Необходимое количество эпох зависит от сложглсти выбранного вычисления и рандома


## Задание 3
### Построить визуальную модель прецептрона на сцене Unity
в следующем примере я использую два куба с изменением цвета чтобы показать как прецептрон работает с операцией AND
Красный цвет куб - 0
Синий цвет - 1
Красный цвет итоговый кубов - 0
Желтый цвет - 1

![cube 1 1](https://user-images.githubusercontent.com/92369801/205049468-88a2afe7-7410-4e47-9950-6581dc8b3378.jpg)

![cube 1 2](https://user-images.githubusercontent.com/92369801/205049493-84ddd30b-3016-4942-8130-ba8b058d304d.jpg)


![cube 2 1](https://user-images.githubusercontent.com/92369801/205049595-255070e5-941b-4f8e-af6d-5b1f9278d2f4.jpg)

![cube 2 2](https://user-images.githubusercontent.com/92369801/205049604-c953c02b-b82f-4aff-abf3-9d29d37718ee.jpg)

![cube 3 1](https://user-images.githubusercontent.com/92369801/205049606-c437e02e-15b9-4c19-8cfc-adefceb6e159.jpg)

![cube 3 2](https://user-images.githubusercontent.com/92369801/205049609-7d784028-afec-4817-a96c-2bf81a5551c1.jpg)

![cube 4 1](https://user-images.githubusercontent.com/92369801/205049611-216c524c-92f6-45ea-a36a-a7fc59a8e6e5.jpg)

![cube 4 2](https://user-images.githubusercontent.com/92369801/205049614-451f4107-7ebb-49d9-aa45-a1de5b689edb.jpg)


## Выводы
Я узнал что такое прецептрон и опробовал принципы его работы на практике


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
