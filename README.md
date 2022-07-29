# ControlTask

# Контрольная работа по курсу "Знакомство с языками программирования"

## **Формулировка задачи**

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна трём символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## **Описание алгоритма**

Шаг 1. Задаем исходный массив.
Шаг 2. Объявляем результирующий массив.
Шаг 3. Инициализируем счетчик элементов массива строк count.
Просматриваем в цикле все элементы исходного массива.
Если встречаем элемент с длиной строки меньше или равной 3:
— помещаем его в результирующий массив;
— увеличиваем счетчик count.
Иначе — переходим к следующему элементу исходного массива.
Шаг 4. Выводим в консоль исходный массив.
Шаг 5. Выводим в консоль результирующий массив.

## *Контрольный пример*
*Исходный массив:*
"1234", "123", "23", "Hello", "Yes", "No", "!", "+/*", "+-/*"
*Результирующий массив:*
"123", "23", "Yes", "No", "!", "+/*"


### Блок-схема алгоритма - в файле *Block diagram.drawio*

### Программа - в файле *Program.cs*
