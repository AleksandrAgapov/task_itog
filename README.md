Итоговая проверочная работа 
Задача:
 Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Создаем одномерный массив array1 состоящий из 5 элементов типа string (строка), элементы массива задаем в фигурных скобках вручную. Создаем одномерный массив array2, элементами которого будут некоторые элементы из массива array1. Запускаем цикл for который перебирает по порядку все элементы массива array1. В теле цикла for запускаем оператор if , условием которого является количество символов каждого элемента из массива array1 сравнивать c < =3, «if(array1[i].Length <= 3». Если условие «истина» элемент массива выводится в консоль, тем самым создаём в консоли массив array2 с количеством элементов 3 и менее.