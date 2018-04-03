# Калькулятор арифмитических выражений

## Что происходит:

Входное выражение разбивается на токены по мере прохождения по строке. 
Доступные операции: +, -, /, *, (), константы:  e, pi.

## Как заупусать:

$ make
$ ./calc

## Формат ввода

На stdin подается арифмитическое выражение:
Пример:
2 + 3 - pi * (1 - 7) + 10 / 2

## Формат вывода:

Результат вычислений