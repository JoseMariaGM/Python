# coding utf8
# python 3

condicion = int(input("Introduzca un numero:"))

if (condicion % 2 == 0 and condicion >= -10 and condicion <= 40 or condicion < 0 and condicion % 2 == 0) :
    print("Está dentro de la condicion")
else:
    print("No está dentro de la condicion")
    
| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| Resultado | Respuesta |
| -30 | Condició correcta |
| -11 | Condició incorrecta |
| -10 | Condició correcta |
| -6  | Condició correcta |
| -5 | Condició incorrecta |
| 0 | Condició correcta |
| 6 | Condició correcta |
| 40 | Condicio correcta |
| 41 | Condició incorrecta |
| 234 | Condició incorrecta |
