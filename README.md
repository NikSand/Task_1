1. Реализовать алгоритм определения правильной скобочной последовательности в выражении,
например:

{(x * y) + (2 * (x + y))} * [y + 3] - правильная скобочная последовательность.
({((x * y) + [2 * (x - y)]}) - неправильная скобочная последовательность.
(x * y) +) 2 * [x - y]( - неправильная скобочная последовательность.

В выражении могут быть использованы круглые "()", фигурные "{}" и квадратные "[]" скобки, а также
произвольные печатные символы.

Программе на вход передается текстовый файл, содержащий несколько выражений, по одному в
каждой строке. Необходимо определить, является ли скобочная последовательность в каждом из выражений правильной и вывести результат на экран в виде:

<выражение> - правильная скобочная последовательность
или
<выражение> - неправильная скобочная последовательность
