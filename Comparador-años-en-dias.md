Comparador-años-en-meses.


<pre>

# coding : utf8
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
    print("Hace" , abs(resultado) , "dias que llegamos a", año_cualqu
</pre>


### Tabla


| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| De años a dias | Respuesta |
| Año 2019-2020  | Han de pasar 365 dias para llegar a 2020 |
| Año 2019-2018  | Ya han pasado 365 días desde 2018 |
| Año 2019-2019  | No ha pasado nada de tiempo, ponga otro año |
| Año 2019-2021  | **Faltan/Han pasado** 730 días para llegar a 2021 |
