# ANALIZDAN4
# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Лысиков Дмитрий Александрович
- РИ-220948
- 
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

## Цель работы
Изучение модели работы перцептрона посредством использования Unity.

## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления: OR, AND, NAND, XOR.
1. OR. Необходимо 3 эпохи, чтобы перцептрон работал без ошибок.
2. AND. Необходимо 4 эпох, чтобы перцептрон работал без ошибок.
3. NAND. Необходимо 4 эпох, чтобы перцептрон работал без ошибок.
4. XOR. Работает нестабильно, выдает ошибки с каждым повторением все больше.

Ход работы:
- Создал проект Unity и добавил туда скрипт Perceptron и проверил, что происходит в Console.
  OR:
  ![Снимок экрана 2023-11-22 005410](https://github.com/DmitryLysikov/ANALIZDAN4/assets/129677338/b6d22133-85d1-43be-82dd-65e943bd5fc5)
  AND:
  ![image](https://github.com/DmitryLysikov/ANALIZDAN4/assets/129677338/16140f61-14b8-429a-908d-f85a0924208f)
  NAND:
  ![Снимок экрана 2023-11-22 005337](https://github.com/DmitryLysikov/ANALIZDAN4/assets/129677338/e9d5571d-3672-4deb-8c8c-5d102e93da0b)
  XOR:
  ![Снимок экрана 2023-11-22 004440](https://github.com/DmitryLysikov/ANALIZDAN4/assets/129677338/fb9c803b-5bf1-4023-bbe0-9e41d20ee991)



## Задание 2
###  Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.
Ход работы:
- Я проанализировал данные, полученные после запуска персептрона для каждой логики, и оформил их в таблицу.
- Для первых трех логик персептрон быстро обучается и к 4 эпохе уже перестает делать ошибки, однако XOR работает нестабтльно, так как нелинейная функция.

![image](https://github.com/DmitryLysikov/ANALIZDAN4/assets/129677338/4b71cf98-aad0-4e40-aeca-10b3b2166d17)


## Задание 3
### Построить визуальную модель работы перцептрона на сцене Unity.
Ход работы:
![image](https://github.com/DmitryLysikov/ANALIZDAN4/assets/129677338/a9b13d8a-4fcf-4dd0-90b9-a4b89679084f)

- Выше я прекрепил сам проект.



## Выводы
Я научился реализовывать персептрон на Unity, также с помощью шаров визуализировал действия логик OR, AND, NAND, XOR.
Также проанализировал эпохи и построил график.



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
