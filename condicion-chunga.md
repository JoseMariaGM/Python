# coding utf8
# python 3

condicion = int(input("Introduzca un numero:"))

if (condicion % 2 == 0 and condicion >= -10 and condicion <= 40 or condicion < 0 and condicion % 2 == 0) :
    print("Está dentro de la condicion")
else:
    print("No está dentro de la condicion")
    

