К сожалению тогда я ещё не понимала, почему важно писать хорошие отчёты, но справедливости ради и сами лабы были очень маленькие

В данном репозитории есть следующие лабораторные работы:
1) Небольшая лабораторная работа на понимание разрядности архитектуры      (lab5.c)
2) Подсчёт количества букв в введённой строке (включая кириллицу)          (letter_counter.c)
3) Исследование диапазонов целочисленных типов данных в C                  ( o_laba1.cpp)
   
4) o_laba2.c
Тема: "Ряды Тейлора и вычисление сумм с заданной точностью"
Цель: Реализовать вычисление суммы ряда с использованием рекуррентных формул,
позволяющих добиться заданной точности или определить сумму с фиксированным числом членов.

Задание:
    Функция для факториала:
      Реализуйте функцию fact, которая вычисляет факториал заданного целого числа n. Функция возвращает значение типа long double.

    Член ряда:
      Реализуйте функцию f, которая принимает параметры n и x и вычисляет 𝑓(𝑛,𝑥) = pow(-1, n) / fact(2 * n) * pow(x, 2 * n),
      что соответствует одному члену ряда. Используйте функцию fact для вычисления факториала.

    Вычисление с заданной точностью:
      Создайте функцию given_acc, которая принимает аргументы x и eps 
      и вычисляет сумму ряда, пока разница между двумя последовательными 
      членами не станет меньше eps. Возвращаемое значение — итоговая сумма ряда.

    Сумма первых n членов:
      Создайте функцию sum_n, которая принимает аргументы x и n 
      и возвращает сумму первых n членов ряда. Используйте функцию 
      f для добавления каждого члена к сумме.

    Максимальная точность:
      Реализуйте функцию max_acc, которая вычисляет сумму ряда, 
      достигая предела точности типа long double (используя LDBL_EPSILON). 
      Используйте метод, аналогичный функции given_acc, но с порогом eps = LDBL_EPSILON.

    Основная функция:
      В main запросите у пользователя значения x, eps и n, 
      вызовите функции given_acc, sum_n, и max_acc, и выведите результаты.

5) Программа, на вход которой подается файл
   формата .c и .cpp, и она удаляет из него комментарии
   (о_laba3final.cpp)
7) Разные сортировки и замер времени их выполнения 
   (o_laba5.cpp)
8) Шлакоблокунь - лабораторная работа по написанию портманто - генератора словослияний
9) Решение задачи о 8 ферзях методом перебора с возвратом
