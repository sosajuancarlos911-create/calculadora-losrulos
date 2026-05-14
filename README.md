# calculadora-losrulos 
Estudainte B
def multiplicar(a, b):
    resultado = a * b
    print "El resultado de la multiplicación es:", resultado
    return resultado



def dividir(a, b):
    if b == 0:
        print "Error: no se puede dividir por cero."
        return None
    else:
        resultado = a / b
        print "El resultado de la división es:", resultado
        return resultado



print " MULTIPLICACION "
num1 = int(raw_input("Ingrese el primer numero para multiplicar: "))
num2 = int(raw_input("Ingrese el segundo numero para multiplicar: "))

multiplicar(num1, num2)



print "DIVISION "
num3 = int(raw_input("Ingrese el primer numero para dividir: "))
num4 = int(raw_input("Ingrese el segundo numero para dividir: "))

dividir(num3, num4)
