# coding utf8
# python 3


numero = int(input("Introduzca un número :"))
if (numero == 0):
    print("El número es 0")
elif (numero <= 0):
    print("El número es negativo")
elif (numero % 2 > 0):
    print("El número es impar")
else:
    print("El número será par")
    

| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| Numero | Respuesta |
| 0 | El número es 0|
| <0  | Negativo |
| >0 % 2 | Residuo = 1 -> impar |
| >0 % 2 | Residuo = 0 -> par |  
