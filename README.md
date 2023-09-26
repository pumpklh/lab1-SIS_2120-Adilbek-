
# lab1-SIS_2120-Adilbek-
lab 1


Python lab 1 
Mels Adilbek SIS-2120 


"""
1
num = "4 8 15 16 23 42"
print(num)
"""

"""
2
numbers = "4 8 15 16 23 42"
.split()
for number in numbers:
    print(number)
"""


"""
3
first_number = int(input("Введите первое число: "))

print(first_number)
print(first_number + 1)
print(first_number + 2)
"""

"""

4
num = int(input())
num1 = int(input())
num2 = int(input())

total = num + num1 + num2
print(f"Сумма трех чисел: {total}")
"""

"""

5
length = float(input())
print(f"Volume = (length ** 3))
print(f"Total surface area = (6 * (length ** 2)")
"""

"""

6
num=int(input())
num1=int(input())
print(num/num1)
print(num%num1)
"""

"""

7
number = int(input()) 
units = number % 10 
tens = (number // 10) % 10 
hundreds = (number // 100) % 10 
thousands = (number // 1000) % 10 
print(f"The digit in the thousands position is {thousands}") 
print(f"The number in the hundreds position is {hundreds}") 
print(f"The digit in the tens position is {tens}") 
print(f"The digit in the position of units is {units}")
"""

"""

8
num = int(input())


if number % 2 == 0:
    result = number // 2
else:
    result = (number + 1) // 2


print(result)
"""

"""

9
number = int(input("Введите число: "))

result = number << 1

if result == 0:
    print(Результат << равен нулю!")
else:
    print("Результат << равен", result)
"""

"""
10

try:
    
    num1 = float(input("Пожалуйста, введите первое число: "))
    num2 = float(input("Пожалуйста, введите второе число: "))

    
    operation = input("Пожалуйста, выберите операцию (+, -, *, /): ")

    
    if operation == '+':
        result = num1 + num2
        print(f"{num1} + {num2} = {result}")
    elif operation == '-':
        result = num1 - num2
        print(f"{num1} - {num2} = {result}")
    elif operation == '*':
        result = num1 * num2
        print(f"{num1} * {num2} = {result}")
    elif operation == '/':
        if num2 == 0:
            print("Ошибка: Деление на ноль недопустимо.")
        else:
            result = num1 / num2
            print(f"{num1} / {num2} = {result}")
    else:
        print("Недопустимая операция.")

except ValueError:
    print("Ошибка: Пожалуйста, введите корректные числа.")
except Exception as e:
    print(f"Ошибка: {e}")
"""
"""



