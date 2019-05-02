# Comparador-años-en-meses.


<pre>

año_actual = int(input("Número del año en el que estamos : "))
año_cualquiera = int(input("Número de un año cualquiera : "))
resultado = (año_actual - año_cualquiera)*365

if (año_actual == año_cualquiera):
    print("El año que ha utilizado es el mismo.")
elif (resultado<0 and abs(resultado)==1):
    print("Para poder llegar al año de" , año_cualquiera , "faltan" , abs(resultado) , "dias")
elif (resultado>0 and abs(resultado)==1):
    print("Hace" , abs(resultado)," dias que llegamos a " , año_cualquiera)
elif (resultado<0 and abs(resultado)!=1):
    print("Para llegar a " , año_cualquiera , "faltan" , abs(resultado) , "dias")
elif (resultado>0 and abs(resultado)!=1):
    print("Hace" , abs(resultado) , "dias que llegamos a", año_cualquiera)
 	
</pre>


### Tabla


| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| Años en meses | Respuesta |
| 1 año menos(12 meses) | Faltan 12 meses para llegar a tal año |
| 2 años(24 meses) menos | Faltan 24 meses para llegar a tal año |
| 0 años de diferencia | Los años continuan siendo los mismos |
| 2 años(24 meses) más | Desde tal año ya han pasado/faltan 24 meses  |



## meses_alternativo
# coding utf8
# python 3

mes_actual = int(input("Número del mes en el que estamos : "))
mes_cualquiera = int(input("Número de un mes cualquiera : "))
resultado = mes_actual - mes_cualquiera

if (mes_actual == mes_cualquiera):
    print("El mes que ha utilizado es el mismo.")
elif (resultado<0 and abs(resultado)==1):
    print("Para poder llegar al mes de" , mes_cualquiera , "falta/n" , abs(resultado) , "mes/es")
elif (resultado>0 and abs(resultado)==1):
    print("Hace 1 mes que llegamos a " , mes_cualquiera)
elif (resultado<0 and abs(resultado)!=1):
    print("Para llegar a " , mes_cualquiera , "falta/n" , abs(resultado) , "mes/es ")
elif (resultado>0 and abs(resultado)!=1):
    print("Hace 1 año que llegamos a", mes_cualquiera)
