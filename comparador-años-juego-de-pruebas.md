
Comparador-años-jugando-JuegoDePruebas.


<pre>

# coding utf8
# python 3

anyo_actual = int(input(" Año en el que estamos : "))
anyo_cualquiera = int(input("Pruebe un año cualquiera : "))
resultado = anyo_actual - anyo_cualquiera

if (anyo_actual == anyo_cualquiera):
    print("El año que ha utilizado es el mismo.")
elif (resultado<0 and abs(resultado)==1):
    print("Para poder llegar al año" , anyo_cualquiera , "falta/n" , abs(resultado) , "año/s")
elif (resultado>0 and abs(resultado)==1):
    print("Hace", abs(resultado) , "año que llegamos a" , anyo_cualquiera )
elif (resultado<0 and abs(resultado)!=1):
    print("Para llegar a " , anyo_cualquiera , "falta/n" , abs(resultado) , " año/s")
elif (resultado>0 and abs(resultado)!=1):
    print("Hace" , abs(resultado) , "año/s que llegamos a", anyo_cualquiera)




 	
</pre>


### Tabla


| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| Año actual-Año cualquiera | Respuesta |
| 2019-2020 | Falta 1 año para poder llegar a 2020 |
| 2019-2019 | Es el mismo año, por favor, cambia el número |
| 2019-2018 | Hemos llegado a ese año hace 1 año |
| 2019-2021 | Llegaremos a ese año dentro de 2 años |
| 2019-2017 | Hemos llegado a ese año hace 2 años |




