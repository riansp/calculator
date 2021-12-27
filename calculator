print ('Calculator')
print ('=' * 23)

def add (x, y):
    return x + y
def subtract (x, y):
    return x - y
def multiply (x, y):
    return x * y
def devide (x, y):
    return x / y

print('Menu')

print('  1. Add \t [+]')
print('  2. Subtract \t [-]')
print('  3. Multiply \t [*]')
print('  4. Devide \t [/]')
print('=' * 23)


while True :
    select = input('Select Menu (1/2/3/4): ')
    
    if select in ('1','2','3','4'):
        num1 = float(input('input first number: '))
        num2 = float(input('input second number: '))
        print('The Result')

        if select == '1':
            print(num1, "+", num2, "=", add(num1, num2))
        elif select == '2':
            print(num1, "-", num2, "=", subtract(num1, num2))
        elif select == '3':
            print(num1, "*", num2, "=", multiply(num1, num2))
        elif select == '4':
            print(num1, "/", num2, "=", devide(num1, num2)) 
        break
    else:
        print('error')
