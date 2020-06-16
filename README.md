Решение задач для "Онлайн-школа Т"
----------------------------------


## Задача 1.
### Условие:
#### Дан массив целых чисел array и целое число k. Нужно вывести все уникальные пары чисел из массива, сумма которых равна k.
##### input: 
```
1 2 6 5 3 4 7 8 3 2
```
##### input:
```
5
```
##### output: 
```
[(1, 4), (2, 3)]
```
#
## Задача 2.
### Условие:
#### Есть файл с именами <https://yadi.sk/i/97rbNP2ucGoAKw>. Нужно выполнить следующие действия и посчитать результат:

1. Отсортировать все имена в лексикографическом порядке
2. Посчитать для каждого имени алфавитную сумму – сумму порядковых номеров букв (MAY: 13 + 1 + 25 = 39)
3. Умножить алфавитную сумму каждого имени на порядковый номер имени в отсортированном списке (индексация начинается с 1). Например, если MAY находится на 63 месте в списке, то результат для него будет 63 * 39 = 2457.
4. Просуммировать произведения из третьего пункта по всем именам из файла.
##### Положите файл names.txt в директорию, в которой находится скрипт.
##### Запустите скрипт.
##### output: 
```
871853874
```
#
## Задача 3.
### Условие:
#### Дано число n. Написать функцию, которая возвращает количество идущих подряд нулей на конце фаториала n!
##### input: 
```
12
```
##### output: 
```
2
```
 Решение задач.
----------------
### Задача 1.
1. Запустите скрипт task_01.py в консоли.
2. Введите массив чисел разделенных пробелами.
3. Введите число k.
4. Результат будет выведен в консоль.
#### Вопросы:
 - Какая сложность у вашего алгоритма?
##### Точно не могу сказать. Но предполагаю, что O(N/2).
 - Можно ли его оптимизировать?
##### Можно. Если уточнить исходные данные. Например, присутствуют ли в массиве отрицательные числа. Если нет, то можно сразу отбросить из массива числа больше k.
### Задача 2.
1. Положите файл names.txt в одну директорию со скриптом task_02.py.
2. Запустите скрипт task_02.py в консоли.
3. Результат будет выведен в консоль. В данном случае ответ: 871853874.
### Задача 3.
1. Запустите скрипт task_03.py в консоли.
2. Введите число n.
3. Результат будет выведен в консоль.
#### Вопросы:
 - Какая сложность у вашего алгоритма?
##### Могу предположить, что O(N).
