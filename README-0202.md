# Задание по теме "Условная конструкция. Операторы if, elif, else"
first = int(input('Введите первое целое число: '))
second = int(input('Введите второе целое число: '))
third = int(input('Введите третье целое число: '))
if first == second and first == third:
    print(3, 'одинаковых числа')
elif first == second or first == third:
    print(2, 'одинаковых числа')
elif second == third:
    print(2, 'одинаковых числа')
else:
    print(0, '- Нет одинаковых чисел')


