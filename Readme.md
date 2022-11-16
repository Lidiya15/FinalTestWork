# *__Итоговая проверочная работа.__*

## *__Задача__*:

*Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*

*Примеры*:

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

## *__Алгоритм решения__*:

1. Делаем перебор значений из исходного массива

2. Проверяем каждое значение из массива на соответствие условию: длина строки меньше или равна трем
3. Если строка удовлетворяет условию кладем значение в новый массив
4. Повторяем пункты 2 и 3 до тех пор пока не достигнем конца исходного массива
5. Возвращаем новый заполненый массив как результат

## ![Блок-схема алгоритма](diagram/diagram.drawio.png):


## *__Программа__*:

Для запуска программы перейдите в папку **solution** и запустите команду через терминал:

*dotnet run*

Далее введите значения через пробел, например:

*Введите значения через пробел: 2 hello sun 33 world*

Пример вывода программы:

*[2, hello, sun, 33, world] -> [2, sun, 33]*

