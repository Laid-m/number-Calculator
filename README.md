x = float(input("Введите число: "))
y = int(input("Введите второе число: "))
op = input("Введите знамение (+,-,*,/): ")

if op == "+":
    print(x + y)
elif op == "-":
    print(x - y)
elif op == "*":
    print(x * y)
elif op == "/":
    print(x / y)
else:
    print("ошибка")

    
