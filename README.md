
Условие задачи:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
Решение:
Сначала задается два массива одинаковой длины. В первый вносятся элементы, котрые пользователь вводит через командную строку. Далее выполняется метод, который посредством цикла for выбирает элементы, длина которых меньше либо равна 3 символа. Отобранные элементы последовательно заносятся во второй созданный массив при помощи переменой count. После каждого занесенного элемента count увеличивается на 1. Когда цикл звершается, выполняется метод вывода второго массива